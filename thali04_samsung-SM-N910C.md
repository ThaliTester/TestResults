#### Test 5797209499148df_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3514): !@Sync 7
V/AlarmManager( 3514): waitForAlarm result :4
,--------- beginning of main
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
I/EventLogService( 6778): Aggregate from 1454414847149 (log), 1454414847149 (data)
D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/AndroidRuntime(11957): 
D/AndroidRuntime(11957): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11957): CheckJNI is OFF
D/AndroidRuntime(11957): readGMSProperty: start
D/AndroidRuntime(11957): readGMSProperty: already setted!!
D/AndroidRuntime(11957): readGMSProperty: end
D/AndroidRuntime(11957): addProductProperty: start
E/AffinityControl(11957): AffinityControl: registerfunction enter
D/AndroidRuntime(11957): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3514): inState():  stateMachine is null !!
I/PersonaManagerService( 3514): PersonaId don't exist
I/ActivityManager( 3514): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3514): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3514): mDVFSHelper.acquire()
D/FocusedStackFrame( 3514): Set to : 0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/Zygote  (11974): MountEmulatedStorage()
E/Zygote  (11974): v2
I/libpersona(11974): KNOX_SDCARD checking this for 10615
I/libpersona(11974): KNOX_SDCARD not a persona
I/SELinux (11974): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3514): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11974 uid=10615 gids={50615, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11974): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11974): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11957): Shutting down VM
D/PointerIcon( 3514): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3514): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3514): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3514): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11974): TimaSignature is unavailable
D/ActivityThread(11974): Added TimaKeyStore provider
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3514): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3514): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager( 3514): Display changed displayId=0
D/ResourcesManager(11974): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2848): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2848): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3999): updateVisibility : ActivityRecord{3125eb11 token=android.os.BinderProxy@251e698 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3999): onTrimMemory. Level: 20
I/WebViewFactory(11974): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11974): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11974): Loading: webviewchromium
I/LibraryLoader(11974): Time to load native libraries: 4 ms (timestamps 3878-3882)
I/LibraryLoader(11974): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11974): Binding Chromium to main looper Looper (main, tid 1) {de8f8c9}
,I/LibraryLoader(11974): Expected native library version number "",actual native library version number ""
I/chromium(11974): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11974): Initializing chromium process, renderers=0
,W/art     (11974): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11974): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11974): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11974): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11974): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11974): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11974): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11974): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11974): CordovaWebView is running on device made by: samsung
,W/art     (11974): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11974): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11974): performCreate Call secproduct feature valuefalse
D/Activity(11974): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11974): Render dirty regions requested: true
,D/ActivityManager( 3514): post active user change for 0
D/KnoxTimeoutHandler( 3514): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3514): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2848): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3514): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3514): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3514): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3514): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3514): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3514): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11974): Initialized EGL, version 1.4
,I/OpenGLRenderer(11974): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279811312 
,D/OpenGLRenderer(11974): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11974): Enabling debug mode 0
,D/mali_winsys(11974): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11974): updateVisibility : ActivityRecord{da4a639 token=android.os.BinderProxy@3d8f7264 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3514): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3514): mDVFSHelper.release()
I/Timeline( 3514): Timeline: Activity_windows_visible id: ActivityRecord{22408edc u0 com.test.thalitest/.MainActivity t25} time:224338
,W/IInputConnectionWrapper(11974): showStatusIcon on inactive InputConnection
,I/Timeline(11974): Timeline: Activity_idle id: android.os.BinderProxy@3d8f7264 time:224346
,I/chromium(11974): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11974): 
,D/JsMessageQueue(11974): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11974): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1361352960
,I/chromium(11974): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRM:n  ( 3514): SIOP:: AP = 260, PST = 269, CUR = 71
,D/BatteryService( 3514): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3514): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3514): online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3514): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3514): stay LED for fully charged
,I/MotionRecognitionService( 3514): Plugged
,I/MotionRecognitionService( 3514): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5636): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/jxcore-log(11974): Initializing JXcore engine
W/jxcore-log(11974): JXcore engine is ready
,E/auditd  ( 4617): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3514): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3514): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11974): Starting JXcore engine
,W/jxcore-log(11974): Platform android
W/jxcore-log(11974): 
W/jxcore-log(11974): Process ARCH arm
W/jxcore-log(11974): 
,I/jxcore-log(11974): JXcore Cordova bridge is ready!
I/jxcore-log(11974): 
W/jxcore-log(11974): JXcore engine is started
,I/jxcore-log(11974): Toggling radios to true
I/jxcore-log(11974): 
,D/BluetoothAdapter(11974): enable()
,D/BluetoothAdapter(11974): enable(): BT is already enabled..!
,D/WifiService( 3514): New client listening to asynchronous messages
,I/WifiManager(11974): packageName : com.test.thalitest
,D/SecContentProvider( 3514): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3514): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3514): mCursor = null
,D/WifiService( 3514): setWifiEnabled: true pid=11974, uid=10615
E/WifiService( 3514): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3514): Permission Denial: getCurrentUser() from pid=11974, uid=10615 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3514): Failed getting userId using ActivityManagerNative
W/WifiService( 3514): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11974, uid=10615 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3514): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3514): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3514): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3514): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3514): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider( 3514): name = wifi_on
,I/WifiService( 3514): disconnect: pid=11974, uid=10615
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11974): Radios toggled
I/jxcore-log(11974): 
,I/jxcore-log(11974): My device name is: samsung-SM-N910C
I/jxcore-log(11974): 
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3514): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): Disconnected - do not scan
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3514): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3514): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3514): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3514): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3514): do suspend true
,D/WifiP2pService( 3514): InactiveState{ what=143375 }
D/WifiP2pService( 3514): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2844): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,E/WifiStateMachine( 3514): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3514): updateNetworkInfo()
E/WifiConfigStore( 3514): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3514): evaluateTrafficStatsPolling
D/ConnectivityService( 3514): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3514): updateNetworkInfo()
D/ConnectivityService( 3514): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine( 3514): Start Disconnecting Watchdog 1
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
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3833): First Scan Start
E/WifiStateMachine( 3514): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3514): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3514): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3514): do suspend true
,D/WifiP2pService( 3514): InactiveState{ what=143375 }
D/WifiP2pService( 3514): P2pEnabledState{ what=143375 }
,I/Hs20UtilService( 4111): Starting #8
,I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8766): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8766): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8766): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8766): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8766): DMSUtil.isNetworkConnected - flag-null, state-null
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3514): New client listening to asynchronous messages
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8766): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8766): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11541): NETWORK_STATE_CHANGED_ACTION
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3514): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3514): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
E/WifiStateMachine( 3514): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityService( 3514): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine( 3514): updateConfiguredNetworkExpiration - currTime: 1454416737437
D/CSLegacyTypeTracker( 3514): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiStateMachine( 3514): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/CSLegacyTypeTracker( 3514): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3514): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 6778): CM callback handler got msg 524292
,E/WifiStateMachine( 3514): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/WifiTrafficPoller( 3514): evaluateTrafficStatsPolling
D/TelephonyNetworkFactory( 3977): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine( 3514): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
E/WifiStateMachine( 3514): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3514): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3514): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3514): Not allowed due to - mEnabled false
D/ConnectivityService( 3514): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,I/Hs20UtilService( 4111): Starting #9
,D/Tethering( 3514): MasterInitialState.processMessage what=3
D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/Hs20UtilService( 4111): Message received 5007
,V/NetworkStats( 3514): updateIfacesLocked()
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
V/NetworkStats( 3514): performPollLocked(flags=0x1)
D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3514): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
,V/NetworkStats( 3514): performPollLocked() took 3ms
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
V/NetworkStats( 3514): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
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
,D/NearbySettings( 8766): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8766): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8766): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8766): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,I/SignOutReceiver(11541): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3977): FileWriteThread : threadType = 3
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
,D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3514): updateDataUsageMap
I/ApplicationPolicy( 3514): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3514): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
W/SLocation( 3514): No Active Data Connection
I/DBG_DM  ( 6245): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
I/DBG_DM  ( 6245): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12066): MountEmulatedStorage()
E/Zygote  (12066): v2
I/libpersona(12066): KNOX_SDCARD checking this for 1000
I/libpersona(12066): KNOX_SDCARD not a persona
,I/SELinux (12066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12066): TimaSignature is unavailable
,D/ActivityThread(12066): Added TimaKeyStore provider
,D/ResourcesManager(12066): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12066): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12066): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12066): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(12066): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12066): sales region : global
I/PCWCLIENTTRACE_PushUtil(12066): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12066): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver(12066): noConnectivity : true
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12082): MountEmulatedStorage()
I/libpersona(12082): KNOX_SDCARD checking this for 10135
E/Zygote  (12082): v2
I/libpersona(12082): KNOX_SDCARD not a persona
,I/SELinux (12082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12082 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12082): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 11335:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12082): TimaSignature is unavailable
,D/ActivityThread(12082): Added TimaKeyStore provider
,D/ResourcesManager(12082): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(12082): Database version: 104
,D/ResourcesManager(12082): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12082): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12082): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12082): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12082): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12082): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b8c1e8d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12082): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12082): GMSCore installation verified
,I/ConfigStore(12082): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12082): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12082): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12082): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3514): getStreamVolume 3 index 0
,I/MediaRouter(12082): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12107): MountEmulatedStorage()
I/libpersona(12107): KNOX_SDCARD checking this for 10002
E/Zygote  (12107): v2
I/libpersona(12107): KNOX_SDCARD not a persona
,I/SELinux (12107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12107 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor(12082): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12107): TimaSignature is unavailable
,D/ActivityThread(12107): Added TimaKeyStore provider
,I/ActivityManager( 3514): Killing 11380:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/ResourcesManager(12107): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3514): Killing 11358:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12126): MountEmulatedStorage()
I/libpersona(12126): KNOX_SDCARD checking this for 1000
E/Zygote  (12126): v2
I/libpersona(12126): KNOX_SDCARD not a persona
,I/SELinux (12126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12126): TimaSignature is unavailable
,D/ActivityThread(12126): Added TimaKeyStore provider
,D/ResourcesManager(12126): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT(12126): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT(12126): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12126): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12126): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12126): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/wpa_supplicant( 3833): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3833): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3833): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3833): wlan0: State: SCANNING -> ASSOCIATING
,E/WifiStateMachine( 3514): [1,454,416,738,477 ms] noteScanEnd no scan source
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3514): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2b3d3424 sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3514): setDetailed state send new extra info
D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12142): MountEmulatedStorage()
I/libpersona(12142): KNOX_SDCARD checking this for 10012
E/Zygote  (12142): v2
I/libpersona(12142): KNOX_SDCARD not a persona
,I/SELinux (12142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12142): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12142 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12142): TimaSignature is unavailable
,D/ActivityThread(12142): Added TimaKeyStore provider
,D/ResourcesManager(12142): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3833): Associated with C0.AA.48
E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3514): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,I/ActivityManager( 3514): Killing 11428:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/FOTA_Client(12142): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3833): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3833): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3833): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3833): Blacklist: Clear (temp) 
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine( 3514): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3514): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3514): mCursor = null
,E/WifiStateMachine( 3514): Network connection established
,I/FOTA_Client(12142): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
D/WifiNative-HAL( 3514): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3514): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3514): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,E/WifiStateMachine( 3514): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3514): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3514): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3514): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 3514): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 3514): updateNetworkInfo()
,D/ConnectivityService( 3514): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/FOTA_Client(12142): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/WifiStateMachine( 3514): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3514): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3514): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3514): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3514): Start Dhcp Watchdog 2
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/Zygote  (12160): MountEmulatedStorage()
E/Zygote  (12160): v2
I/libpersona(12160): KNOX_SDCARD checking this for 10021
I/libpersona(12160): KNOX_SDCARD not a persona
,I/SELinux (12160): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12160): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12160 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12160): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 11446:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12160): TimaSignature is unavailable
,D/ActivityThread(12160): Added TimaKeyStore provider
,D/ResourcesManager(12160): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12160): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 13:38:58 GMT+01:00 2016
,I/KLMS-2.4.521: (12160): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12160): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12160): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12160): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12160): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12160): StateImplV2(): networkChangeListener().END
,E/Zygote  (12176): MountEmulatedStorage()
E/Zygote  (12176): v2
I/libpersona(12176): KNOX_SDCARD checking this for 10038
I/libpersona(12176): KNOX_SDCARD not a persona
,I/SELinux (12176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12176 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
E/SELinux (12176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3514): Killing 11413:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12176): TimaSignature is unavailable
,D/ActivityThread(12176): Added TimaKeyStore provider
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3514): do suspend false
,D/ResourcesManager(12176): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/SecContentProvider2( 3514): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService( 3514): InactiveState{ what=143375 }
D/SecContentProvider2( 3514): mCursor = null
,D/WifiP2pService( 3514): P2pEnabledState{ what=143375 }
,I/SO_AGENT(12176): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12191): MountEmulatedStorage()
E/Zygote  (12191): v2
I/libpersona(12191): KNOX_SDCARD checking this for 1000
I/libpersona(12191): KNOX_SDCARD not a persona
,I/SELinux (12191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12191 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3514): Killing 11463:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 272us total 11.590ms
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 251us total 7.948ms
,D/TimaKeyStoreProvider(12191): TimaSignature is unavailable
,D/ActivityThread(12191): Added TimaKeyStore provider
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 252us total 8.362ms
,D/ResourcesManager(12191): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12211): MountEmulatedStorage()
E/Zygote  (12211): v2
I/libpersona(12211): KNOX_SDCARD checking this for 10039
I/libpersona(12211): KNOX_SDCARD not a persona
,I/SELinux (12211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12211 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12211): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Killing 11476:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12211): TimaSignature is unavailable
,D/ActivityThread(12211): Added TimaKeyStore provider
,D/ResourcesManager(12211): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12211): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12211): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12211): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12211): PushLog.txt file is not deleted.
D/SPPClientService(12211): PushLog.txt file is not deleted.
D/SPPClientService(12211): ============PushLog. stop!
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12228): MountEmulatedStorage()
E/Zygote  (12228): v2
I/libpersona(12228): KNOX_SDCARD checking this for 10045
I/libpersona(12228): KNOX_SDCARD not a persona
,I/SELinux (12228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12228): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=12228 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3514): Killing 11511:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,E/SPPClientService(12211): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider(12228): TimaSignature is unavailable
,D/ActivityThread(12228): Added TimaKeyStore provider
,E/dhcpcd  (12245): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12245): version 5.5.6 starting
,D/ResourcesManager(12228): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
E/dhcpcd  (12245): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SA      (12228): [SSP] onCreated
,I/SA      (12228): [TPM] There is no property file
,I/SA      (12228): [SCU] isHaveSA() - false
,I/SA      (12228): [TPM] getModelProperty : null
I/SA      (12228): [TPM] getCSCProperty : null
,I/SA      (12228): [DM] init START
,I/SA      (12228): [DM] This device is not a Vodafone
,I/SA      (12228): checkReactivationActive for LOLLIPOP
I/SA      (12228): checkReactivationActive for reactiveActive
I/SA      (12228): setSupportRL : true
,I/SA      (12228): [SCU] isHaveSA() - false
I/SA      (12228): support phone number id : false
,I/SA      (12228): [DM] init END
I/SA      (12228): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (12228): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (12228): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12228): [SLFUCHKMGR] constructor called
I/dhcpcd  (12245): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12245): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12245): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12245): bssid match
I/dhcpcd  (12245): wlan0: rebinding lease of 192.168.1.124
,I/SA      (12228): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12228): [OR] == isSIMCardReady false ==
,I/SA      (12228): [SCU] == networkStateCheck == false
I/SA      (12228): [OR] onReceive END
,I/ActivityManager( 3514): Killing 11564:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12256): MountEmulatedStorage()
I/libpersona(12256): KNOX_SDCARD checking this for 10067
E/Zygote  (12256): v2
I/libpersona(12256): KNOX_SDCARD not a persona
,I/SELinux (12256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12256 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12256): TimaSignature is unavailable
,D/ActivityThread(12256): Added TimaKeyStore provider
,D/ResourcesManager(12256): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12256): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12256): Other Intent
,I/ActivityManager( 3514): Killing 11581:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/accuweather( 5211): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5211): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5211): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12272): MountEmulatedStorage()
E/Zygote  (12272): v2
I/libpersona(12272): KNOX_SDCARD checking this for 1000
I/libpersona(12272): KNOX_SDCARD not a persona
,I/SELinux (12272): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12272): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12272 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12272): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12272): TimaSignature is unavailable
,D/ActivityThread(12272): Added TimaKeyStore provider
,D/ResourcesManager(12272): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12272): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12272): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12272): premStatus:2
,I/KnoxUsageLogPro(12272): isEulaShown : false
I/KnoxUsageLogPro(12272): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12287): MountEmulatedStorage()
I/libpersona(12287): KNOX_SDCARD checking this for 10090
E/Zygote  (12287): v2
I/libpersona(12287): KNOX_SDCARD not a persona
,I/SELinux (12287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12287): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12287 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3514): Killing 11599:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12287): TimaSignature is unavailable
,D/ActivityThread(12287): Added TimaKeyStore provider
,D/ResourcesManager(12287): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12303): MountEmulatedStorage()
E/Zygote  (12303): v2
I/libpersona(12303): KNOX_SDCARD checking this for 10127
I/libpersona(12303): KNOX_SDCARD not a persona
,I/SELinux (12303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12303): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12303 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3514): Killing 11615:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12303): TimaSignature is unavailable
,D/ActivityThread(12303): Added TimaKeyStore provider
,D/ResourcesManager(12303): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12303): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12303): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12303): stopCheckCategoryVersion
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12319): MountEmulatedStorage()
I/libpersona(12319): KNOX_SDCARD checking this for 10136
E/Zygote  (12319): v2
I/libpersona(12319): KNOX_SDCARD not a persona
I/SELinux (12319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12319): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12319 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3514): Killing 11722:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12319): TimaSignature is unavailable
,D/ActivityThread(12319): Added TimaKeyStore provider
,D/ResourcesManager(12319): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/ContextImpl( 3514): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12319): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12319): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12319): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12319): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12319): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12319): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12319): Loading: webviewchromium
,I/LibraryLoader(12319): Time to load native libraries: 3 ms (timestamps 7734-7737)
I/LibraryLoader(12319): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12319): Binding Chromium to main looper Looper (main, tid 1) {1b291689}
,I/LibraryLoader(12319): Expected native library version number "",actual native library version number ""
,I/chromium(12319): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12319): Initializing chromium process, renderers=0
,W/art     (12319): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12319): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12319): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12319): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12319): Requires BLUETOOTH permission
,I/NSApplication(12319): Starting up...
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12386): MountEmulatedStorage()
I/libpersona(12386): KNOX_SDCARD checking this for 10147
E/Zygote  (12386): v2
I/libpersona(12386): KNOX_SDCARD not a persona
,I/SELinux (12386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12386): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=12386 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3514): Killing 11761:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12386): TimaSignature is unavailable
,D/ActivityThread(12386): Added TimaKeyStore provider
,D/ResourcesManager(12386): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(12386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 4671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 4671): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  (12414): MountEmulatedStorage()
E/Zygote  (12414): v2
I/libpersona(12414): KNOX_SDCARD checking this for 10150
I/libpersona(12414): KNOX_SDCARD not a persona
,I/SELinux (12414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12414 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12414): TimaSignature is unavailable
,D/ActivityThread(12414): Added TimaKeyStore provider
,D/ResourcesManager(12414): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12414): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12414): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12414): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12414): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/art     ( 3514): Explicit concurrent mark sweep GC freed 87847(5MB) AllocSpace objects, 37(592KB) LOS objects, 24% free, 49MB/65MB, paused 1.271ms total 80.036ms
,I/QuickConnect(12414): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12430): MountEmulatedStorage()
I/libpersona(12430): KNOX_SDCARD checking this for 10178
E/Zygote  (12430): v2
I/libpersona(12430): KNOX_SDCARD not a persona
I/SELinux (12430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12430 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3514): Killing 11776:com.android.calendar/u0a164 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12430): TimaSignature is unavailable
,D/ActivityThread(12430): Added TimaKeyStore provider
,D/ResourcesManager(12430): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12430): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12430): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12430): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12430): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12430): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,E/Zygote  (12457): MountEmulatedStorage()
E/Zygote  (12457): v2
I/libpersona(12457): KNOX_SDCARD checking this for 10082
I/libpersona(12457): KNOX_SDCARD not a persona
D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,I/SELinux (12457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12457): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12457 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 8751(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 347us total 10.378ms
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 720us total 9.088ms
,D/TimaKeyStoreProvider(12457): TimaSignature is unavailable
,D/ActivityThread(12457): Added TimaKeyStore provider
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 453us total 8.500ms
,E/Zygote  (12473): MountEmulatedStorage()
I/libpersona(12473): KNOX_SDCARD checking this for 1000
E/Zygote  (12473): v2
I/libpersona(12473): KNOX_SDCARD not a persona
,I/SELinux (12473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Killing 11741:com.sec.android.widgetapp.locationwidget/u0a22 (adj 13): bgCount ##31
,I/ActivityManager( 3514): Killing 10219:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12473): TimaSignature is unavailable
,D/ResourcesManager(12457): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/ActivityThread(12473): Added TimaKeyStore provider
,D/BadgeProvider(12457): onCreate
D/BadgeProvider(12457): DatabaseHelper
,D/ResourcesManager(12473): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,V/AlarmManager( 3514): waitForAlarm result :8
,D/BadgeProvider(12457): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager( 3514): Killing 10959:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/BadgeProvider(12457): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12457): sendNotify, [notify] : null
D/BadgeProvider(12457): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12457): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12457): update, [UpdateCount] : 1
,D/CountryDetector( 3514): No listener is left
,D/Launcher.Model( 3999): reloadBadges entered.
,I/dhcpcd  (12245): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,W/ActivityManager( 3514): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 6778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6778): num queued entries: 0
,I/iu.UploadsManager( 6778): num updated entries: 0
I/iu.SyncManager( 6778): NEXT; no task
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12491): MountEmulatedStorage()
I/libpersona(12491): KNOX_SDCARD checking this for 10013
E/Zygote  (12491): v2
I/libpersona(12491): KNOX_SDCARD not a persona
,I/SELinux (12491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12491): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3514): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12491 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/dhcpcd  (12245): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/TimaKeyStoreProvider(12491): TimaSignature is unavailable
D/ActivityThread(12491): Added TimaKeyStore provider
,D/ResourcesManager(12491): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3514): Killing 11820:com.sec.android.widgetapp.digitalclock/u0a97 (adj 13): bgCount ##31
,I/Hs20UtilService( 4111): Starting #10
I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8766): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8766): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8766): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8766): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11541): NETWORK_STATE_CHANGED_ACTION
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine( 3514): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3514): do suspend true
,D/WifiP2pService( 3514): InactiveState{ what=143375 }
D/WifiP2pService( 3514): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 3514): WifiStateMachine DHCP successful
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3514): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3514): Not connected state, yet.
E/WifiStateMachine( 3514): VerifyingLinkState enter
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiStateMachine( 3514): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3514): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3514): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3514): callSECApiInt - ID [210]
E/WifiStateMachine( 3514): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3514): updateNetworkInfo()
,D/ConnectivityService( 3514): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3514): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 3514): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3514): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3514): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3514): Now, connected state.
E/WifiStateMachine( 3514): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,E/WifiStateMachine( 3514): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller( 3514): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3514): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService( 3514): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/WifiTrafficPoller( 3514): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3514): callSECApiVoid - ID [212]
D/ConnectivityService( 3514): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 3514): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/WifiStateMachine( 3514): ConnectedState Enter  mScreenOn=false scanperiod=20000
,E/ConnectivityService( 3514): Unexpected mtu value: 0, wlan0
,V/        ( 2844): QcRouteController
I/WifiStateMachine( 3514): REQUEST_POWER_SAVE_ON
,I/Hs20UtilService( 4111): Starting #11
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
I/Hs20UtilService( 4111): Message received 5007
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/NearbySettings( 8766): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/        ( 2844): QcRouteController
I/NearbySettings( 8766): MountReceiver.onReceive - Keep current state
,V/        ( 2844): QcRouteController
,V/        ( 2844): QcRouteController
,I/SignOutReceiver(11541): NETWORK_STATE_CHANGED_ACTION
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4111): Starting #12
,V/        ( 2844): QcRouteController
,I/Hs20UtilService( 4111): Message received 5007
V/        ( 2844): QcRouteController
,D/NearbySettings( 8766): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8766): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8766): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8766): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8766): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8766): MountReceiver.mPrefHandler - 7002
,V/        ( 2844): QcRouteController
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11974): 
I/SignOutReceiver(11541): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 3514): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 3514): LTETest block dns file not exists
,I/Hs20UtilService( 4111): Starting #13
,I/Hs20UtilService( 4111): Message received 5007
,D/NearbySettings( 8766): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 8766): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 3514): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3514): updateNetworkInfo()
E/ConnectivityService( 3514): updateNetworkInfo()
D/ConnectivityService( 3514): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3514): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3514): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService( 3514):    accepting network in place of null
,D/TelephonyNetworkFactory( 3977): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 3514): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3514): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 3514): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 3514): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 3514): MasterInitialState.processMessage what=3
D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 3514): Not allowed due to - mEnabled false
D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/ConnectivityService( 3514): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,V/NetworkStats( 3514): updateIfacesLocked()
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
V/NetworkStats( 3514): performPollLocked(flags=0x1)
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 6778): CM callback handler got msg 524290
D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
,D/NetworkStatsFactory( 3514): UpdateStatsForKnox
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
V/NetworkStats( 3514): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,V/NetworkStats( 3514): performPollLocked() took 5ms
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
D/NtpTrustedTime( 3514): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/WifiStateMachine( 3514): callSECApi what=220
D/WifiStateMachine( 3514): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/SignOutReceiver(11541): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 3514): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3514
,D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
,I/System.out( 3514): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:39:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454416740554], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454416740541]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3514): Validated
D/ConnectivityService( 3514): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3514): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3514): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3514): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 6778): CM callback handler got msg 524290
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
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11974): 
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11974): 
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log(11974): 
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log(11974): 
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log(11974): 
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log(11974): 
,I/jxcore-log(11974): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11974): 
,D/ConnectivityService( 3514): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3514): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3514): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3514): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3514): getNetworkEnabled : wifi : true mobile : false
,I/DBG_DM  ( 6245): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6245): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(12082): type=WIFI subType= reason=null isConnected=true
,W/ResourceType( 5350): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5350): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(12066): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12066): sales region : global
I/PCWCLIENTTRACE_PushUtil(12066): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12066): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12126): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12126): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3514): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3514): mCursor = null
,I/FOTA_Client(12142): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12142): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12142): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12160): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 13:39:01 GMT+01:00 2016
,I/KLMS-2.4.521: (12160): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12160): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12160): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12160): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/SO_AGENT(12176): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12160): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12160): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12160): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.521: (12160): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12160): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onDestroy()
,E/SPPClientService(12211): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (12228): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
I/SA      (12228): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (12228): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (12228): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (12228): [OR] == isSIMCardReady false ==
,I/SA      (12228): [SCU] == networkStateCheck == true
I/SA      (12228): [DM] getCountryCodeFromCSC : PL
I/SA      (12228): isChinaCountryCode : false
I/SA      (12228): [SCU] is ChinestModel Data Restricted   : false
I/SA      (12228): [OR] == networkStateCheck true ==
,I/SA      (12228): [OR] GetMyCountryZoneTask
I/SA      (12228): [OR] onReceive END
,I/SA      (12228): [SRS] prepareGetMyCountryZone
,I/SA      (12228): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (12228): [SSP] query invoked
,V/DownloadManager( 3717): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (12228): [TPMU] GetMccFromDB : null
I/SA      (12228): [SCU] getMccFromPreferece mcc = 260
I/SA      (12228): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12256): Other Intent
,D/accuweather( 5211): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3775): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5211): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5211): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5211): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5211): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5211): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12272): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12272): premStatus:2
,I/KnoxUsageLogPro(12272): isEulaShown : false
I/KnoxUsageLogPro(12272): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12303): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12303): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12303): stopCheckCategoryVersion
,I/PowerManagerService( 3514): [PWL] Off : 105s ago
I/PowerManagerService( 3514): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 3514): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3514): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3514, ws=null) (elapsedTime=3720)
,D/QuickConnect(12414): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12414): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12414): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,D/RCPManagerService( 3514): exchangeData() failure , invalid userId
,I/iu.Environment( 6778): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6778): num queued entries: 0
,I/iu.UploadsManager( 6778): num updated entries: 0
I/iu.SyncManager( 6778): NEXT; no task
,D/WaitQueueForNetworkActivate(12491): notifyNetworkActivated
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12491): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3514): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12491): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12491): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12491): exit::IDLE
D/InitializeManagerStateMachine(12491): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12491): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12491): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12491): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12491): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12491): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12491): entry::SUCCESS
D/hcjo    (12491): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    (12491): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12491): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12491): exit::SUCCESS
D/InitializeManagerStateMachine(12491): entry::IDLE
,I/SA      (12228): [RC New] Execute method=[GET] start
,I/SA      (12228): [RC New] Security=[true]
,I/System.out(12228): Thread-1725(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(12228): Thread-1725(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(12228): Thread-1725(ApacheHTTPLog):isShipBuild true
I/System.out(12228): Thread-1725(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3514): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      (12228): [RC New] [v2liruge] api execute + 575
I/SA      (12228): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(12228): AsyncTask #1 calls detatch()
,I/SA      (12228): [TPMU] getNetworkMcc : 
,I/SA      (12228): [SCU] saveMccToPreferece Start
I/SA      (12228): [SCU] RegionMCC : 260
I/SA      (12228): [SSP] query invoked
,I/SA      (12228): [TPMU] GetMccFromDB : null
I/SA      (12228): [SCU] getMccFromPreferece mcc = 260
I/SA      (12228): [SCU] saveMccToPreferece End
,I/SA      (12228): [RC New] executeRequest [v2liruge] end. 595
I/SA      (12228): [RC New] Execute end
I/SA      (12228): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (12228): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  (12245): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12245): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 4671): callingUid 10014, callindPid: 4671
,D/ResourcesManager(12082): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12082): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12082): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12082): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12082): Conditions not met for autocaching.
I/MusicLeanback(12082): Stop autocaching.
,I/art     ( 4671): Explicit concurrent mark sweep GC freed 91679(4MB) AllocSpace objects, 19(615KB) LOS objects, 34% free, 30MB/46MB, paused 745us total 31.505ms
,D/WearableClient(12082): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12082): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12082): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12082): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12082): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12082): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12082): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@9b78c05 that was originally bound here
E/ActivityThread(12082): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@9b78c05 that was originally bound here
E/ActivityThread(12082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12082): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12082): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12082): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12082): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12082): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12082): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12082): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12082): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12082): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12082): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12082): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12082): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12082): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12082): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12082): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3514): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3514): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/WifiStateMachine( 3514): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3514): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService( 3514): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
V/        ( 2844): QcRouteController
D/SmartBondingService( 3514): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/SmartBondingService( 3514): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
D/SmartBondingService( 3514): getSBEnabled() enabled =false
,V/        ( 2844): QcRouteController
,W/NetworkManagementService( 3514): route cmd failed: 
W/NetworkManagementService( 3514): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3514): '
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3514): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3514): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3514): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3514): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3514): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3514): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3514): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityService( 3514): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 6778): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6778): CM callback handler got msg 524295
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (-2/9)
D/PowerManagerService( 3514): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3514) eventTime = 232318
,D/PowerManagerService( 3514): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3514 (0x0)
D/PowerManagerService( 3514): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3514, ws=WorkSource{10060}) (elapsedTime=3473)
,I/jxcore-log(11974): Test app app.js loaded
I/jxcore-log(11974): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11974): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55dbd0b added. We now have 1 listener(s)
,I/jxcore-log(11974): BLE advertisement is supported
I/jxcore-log(11974): 
,I/chromium(11974): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log(11974): --= Surplus to requirements =--
I/jxcore-log(11974): 
I/jxcore-log(11974): ****TEST TOOK:  ms ****
I/jxcore-log(11974): 
I/jxcore-log(11974): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11974): 
,I/GAV4    (12319): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime(12587): 
D/AndroidRuntime(12587): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12587): CheckJNI is OFF
,D/AndroidRuntime(12587): readGMSProperty: start
D/AndroidRuntime(12587): readGMSProperty: already setted!!
,D/AndroidRuntime(12587): readGMSProperty: end
D/AndroidRuntime(12587): addProductProperty: start
,E/AffinityControl(12587): AffinityControl: registerfunction enter
,D/AndroidRuntime(12587): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3514): START PACKAGE DELETE: observer{685867447}
D/PackageManager( 3514): pkg{<packageName>}
D/PackageManager( 3514): user{0}
D/PackageManager( 3514): caller{2000}
D/PackageManager( 3514): flags{3}
D/PersonaManagerService( 3514): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3514): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3514): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3514): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3514): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3514): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3514): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3514): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3514): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3514): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3514): !@killApplicatoin: 10615, uninstall pkg
,I/ActivityManager( 3514): Force stopping com.test.thalitest appid=10615 user=-1: uninstall pkg
I/ActivityManager( 3514): Killing 11974:com.test.thalitest/u0a615 (adj 0): stop com.test.thalitest
,I/GAV2    (12386): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 3514):   Force finishing activity ActivityRecord{22408edc u0 com.test.thalitest/.MainActivity t25}
,I/SurfaceFlinger( 2848): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2848): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3514): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3514): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3514): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3514): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3514): Skipping PackageSetting{1905ee8 com.example.hello/10563} due to missing metadata
,I/ActivityManager( 3514): Force stopping com.test.thalitest appid=10615 user=0: pkg removed
,D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/WifiService( 3514): Client connection lost with reason: 4
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/art     ( 8869): Explicit concurrent mark sweep GC freed 26063(1506KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.608ms total 40.674ms
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 6778): Explicit concurrent mark sweep GC freed 5642(299KB) AllocSpace objects, 2(32KB) LOS objects, 20% free, 31MB/39MB, paused 1.009ms total 71.166ms
E/SamsungIME( 4463): mOCRHelper is null
,W/GeofencerStateMachine( 4671): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12602): MountEmulatedStorage()
E/Zygote  (12602): v2
I/libpersona(12602): KNOX_SDCARD checking this for 10063
I/libpersona(12602): KNOX_SDCARD not a persona
,I/SELinux (12602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12602 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourceType( 5350): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5350): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager( 3514): Killing 11835:com.sec.android.app.camera/u0a168 (adj 15): bgCount ##31
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/InputReader( 3514): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/EnterpriseDeviceManagerService( 3514): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3514): Admin package name: com.google.android.gms
,D/TimaKeyStoreProvider(12602): TimaSignature is unavailable
,D/ActivityThread(12602): Added TimaKeyStore provider
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(12602): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 3514): Explicit concurrent mark sweep GC freed 56077(3MB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 49MB/65MB, paused 2.972ms total 182.286ms
,D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/PackageManager( 3514): delete codoeFile: 
,I/AASAUninstall( 3514):  com.test.thalitest not target!
D/PackageManager( 3514): result of delete: 1{685867447}
D/AndroidRuntime(12587): Shutting down VM
D/VRSetupWizardStub/PackageIntentReceiver(12602): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12602): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12602): packagename:com.test.thalitest
,D/SecContentProvider2( 3514): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3514): mCursor = null
,I/KLMS-2.4.521: (12160): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Feb 02 13:39:04 GMT+01:00 2016
,I/KLMS-2.4.521: (12160): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3514): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3514): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12160): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12160): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12160): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12160): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12160): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (12160): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,E/Zygote  (12622): MountEmulatedStorage()
E/Zygote  (12622): v2
I/libpersona(12622): KNOX_SDCARD checking this for 10106
I/libpersona(12622): KNOX_SDCARD not a persona
I/ActivityManager( 3514): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12622 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (12622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/RegisteredServicesCache( 3961): empty dynamic service
,I/SELinux (12622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
D/RCPManager(12272):  in createShortcut() for packageName: com.test.thalitest userId0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3514):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3514): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/Zygote  (12637): MountEmulatedStorage()
E/Zygote  (12637): v2
I/libpersona(12637): KNOX_SDCARD checking this for 10050
I/libpersona(12637): KNOX_SDCARD not a persona
,I/SELinux (12637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3514): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=12637 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12622): TimaSignature is unavailable
,I/SELinux (12637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12637): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityThread(12622): Added TimaKeyStore provider
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12649): MountEmulatedStorage()
E/Zygote  (12649): v2
I/libpersona(12649): KNOX_SDCARD checking this for 10101
I/libpersona(12649): KNOX_SDCARD not a persona
I/SELinux (12649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12649 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12649): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12637): TimaSignature is unavailable
,D/ActivityThread(12637): Added TimaKeyStore provider
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12160): KLMSIntentService(): listeningToPackageRemoved().END
,D/TimaKeyStoreProvider(12649): TimaSignature is unavailable
,D/ActivityThread(12649): Added TimaKeyStore provider
,E/Zygote  (12667): MountEmulatedStorage()
E/Zygote  (12667): v2
I/libpersona(12667): KNOX_SDCARD checking this for 10183
I/libpersona(12667): KNOX_SDCARD not a persona
,I/SELinux (12667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux (12667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3514): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=12667 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (12667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(12622): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/KLMS-2.4.521: (12160): KLMSIntentService(): onDestroy()
D/elm:14491(12622): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12622): ELMEngine.ELMEngine( context ).
,D/elm:14491(12622): MDMBridge.setEnterpriseBridge()
,I/ActivityManager( 3514): Killing 11852:com.sec.android.widgetapp.dualclockdigital/u0a105 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12667): TimaSignature is unavailable
,D/ActivityThread(12667): Added TimaKeyStore provider
,D/ResourcesManager(12649): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/elm:14491(12622): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12622): ElmAgentService : onCreate()
D/elm:14491(12622): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(12622): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12622): MDMBridge.getInstance()
D/elm:14491(12622): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(12622): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(12637): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12637): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(12637): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12637): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12637): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12637): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12637): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(12667): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
W/ResourcesManager(12637): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager(12637): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (12684): MountEmulatedStorage()
E/Zygote  (12684): v2
I/libpersona(12684): KNOX_SDCARD checking this for 10019
I/libpersona(12684): KNOX_SDCARD not a persona
I/SELinux (12684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3514): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12684 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (12684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 3514): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/elm:14491(12622): ElmAgentService : onDestroy().
,I/ActivityManager( 3514): Killing 10913:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SQLiteLog(12667): (284) automatic index on shooting_modes(title_id)
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/DocsApplication(12649): Installing DEX configuration.
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
D/DexInstaller(12649): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12684): TimaSignature is unavailable
W/ResourcesManager( 3514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3514): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/PackageInfoHelper(12649): Provided clientMode=RELEASE, packageInfo=PackageInfo{2a8dc3f6 com.google.android.apps.docs}
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/TAG     (12649): onCreate()
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ActivityThread(12684): Added TimaKeyStore provider
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/CrossAppStateProvider(12649): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/PackageManager( 3514): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (12701): MountEmulatedStorage()
E/Zygote  (12701): v2
I/libpersona(12701): KNOX_SDCARD checking this for 10190
I/libpersona(12701): KNOX_SDCARD not a persona
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/SELinux (12701): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12701): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
E/SELinux (12701): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3514): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12701 uid=10190 gids={50190, 9997} abi=armeabi-v7a
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager( 3514): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/RCPManagerService( 3514): PackageReceiver onReceive()
I/HarmonyEASService( 3514): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3514): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/KnoxMUMContainerPolicy( 3514): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,E/SQLiteLog(12637): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3514): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 3514): Killing 11667:com.android.vending/u0a31 (adj 13): bgCount ##31
E/SQLiteDatabase(12637): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase(12637): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12637): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12637): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12637): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase(12637): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12637): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12637): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12637): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12637): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12637): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12637): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/TimaKeyStoreProvider(12701): TimaSignature is unavailable
I/CrashAnrDetector( 3514): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3514): clearDefaults: com.test.thalitest
D/ActivityThread(12701): Added TimaKeyStore provider
D/ResourcesManager(12684): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
E/SharedPreferencesImpl(12637): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/ResourcesManager(12701): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/PackageManager( 3514): findPreferredActivity: No PreferredActivities set
,I/TapandpayWidget:TanpandpayAppWidgetProvider(12701): onReceive()
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12701): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12684): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12684): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12684): onReceive() : package name is not s health. Return !!!
,I/TapandpayWidget:Utils(12701): Clear T&P info.
,E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TanpandpayAppWidgetProvider(12701): Widget is not attached.
,D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3514): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3514): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3514): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3514): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3514): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3514): displayNotification : [09h,00h,00h]
D/UsbHostManager( 3514): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3514): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3514): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/Zygote  (12726): MountEmulatedStorage()
E/Zygote  (12726): v2
I/libpersona(12726): KNOX_SDCARD checking this for 10022
I/libpersona(12726): KNOX_SDCARD not a persona
,I/ActivityManager( 3514): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=12726 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3514): Killing 11798:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,I/SELinux (12726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3514): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3514): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/NearbySource(12637): Nearby Source Create!
D/NearbyContext(12637): Nearby Context Create!
,I/ActivityManager( 3514): Killing 12457:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,I/EventHub( 3514): Removing device '/dev/input/event10' due to inotify event
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/TimaKeyStoreProvider(12726): TimaSignature is unavailable
,D/ActivityThread(12726): Added TimaKeyStore provider
,I/EventHub( 3514): Removing device '/dev/input/event7' due to inotify event
,W/ContextImpl(12637): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(12637): Samsung link source created
,D/PackageBroadcastService( 6778): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6778): Clearing selected account for com.test.thalitest
,I/EventHub( 3514): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(12726): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(12726): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12726): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog(12637): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,W/ResourcesManager(12726): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/EventHub( 3514): Removing device '/dev/input/event9' due to inotify event
,E/SQLiteDatabase(12637): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase(12637): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12637): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12637): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12637): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(12637): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase(12637): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase(12637): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase(12637): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteDatabase(12637): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteDatabase(12637): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12637): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12637): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12637): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12637): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12637): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12637): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12637): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper(12637): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper(12637): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteConne,ctionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(12637): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(12637): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(12637): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(12637): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper(12637): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper(12637): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper(12637): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:202)
E/SQLiteOpenHelper(12637): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:194)
E/SQLiteOpenHelper(12637): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper(12637): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
E/SQLiteOpenHelper(12637): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteOpenHelper(12637): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteOpenHelper(12637): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(12637): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper(12637): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteOpenHelper(12637): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper(12637): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper(12637): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper(12637): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteLog( 6778): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6778): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/SQLiteOpenHelper(12637): Opened local.db in read-only mode
E/DriveAsyncService( 6778): disk I/O error (code 3850)
E/DriveAsyncService( 6778): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 6778): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 6778): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 6778): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 6778): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 6778): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 6778): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 6778): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 6778): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 6778): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 6778): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 6778): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 6778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 6778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 6778): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 6778): 	at java.lang.Thread.run(Thread.java:818)
D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/EventHub( 3514): Removing device '/dev/input/event11' due to inotify event
,I/LocationSettingsChecker( 6778): Removing dialog suppression flag for package com.test.thalitest
I/EventHub( 3514): Removing device '/dev/input/event12' due to inotify event
I/LocationWidgetApplication(12726): onCreate() : start
D/LocationWidgetApplication(12726): countryCode = POLAND
E/SQLiteLog( 6778): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
D/ChimeraCfgMgr( 6778): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6778): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase( 6778): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 6778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6778): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 6778): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 6778): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 6778): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 6778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6778): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 6778): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 6778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 6778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6778): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 6778): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 6778): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 6778): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 6778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 6778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6778): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 6778): Opened metrics.db in read-only mode
,D/gH_CompatibleDatabase( 6778): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 6778): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/WifiDisplayAdapter( 3514): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(12637): getAllContactInfoList Start
,E/SQLiteLog( 6778): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 6778): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,E/AndroidRuntime( 6778): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 6778): Process: com.google.android.gms, PID: 6778
E/AndroidRuntime( 6778): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 6778): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6778): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 6778): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6778): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6778): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 6778): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 6778): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 6778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6778): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3514): Removing device '/dev/input/event13' due to inotify event
,D/LocationManagerService( 3514): getProviders()=[]
D/LocationManagerService( 3514): getProviders()=[passive]
D/LocationManagerService( 3514): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(12726): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(12726): getLastUiLocationId() : mLastUiLocationId = -100
,E/SharedPreferencesImpl(12637): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,E/SQLiteLog(12726): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(12726): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(12726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12726): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12726): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(12726): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(12726): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(12726): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(12726): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(12726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(12726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(12726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(12726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12726): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12726): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12726): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12726): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(12726): Shutting down VM
,E/AndroidRuntime(12726): FATAL EXCEPTION: main
E/AndroidRuntime(12726): Process: com.sec.android.widgetapp.locationwidget, PID: 12726
E/AndroidRuntime(12726): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(12726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(12726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(12726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12726): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12726): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12726): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12726): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12726): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12726): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12726): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(12726): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(12726): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(12726): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(12726): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(12726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(12726): 	... 9 more
,E/SQLiteLog( 6778): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
,D/ChimeraCfgMgr( 6778): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6778): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase( 6778): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 6778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6778): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6778): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/PhenotypeInitializer( 6778): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6778): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 6778): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 6778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6778): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 6778): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6778): 	at andro,id.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6778): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6778): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6778): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 6778): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3514): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 6778): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 6778): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/EventHub( 3514): Removing device '/dev/input/event14' due to inotify event
,E/ClearPendingStateOp( 6778): Runtime exception while performing operation
E/ClearPendingStateOp( 6778): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 6778): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 6778): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 6778): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 6778): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 6778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 6778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 6778): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 6778): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 6778): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 6778): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 6778): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 6778): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 6778): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 6778): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 6778): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 6778): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 6778): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 6778): 	at java.lang.Thread.run(Thread.java:818)
,E/Zygote  (12752): MountEmulatedStorage()
E/SQLiteLog( 6778): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6778): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/libpersona(12752): KNOX_SDCARD checking this for 10052
E/Zygote  (12752): v2
I/libpersona(12752): KNOX_SDCARD not a persona
,I/SELinux (12752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/GMPM-SVC( 6778): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SQLiteLog( 6778): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6778): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 6778): Sending signal. PID: 6778 SIG: 9
,I/ActivityManager( 3514): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=12752 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (12752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12752): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/JavaBinder( 3514): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 3514): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.011ms total 39.188ms
,V/ApplicationPolicy( 3514): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
,E/DropBoxManagerService( 3514): Can't write: system_app_wtf
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 593us total 25.730ms
,E/SQLiteLog( 4671): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 4671): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4671): Shutting down VM
,E/AndroidRuntime( 4671): FATAL EXCEPTION: main
E/AndroidRuntime( 4671): Process: com.google.android.gms.persistent, PID: 4671
E/AndroidRuntime( 4671): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4671): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4671): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4671): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4671): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4671): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4671): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4671): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4671): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4671): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4671): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4671): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4671): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4671): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4671): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4671): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4671): 	... 9 more
,I/art     ( 2875): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 598us total 27.549ms
I/Process (12726): Sending signal. PID: 12726 SIG: 9
,I/PCWCLIENTTRACE_PushUtil(12066): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12066): sales region : global
I/PCWCLIENTTRACE_PushUtil(12066): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12066): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/DropBoxManagerService( 3514): Can't write: system_app_crash
E/DropBoxManagerService( 3514): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3514): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3514): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3514): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3514): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3514): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,E/DropBoxManagerService( 3514): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3514): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3514): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3514): 	... 5 more

```
