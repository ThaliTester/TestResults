#### Test 50650278e989a4f_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3524): !@Sync 4
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 279, CUR = 41
--------- beginning of main
D/AndroidRuntime(11833): 
D/AndroidRuntime(11833): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11833): CheckJNI is OFF
D/AndroidRuntime(11833): readGMSProperty: start
D/AndroidRuntime(11833): readGMSProperty: already setted!!
D/AndroidRuntime(11833): readGMSProperty: end
D/AndroidRuntime(11833): addProductProperty: start
E/AffinityControl(11833): AffinityControl: registerfunction enter
V/AlarmManager( 3524): waitForAlarm result :8
D/AndroidRuntime(11833): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3524): mDVFSHelper.acquire()
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  (11857): MountEmulatedStorage()
E/Zygote  (11857): v2
I/libpersona(11857): KNOX_SDCARD checking this for 10503
I/libpersona(11857): KNOX_SDCARD not a persona
I/SELinux (11857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11857 uid=10503 gids={50503, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11857): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime(11833): Shutting down VM
D/TimaKeyStoreProvider(11857): TimaSignature is unavailable
D/ActivityThread(11857): Added TimaKeyStore provider
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2851): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11857): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6245): updateVisibility : ActivityRecord{38055881 token=android.os.BinderProxy@13d927da {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:85
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/WebViewFactory(11857): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11857): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11857): Loading: webviewchromium
,I/LibraryLoader(11857): Time to load native libraries: 4 ms (timestamps 4427-4431)
I/LibraryLoader(11857): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11857): Binding Chromium to main looper Looper (main, tid 1) {374f66f8}
,I/LibraryLoader(11857): Expected native library version number "",actual native library version number ""
,I/chromium(11857): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11857): Initializing chromium process, renderers=0
,W/art     (11857): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11857): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11857): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11857): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11857): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11857): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11857): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11857): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11857): CordovaWebView is running on device made by: samsung
,W/art     (11857): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11857): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11857): performCreate Call secproduct feature valuefalse
D/Activity(11857): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11857): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2851): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11857): Initialized EGL, version 1.4
,I/OpenGLRenderer(11857): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278639856 
,D/OpenGLRenderer(11857): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11857): Enabling debug mode 0
,D/mali_winsys(11857): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11857): updateVisibility : ActivityRecord{32e67e28 token=android.os.BinderProxy@bbd3f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{b9cec83 u0 com.test.thalitest/.MainActivity t26} time:134782
,W/IInputConnectionWrapper(11857): showStatusIcon on inactive InputConnection
,I/Timeline(11857): Timeline: Activity_idle id: android.os.BinderProxy@bbd3f time:134794
,D/JsMessageQueue(11857): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11857): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11857): 
,D/jxcore_app_log(11857): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361619200
D/JX-Cordova(11857): jxcore cordova android initializing
,I/art     (11857): Background sticky concurrent mark sweep GC freed 76095(7MB) AllocSpace objects, 15(3MB) LOS objects, 18% free, 34MB/42MB, paused 1.820ms total 100.657ms
,W/jxcore-log(11857): Initializing JXcore engine
W/jxcore-log(11857): JXcore engine is ready
,W/jxcore-log(11857): Starting JXcore engine
,E/auditd  ( 4642): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11857): Platform android
W/jxcore-log(11857): 
W/jxcore-log(11857): Process ARCH arm
W/jxcore-log(11857): 
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11857): JXcore Cordova bridge is ready!
I/jxcore-log(11857): 
W/jxcore-log(11857): JXcore engine is started
,I/jxcore-log(11857): Toggling radios to true
I/jxcore-log(11857): 
,D/BluetoothAdapter(11857): enable()
,D/BluetoothAdapter(11857): enable(): BT is already enabled..!
,D/WifiService( 3524): New client listening to asynchronous messages
,I/WifiManager(11857): packageName : com.test.thalitest
,D/SecContentProvider( 3524): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3524): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3524): mCursor = null
D/WifiService( 3524): setWifiEnabled: true pid=11857, uid=10503
E/WifiService( 3524): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3524): Permission Denial: getCurrentUser() from pid=11857, uid=10503 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3524): Failed getting userId using ActivityManagerNative
W/WifiService( 3524): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11857, uid=10503 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3524): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3524): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3524): name = wifi_on
,I/WifiService( 3524): disconnect: pid=11857, uid=10503
,I/wpa_supplicant( 3832): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3832): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log(11857): Radios toggled
I/jxcore-log(11857): 
I/wpa_supplicant( 3832): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3524): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3832): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): Disconnected - do not scan
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3524): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11857): Got Device Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11857): 
,I/jxcore-log(11857): Perf Test app loaded loaded
I/jxcore-log(11857): 
,I/jxcore-log(11857): check test folder
I/jxcore-log(11857): 
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
,I/jxcore-log(11857): found test : ./testFindPeers.js
I/jxcore-log(11857): 
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2846): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3524): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3524): updateNetworkInfo()
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,I/jxcore-log(11857): found test : ./testSendData.js
I/jxcore-log(11857): 
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
,I/Hs20UtilService( 4069): Starting #8
I/Hs20UtilService( 4069): Message received 5007
,D/NearbySettings( 8901): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8901): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8901): MountReceiver.onReceive - Create mPrefHandler
,E/WifiStateMachine( 3524): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3832): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3832): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3832): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3832): First Scan Start
D/NearbySettings( 8901): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/WifiStateMachine( 3524): ConnectModeState: Network connection lost 
V/NearbySettings( 8901): DMSUtil.isNetworkConnected - flag-null, state-null
E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/wpa_supplicant( 3832): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
,I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/WifiService( 3524): New client listening to asynchronous messages
I/NearbySettings( 8901): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8901): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8901): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11573): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2846): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3524): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3524): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3524): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3524): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - currTime: 1450233123076
D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
,D/TelephonyNetworkFactory( 3985): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES,
D/WifiNetworkAgent( 3524): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,D/ConnectivityManager.CallbackHandler( 6648): CM callback handler got msg 524292
D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/Choreographer(11857): Skipped 47 frames!  The application may be doing too much work on its main thread.
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3524): MasterInitialState.processMessage what=3
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
,D/ConnectivityService( 3524): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): updateIfacesLocked()
V/NetworkStats( 3524): performPollLocked(flags=0x1)
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
I/chromium(11857): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
D/NetworkStatsFactory( 3524): UpdateStatsForKnox
,I/Hs20UtilService( 4069): Starting #9
D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/chromium(11857): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Hs20UtilService( 4069): Message received 5007
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
,V/NetworkStats( 3524): performPollLocked() took 14ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NearbySettings( 8901): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8901): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8901): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8901): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8901): MountReceiver.mPrefHandler - 7002
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
I/SignOutReceiver(11573): NETWORK_STATE_CHANGED_ACTION
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3524): updateDataUsageMap
,I/ApplicationPolicy( 3524): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3524): No Active Data Connection
,I/DBG_DM  ( 6245): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6245): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11965): MountEmulatedStorage()
E/Zygote  (11965): v2
I/libpersona(11965): KNOX_SDCARD checking this for 10110
I/libpersona(11965): KNOX_SDCARD not a persona
,I/SELinux (11965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11965 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (11965): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11965): TimaSignature is unavailable
,D/ActivityThread(11965): Added TimaKeyStore provider
,D/ResourcesManager(11965): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11965): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11965): not using cross-dex optimization: ART in use
,I/art     (11965): Thread[1,tid=11965,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11965): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11965): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
,V/DexLibLoader(11965): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11965): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11965): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11965): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11965): loading pre-built fallback odex files
V/MultiDexClassLoader(11965): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11965): released odex store lock
D/DexLibLoader(11965): DexLibLoader.loadAll took 30 ms
,W/ca      (11965): Verify
,W/LightSharedPreferencesImpl(11965): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11965): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11965): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11965): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11965): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11965): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11965): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11965): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11965): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11965): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11965): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11965): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11965): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11965): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11965): 	... 10 more
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11994): MountEmulatedStorage()
E/Zygote  (11994): v2
I/libpersona(11994): KNOX_SDCARD checking this for 1000
I/libpersona(11994): KNOX_SDCARD not a persona
,I/SELinux (11994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11994 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11157:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11965): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/wpa_supplicant( 3832): nl80211: Received scan results (15 BSSes)
,I/wpa_supplicant( 3832): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3832): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3832): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3524): [1,450,233,124,139 ms] noteScanEnd no scan source
,D/TimaKeyStoreProvider(11994): TimaSignature is unavailable
,D/ActivityThread(11994): Added TimaKeyStore provider
,W/appmanager(:<default>):b(11965): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/WifiStateMachine( 3524): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@242fe959 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/ResourcesManager(11994): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11994): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11994): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11994): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11994): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11994): sales region : global
I/PCWCLIENTTRACE_PushUtil(11994): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11994): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
W/appmanager(:<default>):QuickExperimentControllerImpl(11965): Exposure of experiment com.facebook.common.network.l@18189cf occurred when no user was logged in
,I/PCWCLIENTTRACE_SYSTEMReceiver(11994): noConnectivity : true
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{16d396b6 u0 ReceiverList{16d12e51 11965 com.facebook.appmanager/10110/u0 remote:90c4778}}
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{16d396b6 u0 ReceiverList{16d12e51 11965 com.facebook.appmanager/10110/u0 remote:90c4778}}
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3832): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3832): Associated with C0.AA.48
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,E/Zygote  (12017): MountEmulatedStorage()
E/Zygote  (12017): v2
I/libpersona(12017): KNOX_SDCARD checking this for 10135
I/libpersona(12017): KNOX_SDCARD not a persona
,I/SELinux (12017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12017 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12017): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3832): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/ActivityManager( 3524): Killing 11172:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/wpa_supplicant( 3832): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3832): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3832): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3832): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3832): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3832): Blacklist: Clear (temp) 
I/wpa_supplicant( 3832): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3524): Network connection established
,D/WifiNative-HAL( 3524): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/TimaKeyStoreProvider(12017): TimaSignature is unavailable
,D/ActivityThread(12017): Added TimaKeyStore provider
,D/ConnectivityService( 3524): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3524): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3524): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3524): L2ConnectedState "NG700" nid=0
E/ConnectivityService( 3524): updateNetworkInfo()
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3524): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3524): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2846): Setting iface cfg
,E/WifiStateMachine( 3524): Start Dhcp Watchdog 2
D/ResourcesManager(12017): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{21e67ac0 u0 ReceiverList{23d45443 11965 com.facebook.appmanager/10110/u0 remote:370165f2}}
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,I/MusicStore(12017): Database version: 104
,D/ResourcesManager(12017): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12017): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12017): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12017): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PowerManagerService( 3524): [PWL] Off : 75s ago
I/PowerManagerService( 3524): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3524): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3524): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3524, ws=null) (elapsedTime=1430)
,W/ActivityThread(12017): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (12017): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e838ecc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12017): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12017): GMSCore installation verified
,I/ConfigStore(12017): Config Database version: 1
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/dhcpcd  (12053): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12053): version 5.5.6 starting
,E/dhcpcd  (12053): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12017): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3524): getStreamVolume 3 index 0
,I/MediaRouter(12017): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/dhcpcd  (12053): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12053): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  (12053): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12053): bssid match
,I/dhcpcd  (12053): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12060): MountEmulatedStorage()
E/Zygote  (12060): v2
I/libpersona(12060): KNOX_SDCARD checking this for 10002
I/libpersona(12060): KNOX_SDCARD not a persona
,I/SELinux (12060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12060 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11965): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11965): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/NetworkMonitor(12017): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12060): TimaSignature is unavailable
,D/ActivityThread(12060): Added TimaKeyStore provider
,I/ActivityManager( 3524): Killing 11188:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(12060): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/dhcpcd  (12053): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,W/appmanager(:<default>):QuickExperimentControllerImpl(11965): Exposure of experiment com.facebook.imagepipeline.a.g@fa80dc occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11965): Exposure of experiment com.facebook.imagepipeline.a.d@3bf52b61 occurred when no user was logged in
,I/dhcpcd  (12053): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,I/ActivityManager( 3524): Killing 11204:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/art     (11965): Explicit concurrent mark sweep GC freed 47274(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.099ms total 49.754ms
,W/appmanager(:<default>):m(11965): No feature status reporters found; is this dead code?
,E/Zygote  (12085): MountEmulatedStorage()
E/Zygote  (12085): v2
I/libpersona(12085): KNOX_SDCARD checking this for 1000
I/libpersona(12085): KNOX_SDCARD not a persona
,I/SELinux (12085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12085): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 881us total 25.783ms
,D/TimaKeyStoreProvider(12085): TimaSignature is unavailable
,D/ActivityThread(12085): Added TimaKeyStore provider
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 763us total 21.133ms
,D/ResourcesManager(12085): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 799us total 18.800ms
,I/DIAGMON_AGENT(12085): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12085): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12085): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12085): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12085): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12120): MountEmulatedStorage()
E/Zygote  (12120): v2
I/libpersona(12120): KNOX_SDCARD checking this for 10012
I/libpersona(12120): KNOX_SDCARD not a persona
,I/SELinux (12120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12120 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12120): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend true
,D/TimaKeyStoreProvider(12120): TimaSignature is unavailable
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/ActivityThread(12120): Added TimaKeyStore provider
,E/WifiStateMachine( 3524): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3524): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3524): Not connected state, yet.
E/WifiStateMachine( 3524): VerifyingLinkState enter
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3524): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3524): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3524): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3524): callSECApiInt - ID [210]
,E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3524): updateNetworkInfo()
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 3524): Adding iface wlan0 to network 503
D/WifiWatchdogStateMachine( 3524): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ResourcesManager(12120): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3524): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine( 3524): Now, connected state.
E/WifiStateMachine( 3524): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine( 3524): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/WifiNative-HAL( 3524): callSECApiVoid - ID [212]
,D/ConnectivityService( 3524): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine( 3524): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService( 3524): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/ConnectivityService( 3524): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,E/ConnectivityService( 3524): Unexpected mtu value: 0, wlan0
V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,I/ActivityManager( 3524): Killing 11237:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,V/        ( 2846): QcRouteController
,I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,V/        ( 2846): QcRouteController
,I/FOTA_Client(12120): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,V/        ( 2846): QcRouteController
,V/        ( 2846): QcRouteController
,E/Zygote  (12151): MountEmulatedStorage()
,E/Zygote  (12151): v2
I/libpersona(12151): KNOX_SDCARD checking this for 10021
I/libpersona(12151): KNOX_SDCARD not a persona
V/        ( 2846): QcRouteController
,I/SELinux (12151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12151 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11225:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/ConnectivityService( 3524): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3524): LTETest block dns file not exists
,D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3524): updateNetworkInfo()
E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3524): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Connected
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3524):    accepting network in place of null
,D/TelephonyNetworkFactory( 3985): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3524): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3524): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3524): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 3524): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 1000
,D/Tethering( 3524): MasterInitialState.processMessage what=3
,D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 6648): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/TimaKeyStoreProvider(12151): TimaSignature is unavailable
,V/NetworkStats( 3524): updateIfacesLocked()
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked(flags=0x1)
,D/ActivityThread(12151): Added TimaKeyStore provider
,D/NetworkStatsFactory( 3524): UpdateStatsForKnox
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,V/NetworkStats( 3524): performPollLocked() took 10ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/ResourcesManager(12151): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12151): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 03:32:05 GMT+01:00 2015
,I/KLMS-2.4.521: (12151): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12151): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12151): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12151): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12151): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12151): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12151): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/System.out( 3524): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/KLMS-2.4.521: (12151): StateImplV2(): networkChangeListener().START
,E/Zygote  (12171): MountEmulatedStorage()
E/Zygote  (12171): v2
I/libpersona(12171): KNOX_SDCARD checking this for 10038
I/libpersona(12171): KNOX_SDCARD not a persona
,I/SELinux (12171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12151): NetworkChangeOperations(): uploadRequestLog().START 
,I/SELinux (12171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12171 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/SELinux (12171): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12151): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12151): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider(12171): TimaSignature is unavailable
I/KLMS-2.4.521: (12151): KLMSIntentService(): onDestroy()
,D/ActivityThread(12171): Added TimaKeyStore provider
,I/ActivityManager( 3524): Killing 11264:com.wsomacp/u0a28 (adj 15): bgCount ##31
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 02:32:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450233125552], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450233125535]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Validated
,D/ConnectivityService( 3524): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6648): CM callback handler got msg 524290
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
,D/ResourcesManager(12171): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12171): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12188): MountEmulatedStorage()
E/Zygote  (12188): v2
I/libpersona(12188): KNOX_SDCARD checking this for 1000
I/libpersona(12188): KNOX_SDCARD not a persona
,I/SELinux (12188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 11053:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12188): TimaSignature is unavailable
,D/ActivityThread(12188): Added TimaKeyStore provider
,D/ResourcesManager(12188): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12208): MountEmulatedStorage()
E/Zygote  (12208): v2
,I/libpersona(12208): KNOX_SDCARD checking this for 10039
I/libpersona(12208): KNOX_SDCARD not a persona
,I/SELinux (12208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12208): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12208 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11281:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12208): TimaSignature is unavailable
,D/ActivityThread(12208): Added TimaKeyStore provider
,D/ResourcesManager(12208): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12208): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12208): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12208): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12208): PushLog.txt file is not deleted.
D/SPPClientService(12208): PushLog.txt file is not deleted.
D/SPPClientService(12208): ============PushLog. stop!
,I/SA      (11365): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11365): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      (11365): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11365): [SLFUCHKMGR] constructor called
,I/SA      (11365): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11365): [OR] == isSIMCardReady false ==
,I/SA      (11365): [SCU] == networkStateCheck == true
,I/SA      (11365): [DM] getCountryCodeFromCSC : PL
I/SA      (11365): isChinaCountryCode : false
E/SPPClientService(12208): [[SystemStateMonitorService]] No Active Internet
I/SA      (11365): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11365): [OR] == networkStateCheck true ==
,I/SA      (11365): [OR] GetMyCountryZoneTask
I/SA      (11365): [OR] onReceive END
,I/SA      (11365): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11365): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11365): [SSP] query invoked
,I/ActivityManager( 3524): Killing 11295:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/SA      (11365): [TPMU] GetMccFromDB : null
I/SA      (11365): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11365): [TPM] isNoProxy(default) : true
E/lowmemorykiller( 2829): Error writing /proc/11295/oom_score_adj; errno=22
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  (12232): MountEmulatedStorage()
E/Zygote  (12232): v2
I/libpersona(12232): KNOX_SDCARD checking this for 10067
I/libpersona(12232): KNOX_SDCARD not a persona
,I/SELinux (12232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12232 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3524): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3524): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/TimaKeyStoreProvider(12232): TimaSignature is unavailable
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityThread(12232): Added TimaKeyStore provider
,I/DBG_DM  ( 6245): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6245): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5370): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5370): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 79431(4MB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 49MB/65MB, paused 11.836ms total 167.208ms
,I/NetworkMonitor(12017): type=WIFI subType= reason=null isConnected=true
,D/ResourcesManager(12232): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,I/sCloudBackupApp(12232): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12232): Other Intent
,I/ActivityManager( 3524): Killing 11345:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5100): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3800): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5100): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5100): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5100): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5100): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5100): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5100): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12250): MountEmulatedStorage()
I/libpersona(12250): KNOX_SDCARD checking this for 1000
E/Zygote  (12250): v2
I/libpersona(12250): KNOX_SDCARD not a persona
,I/SELinux (12250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12250 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12250): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12250): TimaSignature is unavailable
,D/ActivityThread(12250): Added TimaKeyStore provider
,D/ResourcesManager(12250): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12250): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12250): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12250): premStatus:2
,I/KnoxUsageLogPro(12250): isEulaShown : false
I/KnoxUsageLogPro(12250): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/SA      (11365): [RC New] Execute method=[GET] start
,E/Zygote  (12265): MountEmulatedStorage()
E/Zygote  (12265): v2
I/libpersona(12265): KNOX_SDCARD checking this for 10090
I/libpersona(12265): KNOX_SDCARD not a persona
,I/SELinux (12265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SA      (11365): [RC New] Security=[true]
,I/ActivityManager( 3524): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12265 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/System.out(11365): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/SELinux (12265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/System.out(11365): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11365): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11365): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager( 3524): Killing 11318:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/EnterpriseController( 2846): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2846): getNetworkForDns: using netid 503 for uid 10045
E/SELinux (12265): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12265): TimaSignature is unavailable
,D/ActivityThread(12265): Added TimaKeyStore provider
,D/ResourcesManager(12265): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12282): MountEmulatedStorage()
I/libpersona(12282): KNOX_SDCARD checking this for 10127
E/Zygote  (12282): v2
I/libpersona(12282): KNOX_SDCARD not a persona
,I/SELinux (12282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12282 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12282): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11435:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12282): TimaSignature is unavailable
,D/ActivityThread(12282): Added TimaKeyStore provider
,D/ResourcesManager(12282): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/ConnectivityService( 3524): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/KeyguardWallpaperUpdator(12282): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12282): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12282): stopCheckCategoryVersion
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12298): MountEmulatedStorage()
E/Zygote  (12298): v2
I/libpersona(12298): KNOX_SDCARD checking this for 10136
I/libpersona(12298): KNOX_SDCARD not a persona
,I/SELinux (12298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12298 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12298): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11452:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12298): TimaSignature is unavailable
,D/ActivityThread(12298): Added TimaKeyStore provider
,D/ResourcesManager(12298): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12298): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12298): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12298): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2831): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2831): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12298): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12298): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12298): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12298): Loading: webviewchromium
,I/LibraryLoader(12298): Time to load native libraries: 4 ms (timestamps 802-806)
I/LibraryLoader(12298): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12298): Binding Chromium to main looper Looper (main, tid 1) {10ec54f6}
,I/LibraryLoader(12298): Expected native library version number "",actual native library version number ""
I/chromium(12298): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12298): Initializing chromium process, renderers=0
,W/art     (12298): Attempt to remove local handle scope entry from IRT, ignoring
,W/AudioManagerAndroid(12298): Requires BLUETOOTH permission
,W/chromium(12298): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12298): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12298): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/SA      (11365): [RC New] [v2liruge] api execute + 612
,I/SA      (11365): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11365): AsyncTask #1 calls detatch()
,I/SA      (11365): [TPMU] getNetworkMcc : 
,I/SA      (11365): [SCU] saveMccToPreferece Start
,I/SA      (11365): [SCU] RegionMCC : 260
I/SA      (11365): [SSP] query invoked
,I/SA      (11365): [TPMU] GetMccFromDB : null
,I/SA      (11365): [SCU] getMccFromPreferece mcc = 260
I/SA      (11365): [SCU] saveMccToPreferece End
,I/SA      (11365): [RC New] executeRequest [v2liruge] end. 646
,I/SA      (11365): [RC New] Execute end
,I/SA      (11365): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11365): [OR] GetMyCountryZoneTask Success
,I/NSApplication(12298): Starting up...
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12365): MountEmulatedStorage()
E/Zygote  (12365): v2
I/libpersona(12365): KNOX_SDCARD checking this for 10150
I/libpersona(12365): KNOX_SDCARD not a persona
,I/SELinux (12365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12365 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (12365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12365): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 11468:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12365): TimaSignature is unavailable
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 935us total 25.976ms
,D/ActivityThread(12365): Added TimaKeyStore provider
,D/ResourcesManager(12365): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12365): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12365): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 841us total 19.052ms
W/ResourcesManager(12365): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 2882): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.505ms total 19.063ms
,D/QuickConnect(12365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12365): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12380): MountEmulatedStorage()
E/Zygote  (12380): v2
I/libpersona(12380): KNOX_SDCARD checking this for 10178
I/libpersona(12380): KNOX_SDCARD not a persona
,I/SELinux (12380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12380 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (12380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 11420:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12380): TimaSignature is unavailable
,D/ActivityThread(12380): Added TimaKeyStore provider
,D/ResourcesManager(12380): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12380): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12380): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12380): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12380): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12380): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/Zygote  (12403): MountEmulatedStorage()
E/Zygote  (12403): v2
I/libpersona(12403): KNOX_SDCARD checking this for 10082
I/libpersona(12403): KNOX_SDCARD not a persona
,I/SELinux (12403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12403 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/SELinux (12403): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12417): MountEmulatedStorage()
E/Zygote  (12417): v2
I/libpersona(12417): KNOX_SDCARD checking this for 1000
I/libpersona(12417): KNOX_SDCARD not a persona
,I/SELinux (12417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12417): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12417 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12403): TimaSignature is unavailable
,D/ActivityThread(12403): Added TimaKeyStore provider
,I/ActivityManager( 3524): Killing 11485:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/ActivityManager( 3524): Killing 11598:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12417): TimaSignature is unavailable
,D/ResourcesManager(12403): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ActivityThread(12417): Added TimaKeyStore provider
,D/BadgeProvider(12403): onCreate
D/BadgeProvider(12403): DatabaseHelper
D/ResourcesManager(12417): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12403): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3524): Killing 11617:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12403): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12403): sendNotify, [notify] : null
D/BadgeProvider(12403): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12403): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12403): update, [UpdateCount] : 1
D/Launcher.Model( 4002): reloadBadges entered.
,W/ActivityManager( 3524): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12437): MountEmulatedStorage()
I/libpersona(12437): KNOX_SDCARD checking this for 10013
E/Zygote  (12437): v2
I/libpersona(12437): KNOX_SDCARD not a persona
,I/SELinux (12437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12437 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12437): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12437): TimaSignature is unavailable
,D/ActivityThread(12437): Added TimaKeyStore provider
,D/ResourcesManager(12437): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/WaitQueueForNetworkActivate(12437): notifyNetworkActivated
,W/ContextImpl(12437): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3524): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12437): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12437): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12437): exit::IDLE
D/InitializeManagerStateMachine(12437): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12437): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12437): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12437): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12437): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12437): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12437): entry::SUCCESS
D/hcjo    (12437): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12437): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12437): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12437): exit::SUCCESS
D/InitializeManagerStateMachine(12437): entry::IDLE
,D/NearbySettings( 8901): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8901): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8901): DMSUtil.isNetworkConnected - P2P: IDLE
I/Hs20UtilService( 4069): Starting #10
,I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8901): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 4069): Message received 5007
,I/ActivityManager( 3524): Killing 11634:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/SignOutReceiver(11573): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4069): Starting #11
,I/Hs20UtilService( 4069): Message received 5007
,D/NearbySettings( 8901): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8901): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11573): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4069): Starting #12
,I/Hs20UtilService( 4069): Message received 5007
,D/NearbySettings( 8901): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8901): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 8901): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8901): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8901): MountReceiver.onReceive - Keep current state
,I/SignOutReceiver(11573): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4069): Starting #13
,I/Hs20UtilService( 4069): Message received 5007
,D/NearbySettings( 8901): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8901): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3524): callSECApi what=220
D/WifiStateMachine( 3524): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11573): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil(11994): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11994): sales region : global
I/PCWCLIENTTRACE_PushUtil(11994): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11994): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger( 2851): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3524): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
I/DIAGMON_AGENT(12085): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12085): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12120): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/jxcore-log(11857): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log(11857): 
,I/FOTA_Client(12120): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12151): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 03:32:08 GMT+01:00 2015
,I/KLMS-2.4.521: (12151): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12151): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12151): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12151): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12151): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12151): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12151): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(12171): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12151): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12151): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12151): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12151): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12151): KLMSIntentService(): onDestroy()
,E/SPPClientService(12208): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11365): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11365): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11365): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11365): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11365): [OR] == isSIMCardReady false ==
,I/SA      (11365): [SCU] == networkStateCheck == true
I/SA      (11365): [DM] getCountryCodeFromCSC : PL
I/SA      (11365): isChinaCountryCode : false
I/SA      (11365): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11365): [OR] == networkStateCheck true ==
I/SA      (11365): [OR] GetMyCountryZoneTask
,I/SA      (11365): [OR] onReceive END
,I/SA      (11365): [SRS] prepareGetMyCountryZone
,I/SA      (11365): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11365): [SSP] query invoked
,V/DownloadManager( 3716): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11365): [TPMU] GetMccFromDB : null
I/SA      (11365): [SCU] getMccFromPreferece mcc = 260
I/SA      (11365): [TPM] isNoProxy(default) : true
I/SA      (11365): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver(12232): Other Intent
,D/accuweather( 5100): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3800): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5100): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5100): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5100): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5100): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5100): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5100): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12250): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12250): premStatus:2
,I/KnoxUsageLogPro(12250): isEulaShown : false
I/KnoxUsageLogPro(12250): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      (11365): [RC New] Security=[true]
,D/KeyguardWallpaperUpdator(12282): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12282): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12282): stopCheckCategoryVersion
,D/QuickConnect(12365): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12365): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12365): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/hcjo    (12437): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12437): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12437): exit::IDLE
D/InitializeManagerStateMachine(12437): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12437): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12437): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12437): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12437): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12437): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12437): entry::SUCCESS
D/hcjo    (12437): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12437): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12437): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12437): exit::SUCCESS
D/InitializeManagerStateMachine(12437): entry::IDLE
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3524): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      (11365): [RC New] [v2liruge] api execute + 648
,I/SA      (11365): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11365): AsyncTask #2 calls detatch()
,I/SA      (11365): [TPMU] getNetworkMcc : 
,I/SA      (11365): [SCU] saveMccToPreferece Start
,I/SA      (11365): [SCU] RegionMCC : 260
,I/SA      (11365): [SSP] query invoked
,I/SA      (11365): [TPMU] GetMccFromDB : null
,I/SA      (11365): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11365): [SCU] saveMccToPreferece End
,I/SA      (11365): [RC New] executeRequest [v2liruge] end. 722
,I/SA      (11365): [RC New] Execute end
,I/SA      (11365): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11365): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12053): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12053): wlan0: sendmsg: Cannot assign requested address
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2846): QcRouteController
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,V/        ( 2846): QcRouteController
,W/NetworkManagementService( 3524): route cmd failed: 
W/NetworkManagementService( 3524): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3524): '
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
,W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3524): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3524): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6648): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6648): CM callback handler got msg 524295
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 274, CUR = 56,
,D/WearableService( 4675): callingUid 10014, callindPid: 4675
,D/ResourcesManager(12017): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12017): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12017): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12017): Using the GMSCore's GoogleHttpClient
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12017): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12017): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12017): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback(12017): Conditions not met for autocaching.
I/MusicLeanback(12017): Stop autocaching.
,E/ActivityThread(12017): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3cfae7b6 that was originally bound here
E/ActivityThread(12017): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3cfae7b6 that was originally bound here
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
,D/PackageManager( 3524): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SurfaceFlinger( 2851): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2851): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3524): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3524) eventTime = 145446
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524 (0x0)
,D/PowerManagerService( 3524): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3524, ws=WorkSource{10060}) (elapsedTime=3507)
,I/GAV4    (12298): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver(11994): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11994): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11994): ================================================
,I/CSTORAGE(11994):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11994): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11994): [GetString-S]
,E/art     (11994): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11994): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/dhcpcd  (12053): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11994): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11994): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11994): sales region : global
I/PCWCLIENTTRACE_PushUtil(11994): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler(11994): [ensureRegistration] - No Samsung account
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12568
,I/dhcpcd  (12053): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12053): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12437): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12437): exit::IDLE
D/PreloadUpdateManagerStateMachine(12437): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12437): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12437): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12437): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12437): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12437): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12437): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12437): exit::IDLE
D/PreloadUpdateManagerStateMachine(12437): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12437): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12437): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12437): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12437): entry::IDLE
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 269, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4675): disconnect managed GoogleApiClient
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{7771412 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/Watchdog( 3524): !@Sync 5
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 266, CUR = 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 105s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 264, CUR = 46
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12617
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 263, CUR = 47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 6
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 259, CUR = 45
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 140s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 254, CUR = 42
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 251, CUR = 40
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
I/EventLogService( 6648): Aggregate from 1450231378261 (log), 1450231378261 (data)
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 39868(2MB) AllocSpace objects, 27(432KB) LOS objects, 24% free, 49MB/65MB, paused 2.305ms total 148.501ms
,E/Watchdog( 3524): !@Sync 7
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 250, CUR = 38,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 247, CUR = 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 180s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 245, CUR = 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 8
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 244, CUR = 35
,V/AlarmManager( 3524): waitForAlarm result :8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 243, CUR = 33
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 242, CUR = 33
,I/jxcore-log(11857): Connected to the server!
I/jxcore-log(11857): 
,I/chromium(11857): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 9
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 241, CUR = 33
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 225s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 241, CUR = 32
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 32
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3524): initializing...
,I/TLC_TIMA_PKM_initialize( 3524): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3524): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3524): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3524): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3524): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3524): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 3524): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3524): device_id = 0x0
I/TZ: mc_tlc_communication( 3524): tlc_open() was called
I/TZ: mc_tlc_communication( 3524): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3524): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3524): Opening the session
,I/TZ: mc_tlc_communication( 3524): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3524): Trustlet response is completed
,E/Watchdog( 3524): !@Sync 10
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12773
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 30
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 29
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 275s ago
,E/Watchdog( 3524): !@Sync 11
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 12
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 27
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 330s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 26
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 13
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 240, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 239, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 239, CUR = 25
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 14
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 237, CUR = 22
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 237, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 390s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 237, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 15
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 236, CUR = 23
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged,
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 235, CUR = 22,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 235, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 16
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 235, CUR = 22
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 234, CUR = 23
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 233, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 455s ago
,E/Watchdog( 3524): !@Sync 17
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 233, CUR = 23
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 233, CUR = 22
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 232, CUR = 21
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 18
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 232, CUR = 20
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 232, CUR = 20
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 231, CUR = 20,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 19
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 231, CUR = 20
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 525s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 231, CUR = 20
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 19,
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3524): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 19
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 18
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 3524): Killing 11675:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 21
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 17,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 600s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 22
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 17
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 17
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged,
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 23
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 17,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 24
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 680s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 25
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 26
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 16
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 27
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,I/PowerManagerService( 3524): [PWL] Off : 765s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 28
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 14
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 29
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 14
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/LightsService( 3524): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3524): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3524): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,I/Sensors ( 3524): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3524): unregisterListener ::   
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 15
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 30
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 14
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 855s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 31
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 32
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 33
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 950s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 34
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 35
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9,
,E/Watchdog( 3524): !@Sync 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3524): !@Sync 37
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3524): !@Sync 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3524): !@Sync 39
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3524): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3524): handleMessage : MSG_UPDATE_USAGE_DB
I/ApplicationUsage( 3524): Updating Usage Statistics in DB @ 1450234197597
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350),
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
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
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
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
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
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
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
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
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3524): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3524): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
,W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
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
W/System.err( 3524): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3524): ::getAppControlDB: Exception to create DB
W/System.err( 3524): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3524): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
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
I/ApplicationUsage( 3524): Done Updating Usage Statistics in DB @ 1450234197653
,E/Watchdog( 3524): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,I/PowerManagerService( 3524): [PWL] Off : 1155s ago,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3524): !@Sync 41
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 11
,E/Watchdog( 3524): !@Sync 42
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3524): !@Sync 43
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,I/PowerManagerService( 3524): [PWL] Off : 1265s ago
,E/Watchdog( 3524): !@Sync 44
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3524): !@Sync 45
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7,
,E/Watchdog( 3524): !@Sync 46
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3524): !@Sync 47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 10
,I/PowerManagerService( 3524): [PWL] Off : 1380s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3524): !@Sync 48
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 49
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3524): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3524): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/art     ( 3524): Background sticky concurrent mark sweep GC freed 81797(9MB) AllocSpace objects, 398(6MB) LOS objects, 13% free, 49MB/57MB, paused 3.521ms total 113.060ms
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 51
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 52
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 53
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3,
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 54
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-17
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 55
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,I/PowerManagerService( 3524): [PWL] Off : 1625s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 56
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 57
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/BatteryService( 3524): stay LED for fully charged
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 58,
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 59
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,V/AlarmManager( 3524): waitForAlarm result :4
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,V/AlarmManager( 3524): waitForAlarm result :4
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/LightsService( 3524): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3524): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/NetworkStatsFactory( 3524): UpdateStatsForKnox
,V/AlarmManager( 3524): OOI=Alarm{161f909c type 0 when 1450236585975 com.google.android.gms}
,V/AlarmManager( 3524): waitForAlarm result :8
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3524): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3524): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3524): unregisterListener ::   
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3524): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3524): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3524): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3524): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3524): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3524): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,V/AlarmManager( 3524): waitForAlarm result :8
,I/ProcessStatsService( 3524): Prepared write state in 22ms
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,I/ProcessStatsService( 3524): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-44-48.bin
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,I/PowerManagerService( 3524): [PWL] Off : 1755s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3524): !@Sync 61
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 62
,V/AlarmManager( 3524): waitForAlarm result :8
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 4,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 63
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-18
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-23
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 64
,I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5639): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms)
```
