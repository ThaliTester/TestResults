#### Test 5531115118861c0_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3525): !@Sync 4
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 253, CUR = 32
--------- beginning of main
D/AndroidRuntime(11740): 
D/AndroidRuntime(11740): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11740): CheckJNI is OFF
D/AndroidRuntime(11740): readGMSProperty: start
D/AndroidRuntime(11740): readGMSProperty: already setted!!
D/AndroidRuntime(11740): readGMSProperty: end
D/AndroidRuntime(11740): addProductProperty: start
E/AffinityControl(11740): AffinityControl: registerfunction enter
D/AndroidRuntime(11740): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3525): inState():  stateMachine is null !!
I/PersonaManagerService( 3525): PersonaId don't exist
I/ActivityManager( 3525): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3525): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
W/ActivityManager( 3525): mDVFSHelper.acquire()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/Zygote  (11759): MountEmulatedStorage()
I/libpersona(11759): KNOX_SDCARD checking this for 10540
E/Zygote  (11759): v2
I/libpersona(11759): KNOX_SDCARD not a persona
I/SELinux (11759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11759 uid=10540 gids={50540, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11759): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11740): Shutting down VM
I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
D/TimaKeyStoreProvider(11759): TimaSignature is unavailable
D/ActivityThread(11759): Added TimaKeyStore provider
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/ResourcesManager(11759): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6268): updateVisibility : ActivityRecord{a75539f token=android.os.BinderProxy@361efb40 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11759): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11759): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11759): Loading: webviewchromium
I/LibraryLoader(11759): Time to load native libraries: 3 ms (timestamps 4435-4438)
I/LibraryLoader(11759): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11759): Binding Chromium to main looper Looper (main, tid 1) {3170b04e}
I/LibraryLoader(11759): Expected native library version number "",actual native library version number ""
I/chromium(11759): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11759): Initializing chromium process, renderers=0
,W/art     (11759): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11759): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11759): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11759): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11759): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11759): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11759): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11759): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11759): CordovaWebView is running on device made by: samsung
,W/art     (11759): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11759): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11759): performCreate Call secproduct feature valuefalse
D/Activity(11759): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11759): Render dirty regions requested: true
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11759): Initialized EGL, version 1.4
,I/OpenGLRenderer(11759): HWUI protection enabled for context ,  &this =0xaf6af1a0 ,&mEglDisplay = 1 , &mEglConfig = -1278648048 
,D/OpenGLRenderer(11759): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11759): Enabling debug mode 0
,D/mali_winsys(11759): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11759): updateVisibility : ActivityRecord{18fc8fe token=android.os.BinderProxy@1497cb4d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3525): mDVFSHelper.release()
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{3d13bc0b u0 com.test.thalitest/.MainActivity t26} time:134798
W/IInputConnectionWrapper(11759): showStatusIcon on inactive InputConnection
I/Timeline(11759): Timeline: Activity_idle id: android.os.BinderProxy@1497cb4d time:134807
,I/chromium(11759): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11759): 
,D/JsMessageQueue(11759): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11759): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11759): jxcore cordova android initializing
,W/jxcore-log(11759): Initializing JXcore engine
W/jxcore-log(11759): JXcore engine is ready
,W/jxcore-log(11759): Starting JXcore engine
,E/auditd  ( 4627): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3525): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3525): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/jxcore-log(11759): Platform android
W/jxcore-log(11759): 
W/jxcore-log(11759): Process ARCH arm
W/jxcore-log(11759): 
,I/jxcore-log(11759): JXcore Cordova bridge is ready!
I/jxcore-log(11759): 
W/jxcore-log(11759): JXcore engine is started
,I/jxcore-log(11759): Toggling radios to true
I/jxcore-log(11759): 
,D/BluetoothAdapter(11759): enable()
,D/BluetoothAdapter(11759): enable(): BT is already enabled..!
,D/WifiService( 3525): New client listening to asynchronous messages
,I/WifiManager(11759): packageName : com.test.thalitest
D/SecContentProvider( 3525): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3525): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3525): mCursor = null
D/WifiService( 3525): setWifiEnabled: true pid=11759, uid=10540
E/WifiService( 3525): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3525): Permission Denial: getCurrentUser() from pid=11759, uid=10540 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3525): Failed getting userId using ActivityManagerNative
W/WifiService( 3525): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11759, uid=10540 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3525): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3525): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3525): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3525): name = wifi_on
,I/WifiService( 3525): disconnect: pid=11759, uid=10540
,I/wpa_supplicant( 3825): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3825): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/jxcore-log(11759): Radios toggled
I/jxcore-log(11759): 
I/wpa_supplicant( 3825): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3525): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3825): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): Disconnected - do not scan
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3525): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3525): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/jxcore-log(11759): Received device characteristics:
I/jxcore-log(11759): Bluetooth address: E0:DB:10:14:E2:C0
I/jxcore-log(11759): Bluetooth name: Note4-1
I/jxcore-log(11759): Device name: samsung-SM-N910C
I/jxcore-log(11759): 
,I/jxcore-log(11759): Perf Test app loaded loaded
I/jxcore-log(11759): 
I/jxcore-log(11759): check test folder
I/jxcore-log(11759): 
I/jxcore-log(11759): found test : ./testFindPeers.js
I/jxcore-log(11759): 
E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3525): do suspend true
D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3525): updateNetworkInfo()
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
I/jxcore-log(11759): found test : ./testSendData.js
I/jxcore-log(11759): 
I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
E/WifiStateMachine( 3525): Start Disconnecting Watchdog 1
I/wpa_supplicant( 3825): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3825): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3825): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3825): First Scan Start
,E/WifiStateMachine( 3525): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3525): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/wpa_supplicant( 3825): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3525): do suspend true
,I/Hs20UtilService( 4085): Starting #8
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
I/Hs20UtilService( 4085): Message received 5007
,D/NearbySettings( 8802): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8802): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 8802): MountReceiver.onReceive - Create mPrefHandler
D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
D/NearbySettings( 8802): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8802): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3525): New client listening to asynchronous messages
,I/NearbySettings( 8802): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8802): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8802): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,I/SignOutReceiver(11407): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3525): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3525): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - currTime: 1452159921938
D/WifiStateMachine( 3525): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker( 3525): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/CSLegacyTypeTracker( 3525): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 6886): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 3977): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3525): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3525): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/Tethering( 3525): MasterInitialState.processMessage what=3
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 3525): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
V/NetworkStats( 3525): updateIfacesLocked()
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3525): UpdateStatsForKnox
D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): performPollLocked() took 8ms
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/Hs20UtilService( 4085): Starting #9
I/Hs20UtilService( 4085): Message received 5007
,D/NearbySettings( 8802): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8802): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8802): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8802): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8802): MountReceiver.mPrefHandler - 7002
,I/Choreographer(11759): Skipped 46 frames!  The application may be doing too much work on its main thread.
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,I/chromium(11759): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SignOutReceiver(11407): NETWORK_STATE_CHANGED_ACTION
,I/chromium(11759): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3525): updateDataUsageMap
,I/ApplicationPolicy( 3525): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,W/SLocation( 3525): No Active Data Connection
,E/Zygote  (11868): MountEmulatedStorage()
,E/Zygote  (11868): v2
I/libpersona(11868): KNOX_SDCARD checking this for 10110
I/libpersona(11868): KNOX_SDCARD not a persona
,I/SELinux (11868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11868 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (11868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11868): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6268): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6268): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider(11868): TimaSignature is unavailable
,D/ActivityThread(11868): Added TimaKeyStore provider
,D/ResourcesManager(11868): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (11868): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11868): not using cross-dex optimization: ART in use
,I/art     (11868): Thread[1,tid=11868,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11868): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(11868): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
,V/DexLibLoader(11868): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11868): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(11868): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11868): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11868): loading pre-built fallback odex files
V/MultiDexClassLoader(11868): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11868): released odex store lock
,D/DexLibLoader(11868): DexLibLoader.loadAll took 33 ms
,W/ca      (11868): Verify
,W/LightSharedPreferencesImpl(11868): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11868): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11868): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11868): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11868): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11868): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11868): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11868): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11868): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11868): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11868): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11868): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11868): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11868): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11868): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11868): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11868): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11868): 	... 10 more
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11900): MountEmulatedStorage()
E/Zygote  (11900): v2
I/libpersona(11900): KNOX_SDCARD checking this for 1000
I/libpersona(11900): KNOX_SDCARD not a persona
,I/SELinux (11900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11900 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11900): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 9849:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/wpa_supplicant( 3825): nl80211: Received scan results (10 BSSes)
I/wpa_supplicant( 3825): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3825): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3825): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3525): [1,452,159,922,998 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3525): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@365c47d3 sup_state=SCANNING debouncing=false
,D/TimaKeyStoreProvider(11900): TimaSignature is unavailable
,W/appmanager(:<default>):b(11868): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ActivityThread(11900): Added TimaKeyStore provider
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3525): setDetailed state send new extra info
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/ResourcesManager(11900): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11900): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11900): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11900): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11900): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11900): sales region : global
I/PCWCLIENTTRACE_PushUtil(11900): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11900): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(11900): noConnectivity : true
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 3825): Associated with C0.AA.48
E/WifiStateMachine( 3525): setDetailed state send new extra info"NG700"
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/wpa_supplicant( 3825): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/Zygote  (11920): MountEmulatedStorage()
E/Zygote  (11920): v2
I/libpersona(11920): KNOX_SDCARD checking this for 10135
I/libpersona(11920): KNOX_SDCARD not a persona
,I/SELinux (11920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/SELinux (11920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11920): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3825): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/ActivityManager( 3525): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=11920 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3825): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3825): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3825): Blacklist: Clear (temp) 
I/wpa_supplicant( 3825): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3525): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine( 3525): Network connection established
,D/WifiNative-HAL( 3525): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3525): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3525): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3525): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3525): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3525): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiStateMachine( 3525): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3525): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
,E/WifiStateMachine( 3525): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3525): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3525): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider(11920): TimaSignature is unavailable
,D/ActivityThread(11920): Added TimaKeyStore provider
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3525): Start Dhcp Watchdog 2
,W/appmanager(:<default>):QuickExperimentControllerImpl(11868): Exposure of experiment com.facebook.common.network.l@2ecb4e34 occurred when no user was logged in
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,I/ActivityManager( 3525): Killing 11011:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2fdd2424 u0 ReceiverList{34e7f4b7 11868 com.facebook.appmanager/10110/u0 remote:3de2fb6}}
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2fdd2424 u0 ReceiverList{34e7f4b7 11868 com.facebook.appmanager/10110/u0 remote:3de2fb6}}
,D/ResourcesManager(11920): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,W/BroadcastQueue( 3525): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1cf36fa8 u0 ReceiverList{69ebcb 11868 com.facebook.appmanager/10110/u0 remote:168069a}}
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3525): do suspend false
,D/SecContentProvider2( 3525): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3525): mCursor = null
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,I/MusicStore(11920): Database version: 104
,D/ResourcesManager(11920): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11920): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11920): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11920): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11920): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11920): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@337db4c2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11920): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11920): GMSCore installation verified
,I/ConfigStore(11920): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11920): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/dhcpcd  (11958): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (11958): version 5.5.6 starting
,E/dhcpcd  (11958): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11920): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl(11920): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3525): getStreamVolume 3 index 0
,I/MediaRouter(11920): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/dhcpcd  (11958): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (11958): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (11958): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (11958): bssid match
,I/dhcpcd  (11958): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11965): MountEmulatedStorage()
E/Zygote  (11965): v2
I/libpersona(11965): KNOX_SDCARD checking this for 10002
I/libpersona(11965): KNOX_SDCARD not a persona
,I/SELinux (11965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=11965 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.027ms total 21.631ms
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(11920): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(11965): TimaSignature is unavailable
,D/ActivityThread(11965): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 822us total 18.550ms
,I/ActivityManager( 3525): Killing 11026:com.policydm/1000 (adj 15): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 630us total 19.120ms
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11868): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11868): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
D/ResourcesManager(11965): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,W/appmanager(:<default>):QuickExperimentControllerImpl(11868): Exposure of experiment com.facebook.imagepipeline.a.g@3743b7dd occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11868): Exposure of experiment com.facebook.imagepipeline.a.d@5808e9e occurred when no user was logged in
,I/ActivityManager( 3525): Killing 11041:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11984): MountEmulatedStorage()
E/Zygote  (11984): v2
I/libpersona(11984): KNOX_SDCARD checking this for 1000
I/libpersona(11984): KNOX_SDCARD not a persona
,I/SELinux (11984): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11984): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=11984 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11984): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11984): TimaSignature is unavailable
,D/ActivityThread(11984): Added TimaKeyStore provider
,I/art     (11868): Explicit concurrent mark sweep GC freed 48265(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 1.973ms total 56.310ms
,W/appmanager(:<default>):m(11868): No feature status reporters found; is this dead code?
,D/ResourcesManager(11984): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(11984): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(11984): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(11984): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(11984): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11984): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12003): MountEmulatedStorage()
I/libpersona(12003): KNOX_SDCARD checking this for 10012
E/Zygote  (12003): v2
I/libpersona(12003): KNOX_SDCARD not a persona
,I/SELinux (12003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12003 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12003): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12003): TimaSignature is unavailable
,D/ActivityThread(12003): Added TimaKeyStore provider
,D/ResourcesManager(12003): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3525): Killing 11078:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(12003): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12003): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12003): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  (11958): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,E/Zygote  (12019): MountEmulatedStorage()
E/Zygote  (12019): v2
I/libpersona(12019): KNOX_SDCARD checking this for 10021
I/libpersona(12019): KNOX_SDCARD not a persona
,I/SELinux (12019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12019): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12019 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11063:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11063/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12019): TimaSignature is unavailable
,D/ActivityThread(12019): Added TimaKeyStore provider
,I/dhcpcd  (11958): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/ResourcesManager(12019): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12019): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 07 10:45:24 GMT+01:00 2016
,I/KLMS-2.4.521: (12019): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12019): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12019): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12019): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12019): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12019): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  (12041): MountEmulatedStorage()
E/Zygote  (12041): v2
I/libpersona(12041): KNOX_SDCARD checking this for 10038
I/libpersona(12041): KNOX_SDCARD not a persona
,I/SELinux (12041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12041 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/SELinux (12041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12041): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12019): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12019): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider(12041): TimaSignature is unavailable
I/KLMS-2.4.521: (12019): KLMSIntentService(): onDestroy()
,D/ActivityThread(12041): Added TimaKeyStore provider
I/ActivityManager( 3525): Killing 11094:com.wsomacp/u0a28 (adj 15): bgCount ##31
,D/ResourcesManager(12041): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12041): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12068): MountEmulatedStorage()
E/Zygote  (12068): v2
I/libpersona(12068): KNOX_SDCARD checking this for 1000
I/libpersona(12068): KNOX_SDCARD not a persona
,I/SELinux (12068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 10876:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12068): TimaSignature is unavailable
,D/ActivityThread(12068): Added TimaKeyStore provider
,D/ResourcesManager(12068): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12096): MountEmulatedStorage()
I/libpersona(12096): KNOX_SDCARD checking this for 10039
E/Zygote  (12096): v2
I/libpersona(12096): KNOX_SDCARD not a persona
I/SELinux (12096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12096): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12096 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11133:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12096): TimaSignature is unavailable
,D/ActivityThread(12096): Added TimaKeyStore provider
,D/ResourcesManager(12096): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3525): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  ( 3525): do suspend true
,D/WifiP2pService( 3525): InactiveState{ what=143375 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3525): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine( 3525): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3525): Not connected state, yet.
E/WifiStateMachine( 3525): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3525): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3525): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3525): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3525): callSECApiInt - ID [210]
,E/WifiStateMachine( 3525): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3525): updateNetworkInfo()
,D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3525): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3525): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3525): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
E/WifiStateMachine( 3525): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3525): Now, connected state.
E/WifiStateMachine( 3525): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3525): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
,D/ConnectivityService( 3525): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 3525): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3525): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService( 3525): Unexpected mtu value: 0, wlan0
,V/        ( 2845): QcRouteController
,I/WifiTrafficPoller( 3525): evaluateTrafficStatsPolling
E/WifiStateMachine( 3525): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiNative-HAL( 3525): callSECApiVoid - ID [212]
,E/WifiStateMachine( 3525): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
E/SPPClientService(12096): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
E/SPPClientService(12096): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12096): [PushClientApplication] Push log off : This is Ship build version
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
V/        ( 2845): QcRouteController
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/SPPClientService(12096): PushLog.txt file is not deleted.
,D/SPPClientService(12096): PushLog.txt file is not deleted.
D/SPPClientService(12096): ============PushLog. stop!
,I/SA      (11203): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11203): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      (11203): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11203): [SLFUCHKMGR] constructor called
,V/        ( 2845): QcRouteController
,E/SPPClientService(12096): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11203): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11203): [OR] == isSIMCardReady false ==
,V/        ( 2845): QcRouteController
,I/SA      (11203): [SCU] == networkStateCheck == false
,I/SA      (11203): [OR] onReceive END
,V/DownloadManager( 5494): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,V/        ( 2845): QcRouteController
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,V/        ( 2845): QcRouteController
,V/        ( 2845): QcRouteController
,E/Zygote  (12136): MountEmulatedStorage()
E/Zygote  (12136): v2
I/libpersona(12136): KNOX_SDCARD checking this for 10067
I/libpersona(12136): KNOX_SDCARD not a persona
,I/SELinux (12136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12136): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12136 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11116:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,V/        ( 2845): QcRouteController
,D/ConnectivityService( 3525): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3525): LTETest block dns file not exists
,D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3525): updateNetworkInfo()
E/ConnectivityService( 3525): updateNetworkInfo()
D/ConnectivityService( 3525): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3525): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Checking http://clients3.google.com/generate_204 on "NG700"
,D/TimaKeyStoreProvider(12136): TimaSignature is unavailable
,D/ConnectivityService( 3525):    accepting network in place of null
,I/System.out( 3525): (HTTPLog)-Static: isSBSettingEnabled false
,D/ActivityThread(12136): Added TimaKeyStore provider
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
,E/JavaBinder( 3525): !!! FAILED BINDER TRANSACTION !!!
,D/TelephonyNetworkFactory( 3977): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3525): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3525): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ActivityManager( 3525): Failed to clear dns cache for: com.samsung.android.sdk.samsunglink
,D/ConnectivityService( 3525): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering( 3525): MasterInitialState.processMessage what=3
,D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
V/NetworkStats( 3525): updateIfacesLocked()
V/NetworkStats( 3525): performPollLocked(flags=0x1)
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3525): UpdateStatsForKnox
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/EntConnectivity( 3525): Not allowed due to - mEnabled false
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
V/NetworkStats( 3525): performPollLocked() took 6ms
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,V/NetworkStats( 3525): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 6886): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/ResourcesManager(12136): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
D/NtpTrustedTime( 3525): currentTimeMillis() cache hit
,I/System.out( 3525): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/sCloudBackupApp(12136): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12136): Other Intent
,I/ActivityManager( 3525): Killing 11183:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11183/oom_score_adj; errno=22
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jan 2016 09:45:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452159924990], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452159924969]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3525): Validated
,D/ConnectivityService( 3525): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3525): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3525): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3525): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/accuweather( 5223): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6886): CM callback handler got msg 524290
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/accuweather( 5223): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5223): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5223): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5223): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5223): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5223): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12157): MountEmulatedStorage()
,E/Zygote  (12157): v2
I/libpersona(12157): KNOX_SDCARD checking this for 1000
I/libpersona(12157): KNOX_SDCARD not a persona
,I/SELinux (12157): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12157): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12157 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12157): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12157): TimaSignature is unavailable
,D/ActivityThread(12157): Added TimaKeyStore provider
,D/ResourcesManager(12157): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12157): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12157): premStatus:2
,I/KnoxUsageLogPro(12157): isEulaShown : false
I/KnoxUsageLogPro(12157): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12172): MountEmulatedStorage()
E/Zygote  (12172): v2
I/libpersona(12172): KNOX_SDCARD checking this for 10090
I/libpersona(12172): KNOX_SDCARD not a persona
,I/SELinux (12172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12172): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12172 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11154:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12172): TimaSignature is unavailable
,D/ActivityThread(12172): Added TimaKeyStore provider
,D/ResourcesManager(12172): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/WifiStateMachine( 3525): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3525): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3525): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,V/        ( 2845): QcRouteController
,E/Zygote  (12189): MountEmulatedStorage()
,E/Zygote  (12189): v2
I/libpersona(12189): KNOX_SDCARD checking this for 10127
,I/libpersona(12189): KNOX_SDCARD not a persona
,I/SELinux (12189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12189 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Killing 11273:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
V/        ( 2845): QcRouteController
E/SELinux (12189): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/NetworkManagementService( 3525): route cmd failed: 
W/NetworkManagementService( 3525): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3525): '
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3525): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3525): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3525): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3525): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3525): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3525): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524295
,D/ConnectivityService( 3525): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 6886): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6886): CM callback handler got msg 524295
,D/TimaKeyStoreProvider(12189): TimaSignature is unavailable
,D/ActivityThread(12189): Added TimaKeyStore provider
,D/ResourcesManager(12189): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12189): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12189): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12189): stopCheckCategoryVersion
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 3525): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  (12206): MountEmulatedStorage()
E/Zygote  (12206): v2
I/libpersona(12206): KNOX_SDCARD checking this for 10136
I/libpersona(12206): KNOX_SDCARD not a persona
,I/SELinux (12206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12206 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12206): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 11290:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/SmartBondingService( 3525): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3525): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3525): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3525): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getSBEnabled() enabled =false
,D/SmartBondingService( 3525): getNetworkEnabled : wifi : true mobile : false
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 882us total 23.150ms
,D/GpsLocationProvider( 3525): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourceType( 5362): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5362): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 828us total 18.539ms
,I/NetworkMonitor(11920): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 6268): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 6268): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/TimaKeyStoreProvider(12206): TimaSignature is unavailable
,D/ActivityThread(12206): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.137ms total 19.121ms
,D/ResourcesManager(12206): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 83077(4MB) AllocSpace objects, 15(240KB) LOS objects, 24% free, 49MB/65MB, paused 1.910ms total 142.678ms
D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12206): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12206): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12206): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12206): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12206): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ConnectivityService( 3525): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
D/ResourcesManager(12206): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12206): Loading: webviewchromium
,I/LibraryLoader(12206): Time to load native libraries: 6 ms (timestamps 1094-1100)
I/LibraryLoader(12206): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12206): Binding Chromium to main looper Looper (main, tid 1) {c89db3c}
,I/LibraryLoader(12206): Expected native library version number "",actual native library version number ""
,I/chromium(12206): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12206): Initializing chromium process, renderers=0
,W/art     (12206): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12206): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,W/AudioManagerAndroid(12206): Requires BLUETOOTH permission
I/chromium(12206): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12206): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/NSApplication(12206): Starting up...
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12284): MountEmulatedStorage()
E/Zygote  (12284): v2
I/libpersona(12284): KNOX_SDCARD checking this for 10150
I/libpersona(12284): KNOX_SDCARD not a persona
,I/SELinux (12284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12284 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (12284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Killing 11258:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
E/SELinux (12284): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12284): TimaSignature is unavailable
,D/ActivityThread(12284): Added TimaKeyStore provider
,D/ResourcesManager(12284): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12284): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12284): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12284): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12284): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12284): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12299): MountEmulatedStorage()
E/Zygote  (12299): v2
I/libpersona(12299): KNOX_SDCARD checking this for 10178
I/libpersona(12299): KNOX_SDCARD not a persona
,I/SELinux (12299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12299 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux (12299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 11307:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12299): TimaSignature is unavailable
,D/ActivityThread(12299): Added TimaKeyStore provider
,D/ResourcesManager(12299): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12299): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12299): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12299): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12299): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12299): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12299): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,D/RCPManagerService( 3525): exchangeData() failure , invalid userId
,E/Zygote  (12322): MountEmulatedStorage()
,E/Zygote  (12322): v2
I/libpersona(12322): KNOX_SDCARD checking this for 10082
I/libpersona(12322): KNOX_SDCARD not a persona
,I/SELinux (12322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12322): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12322 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12338): MountEmulatedStorage()
E/Zygote  (12338): v2
I/libpersona(12338): KNOX_SDCARD checking this for 1000
I/libpersona(12338): KNOX_SDCARD not a persona
,I/SELinux (12338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 11322:com.samsung.helphub/1000 (adj 13): bgCount ##31
I/SELinux (12338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12322): TimaSignature is unavailable
,D/ActivityThread(12322): Added TimaKeyStore provider
,I/ActivityManager( 3525): Killing 11430:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/ResourcesManager(12322): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/TimaKeyStoreProvider(12338): TimaSignature is unavailable
,D/ActivityThread(12338): Added TimaKeyStore provider
,D/BadgeProvider(12322): onCreate
,D/BadgeProvider(12322): DatabaseHelper
,D/ResourcesManager(12338): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12322): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 3525): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 3525): Killing 11449:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/BadgeProvider(12322): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12322): sendNotify, [notify] : null
D/BadgeProvider(12322): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12322): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12322): update, [UpdateCount] : 1
,D/Launcher.Model( 3997): reloadBadges entered.
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12355): MountEmulatedStorage()
E/Zygote  (12355): v2
I/libpersona(12355): KNOX_SDCARD checking this for 10013
I/libpersona(12355): KNOX_SDCARD not a persona
I/SELinux (12355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12355): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12355 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TimaKeyStoreProvider(12355): TimaSignature is unavailable
D/ActivityThread(12355): Added TimaKeyStore provider
D/ResourcesManager(12355): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
D/WaitQueueForNetworkActivate(12355): notifyNetworkActivated
W/ContextImpl(12355): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 3525): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
D/hcjo    (12355): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine(12355): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12355): exit::IDLE
D/InitializeManagerStateMachine(12355): entry::NETWORK_CHECK
D/InitializeManagerStateMachine(12355): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12355): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12355): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12355): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12355): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12355): entry::SUCCESS
D/hcjo    (12355): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setDiscoveryMode: Mode set to BLE
I/jxcore-log(11759): BLE is supported
I/jxcore-log(11759): 
D/hcjo    (12355): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12355): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12355): exit::SUCCESS
D/InitializeManagerStateMachine(12355): entry::IDLE
I/Hs20UtilService( 4085): Starting #10
I/Hs20UtilService( 4085): Message received 5007
D/NearbySettings( 8802): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8802): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8802): MountReceiver.onReceive - Keep current state
I/ActivityManager( 3525): Killing 11467:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
I/SignOutReceiver(11407): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 4085): Starting #11
I/Hs20UtilService( 4085): Message received 5007
D/NearbySettings( 8802): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8802): MountReceiver.onReceive - Keep current state
I/SignOutReceiver(11407): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 4085): Starting #12
I/Hs20UtilService( 4085): Message received 5007
D/NearbySettings( 8802): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8802): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8802): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8802): MountReceiver.onReceive - Keep current state
I/SignOutReceiver(11407): NETWORK_STATE_CHANGED_ACTION
I/Hs20UtilService( 4085): Starting #13
I/Hs20UtilService( 4085): Message received 5007
D/NearbySettings( 8802): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8802): MountReceiver.onReceive - Keep current state
I/WifiStateMachine( 3525): callSECApi what=220
D/WifiStateMachine( 3525): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
I/SignOutReceiver(11407): NETWORK_STATE_CHANGED_ACTION
I/PCWCLIENTTRACE_PushUtil(11900): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11900): sales region : global
I/PCWCLIENTTRACE_PushUtil(11900): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11900): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 3525): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525
I/DIAGMON_AGENT(11984): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(11984): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/mali_winsys( 3690): new_window_surface returns 0x3000,  [1120x201]-format:1
I/FOTA_Client(12003): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
I/FOTA_Client(12003): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/FOTA_Client(12003): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
I/KLMS-2.4.521: (12019): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 07 10:45:27 GMT+01:00 2016
I/KLMS-2.4.521: (12019): KLMSAbstractReciever(): onReceive().END.
I/KLMS-2.4.521: (12019): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (12019): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12019): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (12019): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (12019): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.4.521: (12019): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
I/KLMS-2.4.521: (12019): StateImplV2(): networkChangeListener().START
I/SO_AGENT(12041): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
I/KLMS-2.4.521: (12019): NetworkChangeOperations(): uploadRequestLog().START 
I/KLMS-2.4.521: (12019): NetworkChangeOperations(): uploadRequestLog().END 
I/KLMS-2.4.521: (12019): StateImplV2(): networkChangeListener().END
I/KLMS-2.4.521: (12019): KLMSIntentService(): onDestroy()
E/SPPClientService(12096): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
I/SA      (11203): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (11203): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11203): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11203): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11203): [OR] == isSIMCardReady false ==
I/SA      (11203): [SCU] == networkStateCheck == true
I/SA      (11203): [DM] getCountryCodeFromCSC : PL
I/SA      (11203): isChinaCountryCode : false
I/SA      (11203): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11203): [OR] == networkStateCheck true ==
I/SA      (11203): [OR] GetMyCountryZoneTask
I/SA      (11203): [OR] onReceive END
I/SA      (11203): [SRS] prepareGetMyCountryZone
V/DownloadManager( 5494): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/SA      (11203): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11203): [SSP] query invoked
I/SCloudBackupReceiver(12136): Other Intent
D/accuweather( 5223): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/SA      (11203): [TPMU] GetMccFromDB : null
I/SA      (11203): [SCU] getMccFromPreferece mcc = 260
I/SA      (11203): [TPM] isNoProxy(default) : true
D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
D/accuweather( 5223): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5223): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5223): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5223): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5223): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/accuweather( 5223): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
I/KnoxUsageLogPro(12157): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12157): premStatus:2
I/KnoxUsageLogPro(12157): isEulaShown : false
I/KnoxUsageLogPro(12157): KnoxUsageReceiver onReceive : not Processible, just return
D/KeyguardWallpaperUpdator(12189): cancelUpdateWallpaper
D/KeyguardWallpaperUpdator(12189): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12189): stopCheckCategoryVersion
D/QuickConnect(12284): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect(12284): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12284): PeriphStartReceiver.onReceive - no need to start
D/RCPManagerService( 3525): exchangeData() failure , invalid userId
D/RCPManagerService( 3525): exchangeData() failure , invalid userId
D/hcjo    (12355): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine(12355): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12355): exit::IDLE
D/InitializeManagerStateMachine(12355): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12355): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12355): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12355): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12355): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12355): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12355): entry::SUCCESS
D/hcjo    (12355): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12355): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12355): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12355): exit::SUCCESS
D/InitializeManagerStateMachine(12355): entry::IDLE
,I/SA      (11203): [RC New] Execute method=[GET] start
,I/SA      (11203): [RC New] Security=[true]
,I/System.out(11203): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11203): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11203): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11203): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,I/dhcpcd  (11958): wlan0: sending IPv6 Router Solicitation
,I/WifiStateMachine( 3525): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3525): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      (11203): [RC New] [v2liruge] api execute + 793
,I/SA      (11203): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11203): AsyncTask #1 calls detatch()
,I/SA      (11203): [TPMU] getNetworkMcc : 
,I/SA      (11203): [SCU] saveMccToPreferece Start
,I/SA      (11203): [SCU] RegionMCC : 260
,I/SA      (11203): [SSP] query invoked
,I/SA      (11203): [TPMU] GetMccFromDB : null
,I/SA      (11203): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11203): [SCU] saveMccToPreferece End
,I/SA      (11203): [RC New] executeRequest [v2liruge] end. 858
,I/SA      (11203): [RC New] Execute end
,I/SA      (11203): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11203): [OR] GetMyCountryZoneTask Success
,D/WearableService( 4633): callingUid 10014, callindPid: 4633
,D/ResourcesManager(11920): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(11920): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(11920): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(11920): Using the GMSCore's GoogleHttpClient
,D/SSRM:n  ( 3525): SIOP:: AP = 250, PST = 251, CUR = 57
,D/WearableClient(11920): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11920): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11920): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11920): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11920): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(11920): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/MusicLeanback(11920): Conditions not met for autocaching.
I/MusicLeanback(11920): Stop autocaching.
,E/ActivityThread(11920): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@18ab23fc that was originally bound here
E/ActivityThread(11920): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@18ab23fc that was originally bound here
E/ActivityThread(11920): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11920): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11920): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11920): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11920): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11920): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11920): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11920): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11920): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11920): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11920): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11920): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11920): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11920): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11920): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11920): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11920): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11920): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11920): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11920): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11920): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11920): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11920): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11920): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/PowerManagerService( 3525): [PWL] Off : 50s ago
,D/PackageManager( 3525): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
D/BatteryService( 3525): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 3525): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3525) eventTime = 145715
,D/PowerManagerService( 3525): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3525 (0x0)
D/PowerManagerService( 3525): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3525, ws=WorkSource{10060}) (elapsedTime=3485)
,I/GAV4    (12206): Thread[GAThread,5,main]: No campaign data found.
,I/dhcpcd  (11958): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PCWCLIENTTRACE_SYSTEMReceiver(11900): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11900): [hasSamungAccount] - No Samsung Account
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 12460
,I/CSTORAGE(11900): ================================================
I/CSTORAGE(11900):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11900): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI(11900): [GetString-S]
,E/art     (11900): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI(11900): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11900): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11900): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11900): sales region : global
I/PCWCLIENTTRACE_PushUtil(11900): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11900): [ensureRegistration] - No Samsung account
,I/dhcpcd  (11958): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (11958): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12355): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12355): exit::IDLE
D/PreloadUpdateManagerStateMachine(12355): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12355): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12355): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12355): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12355): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12355): entry::IDLE
,D/PreloadUpdateManagerStateMachine(12355): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12355): exit::IDLE
D/PreloadUpdateManagerStateMachine(12355): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12355): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12355): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12355): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12355): entry::IDLE
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 248, CUR = 26,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 5
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 246, CUR = 47
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 229, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 75s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 245, CUR = 52
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :8
,I/ClearcutLoggerApiImpl( 4633): disconnect managed GoogleApiClient
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 244, CUR = 51
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:50
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 6
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 241, CUR = 49
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3525): [PWL] Off : 105s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 230, PST = 237, CUR = 45,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 235, CUR = 44
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:41, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3525): !@Sync 7
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 233, CUR = 41
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 231, CUR = 38
,I/PowerManagerService( 3525): [PWL] Off : 140s ago
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3525): waitForAlarm result :8
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 230, CUR = 37
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3525): !@Sync 8
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 228, CUR = 35
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 227, CUR = 34
,I/jxcore-log(11759): Connected to the server!
I/jxcore-log(11759): 
,I/chromium(11759): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 180s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 226, CUR = 33
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 9
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 224, CUR = 32
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 223, CUR = 32
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 223, CUR = 31
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3525): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3525): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3525): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3525): initializing...
,I/TLC_TIMA_PKM_initialize( 3525): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3525): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3525): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3525): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3525): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3525): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3525): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3525): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 3525): device_id = 0x0
I/TZ: mc_tlc_communication( 3525): tlc_open() was called
,I/TZ: mc_tlc_communication( 3525): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3525): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3525): Opening the session
,I/TZ: mc_tlc_communication( 3525): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3525): Trustlet response is completed
,E/Watchdog( 3525): !@Sync 10
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 222, CUR = 30
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3525): [PWL] Off : 225s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 221, CUR = 28
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 221, CUR = 30
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 11
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 29
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 28,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 29
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3525): [PWL] Off : 275s ago
,E/Watchdog( 3525): !@Sync 12
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 28
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11759): --- start :testFindPeers.js---
I/jxcore-log(11759): 
,I/jxcore-log(11759): testFindPeers created [object Object]
I/jxcore-log(11759): 
,I/jxcore-log(11759): serverPort is 8876
I/jxcore-log(11759): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11759): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11759): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,D/BluetoothSocket(11759): bindListen(), new LocalSocket 
D/BluetoothSocket(11759): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket(11759): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f9a5bd1
,D/BluetoothSocket(11759): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): start: OK
,I/io.jxcore.node.ConnectionHelper(11759): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11759): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11759): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): start: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11759): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3525): InactiveState{ what=139292 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 3525): P2pEnabledState add service
,D/WifiP2pService( 3525): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper(11759): start: OK
,D/WifiP2pService( 3525): InactiveState{ what=139265 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3525): callSECApi what=74
D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log(11759): StartBroadcasting started ok
I/jxcore-log(11759): 
,D/WifiP2pService( 3525): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper(11759): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper(11759): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11759): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/chromium(11759): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 28
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 },
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 },
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState add service request
D/WifiP2pManager(11759): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 3525): InactiveState{ what=147494 },
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/jxcore-log(11759): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log(11759): 
,I/jxcore-log(11759): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(11759): 
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 27
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,E/Watchdog( 3525): !@Sync 13
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 27
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 },
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 },
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3525): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=147494 }
D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3525): P2pEnabledState receive service response
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,I/jxcore-log(11759): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log(11759): 
D/WifiDisplayController( 3525): Received list of peers.
I/jxcore-log(11759): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(11759): 
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 6 device(s) discovered
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3525): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiP2pService( 3525): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3525): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3525): InactiveState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 7 device(s) discovered
,D/WifiP2pService( 3525): P2pEnabledState discover services
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
I/WifiStateMachine( 3525): callSECApi what=74
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 26,
,V/AlarmManager( 3525): waitForAlarm result :8
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-5 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.,
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
D/WifiP2pService( 3525): InactiveState{ what=139307 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/PowerManagerService( 3525): [PWL] Off : 330s ago
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
D/WifiP2pService( 3525): P2pEnabledState discover services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
I/WifiStateMachine( 3525): callSECApi what=74
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3525): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 3525): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 26
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 3525): InactiveState{ what=147494 },
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log(11759): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log(11759): 
,I/jxcore-log(11759): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(11759): 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 232, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3525): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log(11759): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log(11759): 
,I/jxcore-log(11759): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(11759): 
,E/Watchdog( 3525): !@Sync 14,
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 27
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/jxcore-log(11759): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log(11759): 
,I/jxcore-log(11759): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(11759): 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 26
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 220, CUR = 25
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3525): !@Sync 15
,D/SSRM:n  ( 3525): SIOP:: AP = 210, PST = 219, CUR = 24
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): restart: Restarting...,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: RESTARTING
,D/WifiP2pService( 3525): InactiveState{ what=139268 }
,I/wpa_supplicant( 3825): P2P-FIND-STOPPED 
,D/WifiP2pService( 3525): InactiveState{ what=147493 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3525): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/SSRM:n  ( 3525): SIOP:: AP = 210, PST = 218, CUR = 24,
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): Start timer timeout, starting now...
,D/WifiP2pService( 3525): InactiveState{ what=139265 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139265 }
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: STARTED
,D/WifiP2pService( 3525): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log(11759): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log(11759): 
,I/jxcore-log(11759): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(11759): 
,I/jxcore-log(11759): timeout now
I/jxcore-log(11759): 
,I/jxcore-log(11759): weAreDoneNow
I/jxcore-log(11759): 
,I/jxcore-log(11759): done, now sending data to server
I/jxcore-log(11759): 
,I/PowerManagerService( 3525): [PWL] Off : 390s ago
,D/SSRM:n  ( 3525): SIOP:: AP = 210, PST = 218, CUR = 22
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 3525): !@Sync 16
,D/SSRM:n  ( 3525): SIOP:: AP = 210, PST = 218, CUR = 23
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/jxcore-log(11759): teardown
I/jxcore-log(11759): 
,I/jxcore-log(11759): testFindPeers stopped
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): shutdown
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@2817e40d, channel: 6, state: LISTENING
D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@2817e40d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f9a5bd1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8b63fc2mSocket: android.net.LocalSocket@f1271d3 impl:android.net.LocalSocketImpl@25baf110 fd:FileDescriptor[115]
D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@f1271d3 impl:android.net.LocalSocketImpl@25baf110 fd:FileDescriptor[115]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): stop: Stopping services
D/WifiP2pService( 3525): InactiveState{ what=139298 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139298 }
D/WifiP2pService( 3525): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: NOT_INITIALIZED
D/WifiP2pService( 3525): InactiveState{ what=139268 }
I/wpa_supplicant( 3825): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11759): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setState: NOT_STARTED
,I/jxcore-log(11759): StopBroadcasting went ok
I/jxcore-log(11759): 
D/WifiP2pService( 3525): InactiveState{ what=147493 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 3525): P2pEnabledState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 3525): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper(11759): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11759): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper(11759): onDiscoveryManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery stopped successfully
D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3525): P2pEnabledState clear service request
D/WifiP2pService( 3525): remove channel information from framework
,I/jxcore-log(11759): --- start :testSendData.js---
I/jxcore-log(11759): 
,I/jxcore-log(11759): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log(11759): 
,I/jxcore-log(11759): daya100000
I/jxcore-log(11759): 
,I/jxcore-log(11759): check server
I/jxcore-log(11759): 
I/jxcore-log(11759): serverPort is 53402
I/jxcore-log(11759): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): initialize: My bluetooth address is E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11759): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket(11759): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[116]}
D/BluetoothSocket(11759): bindListen(), new LocalSocket 
D/BluetoothSocket(11759): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket(11759): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2eac960e
D/BluetoothSocket(11759): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): start: OK
I/io.jxcore.node.ConnectionHelper(11759): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): start: Peer ID: E0:DB:10:14:E2:C0, peer name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent(11759): verifyIdentityString: Identity string created: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11759): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): start: {"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11759): start: Identity string: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 3525): InactiveState{ what=139292 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139292 }
D/WifiP2pService( 3525): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): start: Starting P2P device discovery...
D/WifiP2pService( 3525): add a new client
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setState: RUNNING
I/io.jxcore.node.ConnectionHelper(11759): start: OK
,I/jxcore-log(11759): StartBroadcasting started ok
I/jxcore-log(11759): 
D/WifiP2pService( 3525): InactiveState{ what=139265 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139265 }
I/WifiStateMachine( 3525): callSECApi what=74
D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 3525): discovery change broadcast true
,I/jxcore-log(11759): [ { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log(11759):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log(11759):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log(11759):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log(11759):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log(11759):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log(11759):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log(11759):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log(11759):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log(11759):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log(11759):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log(11759):   { address: '7C:F9:0E:51:18:22', tryCount: 0 } ]
I/jxcore-log(11759): 
,I/jxcore-log(11759): startWithNextDevice
I/jxcore-log(11759): 
I/jxcore-log(11759): do fake peer & start
I/jxcore-log(11759): 
I/jxcore-log(11759): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
I/jxcore-log(11759): 2016-01-07T09:51:27.197Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:27.198Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
I/jxcore-log(11759): 2016-01-07T09:51:27.198Z SendDataConnector.js: do connect now
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): connect: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper(11759): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 1659)
,I/jxcore-log(11759): 2016-01-07T09:51:27.204Z SendDataTCPServer.js: TCP/IP server is bound to port: 53402
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper(11759): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onWifiStateChanged: State changed to 2
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper(11759): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11759): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: STARTED
D/WifiP2pService( 3525): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 3825): P2P-FIND-STOPPED 
,I/chromium(11759): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery stopped successfully
,D/WifiP2pService( 3525): InactiveState{ what=147493 }
D/WifiP2pService( 3525): P2pEnabledState{ what=147493 }
D/WifiP2pService( 3525): discovery change broadcast false
D/BluetoothUtils(11759): isSocketAllowedBySecurityPolicy start : device null,
W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
I/chromium(11759): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 5658): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: RESTARTING
,D/BluetoothSocket(11759): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
D/WifiP2pService( 3525): InactiveState{ what=139268 }
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,W/bt-btif ( 5658): info:x10
,D/        ( 5658): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5658): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 5658): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5658): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,I/BluetoothBondStateMachine( 5658): Entering PendingCommandState State
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12922): MountEmulatedStorage()
I/libpersona(12922): KNOX_SDCARD checking this for 10102
E/Zygote  (12922): v2
I/libpersona(12922): KNOX_SDCARD not a persona
I/ActivityManager( 3525): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.common.receiver.AutoLaunchReceiver: pid=12922 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/SELinux (12922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12922): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12922): TimaSignature is unavailable
,D/ActivityThread(12922): Added TimaKeyStore provider
,D/btif_config_util( 5658): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 5658): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,D/ResourcesManager(12922): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,W/ResourcesManager(12922): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,D/HidService( 5658): getHidService(): returning com.android.bluetooth.hid.HidService@37ebee10
,D/SettingsProvider( 3525): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/HidService( 5658): Saved priority 7C:F9:0E:37:96:AB = -1
W/bt-btif ( 5658): new conn_srvc id:26, app_id:1
W/bt-btif ( 5658): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5658): bta_dm_pm_ssr:2, lat:1200
,D/SettingsProvider( 3525): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
E/BluetoothRemoteDevices( 5658): setRfcommConnected true
D/SettingsProvider( 3525): ret = -1
,D/SettingsProvider( 3525): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,I/BluetoothBondStateMachine( 5658): StableState(): Entering Off State
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onSocketConnected: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1659)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesWritten: 66 bytes successfully written (thread ID: 1660)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Outgoing connection initialized (*handshake* thread ID: 1660)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Exiting thread (thread ID: 1659)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Entering thread (ID: 1660)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesRead: Read 63 bytes successfully (thread ID: 1660)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Handshake succeeded with [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onHandshakeSucceeded: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Exiting thread (ID: 1660)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnected: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper(11759): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11759): Entering thread (ID: 1661)
,D/io.jxcore.node.OutgoingSocketThread(11759): Server socket local port: 41317
I/io.jxcore.node.OutgoingSocketThread(11759): Now accepting connections...
,W/bt-btif ( 5658): invalid rfc slot id: 6
,E/[CarMode](12922): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager(12922): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(12922): mContext is not null
,I/VlingoAndroidCore(12922): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12951): MountEmulatedStorage()
E/Zygote  (12951): v2
I/libpersona(12951): KNOX_SDCARD checking this for 10034
I/libpersona(12951): KNOX_SDCARD not a persona
,I/SELinux (12951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=12951 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/SELinux (12951): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12951): TimaSignature is unavailable
,D/ActivityThread(12951): Added TimaKeyStore provider
,D/ResourcesManager(12951): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/System.out(12951): Inside WakeupProvider
,E/DatabaseUtils(12951): Writing exception to parcel
E/DatabaseUtils(12951): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12951): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12951): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12951): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12951): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12951): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12951): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12951): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12951): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12951): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12951): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(12922): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(12922): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12922): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12922): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12922): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12922): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12922): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12922): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12922): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12922): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err(12922): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(12922): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err(12922): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(12922): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(12922): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(12922): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12922): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12922): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12922): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12922): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12922): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12922): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12922): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12922): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12922): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils(12951): Writing exception to parcel
E/DatabaseUtils(12951): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(12951): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(12951): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(12951): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(12951): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(12951): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(12951): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(12951): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(12951): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(12951): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(12951): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(12922): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err(12922): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(12922): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(12922): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(12922): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(12922): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(12922): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(12922): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(12922): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(12922): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(12922): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(12922): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(12922): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(12922): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(12922): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(12922): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(12922): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(12922): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(12922): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12922): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(12922): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(12922): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(12922): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(12922): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(12922): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode](12922): [DLApplication]-Init Called!:false
W/[CarMode](12922): [CommonUtil]-=========================================
W/[CarMode](12922): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](12922): [CommonUtil]-=========================================
E/[CarMode](12922): [DLApplication]-Init Started!:true
,I/[CarModeFW](12922): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](12922): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](12922): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](12922): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](12922): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](12922): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](12922): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](12922): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](12922): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](12922): ### android.os.Looper::loop(145)
I/[CarModeFW](12922): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](12922): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](12922): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](12922): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoApplication(12951): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
,I/io.jxcore.node.ConnectionHelper(11759): onListeningForIncomingConnections: Outgoing connection is using port 41317 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log(11759): 2016-01-07T09:51:29.150Z SendDataConnector.js: CLIENT connected to 41317, error: null
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:29.150Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11759): 
,I/MessageDataHandler(12922): initialize
,I/io.jxcore.node.OutgoingSocketThread(11759): Incoming data from address: /127.0.0.1, port: 41317
D/io.jxcore.node.OutgoingSocketThread(11759): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
D/[CarModeFW](12922): CDH-initiazlieCaches : before sync
D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1662, name: Sender)
I/io.jxcore.node.OutgoingSocketThread(11759): startStreamCopyingThreads: OK
D/[CarModeFW](12922): CDH-initiazlieCaches : after sync
D/io.jxcore.node.OutgoingSocketThread(11759): Exiting thread (ID: 1661)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1663, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1663, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread(11759): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread(11759): close
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1663
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1662
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local input stream...
I/jxcore-log(11759): 2016-01-07T09:51:29.162Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11759): 
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11759): closeBluetoothSocketAndStreams
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@2a1287c5, channel: 6, state: CONNECTED
D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@2a1287c5, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16a0051a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fcc484bmSocket: android.net.LocalSocket@d03d228 impl:android.net.LocalSocketImpl@2798db41 fd:FileDescriptor[117]
D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@d03d228 impl:android.net.LocalSocketImpl@2798db41 fd:FileDescriptor[117]
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@2a1287c5, channel: 6, state: CLOSED
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@2a1287c5, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1663, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1662, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1662, name: Sender)
,I/VlingoAndroidCore(12951): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
,D/[CarModeFW](12922): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW](12922): CDH-ContactDataHandler initiazlieCaches time : 31
D/[CarModeFW](12922): CDH-initiazlieCaches : end sync
,D/[CarModeFW](12922): DrivingManager-initialize...
,I/SensorService( 3525): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3525): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3525): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3525): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3525): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,D/VlingoApplication(12951): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication(12951): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(12951): initQueue()
,I/MediaPlayer(12922): Need to enable context aware info
V/MediaPlayer-JNI(12922): native_setup
V/MediaPlayer(12922): constructor
,V/MediaPlayer(12922): setListener
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 66310(5MB) AllocSpace objects, 111(1777KB) LOS objects, 24% free, 49MB/65MB, paused 3.125ms total 171.982ms
,D/[CarModeFW](12922): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW](12922): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode](12922): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1452160289452
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1452160289452
D/[CarMode](12922): [DLServiceManager]-updateLocationList
D/[CarMode](12922): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1452160289452
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1452160289453
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1452160289453
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1452160289455
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1452160289455
D/[CarModeFW](12922): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,F/DLApplication(12922): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
,I/[CarMode](12922): [LogNotNull]-Package name is: com.here.app.maps
,D/TP/SmsProvider( 3977): query,matched:2, calling pid = 12922
,E/[CarMode](12922): [DLApplication]-Init End!:true
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 3977): match 2:Elapsed time : 2.589 ms
,D/[CarModeFW](12922): ContactDataHandler-getFavoriteContactList : cur len = 0
D/[CarMode](12922): [TAG]-phone sound mode is: 0
V/[CarMode](12922): [DLApplication]-savePreviousGpsState
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 24
,D/[CarModeFW](12922): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 26
,E/Zygote  (12999): MountEmulatedStorage()
E/Zygote  (12999): v2
I/libpersona(12999): KNOX_SDCARD checking this for 10047
I/libpersona(12999): KNOX_SDCARD not a persona
,I/SELinux (12999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=12999 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12999): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler(12922):  getInboxList smsCursor : 41
,D/TP/SmsProvider( 3977): query,matched:2, calling pid = 12922
,D/TP/SmsProvider( 3977): match 2:Elapsed time : 1.671 ms
,V/[CarMode](12922): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/[CarModeFW](12922): CalllogDataHandler-getCalllogList : cur len = 0
,D/TP/MmsProvider( 3977): Query uri=content://mms/inbox, match=2, calling pid = 12922
D/[CarModeFW](12922): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 56
,D/MessageDataHandler(12922):  getInboxList mmsCursor : 16
,D/TP/MmsProvider( 3977): Query uri=content://mms, match=0, calling pid = 12922
,D/MessageDataHandler(12922):  getInboxList mms,sms cursor join : 5
,I/MessageDataHandler(12922): getUnreadMessageCount :0
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 63
,D/TP/MmsSmsProvider( 3977): query,matched:0, calling pid = 12922
V/TP/MmsSmsProvider( 3977): getSimpleConversations entered.
,D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 67
,D/TP/MmsSmsProvider( 3977): match 0:Elapsed time : 4.843 ms
,D/[CarMode](12922): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](12922): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/TimaKeyStoreProvider(12999): TimaSignature is unavailable
,D/ActivityThread(12999): Added TimaKeyStore provider
,I/[CarMode](12922): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode](12922): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/TP/MmsSmsProvider( 3977): query,matched:13, calling pid = 12922
,D/TP/MmsSmsProvider( 3977): match 13:Elapsed time : 1.105 ms
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED A5-1 state is 11
,D/DialogFlow(12922): initQueue()
,D/ResourcesManager(12999): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,I/ActivityManager( 3525): Killing 11517:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/MessageDataHandler(12922):  getInboxList address cursor : 20
,D/TP/MmsSmsProvider( 3977): query,matched:0, calling pid = 12922
V/TP/MmsSmsProvider( 3977): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3977): match 0:Elapsed time : 1.565 ms
W/ResourcesManager(12999): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SSRM:n  ( 3525): SIOP:: AP = 210, PST = 217, CUR = 23
,D/MessageDataHandler(12922):  getInboxList thread cursor : 8
,D/MessageDataHandler(12922):  thread, addr result: 5
,I/[CarModeFW](12922): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 113
I/[CarModeFW](12922): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 113
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/System.out(12951): INFO:Resource not found:/Common.properties Using default values
,I/CalendarProvider2(12999): CalendarProvider2.onCreate() called
,E/Zygote  (13015): MountEmulatedStorage()
E/Zygote  (13015): v2
I/libpersona(13015): KNOX_SDCARD checking this for 10121
I/libpersona(13015): KNOX_SDCARD not a persona
,I/SELinux (13015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/.GMHFPReceiver: pid=13015 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,I/ActivityManager( 3525): Killing 11500:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/ActivityManager( 3525): Killing 11537:com.android.calendar/u0a164 (adj 15): bgCount ##32
,D/TimaKeyStoreProvider(13015): TimaSignature is unavailable
,D/ActivityThread(13015): Added TimaKeyStore provider
,D/ResourcesManager(13015): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
,D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,W/BackupManagerService( 3525): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/GMFPReceiver(13015): ::::::::Wearable0002::false
,D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,I/ActivityManager( 3525): Killing 10818:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED A5-1 state is 10
,D/[CarModeFW](12922): LocationDataHandler-No schedules found.
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,D/[CarModeFW](12922): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
,D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0002::false
,D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,E/Zygote  (13035): MountEmulatedStorage()
I/libpersona(13035): KNOX_SDCARD checking this for 10003
E/Zygote  (13035): v2
I/libpersona(13035): KNOX_SDCARD not a persona
,I/SELinux (13035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=13035 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
E/SELinux (13035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(13035): TimaSignature is unavailable
,D/ActivityThread(13035): Added TimaKeyStore provider
,D/BootupListener( 3977): ACTION_DRIVELINK
,D/SettingsProvider( 3525): name = drivelink_navigation
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1001
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/BootupListener( 3977): NAVI : com.here.app.maps
,D/SettingsProvider( 3525): name = internet_call_settings_visibility
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1001
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/BootupListener( 3977): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/ResourcesManager(13035): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(13035): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager(13035): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(13035): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(13035): Create SecureDbHelper
,D/IntelligenceServiceApplication(13035): onCreate()
,D/[CarModeFW](12922): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](12922): MyPlaceProvider-=============
D/[CarModeFW](12922): MyPlaceProvider-=============
D/[CarModeFW](12922): MyPlaceProvider-=============
D/[CarModeFW](12922): MyPlaceProvider-=============
D/[CarModeFW](12922): MyPlaceProvider-=============
D/[CarModeFW](12922): MyPlaceProvider-=============
D/[CarModeFW](12922): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](12922): MyPlaceProvider-==============
D/[CarModeFW](12922): MyPlaceProvider-==============
D/[CarModeFW](12922): MyPlaceProvider-==============
D/[CarModeFW](12922): MyPlaceProvider-==============
D/[CarModeFW](12922): MyPlaceProvider-==============
,D/[CarModeFW](12922): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1452160289829 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](12922): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(12922): loadLocationDestinationList is null
D/[CarModeFW](12922): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 377
,I/CalendarProvider2(12999): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13060): MountEmulatedStorage()
E/Zygote  (13060): v2
I/libpersona(13060): KNOX_SDCARD checking this for 10022
I/libpersona(13060): KNOX_SDCARD not a persona
,I/SELinux (13060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13060): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=13060 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11647:com.android.vending/u0a31 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(13060): TimaSignature is unavailable
,D/ActivityThread(13060): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 872us total 33.172ms
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 872us total 19.081ms
,W/ResourcesManager(13060): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13060): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13060): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 809us total 18.735ms
,I/LocationWidgetApplication(13060): onCreate() : start
,D/LocationWidgetApplication(13060): countryCode = POLAND
,D/LocationWidgetUtils(13060): getUpcommingInstances() start: 1452160290905, end: 1452725999999
,D/LocationWidgetUtils(13060): getUpcommingInstances() DB begin time >= start:1452160290905, DB begin time <= end:1452725999999
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13082): MountEmulatedStorage()
,E/Zygote  (13082): v2
I/libpersona(13082): KNOX_SDCARD checking this for 10163
I/libpersona(13082): KNOX_SDCARD not a persona
,I/SELinux (13082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=13082 uid=10163 gids={50163, 9997} abi=armeabi-v7a
E/SELinux (13082): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 12322:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(13082): TimaSignature is unavailable
,D/ActivityThread(13082): Added TimaKeyStore provider
,D/ResourcesManager(13082): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(13082): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(13082): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (13101): MountEmulatedStorage()
E/Zygote  (13101): v2
I/libpersona(13101): KNOX_SDCARD checking this for 10164
I/libpersona(13101): KNOX_SDCARD not a persona
,I/SELinux (13101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=13101 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11407:com.samsung.android.snote/u0a160 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(13101): TimaSignature is unavailable
,D/ActivityThread(13101): Added TimaKeyStore provider
,D/ResourcesManager(13101): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(13101): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(13101): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13101): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationManagerService( 3525): getProviders()=[]
D/LocationManagerService( 3525): getProviders()=[passive]
,D/LocationManagerService( 3525): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(13060): mPrivacy is null
,W/ContextImpl(13060): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3525): Killing 11900:com.sec.pcw.device/1000 (adj 15): bgCount ##31
,D/ContextFramework:PrivacyManager(13060): Service for PrivacyManager is connected
,D/LWLocationManager(13060): Privacy service : STATUS_PLACE
D/LWLocationManager(13060): updateLocationStatus()
,I/LocationWidgetFuctionData(13060): readDB
,I/LocationWidgetFuctionData(13060): selectedAppSize: 3
I/LocationWidgetFuctionData(13060): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(13060): selectedAppSize: 3
,I/LocationWidgetFuctionData(13060): selectedAppSize: 3
,I/LocationWidgetFuctionData(13060): selectedAppSize: 3
,I/LocationWidgetFuctionData(13060): selectedAppSize: 3
,E/LWLocationManager(13060): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(13060): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(13060): setShouldUpdateLocationId
D/LWLocationManager(13060): setShouldUpdateLocationId return false
D/LWLocationManager(13060): setShouldUpdateLocationId
D/LWLocationManager(13060): setShouldUpdateLocationId return false
D/LWLocationManager(13060): setShouldUpdateLocationId
D/LWLocationManager(13060): setShouldUpdateLocationId return false
D/LWLocationManager(13060): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc0e44 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): Start timer timeout, starting now...
,D/WifiP2pService( 3525): InactiveState{ what=139265 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139265 }
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: STARTED
,D/WifiP2pService( 3525): discovery change broadcast true
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 13127
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:-1, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 5658): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5658): btm_sec_disconnected - Clearing Pending flag,
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 5658): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3170b04e
,D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,I/BluetoothPbapService( 5658): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8802): ACTION_ACL_DISCONNECTED
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12922): ConnectivityManager-Paired Devices list is empty
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4038): Bluetooth Device Name: A5-1
,E/[CarMode](12922): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13],
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = -1
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiP2pService( 3525): InactiveState{ what=139283 },
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 3525): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
D/WifiP2pService( 3525): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,I/WifiStateMachine( 3525): callSECApi what=74
D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,E/Watchdog( 3525): !@Sync 17
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 },
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 14
,I/jxcore-log(11759): 2016-01-07T09:51:49.696Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:49.700Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:49.707Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:49.711Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:49.718Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log(11759): 
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11759): 2016-01-07T09:51:54.717Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:54.723Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:54.727Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 20
,D/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB,
,D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection,
,I/jxcore-log(11759): 2016-01-07T09:51:59.751Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:59.753Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:59.754Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:51:59.755Z SendDataConnector.js: do connect now
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): connect: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnecting: A5-1 7C:F9:0E:37:96:AB
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper(11759): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 1664)
,D/BluetoothUtils(11759): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5658): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 5658): db_query_execute: result 1
,D/BluetoothSocket(11759): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,W/bt-btif ( 5658): info:x10
,D/        ( 5658): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_CONNECTED State = -2147483648 Previous = -2147483648
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED
,I/BluetoothClassifier( 4038): Bluetooth Device Name: A5-1
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_CONNECTED onNotifyBluetoothDeviceConnected
D/[CarModeFW](12922): ConnectivityManager-handleMessage CONNECTION_COMPLETE
,W/bt-sdp  ( 5658): process_service_search_attr_rsp
,W/bt-btif ( 5658): new conn_srvc id:26, app_id:1
W/bt-btif ( 5658): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 5658): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5658): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onSocketConnected: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1664)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesWritten: 66 bytes successfully written (thread ID: 1665)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Outgoing connection initialized (*handshake* thread ID: 1665)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Exiting thread (thread ID: 1664)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Entering thread (ID: 1665)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesRead: Read 63 bytes successfully (thread ID: 1665)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Handshake succeeded with [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onHandshakeSucceeded: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Exiting thread (ID: 1665)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnected: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper(11759): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11759): Entering thread (ID: 1666)
,D/io.jxcore.node.OutgoingSocketThread(11759): Server socket local port: 53233
,I/io.jxcore.node.OutgoingSocketThread(11759): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper(11759): onListeningForIncomingConnections: Outgoing connection is using port 53233 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log(11759): 2016-01-07T09:52:00.903Z SendDataConnector.js: CLIENT connected to 53233, error: null
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:00.906Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11759): 
,I/io.jxcore.node.OutgoingSocketThread(11759): Incoming data from address: /127.0.0.1, port: 53233
,D/io.jxcore.node.OutgoingSocketThread(11759): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread(11759): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread(11759): Exiting thread (ID: 1666)
,I/jxcore-log(11759): 2016-01-07T09:52:00.935Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11759): 
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1668, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1667, name: Sender)
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc0e44 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:11516
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3525): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:66932
,I/jxcore-log(11759): 2016-01-07T09:52:04.278Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:58508
,I/jxcore-log(11759): 2016-01-07T09:52:05.079Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11759): 
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,I/WifiStateMachine( 3525): callSECApi what=74,
D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:48388
,I/jxcore-log(11759): 2016-01-07T09:52:06.008Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11759): 
,D/btif_config_util( 5658): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:38268
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
I/jxcore-log(11759): 2016-01-07T09:52:06.496Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11759): 
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 },
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:28148
,I/jxcore-log(11759): 2016-01-07T09:52:06.821Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11759): 
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 22
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 455s ago
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:18028
,I/jxcore-log(11759): 2016-01-07T09:52:15.180Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11759): 
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac,
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,E/Watchdog( 3525): !@Sync 18
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:7908
,I/jxcore-log(11759): 2016-01-07T09:52:19.612Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11759): 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 21
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/jxcore-log(11759): 2016-01-07T09:52:21.854Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11759): 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log(11759): 2016-01-07T09:52:24.463Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11759): 
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/WifiP2pService( 3525): InactiveState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,I/jxcore-log(11759): 2016-01-07T09:52:26.436Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:26.440Z SendDataConnector.js: got all data for this round
I/jxcore-log(11759): 
,I/jxcore-log(11759): oneRoundDownNow
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:26.451Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:26.452Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,D/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread(11759): close
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1668
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1667
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1667, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11759): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@42958e6, channel: 6, state: CONNECTED
D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@42958e6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6951e27, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35d7e8d4mSocket: android.net.LocalSocket@1dd6ea7d impl:android.net.LocalSocketImpl@9a21d72 fd:FileDescriptor[117]
,D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@1dd6ea7d impl:android.net.LocalSocketImpl@9a21d72 fd:FileDescriptor[117]
W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1668, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@42958e6, channel: 6, state: CLOSED
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@42958e6, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1667, name: Sender)
,E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1668, name: Receiver)
,I/jxcore-log(11759): 2016-01-07T09:52:26.483Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log(11759): 
,I/jxcore-log(11759): ---- round done--------
I/jxcore-log(11759): 
,W/bt-btif ( 5658): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log(11759): startWithNextDevice
I/jxcore-log(11759): 
,I/jxcore-log(11759): do fake peer & start
I/jxcore-log(11759): 
I/jxcore-log(11759): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:26.494Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log(11759): 
I/jxcore-log(11759): 2016-01-07T09:52:26.494Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:26.495Z SendDataConnector.js: do connect now
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): connect: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper(11759): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 1669)
,D/BluetoothUtils(11759): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5658): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11759): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 },
D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 3525): InactiveState{ what=139310 },
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerLost: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] removed
,D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] not available
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc0e44 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 21
,E/bt-btm  ( 5658): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5658): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 5658): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3170b04e
,D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 5658): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,E/BluetoothEventManager( 8802): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4038): Bluetooth Device Name: A5-1
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12922): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12922): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,W/bt-btif ( 5658): info:x10
,D/        ( 5658): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 5658): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 5658): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5658): check_cod: remote_cod = 0x5a020c
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
I/BluetoothBondStateMachine( 5658): Entering PendingCommandState State
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 11
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
,D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0001::false
D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0002::false
D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,D/btif_config_util( 5658): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 5658): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/HidService( 5658): getHidService(): returning com.android.bluetooth.hid.HidService@37ebee10
,D/SettingsProvider( 3525): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
,D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/HidService( 5658): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider( 3525): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
,D/SettingsProvider( 3525): selectionArgs: 1002
D/BluetoothTile( 3690):  handleUpdatestate:false name:null
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,D/SettingsProvider( 3525): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
I/BluetoothBondStateMachine( 5658): StableState(): Entering Off State
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G4-1 state is 10
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0002::false
D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/bt-btif ( 5658): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5658): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 5658): bta_dm_pm_ssr:2, lat:1200,
,E/BluetoothRemoteDevices( 5658): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onSocketConnected: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1669)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesWritten: 66 bytes successfully written (thread ID: 1670)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Outgoing connection initialized (*handshake* thread ID: 1670)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Exiting thread (thread ID: 1669)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Entering thread (ID: 1670)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesRead: Read 63 bytes successfully (thread ID: 1670)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Handshake succeeded with [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onHandshakeSucceeded: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnected: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 G4-1]
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Exiting thread (ID: 1670)
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper(11759): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11759): Entering thread (ID: 1671)
,D/io.jxcore.node.OutgoingSocketThread(11759): Server socket local port: 32988
,I/io.jxcore.node.OutgoingSocketThread(11759): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper(11759): onListeningForIncomingConnections: Outgoing connection is using port 32988 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log(11759): 2016-01-07T09:52:32.573Z SendDataConnector.js: CLIENT connected to 32988, error: null
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:32.577Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11759): 
,I/io.jxcore.node.OutgoingSocketThread(11759): Incoming data from address: /127.0.0.1, port: 32988
,D/io.jxcore.node.OutgoingSocketThread(11759): Setting local streams and starting stream copying threads...,
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread(11759): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread(11759): Exiting thread (ID: 1671)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1672, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1673, name: Receiver)
,I/jxcore-log(11759): 2016-01-07T09:52:32.610Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11759): 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:39224
,I/jxcore-log(11759): 2016-01-07T09:52:33.398Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:28872
,I/jxcore-log(11759): 2016-01-07T09:52:33.577Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:15716
,I/jxcore-log(11759): 2016-01-07T09:52:34.035Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:34.193Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:34.529Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:35.272Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:35.528Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:35.722Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:36.134Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:36.449Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:36.457Z SendDataConnector.js: got all data for this round
I/jxcore-log(11759): 
,I/jxcore-log(11759): oneRoundDownNow
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:36.465Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:36.468Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,D/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,I/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread(11759): close
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1673
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1672
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1672, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11759): closeBluetoothSocketAndStreams
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@372b75c3, channel: 7, state: CONNECTED
D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@372b75c3, channel: 7, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1334be40, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24ecb179mSocket: android.net.LocalSocket@13709ebe impl:android.net.LocalSocketImpl@1c45ab1f fd:FileDescriptor[117]
D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@13709ebe impl:android.net.LocalSocketImpl@1c45ab1f fd:FileDescriptor[117]
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1673, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@372b75c3, channel: 7, state: CLOSED
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@372b75c3, channel: 7, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1672, name: Sender)
E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1673, name: Receiver)
,I/jxcore-log(11759): 2016-01-07T09:52:36.493Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log(11759): 
,I/jxcore-log(11759): ---- round done--------
I/jxcore-log(11759): 
,I/jxcore-log(11759): startWithNextDevice
I/jxcore-log(11759): 
I/jxcore-log(11759): do fake peer & start
I/jxcore-log(11759): 
,I/jxcore-log(11759): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log(11759): 
I/jxcore-log(11759): 2016-01-07T09:52:36.498Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:36.498Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log(11759): 
I/jxcore-log(11759): 2016-01-07T09:52:36.499Z SendDataConnector.js: do connect now
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper(11759): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1674)
W/bt-btif ( 5658): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/BluetoothUtils(11759): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5658): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value 1
D/BluetoothSocket(11759): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
D/IOP_DB_BT( 5658): db_query_execute: result 1
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1004 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14),
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0,
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,W/bt-btif ( 5658): info:x10
,D/        ( 5658): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 5658): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 21
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1004 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc11c4 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 5658): process_service_search_attr_rsp
,E/bt-btm  ( 5658): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5658): btm_sec_disconnected - Clearing Pending flag,
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8802): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,D/BluetoothAdapterService( 5658): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3170b04e
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,I/BluetoothPbapService( 5658): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12922): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12922): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.CLASS_CHANGED
,E/bt-btif ( 5658): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
I/BluetoothBondStateMachine( 5658): Entering PendingCommandState State
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4038): Bluetooth Device Name: G4-1
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G3-1 state is 11
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0002::false
D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,D/btif_config_util( 5658): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 5658): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/HidService( 5658): getHidService(): returning com.android.bluetooth.hid.HidService@37ebee10
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 3525): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
,D/SettingsProvider( 3525): selectionArgs: 1002
,D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3525): ret = -1
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,D/HidService( 5658): Saved priority 58:3F:54:73:64:C0 = -1
,D/SettingsProvider( 3525): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
,D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3525): ret = -1
,D/SettingsProvider( 3525): name = bluetooth_headset_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
,D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,I/BluetoothBondStateMachine( 5658): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED G3-1 state is 10
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
,D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0001::false
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0002::false
V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,W/bt-btif ( 5658): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5658): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 5658): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5658): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onSocketConnected: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1674)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesWritten: 66 bytes successfully written (thread ID: 1675)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Outgoing connection initialized (*handshake* thread ID: 1675)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Exiting thread (thread ID: 1674)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Entering thread (ID: 1675)
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc11c4 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesRead: Read 63 bytes successfully (thread ID: 1675)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Handshake succeeded with [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onHandshakeSucceeded: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Exiting thread (ID: 1675),
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnected: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 G3-1]
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper(11759): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread(11759): Entering thread (ID: 1676)
,D/io.jxcore.node.OutgoingSocketThread(11759): Server socket local port: 60975
,I/io.jxcore.node.OutgoingSocketThread(11759): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper(11759): onListeningForIncomingConnections: Outgoing connection is using port 60975 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log(11759): 2016-01-07T09:52:43.133Z SendDataConnector.js: CLIENT connected to 60975, error: null
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:43.134Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log(11759): 
,I/io.jxcore.node.OutgoingSocketThread(11759): Incoming data from address: /127.0.0.1, port: 60975
,D/io.jxcore.node.OutgoingSocketThread(11759): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log(11759): 2016-01-07T09:52:43.148Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11759): 
,I/io.jxcore.node.OutgoingSocketThread(11759): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread(11759): Exiting thread (ID: 1676)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1678, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1677, name: Sender)
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65634
,I/jxcore-log(11759): 2016-01-07T09:52:43.906Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60400
,I/jxcore-log(11759): 2016-01-07T09:52:44.032Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:51490
,I/jxcore-log(11759): 2016-01-07T09:52:44.229Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:39610
,I/jxcore-log(11759): 2016-01-07T09:52:44.428Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:30700
,I/jxcore-log(11759): 2016-01-07T09:52:44.651Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:21790
,I/jxcore-log(11759): 2016-01-07T09:52:45.028Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10900,
,I/jxcore-log(11759): 2016-01-07T09:52:45.556Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1000
,I/jxcore-log(11759): 2016-01-07T09:52:45.816Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.027Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.583Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.587Z SendDataConnector.js: got all data for this round
I/jxcore-log(11759): 
,I/jxcore-log(11759): oneRoundDownNow
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.595Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.598Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,D/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
,I/io.jxcore.node.OutgoingSocketThread(11759): close
,D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1678
,D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1677
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1677, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11759): closeBluetoothSocketAndStreams
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@3cc77e6c, channel: 5, state: CONNECTED
,D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@3cc77e6c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cfdec35, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c13e8camSocket: android.net.LocalSocket@1ba3da3b impl:android.net.LocalSocketImpl@35e41558 fd:FileDescriptor[117]
,D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@1ba3da3b impl:android.net.LocalSocketImpl@35e41558 fd:FileDescriptor[117]
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1678, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@3cc77e6c, channel: 5, state: CLOSED
,D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@3cc77e6c, channel: 5, state: CLOSED
,D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1677, name: Sender)
E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1678, name: Receiver)
,I/jxcore-log(11759): 2016-01-07T09:52:46.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log(11759): 
,I/jxcore-log(11759): ---- round done--------
I/jxcore-log(11759): 
,I/jxcore-log(11759): startWithNextDevice
I/jxcore-log(11759): 
,I/jxcore-log(11759): do fake peer & start
I/jxcore-log(11759): 
,I/jxcore-log(11759): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.633Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.634Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:46.635Z SendDataConnector.js: do connect now
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper(11759): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): connect: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnecting: null 44:80:EB:7B:5A:05
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper(11759): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 1679)
,W/bt-btif ( 5658): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/BluetoothUtils(11759): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter(11759): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 5658): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket(11759): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[117]}
,E/Watchdog( 3525): !@Sync 19
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29,
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 6:2003,
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value 1,
,D/IOP_DB_BT( 5658): db_query_execute: result 1,
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc11c4 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 22
,E/bt-btm  ( 5658): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5658): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 8802): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,D/BluetoothAdapterService( 5658): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3170b04e
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,I/BluetoothPbapService( 5658): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12922): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12922): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4038): Bluetooth Device Name: G3-1
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,W/bt-btif ( 5658): info:x10
,D/        ( 5658): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 5658): aclStateChangeCallback: Device is NULL
,D/IOP_DB_BT( 5658): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 5658): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 5658): db_query_execute: result 1
,W/bt-btif ( 5658): info:x10
,D/        ( 5658): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 5658): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1544 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1384 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14),
,W/bt-sdp  ( 5658): process_service_search_attr_rsp
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5658): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5658): isSecureModeOn:false
I/BluetoothBondStateMachine( 5658): Entering PendingCommandState State
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Thali Test (Galaxy A5) state is 11
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002,
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0002::false
D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,D/btif_config_util( 5658): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
D/BluetoothAdapterProperties( 5658): Failed to remove device: 7C:F9:0E:51:18:22
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/HidService( 5658): getHidService(): returning com.android.bluetooth.hid.HidService@37ebee10
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 3525): name = bluetooth_input_device_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/HidService( 5658): Saved priority 7C:F9:0E:51:18:22 = -1
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,D/SettingsProvider( 3525): name = bluetooth_a2dp_sink_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/SettingsProvider( 3525): name = bluetooth_headset_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
I/BluetoothBondStateMachine( 5658): StableState(): Entering Off State
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED Thali Test (Galaxy A5) state is 10
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0002::false
,D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,W/bt-btif ( 5658): new conn_srvc id:26, app_id:255
W/bt-btif ( 5658): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 5658): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket(11759): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@aae16b1
,E/BluetoothRemoteDevices( 5658): setRfcommConnected true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Incoming connection initialized (thread ID: 1680)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Entering thread (ID: 1680)
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1544 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): onBytesRead: Read 81 bytes successfully (thread ID: 1680)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Got valid identity from [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): onBytesWritten: 66 bytes successfully written (thread ID: 1680)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): removeThreadFromList: Removing thread with ID 1680
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Handshake thread disposed (thread ID: 1680)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Exiting thread (ID: 1680)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], created successfully
,D/io.jxcore.node.ConnectionHelper(11759): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread(11759): Entering thread (ID: 1681)
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10540
,I/io.jxcore.node.IncomingSocketThread(11759): Local host address: localhost/127.0.0.1, port: 53402
,I/jxcore-log(11759): 2016-01-07T09:52:55.866Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log(11759): 
,D/io.jxcore.node.IncomingSocketThread(11759): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread(11759): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread(11759): Exiting thread (ID: 1681)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1682, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1683, name: Receiver)
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1544 rs_disc_pending=0
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 5658): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,I/BluetoothBondStateMachine( 5658): Entering PendingCommandState State
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED XT1072 state is 11
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage PAIRING_DEVICES
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0002::false
,D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,D/btif_config_util( 5658): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 5658): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
D/BluetoothAdapterProperties( 5658): Failed to remove device: 44:80:EB:7B:5A:05
,D/SecContentProvider( 3525): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 5658): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/HidService( 5658): getHidService(): returning com.android.bluetooth.hid.HidService@37ebee10
,D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 3525): name = bluetooth_input_device_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,D/HidService( 5658): Saved priority 44:80:EB:7B:5A:05 = -1
,D/BluetoothNotiBroadcastReceiver( 8802): onReceive
D/SettingsProvider( 3525): name = bluetooth_a2dp_sink_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/SettingsProvider( 3525): name = bluetooth_headset_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 1002
V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
I/BluetoothBondStateMachine( 5658): StableState(): Entering Off State
,D/[CarMode](12922): [AutoLaunchReceiver]-action: android.bluetooth.device.action.BOND_STATE_CHANGED
,D/[CarMode](12922): [AutoLaunchReceiver]-ACTION_BOND_STATE_CHANGED XT1072 state is 10
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.BOND_STATE_CHANGED State = -2147483648 Previous = -2147483648
,E/BluetoothHeadset(13015): BTStateChangeCB is registed
,E/BluetoothHeadset(13015): BluetoothHeadset service is binded
D/GMFPReceiver(13015): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver(13015): jangil::setProperties()
,D/GMFPReceiver(13015): jangil::printBTStatus()
,D/SettingsProvider( 3525): name = Wearable0001
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
D/GMFPReceiver(13015): ::::::::Wearable0001::false
,D/SettingsProvider( 3525): name = Wearable0002
D/SettingsProvider( 3525): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3525): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3525): selectionArgs: false
D/SettingsProvider( 3525): selectionArgs: 10121
D/SecContentProvider( 3525): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3525): ret = -1
,D/GMFPReceiver(13015): ::::::::Wearable0002::false
D/GMFPReceiver(13015): onServiceConnected() : 1
D/GMFPReceiver(13015): mBluetoothHeadset = true
,I/jxcore-log(11759): 2016-01-07T09:52:57.191Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:57.477Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:57.571Z SendDataTCPServer.js: TCP/IP server has received 3036 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:57.598Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log(11759): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: RESTARTING,
,D/WifiP2pService( 3525): InactiveState{ what=139268 }
,I/wpa_supplicant( 3825): P2P-FIND-STOPPED 
,D/WifiP2pService( 3525): InactiveState{ what=147493 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 3525): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1384 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 5658): new conn_srvc id:26, app_id:1
,W/bt-btif ( 5658): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 5658): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 5658): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onSocketConnected: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1679)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesWritten: 66 bytes successfully written (thread ID: 1684)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Outgoing connection initialized (*handshake* thread ID: 1684)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Exiting thread (thread ID: 1679)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Entering thread (ID: 1684)
,I/jxcore-log(11759): 2016-01-07T09:52:59.496Z SendDataTCPServer.js: TCP/IP server has received 5060 bytes of data
I/jxcore-log(11759): 
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 21
,I/jxcore-log(11759): 2016-01-07T09:52:59.819Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:59.873Z SendDataTCPServer.js: TCP/IP server has received 7084 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:59.884Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:59.896Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:52:59.981Z SendDataTCPServer.js: TCP/IP server has received 11132 bytes of data
I/jxcore-log(11759): 
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1384 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): onBytesRead: Read 65 bytes successfully (thread ID: 1684)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread(11759): Handshake succeeded with [44:80:EB:7B:5A:05 XT1072]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onHandshakeSucceeded: [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread(11759): Exiting thread (ID: 1684)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): onConnected: [44:80:EB:7B:5A:05 XT1072]
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 XT1072]
,D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
,I/io.jxcore.node.ConnectionHelper(11759): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 XT1072], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper(11759): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread(11759): Entering thread (ID: 1685)
,D/io.jxcore.node.OutgoingSocketThread(11759): Server socket local port: 47644
,I/io.jxcore.node.OutgoingSocketThread(11759): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper(11759): onListeningForIncomingConnections: Outgoing connection is using port 47644 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log(11759): 2016-01-07T09:53:00.409Z SendDataConnector.js: CLIENT connected to 47644, error: null
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:00.412Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log(11759): 
,I/io.jxcore.node.OutgoingSocketThread(11759): Incoming data from address: /127.0.0.1, port: 47644
,D/io.jxcore.node.OutgoingSocketThread(11759): Setting local streams and starting stream copying threads...,
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread(11759): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread(11759): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread(11759): Exiting thread (ID: 1685)
,I/jxcore-log(11759): 2016-01-07T09:53:00.442Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log(11759): 
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1687, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread(11759): Entering thread (ID: 1686, name: Sender)
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1544 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11759): 2016-01-07T09:53:01.149Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.153Z SendDataTCPServer.js: TCP/IP server has received 13156 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.210Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.218Z SendDataTCPServer.js: TCP/IP server has received 15180 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.264Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:65634
,I/jxcore-log(11759): 2016-01-07T09:53:01.303Z SendDataTCPServer.js: TCP/IP server has received 17396 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.312Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.350Z SendDataTCPServer.js: TCP/IP server has received 18408 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.395Z SendDataTCPServer.js: TCP/IP server has received 19420 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.437Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.490Z SendDataTCPServer.js: TCP/IP server has received 21444 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.531Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58420
,I/jxcore-log(11759): 2016-01-07T09:53:01.549Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.669Z SendDataTCPServer.js: TCP/IP server has received 23468 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.730Z SendDataTCPServer.js: TCP/IP server has received 26504 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.791Z SendDataTCPServer.js: TCP/IP server has received 27516 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.796Z SendDataTCPServer.js: TCP/IP server has received 28528 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.832Z SendDataTCPServer.js: TCP/IP server has received 30552 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.848Z SendDataTCPServer.js: TCP/IP server has received 31564 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.898Z SendDataTCPServer.js: TCP/IP server has received 32576 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:01.977Z SendDataTCPServer.js: TCP/IP server has received 33588 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.020Z SendDataTCPServer.js: TCP/IP server has received 34600 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.104Z SendDataTCPServer.js: TCP/IP server has received 35612 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.111Z SendDataTCPServer.js: TCP/IP server has received 36624 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.158Z SendDataTCPServer.js: TCP/IP server has received 38648 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48520
,I/jxcore-log(11759): 2016-01-07T09:53:02.199Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.611Z SendDataTCPServer.js: TCP/IP server has received 39660 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.616Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.649Z SendDataTCPServer.js: TCP/IP server has received 41684 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.687Z SendDataTCPServer.js: TCP/IP server has received 42696 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.738Z SendDataTCPServer.js: TCP/IP server has received 43708 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.933Z SendDataTCPServer.js: TCP/IP server has received 44720 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.942Z SendDataTCPServer.js: TCP/IP server has received 45732 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.970Z SendDataTCPServer.js: TCP/IP server has received 46744 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.977Z SendDataTCPServer.js: TCP/IP server has received 47756 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:02.985Z SendDataTCPServer.js: TCP/IP server has received 48768 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38620
,I/jxcore-log(11759): 2016-01-07T09:53:02.993Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log(11759): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): Start timer timeout, starting now...
,D/WifiP2pService( 3525): InactiveState{ what=139265 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139265 }
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/WifiStateMachine( 3525): callSECApi what=74
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 3525): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: STARTED,
,I/jxcore-log(11759): 2016-01-07T09:53:03.035Z SendDataTCPServer.js: TCP/IP server has received 49780 bytes of data
I/jxcore-log(11759): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log(11759): 2016-01-07T09:53:03.051Z SendDataTCPServer.js: TCP/IP server has received 51804 bytes of data
I/jxcore-log(11759): 
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 231, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11759): 2016-01-07T09:53:03.545Z SendDataTCPServer.js: TCP/IP server has received 52816 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:03.720Z SendDataTCPServer.js: TCP/IP server has received 53828 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28720
,I/jxcore-log(11759): 2016-01-07T09:53:03.880Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:03.895Z SendDataTCPServer.js: TCP/IP server has received 54840 bytes of data,
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:03.905Z SendDataTCPServer.js: TCP/IP server has received 55852 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.223Z SendDataTCPServer.js: TCP/IP server has received 58888 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.253Z SendDataTCPServer.js: TCP/IP server has received 59900 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.268Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18820
,I/jxcore-log(11759): 2016-01-07T09:53:04.426Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.508Z SendDataTCPServer.js: TCP/IP server has received 62936 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.580Z SendDataTCPServer.js: TCP/IP server has received 63948 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.589Z SendDataTCPServer.js: TCP/IP server has received 64960 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.782Z SendDataTCPServer.js: TCP/IP server has received 66984 bytes of data
I/jxcore-log(11759): 
,D/        ( 5658): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7930
,I/jxcore-log(11759): 2016-01-07T09:53:04.809Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.815Z SendDataTCPServer.js: TCP/IP server has received 67996 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.827Z SendDataTCPServer.js: TCP/IP server has received 70020 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.837Z SendDataTCPServer.js: TCP/IP server has received 71032 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.899Z SendDataTCPServer.js: TCP/IP server has received 72044 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.947Z SendDataTCPServer.js: TCP/IP server has received 74068 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.957Z SendDataTCPServer.js: TCP/IP server has received 75080 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.974Z SendDataTCPServer.js: TCP/IP server has received 76092 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.981Z SendDataTCPServer.js: TCP/IP server has received 77104 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:04.984Z SendDataTCPServer.js: TCP/IP server has received 78116 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:05.584Z SendDataTCPServer.js: TCP/IP server has received 79128 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:05.677Z SendDataTCPServer.js: TCP/IP server has received 80140 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:05.755Z SendDataTCPServer.js: TCP/IP server has received 81152 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:05.772Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:05.784Z SendDataTCPServer.js: TCP/IP server has received 83176 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.012Z SendDataTCPServer.js: TCP/IP server has received 84188 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.070Z SendDataTCPServer.js: TCP/IP server has received 85200 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.316Z SendDataTCPServer.js: TCP/IP server has received 86212 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.337Z SendDataTCPServer.js: TCP/IP server has received 87224 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.350Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.455Z SendDataTCPServer.js: TCP/IP server has received 88236 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.510Z SendDataTCPServer.js: TCP/IP server has received 89248 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:06.874Z SendDataTCPServer.js: TCP/IP server has received 90260 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): timeout now
I/jxcore-log(11759): 
,I/jxcore-log(11759): weAreDoneNow, resultArray.length: 3
I/jxcore-log(11759): 
,I/jxcore-log(11759): sendReportNow
I/jxcore-log(11759): 
,I/jxcore-log(11759): done, now sending data to server
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.262Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log(11759): 
I/jxcore-log(11759): 2016-01-07T09:53:07.262Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.263Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log(11759): 
,D/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread(11759): close
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1687
D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1686
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11759): closeBluetoothSocketAndStreams
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@14efc796, channel: 5, state: CONNECTED
D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@14efc796, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cebdf17, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21312f04mSocket: android.net.LocalSocket@3f5c6ced impl:android.net.LocalSocketImpl@fd8c722 fd:FileDescriptor[117]
D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@3f5c6ced impl:android.net.LocalSocketImpl@fd8c722 fd:FileDescriptor[117]
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@14efc796, channel: 5, state: CLOSED
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@14efc796, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1687, thread name: Receiver): bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper(11759): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1687, name: Receiver)
I/jxcore-log(11759): 2016-01-07T09:53:07.266Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log(11759): 
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1686, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1686, name: Sender)
,I/jxcore-log(11759): 2016-01-07T09:53:07.561Z SendDataTCPServer.js: TCP/IP server has received 91272 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.722Z SendDataTCPServer.js: TCP/IP server has received 92284 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.743Z SendDataTCPServer.js: TCP/IP server has received 94308 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.835Z SendDataTCPServer.js: TCP/IP server has received 95320 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.880Z SendDataTCPServer.js: TCP/IP server has received 96332 bytes of data
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:07.895Z SendDataTCPServer.js: TCP/IP server has received 98356 bytes of data
I/jxcore-log(11759): 
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1384 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,I/jxcore-log(11759): 2016-01-07T09:53:08.864Z SendDataTCPServer.js: TCP/IP server has received 99368 bytes of data
I/jxcore-log(11759): 
,W/bt-btif ( 5658): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,W/bt-btif ( 5658): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 21
,D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1544 rs_disc_pending=1
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1683, thread name: Receiver): bt socket closed, read return: -1
,W/bt-btif ( 5658): invalid rfc slot id: 5,
,E/io.jxcore.node.OutgoingSocketThread(11759): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1681,
,D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1683
,D/io.jxcore.node.OutgoingSocketThread(11759): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread(11759): doStop: Thread ID: 1682
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread(11759): Either failed to read from the output stream or write to the input stream (thread ID: 1682, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread(11759): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper(11759): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the local output stream...
,I/jxcore-log(11759): 2016-01-07T09:53:10.238Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log(11759): 
,D/io.jxcore.node.OutgoingSocketThread(11759): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread(11759): closeBluetoothSocketAndStreams
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@324555b3, channel: 6, state: CONNECTED
,D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@324555b3, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3143770, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@91feae9mSocket: android.net.LocalSocket@3560336e impl:android.net.LocalSocketImpl@3eb59a0f fd:FileDescriptor[115]
D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@3560336e impl:android.net.LocalSocketImpl@3eb59a0f fd:FileDescriptor[115]
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@324555b3, channel: 6, state: CLOSED
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@324555b3, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper(11759): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1682, name: Sender)
,D/io.jxcore.node.StreamCopyingThread(11759): Exiting thread (ID: 1683, name: Receiver)
,I/jxcore-log(11759): 2016-01-07T09:53:10.253Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log(11759): 
,W/bt-rfcomm( 5658): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 5658): RFCOMM_DisconnectInd LCID:0x4b
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND dc:4a:3e:0f:c2:f1 p2p_dev_addr=de:4a:3e:0f:89:ad pri_dev_type=3-0050F204-1 name='DIRECT-AD-HP DeskJet 3630 series' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/BatteryService( 3525): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/WifiDisplayController( 3525): Received list of peers.
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 3525): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 3525): InactiveState{ what=139283 }
D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,E/bt-btm  ( 5658): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5658): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8802): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,D/BluetoothAdapterService( 5658): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3170b04e
D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,I/BluetoothPbapService( 5658): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12922): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12922): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4038): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 G3-1] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper(11759): onPeerLost: [58:3F:54:73:64:C0 G3-1]
D/io.jxcore.node.ConnectionHelper(11759): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] removed
,D/io.jxcore.node.ConnectionHelper(11759): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] not available
,D/TimaService( 3525): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3525): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 3525): TIMA: checkEvent, operation: 50000 subject: 10000,
,W/bt-btm  ( 5658): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 5658): tBTM_SEC_DEV:0xb3cc1384 rs_disc_pending=2
,E/bt-btm  ( 5658): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 5658): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 5658): bta_dm_check_av:0
,W/bt-btif ( 5658): btif_dm_cback : unhandled event (14)
,D/KeyguardViewMediator( 3690): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 5658): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3170b04e
,D/BtConfig.SecureMode( 5658): isSecureModeOn:false
,D/SecContentProvider( 3525): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/BluetoothPbapService( 5658): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 3690): isGear1: device is not B1!
,V/BluetoothEventManager( 8802): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 8802): ACTION_ACL_DISCONNECTED
,I/BTConnectionReceiver( 4038): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,V/[CarModeFW](12922): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.device.action.ACL_DISCONNECTED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED
I/BluetoothClassifier( 4038): Bluetooth Device Name: XT1072
,D/[CarModeFW](12922): ConnectivityManager-handleMessage BLUETOOTH_ACL_DISCONNECTED onNotifyBluetoothDeviceDisconnected
,D/[CarModeFW](12922): ConnectivityManager-Paired Devices list is empty
E/[CarMode](12922): [BluetoothConnectivityListener]-onNotifyBluetoothProfileDisconnected: Unexpected error: Invalid device
,E/Watchdog( 3525): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3525): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3525): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3525): Skipping unknown process pid 13612
,D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 20
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/wpa_supplicant( 3825): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/WifiP2pService( 3525): InactiveState{ what=147477 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 3525): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/WifiDisplayController( 3525): Received list of peers.
,D/WifiDisplayController( 3525):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: A3-1, deviceAddress: 0a:ec:a9:50:75:42, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 3525):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 3525):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 3525): InactiveState{ what=139283 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 3525): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 230, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3525): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
,I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): restart: Restarting...
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState clear service request
V/HeadsetService( 5658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5658): Disconnected process message: 10
,D/WifiP2pService( 3525): InactiveState{ what=139301 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139301 }
D/WifiP2pService( 3525): P2pEnabledState add service request
,D/WifiP2pManager(11759): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service request added successfully
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3525): [PWL] Off : 525s ago
,D/WifiP2pService( 3525): InactiveState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 3525): P2pEnabledState discover services
,D/WifiService( 3525): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/WifiStateMachine( 3525): callSECApi what=74
,D/WifiStateMachine( 3525): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiNative-HAL( 3525): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 3825): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service discovery started successfully
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/WifiP2pService( 3525): InactiveState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 3525): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper(11759): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper(11759): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/jxcore-log(11759): teardown
I/jxcore-log(11759): 
,I/jxcore-log(11759): testSendData stopped
I/jxcore-log(11759): 
,I/io.jxcore.node.ConnectionHelper(11759): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): shutdown
D/BluetoothSocket(11759): close() in, this: android.bluetooth.BluetoothSocket@3edd5a9c, channel: 6, state: LISTENING
D/BluetoothSocket(11759): close() this: android.bluetooth.BluetoothSocket@3edd5a9c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2eac960e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26834ca5mSocket: android.net.LocalSocket@13e0187a impl:android.net.LocalSocketImpl@263bc82b fd:FileDescriptor[116]
,D/BluetoothSocket(11759): Closing mSocket: android.net.LocalSocket@13e0187a impl:android.net.LocalSocketImpl@263bc82b fd:FileDescriptor[116]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread(11759): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector(11759): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager(11759): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer(11759): stop: Stopping services
,D/WifiP2pService( 3525): InactiveState{ what=139298 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 3525): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): stop: Stopping P2P device discovery...
,D/WifiP2pService( 3525): InactiveState{ what=139268 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): setState: NOT_INITIALIZED
,I/wpa_supplicant( 3825): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager(11759): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11759): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager(11759): setState: NOT_STARTED
,D/WifiP2pService( 3525): InactiveState{ what=147493 }
,D/WifiP2pService( 3525): P2pEnabledState{ what=147493 }
,I/jxcore-log(11759): StopBroadcasting went ok
I/jxcore-log(11759): 
,D/WifiP2pService( 3525): discovery change broadcast false
,D/WifiP2pService( 3525): InactiveState{ what=139307 }
,I/jxcore-log(11759): ****TEST TOOK:  ms ****
I/jxcore-log(11759): 
,D/WifiP2pService( 3525): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 3525): P2pEnabledState clear service request
,D/WifiP2pService( 3525): remove channel information from framework
,I/jxcore-log(11759): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11759): 
,I/jxcore-log(11759): 2016-01-07T09:53:28.038Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log(11759): 
I/io.jxcore.node.ConnectionHelper(11759): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser(11759): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper(11759): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer(11759): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher(11759): Service requests cleared successfully
I/chromium(11759): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/AndroidRuntime(13636): 
D/AndroidRuntime(13636): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(13636): CheckJNI is OFF
,D/AndroidRuntime(13636): readGMSProperty: start
D/AndroidRuntime(13636): readGMSProperty: already setted!!
,D/AndroidRuntime(13636): readGMSProperty: end
D/AndroidRuntime(13636): addProductProperty: start
,E/AffinityControl(13636): AffinityControl: registerfunction enter
,D/AndroidRuntime(13636): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3525): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3525): START PACKAGE DELETE: observer{763936448}
D/PackageManager( 3525): pkg{<packageName>}
D/PackageManager( 3525): user{0}
D/PackageManager( 3525): caller{2000}
D/PackageManager( 3525): flags{3}
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3525): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3525): !@killApplicatoin: 10540, uninstall pkg
I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10540 user=-1: uninstall pkg
I/ActivityManager( 3525): Killing 11759:com.test.thalitest/u0a540 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3525):   Force finishing activity ActivityRecord{3d13bc0b u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3525): mDVFSHelper.acquire()
,W/PackageSettings( 3525): Skipping PackageSetting{30fe6c67 com.example.hello/10529} due to missing metadata
,I/WindowState( 3525): WIN DEATH: Window{37fd4ca9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService( 3525): Client connection lost with reason: 4
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10540 user=0: pkg removed
,I/ActivityManager( 3525):   Force finishing activity ActivityRecord{3d13bc0b u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3525): Duplicate finish request for ActivityRecord{3d13bc0b u0 com.test.thalitest/.MainActivity t26 f}
,I/DBG_DM  ( 6268): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 9001): Explicit concurrent mark sweep GC freed 30100(1678KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.148ms total 41.881ms
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/art     ( 4038): Explicit concurrent mark sweep GC freed 51296(2MB) AllocSpace objects, 5(80KB) LOS objects, 21% free, 28MB/36MB, paused 1.314ms total 47.636ms
,I/InputReader( 3525): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4633): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/LWLocationManager(13060): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(13060): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6268): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
E/SamsungIME( 4498): mOCRHelper is null
I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/Zygote  (13654): MountEmulatedStorage()
E/Zygote  (13654): v2
I/libpersona(13654): KNOX_SDCARD checking this for 10063
I/libpersona(13654): KNOX_SDCARD not a persona
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/SELinux (13654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 6268): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/ActivityManager( 3525): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13654 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (13654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 6886): Explicit concurrent mark sweep GC freed 28022(1583KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 2.119ms total 144.685ms
,W/ResourceType( 5362): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5362): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3525): uri = 14 selection = getSealedState
D/SecContentProvider2( 3525): mCursor = null
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ApplicationPolicy( 3525): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/TimaKeyStoreProvider(13654): TimaSignature is unavailable
,D/ActivityThread(13654): Added TimaKeyStore provider
,I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
,I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/EnterpriseDeviceManagerService( 3525): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3525): Admin package name: com.google.android.gms
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/DBG_DM  ( 6268): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/ResourcesManager(13654): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6268): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6268): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6268): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/DBG_DM  ( 6268): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
,I/DBG_DM  ( 6268): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=16 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/VRSetupWizardStub/PackageIntentReceiver(13654): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13654): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13654): packagename:com.test.thalitest
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
V/ActivityThread( 6268): updateVisibility : ActivityRecord{a75539f token=android.os.BinderProxy@361efb40 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/KLMS-2.4.521: (12019): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 07 10:53:29 GMT+01:00 2016
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 57813(4MB) AllocSpace objects, 40(640KB) LOS objects, 24% free, 49MB/65MB, paused 9.139ms total 226.814ms
,I/art     ( 3525): WaitForGcToComplete blocked for 99.018ms for cause Explicit
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/KLMS-2.4.521: (12019): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3525): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3525): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/KLMS-2.4.521: (12019): KLMSIntentService(): onCreate()
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (13673): MountEmulatedStorage()
E/Zygote  (13673): v2
I/libpersona(13673): KNOX_SDCARD checking this for 10106
I/libpersona(13673): KNOX_SDCARD not a persona
,I/SELinux (13673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux (13673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13673 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (13673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/InputMethodManagerService( 3525): Got RemoteException sending setActive(false) notification to pid 11759 uid 10540
,I/Timeline( 6268): Timeline: Activity_idle id: android.os.BinderProxy@361efb40 time:624257
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/KLMS-2.4.521: (12019): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/RCPManager(12157):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3525):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3525): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (13690): MountEmulatedStorage()
E/Zygote  (13690): v2
I/libpersona(13690): KNOX_SDCARD checking this for 10160
I/libpersona(13690): KNOX_SDCARD not a persona
,I/SELinux (13690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13690 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,E/SELinux (13690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 3525): mDVFSHelper.release()
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{36ec9f70 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:624292
,I/KLMS-2.4.521: (12019): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(13673): TimaSignature is unavailable
,D/ActivityThread(13673): Added TimaKeyStore provider
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/TimaKeyStoreProvider(13690): TimaSignature is unavailable
,D/ActivityThread(13690): Added TimaKeyStore provider
,E/Zygote  (13706): MountEmulatedStorage()
E/Zygote  (13706): v2
I/libpersona(13706): KNOX_SDCARD checking this for 10050
I/libpersona(13706): KNOX_SDCARD not a persona
,I/SELinux (13706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13706 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/KLMS-2.4.521: (12019): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12019): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (12019): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12019): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/TimaKeyStoreProvider(13706): TimaSignature is unavailable
,D/RegisteredServicesCache( 3964): empty dynamic service
D/ActivityThread(13706): Added TimaKeyStore provider
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 8216(406KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.954ms total 156.717ms
,I/art     ( 3525): WaitForGcToComplete blocked for 365.749ms for cause Explicit
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(13060): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(13673): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(13690): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/ResourcesManager(13690): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13690): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(13706): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(13706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourceType( 3525): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/ResourcesManager(13706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13706): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(13706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  (13722): MountEmulatedStorage()
E/Zygote  (13722): v2
I/libpersona(13722): KNOX_SDCARD checking this for 10101
I/libpersona(13722): KNOX_SDCARD not a persona
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ResourcesManager(13706): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13706): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13706): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(13706): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SELinux (13722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13722 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (13722): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/elm:14491(13673): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/elm:14491(13673): ELMEngine.ELMEngine( context ).
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/elm:14491(13673): MDMBridge.setEnterpriseBridge()
,W/ResourcesManager(13060): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13060): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13060): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13060): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/elm:14491(13673): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/elm:14491(13673): ElmAgentService : onCreate()
,D/elm:14491(13673): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(13673): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13673): MDMBridge.getInstance()
D/elm:14491(13673): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/elm:14491(13673): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(13722): TimaSignature is unavailable
,D/ActivityThread(13722): Added TimaKeyStore provider
,E/Zygote  (13740): MountEmulatedStorage()
E/Zygote  (13740): v2
I/libpersona(13740): KNOX_SDCARD checking this for 10019
I/libpersona(13740): KNOX_SDCARD not a persona
,I/SELinux (13740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12019): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/SELinux (13740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13740 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (13740): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(13673): ElmAgentService : onDestroy().
,I/KLMS-2.4.521: (12019): KLMSIntentService(): onDestroy()
I/ActivityManager( 3525): Killing 11965:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##31
,V/Common  (13690): getScreenSize 1440 2560
,I/ActivityManager( 3525): Killing 11984:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##31
,D/ResourcesManager(13722): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(13740): TimaSignature is unavailable
,D/ActivityThread(13740): Added TimaKeyStore provider
,I/JAM     (13690): Load The ApaService JNI
,I/JAM     (13690): version: ProfessionalAudio_v1.0.b5
I/JAM     (13690): Try v1.0.b3 ...
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  (13758): MountEmulatedStorage()
I/libpersona(13758): KNOX_SDCARD checking this for 10160
E/Zygote  (13758): v2
I/libpersona(13758): KNOX_SDCARD not a persona
I/SELinux (13758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Spen    (13690): SpenSdk version level = 55
D/Spen    (13690): SpenSdk jar version = 3.0.243
,I/ActivityManager( 3525): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=13758 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/Spen    (13690): SpenSdk apk version = 3.0.235
D/Spen    (13690): Server UPDATE Check
,D/ResourcesManager(13060): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
W/linker  (13690): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 6415(405KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 2.222ms total 201.792ms
,D/SPenError(13690): JNI_OnLoad
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/JNI_Bitmap(13690): Init .. Done
,D/SPenSpiDecoder(13690): JNI_OnLoad .. Done
D/SPenError(13690): JNI_OnLoad Success
,D/PluginManager(13690): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(13690): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(13690): JNI_OnLoad
,D/Init_SPenSdk_Jni(13690): AndroidSDK: 21
D/Init_SPenSdk_Jni(13690): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(13690): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(13690): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(13690): JNI_OnLoad .. Done
D/Model_ObjectText_Jni(13690): JNI_OnLoad .. Done
,D/Model_ObjectContainer_Jni(13690): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(13690): JNI_OnLoad .. Done
D/Model_NoteDoc_Jni(13690): check build type eng[0]
,D/Model_NoteDoc_Jni(13690): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(13690): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(13690): JNI_OnLoad .. Done
D/Model   (13690): OnLoad class Done
,D/ResourcesManager(13740): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/spe_log (13690): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(13690): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(13690): Canvas JNI_OnLoad enter!!
,D/SPen_Library(13690): Canvas JNI_OnLoad Success
D/SPen_Library(13690): TextView JNI_OnLoad enter!!
,D/SPen_Library(13690): TextView JNI_OnLoad Success
D/SPen_Library(13690): Text JNI_OnLoad enter!!
D/SPen_Library(13690): Text JNI_OnLoad Success
D/SPen_Library(13690): FontManager JNI_OnLoad enter!!
D/SPen_Library(13690): FontManager JNI_OnLoad Success
D/SPen_Library(13690): CapturePage JNI_OnLoad enter!!
D/SPen_Library(13690): CapturePage JNI_OnLoad Success
D/SPen_Library(13690): Multi JNI_OnLoad enter!!
,D/SPen_Library(13690): Multi JNI_OnLoad Success
D/SPen_Library(13690): Draw Engine JNI_OnLoad Success
,D/SPen_Library(13690): Brush JNI_OnLoad enter!!
,D/SPen_Library(13690): Brush JNI_OnLoad Success
,D/SPen_Library(13690): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(13690): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(13690): InkPen JNI_OnLoad enter!!
D/SPen_Library(13690): InkPen JNI_OnLoad Success
,D/SPen_Library(13690): Marker JNI_OnLoad enter!!
,D/SPen_Library(13690): Marker JNI_OnLoad Success
D/TimaKeyStoreProvider(13758): TimaSignature is unavailable
,D/SPen_Library(13690): Pencil JNI_OnLoad enter!!
D/SPen_Library(13690): Pencil JNI_OnLoad Success
,D/SPen_Library(13690): NativePen JNI_OnLoad enter!!
D/ActivityThread(13758): Added TimaKeyStore provider
D/SPen_Library(13690): NativePen JNI_OnLoad Success
,D/SPen_Library(13690): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(13690): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(13690): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(13690): MontblancCalligraphyPen JNI_OnLoad Success
,D/PackageManager( 3525): findPreferredActivity: No PreferredActivities set
D/SPen_Library(13690): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(13690): MagicPen JNI_OnLoad Success
,D/SPen_Library(13690): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(13690): ObliquePen JNI_OnLoad Success
,D/SPen_Library(13690): FountainPen JNI_OnLoad enter!!
D/SPen_Library(13690): FountainPen JNI_OnLoad Success
D/Spen    (13690): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(13690): SPenSdk_init2
D/Init_SPenSdk(13690): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(13690): Total S Pen SDK Directory Size = 0
D/Spen    (13690): initialize complete
,W/linker  (13690): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(13060): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/ResourcesManager( 3525): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DocsApplication(13722): Installing DEX configuration.
,D/com.sec.android.service.health.upgrade.UninstallReceiver(13740): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(13740): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(13740): onReceive() : package name is not s health. Return !!!
,D/PackageManager( 3525): delete codoeFile: 
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/DexInstaller(13722): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/AASAUninstall( 3525):  com.test.thalitest not target!
I/PackageInfoHelper(13722): Provided clientMode=RELEASE, packageInfo=PackageInfo{aacbe77 com.google.android.apps.docs}
,D/PackageManager( 3525): result of delete: 1{763936448}
,D/TAG     (13722): onCreate()
,D/LocationWidgetApplication(13060): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(13758): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ResourcesManager( 3525): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CrossAppStateProvider(13722): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,W/ResourcesManager(13758): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13758): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13758): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/AndroidRuntime(13636): Shutting down VM
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/ResourcesManager( 3525): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/Zygote  (13777): MountEmulatedStorage()
E/Zygote  (13777): v2
I/libpersona(13777): KNOX_SDCARD checking this for 10183
I/libpersona(13777): KNOX_SDCARD not a persona
,I/SELinux (13777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=13777 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (13777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 12041:com.sec.android.soagent/u0a38 (adj 15): bgCount ##31
,I/ActivityManager( 3525): Killing 12003:com.sec.android.fotaclient/u0a12 (adj 15): bgCount ##32
D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/SNoteProvider(13758): onCreate enableSnoteSync = true
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider(13777): TimaSignature is unavailable
,D/ActivityThread(13777): Added TimaKeyStore provider
,E/Zygote  (13793): MountEmulatedStorage()
E/Zygote  (13793): v2
I/libpersona(13793): KNOX_SDCARD checking this for 1000
I/libpersona(13793): KNOX_SDCARD not a persona
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/SELinux (13793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/SELinux (13793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/SELinux (13793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=13793 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(13060): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/ActivityManager( 3525): Killing 12068:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Books/Books.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 745us total 15.952ms
,D/SNoteProvider(13758): ===query=== 
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TimaKeyStoreProvider(13793): TimaSignature is unavailable
,D/ActivityThread(13793): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 384us total 12.776ms
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 486us total 13.707ms
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,V/Common  (13758): getScreenSize 1440 2560
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(13777): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(13793): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/NearbySource(13706): Nearby Source Create!
D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/NearbyContext(13706): Nearby Context Create!
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/PCWCLIENTTRACE_LOG(13793): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(13793): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(13793): new DMDBOpenHelper instance
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,I/PCWCLIENTTRACE_PushUtil(13793): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(13793): sales region : global
I/PCWCLIENTTRACE_PushUtil(13793): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(13793): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/SQLiteLog(13777): (284) automatic index on shooting_modes(title_id)
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
E/Zygote  (13810): MountEmulatedStorage()
I/libpersona(13810): KNOX_SDCARD checking this for 10035
E/Zygote  (13810): v2
I/libpersona(13810): KNOX_SDCARD not a persona
,I/SELinux (13810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,I/SELinux (13810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (13810): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/ActivityManager( 3525): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=13810 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11203:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/UsbSettingsManager( 3525): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3525): onPackageRemoved : com.test.thalitest
,D/RCPManagerService( 3525): PackageReceiver onReceive()
I/HarmonyEASService( 3525): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/ContextImpl(13706): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(13706): Samsung link source created
,D/KnoxMUMContainerPolicy( 3525): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3525): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3525): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): uID is 10540
,V/EnterpriseBillingPolicy( 3525): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - enter
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - end - null
,D/TimaKeyStoreProvider(13810): TimaSignature is unavailable
,D/ActivityThread(13810): Added TimaKeyStore provider
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,D/TaskPersister( 3525): removeObsoleteFile: deleting file=26_task.xml
,D/TaskPersister( 3525): removeObsoleteFile: deleting file=24_task.xml
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/StatusBar( 3690): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,D/ResourcesManager(13060): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,E/Zygote  (13829): MountEmulatedStorage()
E/Zygote  (13829): v2
I/libpersona(13829): KNOX_SDCARD checking this for 10190
I/libpersona(13829): KNOX_SDCARD not a persona
,I/SELinux (13829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13829): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=13829 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/SNoteProvider(13758): ===query=== 
,I/FeatureConfig(13810): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 3525): Killing 12136:com.samsung.android.scloud.backup/u0a67 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(13829): TimaSignature is unavailable
,D/ActivityThread(13829): Added TimaKeyStore provider
D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(13810): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ContactProvider(13706): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(13810): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(13829): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/ResourcesManager(13810): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(13060): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(13810): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(13810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(13060): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/SharedPreferencesImpl(13706): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/TapandpayWidget:TanpandpayAppWidgetProvider(13829): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13829): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(13829): Clear T&P info.
D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(13810): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/TapandpayWidget:TanpandpayAppWidgetProvider(13829): Widget is not attached.
,W/ResourcesManager(13810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (13849): MountEmulatedStorage()
E/Zygote  (13849): v2
I/libpersona(13849): KNOX_SDCARD checking this for 10036
I/libpersona(13849): KNOX_SDCARD not a persona
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(13810): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SELinux (13849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3525): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=13849 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/ResourcesManager(13810): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux (13849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/ResourcesManager(13810): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3525): Killing 12172:com.android.chrome/u0a90 (adj 13): bgCount ##31
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3525): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3525): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3525): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3525): displayNotification : [0ah,00h,01h]
E/SELinux (13849): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(13810): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/UsbHostManager( 3525): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3525): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/MtpClient(13706): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(13706): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/ResourcesManager(13810): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(13810): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (13868): MountEmulatedStorage()
E/Zygote  (13868): v2
I/libpersona(13868): KNOX_SDCARD checking this for 10052
I/libpersona(13868): KNOX_SDCARD not a persona
,I/SELinux (13868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(13810): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
E/SELinux (13868): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=13868 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(13849): TimaSignature is unavailable
,D/ActivityThread(13849): Added TimaKeyStore provider
,D/ResourcesManager(13810): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(13810): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/ActivityManager( 3525): Killing 12189:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 13): bgCount ##31
,D/ResourcesManager(13849): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/TimaKeyStoreProvider(13868): TimaSignature is unavailable
,D/ActivityThread(13868): Added TimaKeyStore provider
W/ResourcesManager(13810): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/ActivityManager( 3525): Killing 12206:com.google.android.apps.magazines/u0a136 (adj 15): bgCount ##31
,D/ResourcesManager(13810): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
I/EventHub( 3525): Removing device '/dev/input/event10' due to inotify event
,W/ResourcesManager(13810): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(13810): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog(13722): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13722): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(13722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13722): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(13722): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteDatabase(13722): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteDatabase(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13722): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteDatabase(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13722): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteDatabase(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteDatabase(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13722): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteDatabase(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13722): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteDatabase(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13722): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteDatabase(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteDatabase(13722): 	at buL.a(Scopes.java:65)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteDatabase(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteDatabase(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteDatabase(13722): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteDatabase(13722): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteDatabase(13722): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteDatabase(13722): 	at brQ.a(GellyInjector.ja,va:119)
E/SQLiteDatabase(13722): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteDatabase(13722): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteDatabase(13722): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase(13722): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13722): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13722): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13722): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(13722): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(13722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(13722): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(13722): 	at QF.provideClientFlag(ClientFlagsModule.java:71)
E/SQLiteOpenHelper(13722): 	at QH.a(GellyInjectorStore.java:215)
E/SQLiteOpenHelper(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13722): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at tQ.a(GellyInjectorStore.java:2039)
E/SQLiteOpenHelper(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13722): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at pG.a(GellyInjectorStore.java:478)
E/SQLiteOpenHelper(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at qD.a(GellyInjectorStore.java:118)
E/SQLiteOpenHelper(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13722): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at aEV.a(GellyInjectorStore.java:130)
E/SQLiteOpenHelper(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13722): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at aGH.a(GellyInjectorStore.java:227)
E/SQLiteOpenHelper(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13722): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at aGH.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at aGH.a(GellyInjectorStore.java:369)
E/SQLiteOpenHelper(13722): 	at bsj.a(ProvidesMethodProvider.java:38)
E/SQLiteOpenHelper(13722): 	at buL.a(Scopes.java:65)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at agN.a(GellyInjectorStore.java:799)
E/SQLiteOpenHelper(13722): 	at brD.a(ConstructorProvider.java:30)
E/SQLiteOpenHelper(13722): 	at bsk.a(RuntimeProvider.java:161)
E/SQLiteOpenHelper(13722): 	at pG.a(GellyInjectorStore.java:146)
E/SQLiteOpenHelper(13722): 	at pG.a(GellyInjectorStore.java:392)
E/SQLiteOpenHelper(13722): 	at bsh.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper(13722): 	at brQ.a(GellyInjector.java:119)
E/SQLiteOpenHelper(13722): 	at ajB.a(ScopedInjector.java:216)
E/SQLiteOpenHelper(13722): 	at com.google.android.apps.docs.DocsApplication.a(DocsApplication.java:235)
E/SQLiteOpenHelper(13722): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper(13722): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(13722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(13722): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(13722): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(13722): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(13722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(13722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper(13722): Opened ClientFlag.db in read-only mode
W/GalaxyFinderApplication(13810): system/finder_cp/cpdata.xml file not found
D/PackageBroadcastService( 6886): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6886): Clearing selected account for com.test.thalitest
I/EventHub( 3525): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog(13722): (28) failed to open "/data/data/com.google.android.apps.docs/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(13722): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase(13722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(13722): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase(13722): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/SQLiteDatabase(13722): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/SQLiteDatabase(13722): 	at bjx.a(Suppliers.java:125)
E/SQLiteDatabase(13722): 	at aFp.run(AbstractDatabaseInstance.java:471)
E/AndroidRuntime(13722): FATAL EXCEPTION: Open database in background
E/AndroidRuntime(13722): Process: com.google.android.apps.docs, PID: 13722
E/AndroidRuntime(13722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(13722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(13722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(13722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(13722): 	at aFu.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime(13722): 	at aFo.a(AbstractDatabaseInstance.java:457)
E/AndroidRuntime(13722): 	at aFo.a(AbstractDatabaseInstance.java:453)
E/AndroidRuntime(13722): 	at bjx.a(Suppliers.java:125)
E/AndroidRuntime(13722): 	at aFp.run(AbstractDatabaseInstance.java:471)
I/EventHub( 3525): Removing device '/dev/input/event8' due to inotify event
D/SSRM:n  ( 3525): SIOP:: AP = 220, PST = 217, CUR = 22
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,I/EventHub( 3525): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(13868): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(13868): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(13868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13868): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13868): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(13868): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SQLiteLog(13722): (28) failed to open "/data/data/com.google.android.apps.docs/databases/ClientFlag.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(13722): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase(13722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(13722): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(13722): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase(13722): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteDatabase(13722): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteDatabase(13722): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(13722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13722): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(13722): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(13722): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(13722): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(13722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(13722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(13722): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper(13722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(13722): 	at android.database.sql,ite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(13722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(13722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(13722): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(13722): 	at Qv.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper(13722): 	at com.google.android.apps.docs.DocsApplication.i(DocsApplication.java:349)
E/SQLiteOpenHelper(13722): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:229)
E/SQLiteOpenHelper(13722): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(13722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(13722): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(13722): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(13722): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(13722): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(13722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(13722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteLog(13849): (28) failed to open "/data/data/com.sec.android.app.shealth/databases/base.db" with flag (131138) and mode_t (0) due to error (30)
W/SQLiteOpenHelper(13722): Opened ClientFlag.db in read-only mode
,I/EventHub( 3525): Removing device '/dev/input/event11' due to inotify event
,E/SQLiteDatabase(13849): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13849): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(13849): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(13849): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13849): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13849): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:123)
E/SQLiteDatabase(13849): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:85)
E/SQLiteDatabase(13849): 	at com.sec.android.app.shealth.framework.repository.RepositoryInitializationTask.doInBackground(RepositoryInitializationTask.java:30)
E/SQLiteDatabase(13849): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase(13849): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase(13849): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase(13849): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase(13849): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase(13849): 	at java.lang.Thread.run(Thread.java:818)
,D/ChimeraCfgMgr( 6886): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6886): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 6886): (10) POSIX Error : 9 SQLite Error : 3850
I/LocationSettingsChecker( 6886): Removing dialog suppression flag for package com.test.thalitest
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/SQLiteLog( 6886): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 6886): disk I/O error (code 3850)
E/DriveAsyncService( 6886): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6886): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6886): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6886): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6886): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6886): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6886): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6886): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6886): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6886): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6886): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6886): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6886): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6886): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
,I/EventHub( 3525): Removing device '/dev/input/event12' due to inotify event
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3525): Removing device '/dev/input/event13' due to inotify event
,E/Zygote  (13897): MountEmulatedStorage()
E/Zygote  (13897): v2
I/libpersona(13897): KNOX_SDCARD checking this for 1000
I/libpersona(13897): KNOX_SDCARD not a persona
,I/SELinux (13897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (13897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (13897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=13897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 11355:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##31
,D/ContactProvider(13706): getAllContactInfoList End
,I/Process (13722): Sending signal. PID: 13722 SIG: 9
,D/TimaKeyStoreProvider(13897): TimaSignature is unavailable
I/syncContacts(13706): thread: 1798, sync time = 652
D/ActivityThread(13897): Added TimaKeyStore provider
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): checkState() : APP TYPE = Full
,D/Mms/MmsApp(13868): [start]    onCreate() consume time = 0.0
W/BroadcastQueue( 3525): Skipping deliver [background] BroadcastRecord{c0ade88 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{1eacdd6e 13722 com.google.android.apps.docs/10101/u0 remote:e6cfce9}: process crashing
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)(13849): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/ChimeraCfgMgr( 6886): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6886): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 6886): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/ArtClassLoader(13868): init before art
E/SQLiteDatabase( 6886): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6886): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6886): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6886): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6886): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6886): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6886): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 6886): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQL,iteOpenHelper( 6886): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6886): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6886): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6886): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6886): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6886): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6886): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 6886): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6886): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 6886): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6886): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 6886): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6886): Process: com.google.android.gms, PID: 6886
E/AndroidRuntime( 6886): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6886): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6886): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6886): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6886): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6886): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6886): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6886): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6886): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6886): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Mms/ArtClassLoader(13868): init [DONE] art
E/SQLiteLog( 6886): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6886): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6886): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 6886): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 6886): Sending signal. PID: 6886 SIG: 9
,E/JavaBinder( 3525): !!! FAILED BINDER TRANSACTION !!!
E/lowmemorykiller( 2827): Error writing /proc/13722/oom_score_adj; errno=22
,E/JavaBinder( 3525): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 3525): Scheduling restart of crashed service com.google.android.apps.docs/.sync.syncadapter.ContentSyncService in 1000ms
,D/ResourcesManager(13897): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk

```
