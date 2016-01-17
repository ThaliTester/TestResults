#### Test 56151093914d164_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 269, CUR = 40
I/PowerManagerService( 3524): [PWL] Off : 50s ago
D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:53, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
D/BatteryService( 3524): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11696): 
D/AndroidRuntime(11696): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11696): CheckJNI is OFF
D/AndroidRuntime(11696): readGMSProperty: start
D/AndroidRuntime(11696): readGMSProperty: already setted!!
D/AndroidRuntime(11696): readGMSProperty: end
D/AndroidRuntime(11696): addProductProperty: start
E/AffinityControl(11696): AffinityControl: registerfunction enter
D/AndroidRuntime(11696): Calling main entry com.android.commands.am.Am
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
E/Zygote  (11721): MountEmulatedStorage()
I/libpersona(11721): KNOX_SDCARD checking this for 10580
E/Zygote  (11721): v2
I/libpersona(11721): KNOX_SDCARD not a persona
I/SELinux (11721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11721): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11721 uid=10580 gids={50580, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/AndroidRuntime(11696): Shutting down VM
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
I/art     ( 2881): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 816us total 38.754ms
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11721): TimaSignature is unavailable
D/ActivityThread(11721): Added TimaKeyStore provider
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 877us total 25.290ms
I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 810us total 18.386ms
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11721): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6222): updateVisibility : ActivityRecord{12c8a7cf token=android.os.BinderProxy@247eecb0 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11721): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11721): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11721): Loading: webviewchromium
I/LibraryLoader(11721): Time to load native libraries: 3 ms (timestamps 5145-5148)
I/LibraryLoader(11721): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11721): Binding Chromium to main looper Looper (main, tid 1) {21b0b3e}
I/LibraryLoader(11721): Expected native library version number "",actual native library version number ""
I/chromium(11721): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11721): Initializing chromium process, renderers=0
,W/art     (11721): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11721): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11721): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11721): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11721): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11721): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11721): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11721): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11721): CordovaWebView is running on device made by: samsung
,W/art     (11721): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11721): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11721): performCreate Call secproduct feature valuefalse
D/Activity(11721): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11721): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2852): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11721): Initialized EGL, version 1.4
,I/OpenGLRenderer(11721): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278758640 
,D/OpenGLRenderer(11721): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11721): Enabling debug mode 0
,D/mali_winsys(11721): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11721): updateVisibility : ActivityRecord{3bebfee token=android.os.BinderProxy@3bed50fd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(11721): showStatusIcon on inactive InputConnection
I/Timeline(11721): Timeline: Activity_idle id: android.os.BinderProxy@3bed50fd time:145479
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{1bbc50d1 u0 com.test.thalitest/.MainActivity t26} time:145487
,D/JsMessageQueue(11721): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11721): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11721): 
,D/jxcore_app_log(11721): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11721): jxcore cordova android initializing
,W/jxcore-log(11721): Initializing JXcore engine
W/jxcore-log(11721): JXcore engine is ready
,W/jxcore-log(11721): Starting JXcore engine
,E/auditd  ( 4608): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11721): Platform android
W/jxcore-log(11721): 
W/jxcore-log(11721): Process ARCH arm
W/jxcore-log(11721): 
,I/jxcore-log(11721): JXcore Cordova bridge is ready!
I/jxcore-log(11721): 
W/jxcore-log(11721): JXcore engine is started
,I/Choreographer(11721): Skipped 58 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log(11721): Toggling radios to true
I/jxcore-log(11721): 
,D/BluetoothAdapter(11721): enable()
,D/BluetoothAdapter(11721): enable(): BT is already enabled..!
,D/WifiService( 3524): New client listening to asynchronous messages
,I/WifiManager(11721): packageName : com.test.thalitest
,D/SecContentProvider( 3524): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3524): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3524): mCursor = null
D/WifiService( 3524): setWifiEnabled: true pid=11721, uid=10580
E/WifiService( 3524): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3524): Permission Denial: getCurrentUser() from pid=11721, uid=10580 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3524): Failed getting userId using ActivityManagerNative
W/WifiService( 3524): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11721, uid=10580 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3524): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3524): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3524): name = wifi_on
,I/WifiService( 3524): disconnect: pid=11721, uid=10580
,I/wpa_supplicant( 3829): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3829): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3829): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3524): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3829): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): Disconnected - do not scan
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3524): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11721): Radios toggled
I/jxcore-log(11721): 
,I/jxcore-log(11721): My device name is: samsung-SM-N910C
I/jxcore-log(11721): 
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/CommandListener( 2848): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2848): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3524): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3524): updateNetworkInfo()
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3524): updateNetworkInfo()
,D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4116): Starting #8
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8822): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8822): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8822): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8822): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8822): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,E/WifiStateMachine( 3524): Start Disconnecting Watchdog 1
E/WifiStateMachine( 3524): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3524): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3524): do suspend true
D/WifiService( 3524): New client listening to asynchronous messages
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8822): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8822): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,I/SignOutReceiver(11333): NETWORK_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2848): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3524): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - currTime: 1453043051444
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
D/WifiStateMachine( 3524): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityService( 3524): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 3524): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3524): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/wpa_supplicant( 3829): P2P: Current p2p state = IDLE
D/TelephonyNetworkFactory( 3980): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3829): First Scan Start
,D/ConnectivityManager.CallbackHandler( 6690): CM callback handler got msg 524292
I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/wpa_supplicant( 3829): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3524): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3524): NetworkAgent: NetworkAgent channel lost
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3524): Not allowed due to - mEnabled false
,D/Tethering( 3524): MasterInitialState.processMessage what=3
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/ConnectivityService( 3524): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,V/NetworkStats( 3524): updateIfacesLocked()
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked(flags=0x1)
D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/NetworkStatsFactory( 3524): UpdateStatsForKnox
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,I/Hs20UtilService( 4116): Starting #9
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
I/Hs20UtilService( 4116): Message received 5007
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,D/NearbySettings( 8822): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8822): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked() took 13ms
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8822): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8822): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,I/SignOutReceiver(11333): NETWORK_STATE_CHANGED_ACTION
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
I/ApplicationPolicy( 3524): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3524): No Active Data Connection
,I/DBG_DM  ( 6222): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6222): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11818): MountEmulatedStorage()
E/Zygote  (11818): v2
I/libpersona(11818): KNOX_SDCARD checking this for 10110
I/libpersona(11818): KNOX_SDCARD not a persona
,I/SELinux (11818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11818 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux (11818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11818): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11818): TimaSignature is unavailable
,D/ActivityThread(11818): Added TimaKeyStore provider
,D/ResourcesManager(11818): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11818): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11818): not using cross-dex optimization: ART in use
,I/art     (11818): Thread[1,tid=11818,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11818): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11818): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(11818): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11818): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11818): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11818): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(11818): loading pre-built fallback odex files
,V/MultiDexClassLoader(11818): installing MultiDexClassLoader before application classloader
D/DexLibLoader(11818): released odex store lock
D/DexLibLoader(11818): DexLibLoader.loadAll took 17 ms
,W/ca      (11818): Verify
,W/LightSharedPreferencesImpl(11818): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11818): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11818): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11818): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11818): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11818): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11818): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11818): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11818): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11818): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11818): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11818): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11818): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11818): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11818): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11818): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11818): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11818): 	... 10 more
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11843): MountEmulatedStorage()
E/Zygote  (11843): v2
I/libpersona(11843): KNOX_SDCARD checking this for 1000
I/libpersona(11843): KNOX_SDCARD not a persona
,I/SELinux (11843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11843 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10847:com.android.mms/u0a52 (adj 15): bgCount ##31
,E/SELinux (11843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/appmanager(:<default>):b(11818): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/lowmemorykiller( 2830): Error writing /proc/10847/oom_score_adj; errno=22
,W/appmanager(:<default>):b(11818): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11843): TimaSignature is unavailable
,D/ActivityThread(11843): Added TimaKeyStore provider
,D/CountryDetector( 3524): No listener is left
,D/ResourcesManager(11843): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11818): Exposure of experiment com.facebook.common.network.l@39fa6e0d occurred when no user was logged in
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1d5a339c u0 ReceiverList{322a370f 11818 com.facebook.appmanager/10110/u0 remote:381246e}}
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1d5a339c u0 ReceiverList{322a370f 11818 com.facebook.appmanager/10110/u0 remote:381246e}}
,I/PCWCLIENTTRACE_LOG(11843): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11843): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11843): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): noConnectivity : true
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11874): MountEmulatedStorage()
I/libpersona(11874): KNOX_SDCARD checking this for 10135
E/Zygote  (11874): v2
I/libpersona(11874): KNOX_SDCARD not a persona
,I/SELinux (11874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11874): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11874 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10932:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11874): TimaSignature is unavailable
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1e75b559 u0 ReceiverList{19b1e5a0 11818 com.facebook.appmanager/10110/u0 remote:1e111ea3}}
D/ActivityThread(11874): Added TimaKeyStore provider
,D/ResourcesManager(11874): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11874): Database version: 104
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(11874): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11874): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11874): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11874): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11874): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11874): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e28b0b2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11874): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11874): GMSCore installation verified
,I/ConfigStore(11874): Config Database version: 1
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11818): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11818): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11874): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(11818): Exposure of experiment com.facebook.imagepipeline.a.g@9d03f42 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11818): Exposure of experiment com.facebook.imagepipeline.a.d@149639af occurred when no user was logged in
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11874): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11874): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     (11818): Explicit concurrent mark sweep GC freed 42568(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 673us total 21.576ms
,W/appmanager(:<default>):m(11818): No feature status reporters found; is this dead code?
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3524): getStreamVolume 3 index 0
,I/MediaRouter(11874): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11904): MountEmulatedStorage()
I/libpersona(11904): KNOX_SDCARD checking this for 10002
E/Zygote  (11904): v2
I/libpersona(11904): KNOX_SDCARD not a persona
I/SELinux (11904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11904 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3829): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 3829): wlan0: Setting scan request: 8 sec 0 usec
D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/wpa_supplicant( 3829): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3829): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine( 3524): [1,453,043,052,528 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3524): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@aa34d49 sup_state=SCANNING debouncing=false
,D/TimaKeyStoreProvider(11904): TimaSignature is unavailable
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
D/ActivityThread(11904): Added TimaKeyStore provider
E/WifiStateMachine( 3524): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3524): setDetailed state send new extra info
,I/NetworkMonitor(11874): type=WIFI subType= reason=null isConnected=false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/ActivityManager( 3524): Killing 10949:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/lowmemorykiller( 2830): Error writing /proc/10949/oom_score_adj; errno=22
,D/ResourcesManager(11904): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3524): Killing 10971:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11923): MountEmulatedStorage()
I/libpersona(11923): KNOX_SDCARD checking this for 1000
E/Zygote  (11923): v2
I/libpersona(11923): KNOX_SDCARD not a persona
,I/SELinux (11923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11923): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11923 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11923): TimaSignature is unavailable
,D/ActivityThread(11923): Added TimaKeyStore provider
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3829): Associated with C0.AA.48
E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3524): setDetailed state send new extra info"NG700"
,D/ResourcesManager(11923): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,I/DIAGMON_AGENT(11923): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3829): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3829): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3829): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3829): Blacklist: Clear (temp) 
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3524): Network connection established
D/WifiNative-HAL( 3524): callSECApiVoid - ID [50]
E/WifiStateMachine( 3524): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3524): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3524): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3524): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3524): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine( 3524): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3524): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3524): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2848): Setting iface cfg
,E/WifiStateMachine( 3524): Start Dhcp Watchdog 2
D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3524): mCursor = null
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(11923): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11923): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11923): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11923): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11940): MountEmulatedStorage()
E/Zygote  (11940): v2
I/libpersona(11940): KNOX_SDCARD checking this for 10012
I/libpersona(11940): KNOX_SDCARD not a persona
,I/SELinux (11940): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11940): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11940): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=11940 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend false
,D/SecContentProvider2( 3524): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/SecContentProvider2( 3524): mCursor = null
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider(11940): TimaSignature is unavailable
,D/ActivityThread(11940): Added TimaKeyStore provider
,D/ResourcesManager(11940): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3524): Killing 10984:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
E/lowmemorykiller( 2830): Error writing /proc/10984/oom_score_adj; errno=22
,I/FOTA_Client(11940): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11940): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11940): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11956): MountEmulatedStorage()
I/libpersona(11956): KNOX_SDCARD checking this for 10021
E/Zygote  (11956): v2
I/libpersona(11956): KNOX_SDCARD not a persona
,I/SELinux (11956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11956 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/lowmemorykiller( 2830): Error writing /proc/11005/oom_score_adj; errno=22
I/ActivityManager( 3524): Killing 11005:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11956): TimaSignature is unavailable
,D/ActivityThread(11956): Added TimaKeyStore provider
,D/ResourcesManager(11956): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (11956): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 16:04:12 GMT+01:00 2016
,I/KLMS-2.4.521: (11956): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11956): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11956): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11956): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (11956): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.521: (11956): StateImplV2(): networkChangeListener().END
,E/Zygote  (11972): MountEmulatedStorage()
I/libpersona(11972): KNOX_SDCARD checking this for 10038
E/Zygote  (11972): v2
I/libpersona(11972): KNOX_SDCARD not a persona
I/SELinux (11972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=11972 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3524): Killing 11042:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11972): TimaSignature is unavailable
,D/ActivityThread(11972): Added TimaKeyStore provider
,D/ResourcesManager(11972): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(11972): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11988): MountEmulatedStorage()
I/libpersona(11988): KNOX_SDCARD checking this for 1000
E/Zygote  (11988): v2
I/libpersona(11988): KNOX_SDCARD not a persona
I/SELinux (11988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=11988 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10816:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11988): TimaSignature is unavailable
,D/ActivityThread(11988): Added TimaKeyStore provider
,E/dhcpcd  (12003): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12003): version 5.5.6 starting
,D/ResourcesManager(11988): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/dhcpcd  (12003): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12003): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12003): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12003): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12003): bssid match
,I/dhcpcd  (12003): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12015): MountEmulatedStorage()
I/libpersona(12015): KNOX_SDCARD checking this for 10039
E/Zygote  (12015): v2
I/libpersona(12015): KNOX_SDCARD not a persona
,I/SELinux (12015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12015): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12015 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11062:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12015): TimaSignature is unavailable
,D/ActivityThread(12015): Added TimaKeyStore provider
,D/ResourcesManager(12015): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12015): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12015): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12015): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12015): PushLog.txt file is not deleted.
D/SPPClientService(12015): PushLog.txt file is not deleted.
D/SPPClientService(12015): ============PushLog. stop!
,I/SA      (11111): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11111): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11111): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11111): [SLFUCHKMGR] constructor called
,E/SPPClientService(12015): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11111): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11111): [OR] == isSIMCardReady false ==
,I/SA      (11111): [SCU] == networkStateCheck == false
I/SA      (11111): [OR] onReceive END
,V/DownloadManager( 5505): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 3524): Killing 11020:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12035): MountEmulatedStorage()
I/libpersona(12035): KNOX_SDCARD checking this for 10067
E/Zygote  (12035): v2
I/libpersona(12035): KNOX_SDCARD not a persona
,I/SELinux (12035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12035 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8748(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 460us total 11.095ms
,D/TimaKeyStoreProvider(12035): TimaSignature is unavailable
,D/ActivityThread(12035): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 401us total 8.393ms
,D/ResourcesManager(12035): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 260us total 8.263ms
,I/sCloudBackupApp(12035): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12035): Other Intent
,I/ActivityManager( 3524): Killing 11127:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/accuweather( 5215): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3779): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5215): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12051): MountEmulatedStorage()
I/libpersona(12051): KNOX_SDCARD checking this for 1000
E/Zygote  (12051): v2
I/libpersona(12051): KNOX_SDCARD not a persona
,I/SELinux (12051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12051): TimaSignature is unavailable
,D/ActivityThread(12051): Added TimaKeyStore provider
,D/ResourcesManager(12051): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12051): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12051): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12051): premStatus:2
,I/KnoxUsageLogPro(12051): isEulaShown : false
I/KnoxUsageLogPro(12051): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12066): MountEmulatedStorage()
E/Zygote  (12066): v2
I/libpersona(12066): KNOX_SDCARD checking this for 10090
I/libpersona(12066): KNOX_SDCARD not a persona
,I/SELinux (12066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12066): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12066 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11083:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11721): 
,D/TimaKeyStoreProvider(12066): TimaSignature is unavailable
,D/ActivityThread(12066): Added TimaKeyStore provider
,D/ResourcesManager(12066): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12083): MountEmulatedStorage()
E/Zygote  (12083): v2
I/libpersona(12083): KNOX_SDCARD checking this for 10127
I/libpersona(12083): KNOX_SDCARD not a persona
,I/SELinux (12083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12083 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11196:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12083): TimaSignature is unavailable
,D/ActivityThread(12083): Added TimaKeyStore provider
,D/ResourcesManager(12083): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12083): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12083): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12083): stopCheckCategoryVersion
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12100): MountEmulatedStorage()
I/libpersona(12100): KNOX_SDCARD checking this for 10136
E/Zygote  (12100): v2
I/libpersona(12100): KNOX_SDCARD not a persona
I/SELinux (12100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12100): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12100 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11212:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12100): TimaSignature is unavailable
,D/ActivityThread(12100): Added TimaKeyStore provider
,D/ResourcesManager(12100): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12100): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/ContextImpl(12100): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12100): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12100): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12100): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12100): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12100): Loading: webviewchromium
,I/LibraryLoader(12100): Time to load native libraries: 2 ms (timestamps 8868-8870)
I/LibraryLoader(12100): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12100): Binding Chromium to main looper Looper (main, tid 1) {6ed25fe}
,I/LibraryLoader(12100): Expected native library version number "",actual native library version number ""
,I/chromium(12100): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12100): Initializing chromium process, renderers=0
,W/art     (12100): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12100): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12100): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12100): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12100): Requires BLUETOOTH permission
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11721): 
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11721): 
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11721): 
,I/NSApplication(12100): Starting up...
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11721): 
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11721): 
,I/jxcore-log(11721): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11721): 
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12168): MountEmulatedStorage()
E/Zygote  (12168): v2
I/libpersona(12168): KNOX_SDCARD checking this for 10150
I/libpersona(12168): KNOX_SDCARD not a persona
,I/SELinux (12168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12168 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11181:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12168): TimaSignature is unavailable
,D/ActivityThread(12168): Added TimaKeyStore provider
,D/ResourcesManager(12168): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12168): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12168): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12168): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12168): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12168): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12168): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12183): MountEmulatedStorage()
I/libpersona(12183): KNOX_SDCARD checking this for 10178
E/Zygote  (12183): v2
I/libpersona(12183): KNOX_SDCARD not a persona
,I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12183 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11229:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
,D/ActivityThread(12183): Added TimaKeyStore provider
,D/ResourcesManager(12183): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12183): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12183): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12183): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12183): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12183): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12183): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,I/dhcpcd  (12003): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,E/Zygote  (12206): MountEmulatedStorage()
E/Zygote  (12206): v2
I/libpersona(12206): KNOX_SDCARD checking this for 10082
I/libpersona(12206): KNOX_SDCARD not a persona
I/SELinux (12206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12206): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12206 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12206): TimaSignature is unavailable
,D/ActivityThread(12206): Added TimaKeyStore provider
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12206): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(12206): onCreate
D/BadgeProvider(12206): DatabaseHelper
,E/Zygote  (12222): MountEmulatedStorage()
E/Zygote  (12222): v2
I/libpersona(12222): KNOX_SDCARD checking this for 1000
I/libpersona(12222): KNOX_SDCARD not a persona
,I/SELinux (12222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 11353:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3524): Killing 11248:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##32
I/SELinux (12222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/lowmemorykiller( 2830): Error writing /proc/11248/oom_score_adj; errno=22
,I/dhcpcd  (12003): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/TimaKeyStoreProvider(12222): TimaSignature is unavailable
,D/ActivityThread(12222): Added TimaKeyStore provider
,D/ResourcesManager(12222): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,I/ActivityManager( 3524): Killing 11370:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,W/ActivityManager( 3524): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 6690): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6690): num queued entries: 0
,I/iu.UploadsManager( 6690): num updated entries: 0
I/iu.SyncManager( 6690): NEXT; no task
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 70439(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 49MB/65MB, paused 4.260ms total 98.107ms
,E/Zygote  (12254): MountEmulatedStorage()
E/Zygote  (12254): v2
I/libpersona(12254): KNOX_SDCARD checking this for 10013
I/libpersona(12254): KNOX_SDCARD not a persona
,I/SELinux (12254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12254): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12254 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/BadgeProvider(12206): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/jxcore-log(11721): Test app app.js loaded
I/jxcore-log(11721): 
,D/TimaKeyStoreProvider(12254): TimaSignature is unavailable
,D/ActivityThread(12254): Added TimaKeyStore provider
,I/Choreographer(11721): Skipped 158 frames!  The application may be doing too much work on its main thread.
,D/ResourcesManager(12254): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/BadgeProvider(12206): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12206): sendNotify, [notify] : null
D/BadgeProvider(12206): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12206): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12206): update, [UpdateCount] : 1
,D/Launcher.Model( 4004): reloadBadges entered.
,I/chromium(11721): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium(11721): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager( 3524): Killing 11387:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,I/Hs20UtilService( 4116): Starting #10
I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8822): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8822): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8822): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8822): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11333): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3524): do suspend true
,D/WifiP2pService( 3524): InactiveState{ what=143375 }
D/WifiP2pService( 3524): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3524): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3524): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3524): Not connected state, yet.
E/WifiStateMachine( 3524): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3524): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3524): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3524): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3524): callSECApiInt - ID [210]
,E/WifiStateMachine( 3524): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService( 3524): updateNetworkInfo()
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3524): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3524): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3524): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3524): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3524): Now, connected state.
E/WifiStateMachine( 3524): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3524): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3524): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL( 3524): callSECApiVoid - ID [212]
,D/ConnectivityService( 3524): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine( 3524): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService( 3524): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,D/ConnectivityService( 3524): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3524): Unexpected mtu value: 0, wlan0
,V/        ( 2848): QcRouteController
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,I/Hs20UtilService( 4116): Starting #11,
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8822): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8822): MountReceiver.onReceive - Keep current state
,V/        ( 2848): QcRouteController
,V/        ( 2848): QcRouteController
,I/SignOutReceiver(11333): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2848): QcRouteController
,I/Hs20UtilService( 4116): Starting #12
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings( 8822): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8822): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8822): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8822): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8822): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8822): MountReceiver.mPrefHandler - 7002
,V/        ( 2848): QcRouteController
,I/SignOutReceiver(11333): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4116): Starting #13
,I/Hs20UtilService( 4116): Message received 5007
V/        ( 2848): QcRouteController
,V/        ( 2848): QcRouteController
,D/NearbySettings( 8822): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8822): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine( 3524): callSECApi what=220
D/WifiStateMachine( 3524): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        ( 2848): QcRouteController
,I/SignOutReceiver(11333): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3524): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3524): LTETest block dns file not exists
,D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3524): updateNetworkInfo()
E/ConnectivityService( 3524): updateNetworkInfo()
D/ConnectivityService( 3524): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3524): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3524):    accepting network in place of null
,D/TelephonyNetworkFactory( 3980): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3524): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3524): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService( 3524): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,I/System.out( 3524): (HTTPLog)-Static: isSBSettingEnabled false
D/Tethering( 3524): MasterInitialState.processMessage what=3
D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/Netd    ( 2848): getNetworkForDns: using netid 503 for uid 1000
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/EntConnectivity( 3524): Not allowed due to - mEnabled false
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,V/NetworkStats( 3524): updateIfacesLocked()
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): performPollLocked(flags=0x1)
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
,D/NetworkStatsFactory( 3524): UpdateStatsForKnox
D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 6690): CM callback handler got msg 524290
,V/NetworkStats( 3524): performPollLocked() took 7ms
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,I/SurfaceFlinger( 2852): id=15 createSurf (1x1),1 flag=4, Uoast
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
V/NetworkStats( 3524): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3524): currentTimeMillis() cache hit
,D/PowerManagerService( 3524): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524
,D/mali_winsys( 3694): new_window_surface returns 0x3000,  [1120x201]-format:1
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
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
,I/System.out( 3524): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:04:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453043054396], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453043054379]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3524): Validated
D/ConnectivityService( 3524): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3524): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3524): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 6690): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3524): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3524): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3524): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getSBEnabled() enabled =false
,D/SmartBondingService( 3524): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 6222): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6222): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5357): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5357): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/NetworkMonitor(11874): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3524): mCursor = null
,I/DIAGMON_AGENT(11923): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(11923): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(11940): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(11940): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(11940): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (11956): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 16:04:15 GMT+01:00 2016
,I/KLMS-2.4.521: (11956): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11956): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (11956): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (11956): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SO_AGENT(11972): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (11956): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (11956): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (11956): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (11956): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (11956): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onDestroy()
,E/SPPClientService(12015): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11111): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11111): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11111): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11111): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11111): [OR] == isSIMCardReady false ==
,I/SA      (11111): [SCU] == networkStateCheck == true
I/SA      (11111): [DM] getCountryCodeFromCSC : PL
I/SA      (11111): isChinaCountryCode : false
I/SA      (11111): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11111): [OR] == networkStateCheck true ==
,I/SA      (11111): [OR] GetMyCountryZoneTask
I/SA      (11111): [OR] onReceive END
,I/SA      (11111): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 5505): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11111): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11111): [SSP] query invoked
,I/SCloudBackupReceiver(12035): Other Intent
,I/SA      (11111): [TPMU] GetMccFromDB : null
,I/SA      (11111): [SCU] getMccFromPreferece mcc = 260
I/SA      (11111): [TPM] isNoProxy(default) : true
D/accuweather( 5215): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3779): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5215): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5215): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5215): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5215): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5215): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12051): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12051): premStatus:2
,I/KnoxUsageLogPro(12051): isEulaShown : false
I/KnoxUsageLogPro(12051): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12083): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12083): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12083): stopCheckCategoryVersion
,D/QuickConnect(12168): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12168): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12168): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/ConnectivityService( 3524): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/iu.Environment( 6690): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6690): num queued entries: 0
,I/iu.UploadsManager( 6690): num updated entries: 0
,I/iu.SyncManager( 6690): NEXT; no task
,D/WaitQueueForNetworkActivate(12254): notifyNetworkActivated
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12254): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3524): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12254): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12254): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12254): exit::IDLE
D/InitializeManagerStateMachine(12254): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12254): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12254): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12254): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12254): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12254): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12254): entry::SUCCESS
D/hcjo    (12254): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12254): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12254): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12254): exit::SUCCESS
D/InitializeManagerStateMachine(12254): entry::IDLE
,I/SA      (11111): [RC New] Execute method=[GET] start
,I/SA      (11111): [RC New] Security=[true]
,I/System.out(11111): Thread-1510(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11111): Thread-1510(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11111): Thread-1510(ApacheHTTPLog):isShipBuild true
I/System.out(11111): Thread-1510(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 503 for uid 10045
,I/SA      (11111): [RC New] [v2liruge] api execute + 832
,I/SA      (11111): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11111): AsyncTask #1 calls detatch()
,I/SA      (11111): [TPMU] getNetworkMcc : 
,I/SA      (11111): [SCU] saveMccToPreferece Start
,I/SA      (11111): [SCU] RegionMCC : 260
,I/SA      (11111): [SSP] query invoked
,I/SA      (11111): [TPMU] GetMccFromDB : null
,I/SA      (11111): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11111): [SCU] saveMccToPreferece End
,I/SA      (11111): [RC New] executeRequest [v2liruge] end. 938
,I/SA      (11111): [RC New] Execute end
,I/SA      (11111): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11111): [OR] GetMyCountryZoneTask Success
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12348
,I/dhcpcd  (12003): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12003): wlan0: sendmsg: Cannot assign requested address
,I/WifiStateMachine( 3524): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3524): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WearableService( 4646): callingUid 10014, callindPid: 4646
,D/ResourcesManager(11874): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11874): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11874): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11874): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(11874): Conditions not met for autocaching.
I/MusicLeanback(11874): Stop autocaching.
,D/WearableClient(11874): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11874): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11874): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11874): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11874): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils(11874): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(11874): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3c02b06c that was originally bound here
E/ActivityThread(11874): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3c02b06c that was originally bound here
E/ActivityThread(11874): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11874): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11874): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11874): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11874): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11874): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11874): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11874): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11874): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11874): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11874): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11874): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11874): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11874): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11874): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11874): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11874): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11874): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11874): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11874): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11874): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/SurfaceFlinger( 2852): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2852): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3524): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3524) eventTime = 153123
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3524 (0x0)
D/PowerManagerService( 3524): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3524, ws=WorkSource{10060}) (elapsedTime=3477)
,E/WifiStateMachine( 3524): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine( 3524): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3524): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2848): QcRouteController
,D/SmartBondingService( 3524): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3524): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
D/SmartBondingService( 3524): getSBEnabled() enabled =false
,V/        ( 2848): QcRouteController
,W/NetworkManagementService( 3524): route cmd failed: 
W/NetworkManagementService( 3524): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3524): '
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3524): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
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
,D/ConnectivityService( 3524): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6690): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6690): CM callback handler got msg 524295
,I/GAV4    (12100): Thread[GAThread,5,main]: No campaign data found.
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 269, CUR = 53
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-111, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:87
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PackageManager( 3524): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11843): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11843): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11843): ================================================
I/CSTORAGE(11843):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11843): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11843): [GetString-S]
E/art     (11843): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11843): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11843): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11843): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12003): wlan0: sending IPv6 Router Solicitation
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 12448
,I/dhcpcd  (12003): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12003): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12254): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12254): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12254): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12254): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12254): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine(12254): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12254): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12254): entry::IDLE
,E/Watchdog( 3524): !@Sync 5
,D/SSRM:n  ( 3524): SIOP:: AP = 260, PST = 269, CUR = -111
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:-1, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:73
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 75s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 263, CUR = -1
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:68
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4646): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 262, CUR = 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 6
,D/SSRM:n  ( 3524): SIOP:: AP = 250, PST = 260, CUR = 48
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 105s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 258, CUR = 50
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged,
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 254, CUR = 47
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 7
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 252, CUR = 44
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3694): handleTimeUpdate
,D/KeyguardEffectViewController( 3694): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3694): *** don't update sliding image ***
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3694): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 140s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 251, CUR = 42
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 250, CUR = 41
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 8
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 247, CUR = 39
,V/AlarmManager( 3524): waitForAlarm result :8
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 246, CUR = 38
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 180s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 245, CUR = 36
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3524): stay LED for fully charged
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 9
,I/jxcore-log(11721): --= Surplus to requirements =--
I/jxcore-log(11721): 
I/jxcore-log(11721): ****TEST TOOK:  ms ****
I/jxcore-log(11721): 
I/jxcore-log(11721): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11721): 
,D/AndroidRuntime(12609): 
D/AndroidRuntime(12609): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12609): CheckJNI is OFF
,D/AndroidRuntime(12609): readGMSProperty: start
D/AndroidRuntime(12609): readGMSProperty: already setted!!
,D/AndroidRuntime(12609): readGMSProperty: end
D/AndroidRuntime(12609): addProductProperty: start
,E/AffinityControl(12609): AffinityControl: registerfunction enter
,D/AndroidRuntime(12609): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3524): START PACKAGE DELETE: observer{254445390}
D/PackageManager( 3524): pkg{<packageName>}
D/PackageManager( 3524): user{0}
D/PackageManager( 3524): caller{2000}
D/PackageManager( 3524): flags{3}
,D/PersonaManagerService( 3524): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3524): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 3524): !@killApplicatoin: 10580, uninstall pkg
,D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:-1
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10580 user=-1: uninstall pkg
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled
I/ActivityManager( 3524): Killing 11721:com.test.thalitest/u0a580 (adj 0): stop com.test.thalitest
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3524):   Force finishing activity ActivityRecord{1bbc50d1 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3524): mDVFSHelper.acquire()
,W/PackageSettings( 3524): Skipping PackageSetting{193bb1fd com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10580 user=0: pkg removed
,I/ActivityManager( 3524):   Force finishing activity ActivityRecord{1bbc50d1 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3524): Duplicate finish request for ActivityRecord{1bbc50d1 u0 com.test.thalitest/.MainActivity t26 f}
,E/JavaBinder( 3524): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,D/WifiService( 3524): Client connection lost with reason: 4
,I/WindowState( 3524): WIN DEATH: Window{1da9081f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2852): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2852): id=14 Removed NainActivit (-2/8)
,I/DBG_DM  ( 6222): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/SSRM:n  ( 3524): SIOP:: AP = 240, PST = 243, CUR = 35
,I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 8876): Explicit concurrent mark sweep GC freed 25276(1472KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.274ms total 54.037ms
,I/art     ( 6690): Explicit concurrent mark sweep GC freed 29016(1661KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 1.422ms total 94.497ms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6222): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 10
I/InputReader( 3524): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/SamsungIME( 4503): mOCRHelper is null
,I/art     ( 4058): Explicit concurrent mark sweep GC freed 30909(1914KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 894us total 63.606ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,W/GeofencerStateMachine( 4646): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6222): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/LWLocationManager(11405): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11405): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3524): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3524): Admin package name: com.google.android.gms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,E/Zygote  (12630): MountEmulatedStorage()
E/Zygote  (12630): v2
I/libpersona(12630): KNOX_SDCARD checking this for 10063
I/libpersona(12630): KNOX_SDCARD not a persona
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux (12630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12630 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
,I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,W/ResourceType( 5357): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5357): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3524): mCursor = null
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ApplicationPolicy( 3524): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 10
,D/TimaKeyStoreProvider(12630): TimaSignature is unavailable
,D/ActivityThread(12630): Added TimaKeyStore provider
I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6222): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6222): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6222): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6222): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6222): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
,I/DBG_DM  ( 6222): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2852): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 66963(4MB) AllocSpace objects, 50(800KB) LOS objects, 24% free, 49MB/65MB, paused 1.822ms total 181.306ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 3524): WaitForGcToComplete blocked for 180.980ms for cause Explicit
D/ResourcesManager(12630): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,V/ActivityThread( 6222): updateVisibility : ActivityRecord{12c8a7cf token=android.os.BinderProxy@247eecb0 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12630): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12630): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12630): packagename:com.test.thalitest
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/KLMS-2.4.521: (11956): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 16:06:29 GMT+01:00 2016
,W/InputMethodManagerService( 3524): Got RemoteException sending setActive(false) notification to pid 11721 uid 10580
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.4.521: (11956): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onCreate()
,I/Timeline( 6222): Timeline: Activity_idle id: android.os.BinderProxy@247eecb0 time:284771
,I/KLMS-2.4.521: (11956): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11956): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.521: (11956): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (11956): KLMSIntentService(): listeningToPackageRemoved().START
,W/ResourceType( 3524): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,I/KLMS-2.4.521: (11956): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,E/Zygote  (12652): MountEmulatedStorage()
E/Zygote  (12652): v2
I/libpersona(12652): KNOX_SDCARD checking this for 10106
I/libpersona(12652): KNOX_SDCARD not a persona
,I/SELinux (12652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12652 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{3fd9c8fe u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:284797
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/SELinux (12652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 303us total 10.056ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/RegisteredServicesCache( 3965): empty dynamic service
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 463us total 8.586ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/RCPManager(12051):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3524):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524): queryAllProviders():  providerCallBack is not register for 0
,D/TimaKeyStoreProvider(12652): TimaSignature is unavailable
,D/ActivityThread(12652): Added TimaKeyStore provider
,I/art     ( 2881): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 263us total 7.782ms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/art     ( 3524): Explicit concurrent mark sweep GC freed 7345(354KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.655ms total 117.110ms
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (12667): MountEmulatedStorage()
E/Zygote  (12667): v2
I/libpersona(12667): KNOX_SDCARD checking this for 10050
I/libpersona(12667): KNOX_SDCARD not a persona
,I/SELinux (12667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12667 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (12667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (11956): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/Zygote  (12682): MountEmulatedStorage()
E/Zygote  (12682): v2
I/libpersona(12682): KNOX_SDCARD checking this for 10101
I/libpersona(12682): KNOX_SDCARD not a persona
,I/ActivityManager( 3524): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12682 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (12682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12682): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12667): TimaSignature is unavailable
,D/ActivityThread(12667): Added TimaKeyStore provider
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (11956): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider(12682): TimaSignature is unavailable
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
D/ActivityThread(12682): Added TimaKeyStore provider
,W/ResourcesManager(11405): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager(12652): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12667): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12667): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12698): MountEmulatedStorage()
E/Zygote  (12698): v2
I/libpersona(12698): KNOX_SDCARD checking this for 10183
I/libpersona(12698): KNOX_SDCARD not a persona
,I/SELinux (12698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12698 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
E/SELinux (12698): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/elm:14491(12652): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/ActivityManager( 3524): Killing 11422:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/elm:14491(12652): ELMEngine.ELMEngine( context ).
,D/elm:14491(12652): MDMBridge.setEnterpriseBridge()
,D/TimaKeyStoreProvider(12698): TimaSignature is unavailable
D/ResourcesManager(11405): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ActivityThread(12698): Added TimaKeyStore provider
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/ResourcesManager(11405): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11405): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11405): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11405): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(12652): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12652): ElmAgentService : onCreate()
W/ResourcesManager( 3524): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager( 3524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/elm:14491(12652): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager(12682): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/PackageManager( 3524): delete codoeFile: 
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/elm:14491(12652): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12652): MDMBridge.getInstance()
D/elm:14491(12652): MDMBridge.getAllLicenseInfoFromSDK()
,I/AASAUninstall( 3524):  com.test.thalitest not target!
D/ResourcesManager(11405): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/elm:14491(12652): MDMBridge.getAllLicenseInfoFromSDK()
D/PackageManager( 3524): result of delete: 1{254445390}
,D/AndroidRuntime(12609): Shutting down VM
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12698): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (12715): MountEmulatedStorage()
E/Zygote  (12715): v2
I/libpersona(12715): KNOX_SDCARD checking this for 10019
I/libpersona(12715): KNOX_SDCARD not a persona
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/SELinux (12715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux (12715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/ActivityManager( 3524): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12715 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (12715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/elm:14491(12652): ElmAgentService : onDestroy().
,D/RCPManagerService( 3524): PackageReceiver onReceive()
I/HarmonyEASService( 3524): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/KnoxMUMContainerPolicy( 3524): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3524): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3524): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): uID is 10580
V/EnterpriseBillingPolicy( 3524): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(11405): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/DocsApplication(12682): Installing DEX configuration.
,I/ActivityManager( 3524): Killing 11437:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,D/ResourcesManager(11405): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/DexInstaller(12682): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/PackageInfoHelper(12682): Provided clientMode=RELEASE, packageInfo=PackageInfo{f3a80a7 com.google.android.apps.docs}
E/SQLiteLog(12698): (284) automatic index on shooting_modes(title_id)
,D/TAG     (12682): onCreate()
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3524): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3524): onPackageRemoved : com.test.thalitest
,D/CrossAppStateProvider(12682): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/ResourcesManager(11405): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/TimaKeyStoreProvider(12715): TimaSignature is unavailable
,D/ActivityThread(12715): Added TimaKeyStore provider
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
,E/Zygote  (12733): MountEmulatedStorage()
E/Zygote  (12733): v2
I/libpersona(12733): KNOX_SDCARD checking this for 10190
I/libpersona(12733): KNOX_SDCARD not a persona
,I/SELinux (12733): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12733): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12733 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/SELinux (12733): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar( 3694): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=24_task.xml
D/PersonaManager( 3694): isKioskContainerExistOnDevice
D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
,I/StatusBar( 3694): Icon Only
,D/PanelView( 3694): There is/are notification(s) 
,D/PanelView( 3694): There is/are notification(s) 
,D/PersonaManager( 3694): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3694): Icon Only
D/ResourcesManager(11405): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
I/ActivityManager( 3524): Killing 11405:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
I/StatusBar( 3694): Icon Only
,D/PanelView( 3694): There is/are notification(s) 
,D/NearbySource(12667): Nearby Source Create!
D/NearbyContext(12667): Nearby Context Create!
,D/TimaKeyStoreProvider(12733): TimaSignature is unavailable
,D/ActivityThread(12733): Added TimaKeyStore provider
,D/ResourcesManager(12715): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Vold    ( 2832): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2832): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12667): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(12667): Samsung link source created
,D/ResourcesManager(12733): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12715): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12715): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12715): onReceive() : package name is not s health. Return !!!
,I/ActivityManager( 3524): Killing 10718:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,W/BroadcastQueue( 3524): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.locationwidget/com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider}
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
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/TapandpayWidget:TanpandpayAppWidgetProvider(12733): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(12733): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/PanelView( 3694): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/TapandpayWidget:Utils(12733): Clear T&P info.
,E/Zygote  (12750): MountEmulatedStorage()
E/Zygote  (12750): v2
I/libpersona(12750): KNOX_SDCARD checking this for 10022
I/libpersona(12750): KNOX_SDCARD not a persona
,I/SELinux (12750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12750 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/SELinux (12750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12733): Widget is not attached.
,W/ActivityManager( 3524): Spurious death for ProcessRecord{34e43998 12750:com.sec.android.widgetapp.locationwidget/u0a22}, curProc for 11405: null
,I/ActivityManager( 3524): Killing 11552:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider(12750): TimaSignature is unavailable
,D/ActivityThread(12750): Added TimaKeyStore provider
,D/PackageBroadcastService( 6690): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6690): Clearing selected account for com.test.thalitest
,D/ContactProvider(12667): getAllContactInfoList Start
,D/ResourcesManager(12750): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,D/ChimeraCfgMgr( 6690): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6690): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 6690): Removing dialog suppression flag for package com.test.thalitest
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(12750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12750): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/Zygote  (12770): MountEmulatedStorage()
I/libpersona(12770): KNOX_SDCARD checking this for 10052
E/Zygote  (12770): v2
I/libpersona(12770): KNOX_SDCARD not a persona
I/SELinux (12770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12770 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux (12770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12770): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/LocationWidgetApplication(12750): onCreate() : start
D/LocationWidgetApplication(12750): countryCode = POLAND
,D/ChimeraCfgMgr( 6690): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6690): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 6690): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6690): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/TimaKeyStoreProvider(12770): TimaSignature is unavailable
D/LocationManagerService( 3524): getProviders()=[]
,D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12750): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12750): getLastUiLocationId() : mLastUiLocationId = -100
D/ActivityThread(12770): Added TimaKeyStore provider
,E/AndroidRuntime( 6690): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 6690): Process: com.google.android.gms, PID: 6690
E/AndroidRuntime( 6690): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6690): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6690): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 6690): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6690): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6690): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 6690): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/AndroidRuntime( 6690): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 6690): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 6690): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 6690): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/AndroidRuntime( 6690): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 6690): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 6690): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 6690): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 6690): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 6690): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6690): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6690): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 6690): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6690): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/FileUtils( 6690): Failed to chmod(/data/data/com.google.android.gms/databases/metrics.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/SQLiteLog( 6690): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog(12750): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12750): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12750): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12750): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12750): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12750): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12750): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12750): Shutting down VM
,E/AndroidRuntime(12750): FATAL EXCEPTION: main
E/AndroidRuntime(12750): Process: com.sec.android.widgetapp.locationwidget, PID: 12750
E/AndroidRuntime(12750): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12750): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12750): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12750): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12750): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12750): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12750): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12750): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12750): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12750): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12750): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12750): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12750): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12750): 	... 9 more
D/gH_CompatibleDatabase( 6690): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6690): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteDatabase( 6690): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6690): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6690): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6690): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6690): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6690): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6690): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6690): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6690): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6690): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6690): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 3524): Killing 12206:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
E/SQLiteLog( 4646): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4646): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/PhenotypeInitializer( 6690): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6690): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6690): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6690): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6690): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6690): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6690): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6690): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6690): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6690): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6690): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AndroidRuntime( 4646): Shutting down VM
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/AndroidRuntime( 4646): FATAL EXCEPTION: main
E/AndroidRuntime( 4646): Process: com.google.android.gms.persistent, PID: 4646
E/AndroidRuntime( 4646): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4646): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4646): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4646): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4646): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4646): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4646): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4646): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4646): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4646): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4646): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4646): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4646): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4646): 	... 9 more
E/ClearPendingStateOp( 6690): Runtime exception while performing operation
E/ClearPendingStateOp( 6690): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6690): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6690): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6690): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6690): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6690): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6690): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6690): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6690): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6690): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6690): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6690): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6690): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6690): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6690): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6690): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6690): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6690): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 6690): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6690): (3850) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] disk I/O error
D/gH_CompatibleDatabase( 6690): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 6690): Sending signal. PID: 6690 SIG: 9
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
D/ResourcesManager(12770): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
I/PCWCLIENTTRACE_PushUtil(11843): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11843): sales region : global
I/PCWCLIENTTRACE_PushUtil(11843): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11843): [onReceive] - android.intent.action.PACKAGE_REMOVED
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
W/ResourcesManager(12770): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12770): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12770): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12770): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12770): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(12770): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
I/Process (12750): Sending signal. PID: 12750 SIG: 9
E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
W/ActivityManager( 3524): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager( 3524): Killing 4646:com.google.android.gms.persistent/u0a14 (adj 0): crash
E/JavaBinder( 3524): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 3524): Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@12fb03db (in com.google.android.gms)
W/ActivityManager( 3524): android.os.TransactionTooLargeException
W/ActivityManager( 3524): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3524): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3524): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager( 3524): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1686)
W/ActivityManager( 3524): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:17705)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6129)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:7561)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:14542)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:14421)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15187)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14695)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14677)
W/ActivityManager( 3524): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1457)
W/ActivityManager( 3524): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3524): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3524): displayNotification : [0ah,00h,00h]
V/BackupManagerService( 3524): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3524): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3524): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/UsbHostManager( 3524): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3524): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/Zygote  (12800): MountEmulatedStorage()
E/Zygote  (12800): v2
I/libpersona(12800): KNOX_SDCARD checking this for 10035
I/libpersona(12800): KNOX_SDCARD not a persona
,D/ConnectivityService( 3524): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2b76e6d7)
,D/ConnectivityService( 3524): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3524): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SELinux (12800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12800 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 8822:com.android.settings/1000 (adj 13): bgCount ##31
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3524): displayNotification : [09h,00h,00h]
,I/SELinux (12800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12800): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Process com.google.android.gms (pid 6690)(adj 0) has died(345,1181)
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20998ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20997ms
,D/Mms/MmsApp(12770): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 3524): Process com.sec.android.widgetapp.locationwidget (pid 12750)(adj 9) has died(349,1180)
,D/Mms/ArtClassLoader(12770): init before art
,D/Mms/ArtClassLoader(12770): init [DONE] art
,I/EventHub( 3524): Removing device '/dev/input/event10' due to inotify event
D/GpsStatusListenerHelper( 3524): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@1d3ffbc4
,D/LocationManagerService( 3524): Location listener died
I/LocationManagerService( 3524): remove 2e5ab252 by com.google.android.gms
,D/LocationManagerService( 3524): Location listener died
,D/LocationManagerService( 3524): provider request: passive ProviderRequest[ON interval=0]
,I/LocationManagerService( 3524): remove 5ffdf51 by com.google.android.gms
,D/WifiService( 3524): Client connection lost with reason: 4
D/LocationManagerService( 3524): provider request: passive ProviderRequest[ON interval=0]
,I/EventHub( 3524): Removing device '/dev/input/event7' due to inotify event
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12800): TimaSignature is unavailable
,D/WifiService( 3524): Client connection lost with reason: 4
,D/ActivityThread(12800): Added TimaKeyStore provider
,I/EventHub( 3524): Removing device '/dev/input/event8' due to inotify event
,I/EventHub( 3524): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (12822): MountEmulatedStorage()
E/Zygote  (12822): v2
I/libpersona(12822): KNOX_SDCARD checking this for 10031
I/libpersona(12822): KNOX_SDCARD not a persona
,I/SELinux (12822): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=12822 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12822): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12822): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityThread(11818): Failed to find provider info for com.facebook.appmanager.installrecord
,I/EventHub( 3524): Removing device '/dev/input/event11' due to inotify event
,D/Mms/TelephonyPermission(12770): start operation mode monitor
,I/EventHub( 3524): Removing device '/dev/input/event12' due to inotify event
,D/TimaKeyStoreProvider(12822): TimaSignature is unavailable
,D/ActivityThread(12822): Added TimaKeyStore provider
E/SQLiteLog(12682): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12682): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12682): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12682): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(12682): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12682): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12682): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12682): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12682): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12682): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(12682): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(12682): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(12682): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(12682): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(12682): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(12682): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(12682): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(12682): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(12682): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12682): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12682): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12682): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/MtpClient(12667): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(12667): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/SQLiteOpenHelper(12682): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12682): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12682): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(12682): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12682): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12682): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(12682): 	at br,D.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12682): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12682): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12682): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(12682): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(12682): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(12682): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(12682): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(12682): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(12682): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(12682): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(12682): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(12682): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(12682): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(12682): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(12682): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12682): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12682): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12682): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12682): Opened ClientFlag.db in read-only mode
D/ResourcesManager(12770): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/EventHub( 3524): Removing device '/dev/input/event13' due to inotify event
W/ResourcesManager(12770): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager(12800): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ContactProvider(12667): getAllContactInfoList End
I/syncContacts(12667): thread: 1718, sync time = 585
,I/EventHub( 3524): Removing device '/dev/input/event14' due to inotify event
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
E/SQLiteLog(12682): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
,I/MotionRecognitionService( 3524): setPowerConnected  = true
E/SQLiteDatabase(12682): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(12682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12682): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(12682): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(12682): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(12682): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(12682): 	at aFp.run(AbstractDatabaseInstance.java:471)
,E/AndroidRuntime(12682): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(12682): Process: com.google.android.apps.docs, PID: 12682
E/AndroidRuntime(12682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12682): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12682): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(12682): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(12682): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(12682): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(12682): 	at aFp.run(AbstractDatabaseInstance.java:471)
,D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
,D/Mms/TelephonyPermission(12770): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(12770): isDefault true
,D/Mms/MmsApp(12770): onCreate() com.android.mms
D/ResourcesManager(12822): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5646): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5646): Disconnected process message: 10
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SQLiteLog(12682): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
E/SQLiteDatabase(12682): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(12682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12682): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(12682): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(12682): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(12682): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12682): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12682): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12682): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12682): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12682): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(12682): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12682): 	at android.database.sql,ite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12682): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12682): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12682): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12682): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(12682): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(12682): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(12682): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12682): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12682): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12682): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12682): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12682): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12682): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12682): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(12682): Opened ClientFlag.db in read-only mode
I/FeatureConfig(12800): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/Mms/MmsApp(12770): [start]    initCountryIso consume time = 328.190167
D/CountryDetector( 3524): The first listener is added
,D/Mms/MmsApp(12770): [end]    initCountryIso consume time = 26.137
D/Mms/MmsConfig(12770): [start]    MmsConfig.init() consume time = 0.26125
,D/Mms/MmsConfig(12770): before partial update
,E/Zygote  (12845): MountEmulatedStorage()
I/libpersona(12845): KNOX_SDCARD checking this for 1000
E/Zygote  (12845): v2
I/libpersona(12845): KNOX_SDCARD not a persona
,I/SELinux (12845): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12845): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12845): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=12845 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/Mms/MmsConfig(12770): Load Resize quality : 80
,D/Mms/MmsConfig(12770):  enable multiwindow = true
,W/BroadcastQueue( 3524): Skipping deliver [background] BroadcastRecord{bfa2b3a u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{22e0ff5c 12682 com.google.android.apps.docs/10101/u0 remote:1b21d9cf}: process crashing

```
