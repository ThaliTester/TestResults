#### Test 50650278d0426ce_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:56
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5609): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5609): Disconnected process message: 10
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(11907): 
D/AndroidRuntime(11907): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11907): CheckJNI is OFF
D/AndroidRuntime(11907): readGMSProperty: start
D/AndroidRuntime(11907): readGMSProperty: already setted!!
D/AndroidRuntime(11907): readGMSProperty: end
D/AndroidRuntime(11907): addProductProperty: start
E/AffinityControl(11907): AffinityControl: registerfunction enter
D/AndroidRuntime(11907): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3528): inState():  stateMachine is null !!
I/PersonaManagerService( 3528): PersonaId don't exist
I/ActivityManager( 3528): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3528): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3528): mDVFSHelper.acquire()
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (11922): MountEmulatedStorage()
E/Zygote  (11922): v2
I/libpersona(11922): KNOX_SDCARD checking this for 10474
I/libpersona(11922): KNOX_SDCARD not a persona
I/SELinux (11922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11922 uid=10474 gids={50474, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11922): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11907): Shutting down VM
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11922): TimaSignature is unavailable
D/ActivityThread(11922): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11922): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6230): updateVisibility : ActivityRecord{25101564 token=android.os.BinderProxy@3368b411 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11922): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11922): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11922): Loading: webviewchromium
I/LibraryLoader(11922): Time to load native libraries: 4 ms (timestamps 7286-7290)
I/LibraryLoader(11922): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11922): Binding Chromium to main looper Looper (main, tid 1) {259846c7}
,I/LibraryLoader(11922): Expected native library version number "",actual native library version number ""
,I/chromium(11922): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11922): Initializing chromium process, renderers=0
,W/art     (11922): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11922): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11922): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11922): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11922): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11922): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11922): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11922): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11922): CordovaWebView is running on device made by: samsung
W/art     (11922): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11922): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11922): performCreate Call secproduct feature valuefalse
D/Activity(11922): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11922): Render dirty regions requested: true
,D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3528): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11922): Initialized EGL, version 1.4
,I/OpenGLRenderer(11922): HWUI protection enabled for context ,  &this =0xaf6ad1a0 ,&mEglDisplay = 1 , &mEglConfig = -1356938992 
,D/OpenGLRenderer(11922): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11922): Enabling debug mode 0
,D/mali_winsys(11922): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11922): updateVisibility : ActivityRecord{2fda6fb7 token=android.os.BinderProxy@19f3ba3a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{12fd51c6 u0 com.test.thalitest/.MainActivity t26} time:357738
W/ActivityManager( 3528): mDVFSHelper.release()
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 35245(2MB) AllocSpace objects, 48(768KB) LOS objects, 24% free, 48MB/64MB, paused 1.985ms total 170.943ms
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper(11922): showStatusIcon on inactive InputConnection
I/Timeline(11922): Timeline: Activity_idle id: android.os.BinderProxy@19f3ba3a time:357935
,I/chromium(11922): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11922): 
,D/JsMessageQueue(11922): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11922): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11922): jxcore cordova android initializing
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11990): MountEmulatedStorage()
I/libpersona(11990): KNOX_SDCARD checking this for 1000
E/Zygote  (11990): v2
I/libpersona(11990): KNOX_SDCARD not a persona
,I/SELinux (11990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.android.settings for preferred application com.android.settings: pid=11990 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11990): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11990): TimaSignature is unavailable
,D/ActivityThread(11990): Added TimaKeyStore provider
,I/ActivityManager( 3528): Killing 10402:com.facebook.appmanager/u0a110 (adj 15): bgCount ##31
,D/ResourcesManager(11990): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(11990): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(11990): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11990): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager(11990): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11990): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11990): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11990): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MySettingsProvider(11990): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog(11990): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider(11990): onCreate():(mDB == null)? false:true  =true
,W/jxcore-log(11922): Initializing JXcore engine
W/jxcore-log(11922): JXcore engine is ready
,W/jxcore-log(11922): Starting JXcore engine
,E/auditd  ( 4609): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3528): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3528): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11922): Platform android
W/jxcore-log(11922): 
W/jxcore-log(11922): Process ARCH arm
W/jxcore-log(11922): 
,I/jxcore-log(11922): JXcore Cordova bridge is ready!
I/jxcore-log(11922): 
W/jxcore-log(11922): JXcore engine is started
,I/jxcore-log(11922): Toggling radios to true
I/jxcore-log(11922): 
,D/BluetoothAdapter(11922): enable()
,D/BluetoothAdapter(11922): enable(): BT is already enabled..!
,D/WifiService( 3528): New client listening to asynchronous messages
,I/WifiManager(11922): packageName : com.test.thalitest
,D/SecContentProvider( 3528): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3528): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3528): mCursor = null
,D/WifiService( 3528): setWifiEnabled: true pid=11922, uid=10474
E/WifiService( 3528): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3528): Permission Denial: getCurrentUser() from pid=11922, uid=10474 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3528): Failed getting userId using ActivityManagerNative
W/WifiService( 3528): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11922, uid=10474 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3528): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3528): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3528): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3528): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3528): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3528): name = wifi_on
I/WifiService( 3528): disconnect: pid=11922, uid=10474
,I/wpa_supplicant( 3833): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11922): Radios toggled
I/jxcore-log(11922): 
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3528): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): Disconnected - do not scan
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3528): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3528): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3528): do suspend true
,D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.124/24 (Unknown error -1)
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiStateMachine( 3528): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/Hs20UtilService( 4072): Starting #8
I/Hs20UtilService( 4072): Message received 5007
,D/NearbySettings(11990): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(11990): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings(11990): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3528): New client listening to asynchronous messages
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
,E/WifiStateMachine( 3528): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3833): First Scan Start
,V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
E/WifiStateMachine( 3528): ConnectModeState: Network connection lost 
E/WifiStateMachine( 3528): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3528): do suspend true
,I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
,D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3528): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 3528): Not allowed due to - mEnabled false
D/ConnectivityService( 3528): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker( 3528): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3528): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3984): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - currTime: 1449681469300
D/WifiStateMachine( 3528): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
D/ConnectivityManager.CallbackHandler( 6826): CM callback handler got msg 524292
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3528): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/EntConnectivity( 3528): Not allowed due to - mEnabled false
D/Tethering( 3528): MasterInitialState.processMessage what=3
D/ConnectivityService( 3528): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3528): updateIfacesLocked()
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
V/NetworkStats( 3528): performPollLocked() took 3ms
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,I/Hs20UtilService( 4072): Starting #9
,I/Hs20UtilService( 4072): Message received 5007
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
,D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3528): updateDataUsageMap
,I/ApplicationPolicy( 3528): updateDataUsageMap  idList is null 
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/GpsLocationProvider( 3528): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,W/SLocation( 3528): No Active Data Connection
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12029): MountEmulatedStorage()
,E/Zygote  (12029): v2
I/libpersona(12029): KNOX_SDCARD checking this for 10110
I/libpersona(12029): KNOX_SDCARD not a persona
I/SELinux (12029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=12029 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12029): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12029): TimaSignature is unavailable
,D/ActivityThread(12029): Added TimaKeyStore provider
,D/ResourcesManager(12029): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/ACRA    (12029): ACRA is enabled for com.facebook.appmanager, intializing...
I/DexLibLoader(12029): not using cross-dex optimization: ART in use
I/art     (12029): Thread[1,tid=12029,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
V/DexLibLoader(12029): about to lock: /data/data/com.facebook.appmanager/mdex_lock
V/DexLibLoader(12029): locking /data/data/com.facebook.appmanager/mdex_lock took 0 ms
V/DexLibLoader(12029): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(12029): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
D/DexLibLoader(12029): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (12029): Attempt to remove local handle scope entry from IRT, ignoring
D/DexLibLoader(12029): loading pre-built fallback odex files
,V/MultiDexClassLoader(12029): installing MultiDexClassLoader before application classloader
D/DexLibLoader(12029): released odex store lock
D/DexLibLoader(12029): DexLibLoader.loadAll took 22 ms
,W/ca      (12029): Verify
,W/LightSharedPreferencesImpl(12029): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(12029): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12029): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(12029): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(12029): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(12029): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(12029): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(12029): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(12029): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(12029): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(12029): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(12029): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(12029): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(12029): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(12029): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(12029): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(12029): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(12029): 	... 10 more
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12054): MountEmulatedStorage()
E/Zygote  (12054): v2
I/libpersona(12054): KNOX_SDCARD checking this for 1000
I/libpersona(12054): KNOX_SDCARD not a persona
,I/SELinux (12054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 10254:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(12029): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(12029): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(12054): TimaSignature is unavailable
,D/ActivityThread(12054): Added TimaKeyStore provider
,D/ResourcesManager(12054): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(12054): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12054): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12054): new DMDBOpenHelper instance
,W/appmanager(:<default>):QuickExperimentControllerImpl(12029): Exposure of experiment com.facebook.common.network.l@3b881bac occurred when no user was logged in
,I/PCWCLIENTTRACE_PushUtil(12054): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12054): sales region : global
I/PCWCLIENTTRACE_PushUtil(12054): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12054): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(12054): noConnectivity : true
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12077): MountEmulatedStorage()
,E/Zygote  (12077): v2
I/libpersona(12077): KNOX_SDCARD checking this for 10135
I/libpersona(12077): KNOX_SDCARD not a persona
I/SELinux (12077): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12077): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12077): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12077 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 9836:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/BroadcastQueue( 3528): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2ceb1d98 u0 ReceiverList{3c3cdb7b 12029 com.facebook.appmanager/10110/u0 remote:13d7270a}}
,W/BroadcastQueue( 3528): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2ceb1d98 u0 ReceiverList{3c3cdb7b 12029 com.facebook.appmanager/10110/u0 remote:13d7270a}}
,D/TimaKeyStoreProvider(12077): TimaSignature is unavailable
,D/ActivityThread(12077): Added TimaKeyStore provider
,D/ResourcesManager(12077): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3528): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{c771629 u0 ReceiverList{1a6c07b0 12029 com.facebook.appmanager/10110/u0 remote:2553ef3}}
,I/MusicStore(12077): Database version: 104
,D/ResourcesManager(12077): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12077): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12077): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12077): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12077): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12077): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d8c36ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12077): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12077): GMSCore installation verified
,I/ConfigStore(12077): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12077): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/ContextImpl(12029): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12029): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(12077): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12077): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(12029): Exposure of experiment com.facebook.imagepipeline.a.g@18781018 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(12029): Exposure of experiment com.facebook.imagepipeline.a.d@de52cad occurred when no user was logged in
D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3528): getStreamVolume 3 index 0
,I/MediaRouter(12077): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3833): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 3833): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3833): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3833): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3528): [1,449,681,470,359 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3528): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@155cd425 sup_state=SCANNING debouncing=false
,E/Zygote  (12111): MountEmulatedStorage()
E/Zygote  (12111): v2
I/libpersona(12111): KNOX_SDCARD checking this for 10002
I/libpersona(12111): KNOX_SDCARD not a persona
,I/SELinux (12111): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/art     (12029): Explicit concurrent mark sweep GC freed 44392(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 28MB/36MB, paused 904us total 24.129ms
I/SELinux (12111): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12111): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12111 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,V/analytics4a(12029): JNI_OnLoad called
I/NetworkMonitor(12077): type=WIFI subType= reason=null isConnected=false
V/analytics4a(12029): JNI_OnLoad complete
,D/TimaKeyStoreProvider(12111): TimaSignature is unavailable
,D/ActivityThread(12111): Added TimaKeyStore provider
,I/ActivityManager( 3528): Killing 11279:com.policydm/1000 (adj 15): bgCount ##31
W/appmanager(:<default>):m(12029): No feature status reporters found; is this dead code?
,D/ResourcesManager(12111): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3528): Killing 11262:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3528): setDetailed state send new extra info"NG700"
I/wpa_supplicant( 3833): Associated with C0.AA.48
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,E/Zygote  (12131): MountEmulatedStorage()
I/libpersona(12131): KNOX_SDCARD checking this for 1000
E/Zygote  (12131): v2
I/libpersona(12131): KNOX_SDCARD not a persona
I/SELinux (12131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3528): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3833): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/TimaKeyStoreProvider(12131): TimaSignature is unavailable
,D/ActivityThread(12131): Added TimaKeyStore provider
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3833): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3528): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,I/wpa_supplicant( 3833): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3833): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3833): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3833): Blacklist: Clear (temp) 
I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3528): Network connection established
,D/WifiNative-HAL( 3528): callSECApiVoid - ID [50]
,E/WifiStateMachine( 3528): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3528): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ResourcesManager(12131): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
D/ConnectivityService( 3528): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine( 3528): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): L2ConnectedState "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3528): hsengiv:checkWhatTypeOfNetwork and the value is false,
,E/ConnectivityService( 3528): updateNetworkInfo()
,D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3528): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3528): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2845): Setting iface cfg
,E/WifiStateMachine( 3528): Start Dhcp Watchdog 2
D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,I/DIAGMON_AGENT(12131): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12131): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12131): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12131): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12131): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3528): do suspend false
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
,D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12150): MountEmulatedStorage()
E/Zygote  (12150): v2
I/libpersona(12150): KNOX_SDCARD checking this for 10012
I/libpersona(12150): KNOX_SDCARD not a persona
,I/SELinux (12150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12150): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12150 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12150): TimaSignature is unavailable
,D/ActivityThread(12150): Added TimaKeyStore provider
,D/ResourcesManager(12150): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3528): Killing 11294:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11294/oom_score_adj; errno=22
,I/FOTA_Client(12150): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12150): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12150): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12166): MountEmulatedStorage()
E/Zygote  (12166): v2
I/libpersona(12166): KNOX_SDCARD checking this for 10021
I/libpersona(12166): KNOX_SDCARD not a persona
,I/SELinux (12166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12166 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3528): Killing 11165:com.google.android.apps.docs/u0a101 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11165/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12166): TimaSignature is unavailable
,D/ActivityThread(12166): Added TimaKeyStore provider
,D/ResourcesManager(12166): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:17:50 GMT+01:00 2015
,I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12166): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12166): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12166): StateImplV2(): networkChangeListener().END
,E/Zygote  (12183): MountEmulatedStorage()
I/libpersona(12183): KNOX_SDCARD checking this for 10038
E/Zygote  (12183): v2
I/libpersona(12183): KNOX_SDCARD not a persona
,I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12183 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3528): Killing 11312:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
,D/ActivityThread(12183): Added TimaKeyStore provider
,D/ResourcesManager(12183): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12183): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  (12198): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  (12198): version 5.5.6 starting
,E/dhcpcd  (12198): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/Zygote  (12200): MountEmulatedStorage()
I/libpersona(12200): KNOX_SDCARD checking this for 1000
E/Zygote  (12200): v2
I/libpersona(12200): KNOX_SDCARD not a persona
,I/SELinux (12200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 11360:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,E/lowmemorykiller( 2828): Error writing /proc/11360/oom_score_adj; errno=22
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8777(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 574us total 16.578ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 291us total 9ms
,I/dhcpcd  (12198): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12198): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12198): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12198): bssid match
I/dhcpcd  (12198): wlan0: rebinding lease of 192.168.1.124
D/TimaKeyStoreProvider(12200): TimaSignature is unavailable
,D/ActivityThread(12200): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 602us total 8.913ms
,D/ResourcesManager(12200): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12225): MountEmulatedStorage()
E/Zygote  (12225): v2
I/libpersona(12225): KNOX_SDCARD checking this for 10039
I/libpersona(12225): KNOX_SDCARD not a persona
,I/SELinux (12225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12225 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12225): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Killing 11395:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12225): TimaSignature is unavailable
,D/ActivityThread(12225): Added TimaKeyStore provider
,D/ResourcesManager(12225): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12225): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12225): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12225): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12225): PushLog.txt file is not deleted.
D/SPPClientService(12225): PushLog.txt file is not deleted.
D/SPPClientService(12225): ============PushLog. stop!
,I/SA      (11437): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11437): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11437): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11437): [SLFUCHKMGR] constructor called
,E/SPPClientService(12225): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11437): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11437): [OR] == isSIMCardReady false ==
,I/SA      (11437): [SCU] == networkStateCheck == false
I/SA      (11437): [OR] onReceive END
,I/ActivityManager( 3528): Killing 11343:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/lowmemorykiller( 2828): Error writing /proc/11343/oom_score_adj; errno=22
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/lowmemorykiller( 2828): Error writing /proc/11343/oom_score_adj; errno=22
,E/lowmemorykiller( 2828): Error writing /proc/11343/oom_score_adj; errno=22
,E/Zygote  (12245): MountEmulatedStorage()
I/libpersona(12245): KNOX_SDCARD checking this for 10067
E/Zygote  (12245): v2
I/libpersona(12245): KNOX_SDCARD not a persona
I/SELinux (12245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12245 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12245): TimaSignature is unavailable
,D/ActivityThread(12245): Added TimaKeyStore provider
,D/ResourcesManager(12245): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12245): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12245): Other Intent
,I/ActivityManager( 3528): Killing 11377:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/accuweather( 5225): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5225): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5225): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5225): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5225): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5225): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5225): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12261): MountEmulatedStorage()
I/libpersona(12261): KNOX_SDCARD checking this for 1000
E/Zygote  (12261): v2
I/libpersona(12261): KNOX_SDCARD not a persona
I/SELinux (12261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12261): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12261 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12261): TimaSignature is unavailable
,D/ActivityThread(12261): Added TimaKeyStore provider
,D/ResourcesManager(12261): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12261): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12261): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12261): premStatus:2
,I/KnoxUsageLogPro(12261): isEulaShown : false
I/KnoxUsageLogPro(12261): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12276): MountEmulatedStorage()
I/libpersona(12276): KNOX_SDCARD checking this for 10090
E/Zygote  (12276): v2
I/libpersona(12276): KNOX_SDCARD not a persona
I/SELinux (12276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12276): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12276 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11471:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12276): TimaSignature is unavailable
,D/ActivityThread(12276): Added TimaKeyStore provider
,D/ResourcesManager(12276): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12292): MountEmulatedStorage()
E/Zygote  (12292): v2
I/libpersona(12292): KNOX_SDCARD checking this for 10127
I/libpersona(12292): KNOX_SDCARD not a persona
,I/SELinux (12292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12292 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11507:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12292): TimaSignature is unavailable
,D/ActivityThread(12292): Added TimaKeyStore provider
,D/ResourcesManager(12292): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12292): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12292): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12292): stopCheckCategoryVersion
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12308): MountEmulatedStorage()
E/Zygote  (12308): v2
I/libpersona(12308): KNOX_SDCARD checking this for 10136
I/libpersona(12308): KNOX_SDCARD not a persona
,I/SELinux (12308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12308): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12308 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11523:com.samsung.helphub/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12308): TimaSignature is unavailable
,D/ActivityThread(12308): Added TimaKeyStore provider
,D/ResourcesManager(12308): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12308): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12308): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12308): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12308): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12308): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(12308): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12308): Loading: webviewchromium
,I/LibraryLoader(12308): Time to load native libraries: 3 ms (timestamps 1669-1672)
I/LibraryLoader(12308): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12308): Binding Chromium to main looper Looper (main, tid 1) {2dd59287}
,I/LibraryLoader(12308): Expected native library version number "",actual native library version number ""
I/chromium(12308): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12308): Initializing chromium process, renderers=0
,W/art     (12308): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12308): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12308): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12308): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid(12308): Requires BLUETOOTH permission
,I/NSApplication(12308): Starting up...
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12376): MountEmulatedStorage()
I/libpersona(12376): KNOX_SDCARD checking this for 10150
E/Zygote  (12376): v2
I/libpersona(12376): KNOX_SDCARD not a persona
I/SELinux (12376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12376 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11540:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12376): TimaSignature is unavailable
,D/ActivityThread(12376): Added TimaKeyStore provider
,D/ResourcesManager(12376): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12376): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12376): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12376): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12376): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12376): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12391): MountEmulatedStorage()
E/Zygote  (12391): v2
I/libpersona(12391): KNOX_SDCARD checking this for 10178
I/libpersona(12391): KNOX_SDCARD not a persona
,I/SELinux (12391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12391 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 3528): Killing 11624:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12391): TimaSignature is unavailable
,D/ActivityThread(12391): Added TimaKeyStore provider
,D/ResourcesManager(12391): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12391): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12391): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12391): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12391): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12391): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12391): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,E/Zygote  (12414): MountEmulatedStorage()
I/libpersona(12414): KNOX_SDCARD checking this for 10082
E/Zygote  (12414): v2
I/libpersona(12414): KNOX_SDCARD not a persona
,I/SELinux (12414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12414): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3528): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12414 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider(12414): TimaSignature is unavailable
,D/ActivityThread(12414): Added TimaKeyStore provider
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12430): MountEmulatedStorage()
I/libpersona(12430): KNOX_SDCARD checking this for 1000
E/Zygote  (12430): v2
I/libpersona(12430): KNOX_SDCARD not a persona
,I/SELinux (12430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12430 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3528): Killing 11641:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,I/ActivityManager( 3528): Killing 11658:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12430): TimaSignature is unavailable
,D/ActivityThread(12430): Added TimaKeyStore provider
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 50628(2MB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 49MB/65MB, paused 1.234ms total 80.358ms
,D/ResourcesManager(12414): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12430): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12414): onCreate
D/BadgeProvider(12414): DatabaseHelper
I/ActivityManager( 3528): Killing 11456:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
W/ActivityManager( 3528): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/BadgeProvider(12414): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/BadgeProvider(12414): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12414): sendNotify, [notify] : null
D/BadgeProvider(12414): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12414): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12414): update, [UpdateCount] : 1
D/Launcher.Model( 4002): reloadBadges entered.
I/iu.Environment( 6826): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 6826): num queued entries: 0
I/iu.UploadsManager( 6826): num updated entries: 0
I/iu.SyncManager( 6826): NEXT; no task
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/Zygote  (12448): MountEmulatedStorage()
I/libpersona(12448): KNOX_SDCARD checking this for 10013
E/Zygote  (12448): v2
I/libpersona(12448): KNOX_SDCARD not a persona
I/SELinux (12448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12448): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3528): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12448 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8768(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 321us total 9.879ms
D/TimaKeyStoreProvider(12448): TimaSignature is unavailable
D/ActivityThread(12448): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 345us total 8.549ms
D/ResourcesManager(12448): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 491us total 8.222ms
I/ActivityManager( 3528): Killing 11693:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
I/Hs20UtilService( 4072): Starting #10
I/Hs20UtilService( 4072): Message received 5007
D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
I/dhcpcd  (12198): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
I/dhcpcd  (12198): wlan0: leased 192.168.1.124 for 86400 seconds
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3528): do suspend true
D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3528): WifiStateMachine DHCP successful
E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3528): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3528): Not connected state, yet.
E/WifiStateMachine( 3528): VerifyingLinkState enter
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3528): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3528): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3528): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3528): callSECApiInt - ID [210]
E/WifiStateMachine( 3528): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3528): Adding iface wlan0 to network 503
D/WifiWatchdogStateMachine( 3528): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3528): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
I/Hs20UtilService( 4072): Starting #11
I/Hs20UtilService( 4072): Message received 5007
D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings(11990): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 3528): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService( 3528): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 3528): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3528): Unexpected mtu value: 0, wlan0
V/        ( 2845): QcRouteController
E/WifiStateMachine( 3528): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3528): Now, connected state.
E/WifiStateMachine( 3528): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
E/WifiStateMachine( 3528): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
V/        ( 2845): QcRouteController
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3528): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3528): callSECApiVoid - ID [212]
E/WifiStateMachine( 3528): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/WifiStateMachine( 3528): REQUEST_POWER_SAVE_ON
V/        ( 2845): QcRouteController
I/Hs20UtilService( 4072): Starting #12
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
I/Hs20UtilService( 4072): Message received 5007
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/        ( 2845): QcRouteController
I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
V/        ( 2845): QcRouteController
I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
V/        ( 2845): QcRouteController
I/Hs20UtilService( 4072): Starting #13
I/Hs20UtilService( 4072): Message received 5007
D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings(11990): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 3528): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3528): LTETest block dns file not exists
D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3528): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 3528):    accepting network in place of null
I/System.out( 3528): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 1000
E/CSLegacyTypeTracker( 3528): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3528): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 3984): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 3528): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3528): MasterInitialState.processMessage what=3
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/ConnectivityService( 3528): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity( 3528): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 6826): CM callback handler got msg 524290
I/WifiStateMachine( 3528): callSECApi what=220
D/WifiStateMachine( 3528): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
V/NetworkStats( 3528): updateIfacesLocked()
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NetworkStatsFactory( 3528): UpdateStatsForKnox
D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
V/NetworkStats( 3528): performPollLocked() took 8ms
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 3528): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528
D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
I/System.out( 3528): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:17:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449681472415], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449681472401]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Validated
D/ConnectivityService( 3528): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3528): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3528): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3528): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6826): CM callback handler got msg 524290
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3528): SmartBondingReceiver: wifi is connected
D/SmartBondingService( 3528): SmartBondingReceiver: wifi ap is not changed
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
,W/ResourceType( 5310): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5310): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6230): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/NetworkMonitor(12077): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil(12054): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12054): sales region : global
I/PCWCLIENTTRACE_PushUtil(12054): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12054): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3528): mCursor = null
,D/GpsLocationProvider( 3528): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12131): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12131): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client(12150): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12150): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12150): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:17:52 GMT+01:00 2015
,I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12166): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12166): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.521: (12166): StateImplV2(): networkChangeListener().START
,I/art     ( 4615): Explicit concurrent mark sweep GC freed 75398(4MB) AllocSpace objects, 43(1863KB) LOS objects, 34% free, 30MB/46MB, paused 909us total 36.728ms
,I/KLMS-2.4.521: (12166): NetworkChangeOperations(): uploadRequestLog().START 
,I/SO_AGENT(12183): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.4.521: (12166): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.4.521: (12166): StateImplV2(): networkChangeListener().END
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onDestroy()
,E/SPPClientService(12225): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11437): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11437): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11437): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11437): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11437): [OR] == isSIMCardReady false ==
,I/SA      (11437): [SCU] == networkStateCheck == true
I/SA      (11437): [DM] getCountryCodeFromCSC : PL
I/SA      (11437): isChinaCountryCode : false
I/SA      (11437): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11437): [OR] == networkStateCheck true ==
,I/SA      (11437): [OR] GetMyCountryZoneTask
I/SA      (11437): [OR] onReceive END
,I/SA      (11437): [SRS] prepareGetMyCountryZone
,I/SA      (11437): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      (11437): [SSP] query invoked
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      (11437): [TPMU] GetMccFromDB : null
I/SA      (11437): [SCU] getMccFromPreferece mcc = 260
I/SA      (11437): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver(12245): Other Intent
,D/accuweather( 5225): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 5225): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5225): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5225): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5225): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5225): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5225): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12261): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12261): premStatus:2
,I/KnoxUsageLogPro(12261): isEulaShown : false
I/KnoxUsageLogPro(12261): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12292): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12292): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12292): stopCheckCategoryVersion
,D/QuickConnect(12376): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12376): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12376): PeriphStartReceiver.onReceive - no need to start
,W/art     (11571): Attempt to remove local handle scope entry from IRT, ignoring
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,I/iu.Environment( 6826): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10147
,I/iu.UploadsManager( 6826): num queued entries: 0
,I/iu.UploadsManager( 6826): num updated entries: 0
I/iu.SyncManager( 6826): NEXT; no task
,D/WaitQueueForNetworkActivate(12448): notifyNetworkActivated
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12448): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3528): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12448): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12448): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12448): exit::IDLE
D/InitializeManagerStateMachine(12448): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12448): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12448): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12448): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12448): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12448): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12448): entry::SUCCESS
D/hcjo    (12448): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12448): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12448): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine(12448): exit::SUCCESS
D/InitializeManagerStateMachine(12448): entry::IDLE
,I/SA      (11437): [RC New] Execute method=[GET] start
,I/SA      (11437): [RC New] Security=[true]
,I/System.out(11437): Thread-1530(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11437): Thread-1530(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11437): Thread-1530(ApacheHTTPLog):isShipBuild true
I/System.out(11437): Thread-1530(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10045
,D/ConnectivityService( 3528): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/SSRM:n  ( 3528): SIOP:: AP = 270, PST = 241, CUR = 23
,I/SA      (11437): [RC New] [v2liruge] api execute + 637
I/SA      (11437): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out(11437): AsyncTask #1 calls detatch()
,I/SA      (11437): [TPMU] getNetworkMcc : 
,I/SA      (11437): [SCU] saveMccToPreferece Start
I/SA      (11437): [SCU] RegionMCC : 260
I/SA      (11437): [SSP] query invoked
,I/SA      (11437): [TPMU] GetMccFromDB : null
I/SA      (11437): [SCU] getMccFromPreferece mcc = 260
I/SA      (11437): [SCU] saveMccToPreferece End
,I/SA      (11437): [RC New] executeRequest [v2liruge] end. 657
I/SA      (11437): [RC New] Execute end
I/SA      (11437): [OR] GetMyCountryZoneTask mcc = 260
I/SA      (11437): [OR] GetMyCountryZoneTask Success
,I/jxcore-log(11922): Test app app.js loaded
I/jxcore-log(11922): 
,I/chromium(11922): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium(11922): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dhcpcd  (12198): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  (12198): wlan0: sendmsg: Cannot assign requested address
,D/WearableService( 4615): callingUid 10014, callindPid: 4615
,D/ResourcesManager(12077): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12077): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(12077): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12077): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12077): Conditions not met for autocaching.
I/MusicLeanback(12077): Stop autocaching.
,D/WearableClient(12077): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12077): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12077): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12077): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12077): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12077): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12077): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3502d7e3 that was originally bound here
E/ActivityThread(12077): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3502d7e3 that was originally bound here
E/ActivityThread(12077): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12077): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12077): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12077): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12077): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12077): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12077): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12077): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12077): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12077): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12077): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12077): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12077): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12077): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12077): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12077): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12077): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12077): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12077): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12077): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12077): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12077): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12077): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12077): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/WifiStateMachine( 3528): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine( 3528): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2849): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3528): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3528) eventTime = 366107
,D/PowerManagerService( 3528): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3528 (0x0)
D/PowerManagerService( 3528): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3528, ws=WorkSource{10060}) (elapsedTime=3484)
,I/GAV4    (12308): Thread[GAThread,5,main]: No campaign data found.
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:-196, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:81
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5609): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5609): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/WifiStateMachine( 3528): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3528): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 3528): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,V/        ( 2845): QcRouteController
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED,
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false,
,V/        ( 2845): QcRouteController
,W/NetworkManagementService( 3528): route cmd failed: 
W/NetworkManagementService( 3528): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3528): '
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3528): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3528): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3528): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
,D/ConnectivityService( 3528): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6826): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 6826): CM callback handler got msg 524295
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 3528): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(12054): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(12054): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(12054): ================================================
,I/CSTORAGE(12054):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(12054): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12054): [GetString-S]
,E/art     (12054): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(12054): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI(12054): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(12054): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(12054): sales region : global
,I/PCWCLIENTTRACE_PushUtil(12054): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(12054): [ensureRegistration] - No Samsung account
,I/dhcpcd  (12198): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 3528): waitForAlarm result :8
,W/ProcessCpuTracker( 3528): Skipping unknown process pid 12655
,E/Watchdog( 3528): !@Sync 12
,I/dhcpcd  (12198): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12198): wlan0: no IPv6 Routers available
,D/PreloadUpdateManagerStateMachine(12448): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12448): exit::IDLE
D/PreloadUpdateManagerStateMachine(12448): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12448): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  (12448): RestApi Request Add : 2307
,I/System.out(12448): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(12448): (HTTPLog)-Static: isShipBuild true
I/System.out(12448): (HTTPLog)-Thread-1715-221252149: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12448): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 503 for uid 10013
,D/SSRM:n  ( 3528): SIOP:: AP = 260, PST = 245, CUR = -196
,I/System.out(12448): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12448): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12448, getuid(): 10013
,I/qtaguid (12448): Untagging socket 26
,D/hcjo    (12448): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    (12448): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine(12448): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12448): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine(12448): entry::REQ_UPDATE_CHECK
,I/Volley  (12448): RestApi Request Add : 2315
,I/System.out(12448): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(12448): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid (12448): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 12448, getuid(): 10013
,I/qtaguid (12448): Untagging socket -1,
,I/qtaguid (12448): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid (12448): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger(12448): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine(12448): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine(12448): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine(12448): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12448): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine(12448): entry::FINISH
,D/PreloadUpdateManagerStateMachine(12448): exit::FINISH,
D/PreloadUpdateManagerStateMachine(12448): entry::IDLE
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:-47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5609): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5609): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 246, CUR = -47,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5609): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5609): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 330s ago
,V/AlarmManager( 3528): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3528): SIOP:: AP = 250, PST = 247, CUR = 6,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5609): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5609): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 13
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 247, CUR = 26
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5609): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5609): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11922): Toggling radios to false
I/jxcore-log(11922): 
,D/BluetoothAdapter(11922): disable()
,D/SettingsProvider( 3528): name = bluetooth_on
,D/BluetoothAdapterState( 5609): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5609): Setting state to 13
I/BluetoothAdapterState( 5609): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 5609): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5609): updateAdapterState state is 13
,I/BluetoothPbapService( 5609): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 5609): close() in, this: android.bluetooth.BluetoothSocket@97760a1, channel: 19, state: LISTENING
,D/BluetoothAdapterService( 5609): Autoconnection is available 
D/BluetoothAdapterService( 5609): updateAdapterState prevState = 12newState = 13
D/BluetoothSocket( 5609): close() this: android.bluetooth.BluetoothSocket@97760a1, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28cb4fa2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4cb62c6mSocket: android.net.LocalSocket@2dd59287 impl:android.net.LocalSocketImpl@31feb5b4 fd:FileDescriptor[72]
,D/BluetoothAdapterService( 5609): terminating service from this receiver
,D/BluetoothSocket( 5609): Closing mSocket: android.net.LocalSocket@2dd59287 impl:android.net.LocalSocketImpl@31feb5b4 fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 5609): onBluetoothDisable()
,D/SecContentProvider( 3528): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 5609): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5609): Scan Mode:20
,D/BluetoothAdapterState( 5609): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5609): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5609): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 5609): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 5609): cmd socket is not created
,E/bt-btm  ( 5609): btm_ble_start_auto_conn start : 0, 0
,D/btif_config_util( 5609): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 5609): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 5609): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5609): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5609): L2CAP - PSM: 0x001b not found for deregistration
,I/WifiManager(11922): packageName : com.test.thalitest
,D/SecContentProvider( 3528): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3528): uri = 20 selection = isWifiStateChangeAllowed
W/InputMethodManagerService( 3528): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3528): [BT Setting State] State =13
,D/SecContentProvider2( 3528): mCursor = null
,D/WifiService( 3528): setWifiEnabled: false pid=11922, uid=10474
E/WifiService( 3528): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3528): name = wifi_on
,D/BluetoothTile( 3693):  onBluetoothStateChange:
,D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 3693):  handleUpdatestate:false name:null
,I/jxcore-log(11922): Radios toggled
I/jxcore-log(11922): 
,I/SamsungIME( 4506): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
E/WifiStateMachine( 3528): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3833): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
E/WifiStateMachine( 3528): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
,I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3528): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3528): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothSocket( 5609): close() in, this: android.bluetooth.BluetoothSocket@328ae552, channel: 5, state: LISTENING
D/BluetoothSocket( 5609): close() this: android.bluetooth.BluetoothSocket@328ae552, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2232c3ee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@66ed023mSocket: android.net.LocalSocket@1eab7920 impl:android.net.LocalSocketImpl@1caa82d9 fd:FileDescriptor[74]
,D/BluetoothSocket( 5609): Closing mSocket: android.net.LocalSocket@1eab7920 impl:android.net.LocalSocketImpl@1caa82d9 fd:FileDescriptor[74]
,D/BluetoothTile( 3693):  handleUpdatestate:false name:null
I/BtOppRfcommListener( 5609): stopping Accept Thread
D/BluetoothSocket( 5609): close() in, this: android.bluetooth.BluetoothSocket@354e049e, channel: 12, state: LISTENING
D/BluetoothSocket( 5609): close() this: android.bluetooth.BluetoothSocket@354e049e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@109d9108, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27d44b7fmSocket: android.net.LocalSocket@79f074c impl:android.net.LocalSocketImpl@23b77395 fd:FileDescriptor[78]
D/BluetoothSocket( 5609): Closing mSocket: android.net.LocalSocket@79f074c impl:android.net.LocalSocketImpl@23b77395 fd:FileDescriptor[78]
,I/BtOppRfcommListener( 5609): BluetoothSocket listen thread finished
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/StatusBarManagerService( 3528): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3528): setIconVisibility slot=bluetooth visible=false
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3528): do suspend true
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,W/ContextImpl(11990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiP2pService( 3528): InactiveState{ what=143375 }
D/WifiP2pService( 3528): P2pEnabledState{ what=143375 }
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,V/NativeCrypto( 4615): Read error: ssl=0x9c20fe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 4615): SSL shutdown failed: ssl=0x9c20fe00: I/O error during system call, Broken pipe
,E/WifiStateMachine( 3528): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3528): updateNetworkInfo()
,D/ConnectivityService( 3528): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3528): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
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
,E/WifiStateMachine( 3528): scanCount==0 - aborting
,D/ConnectivityService( 3528): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10014
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): ValidatedState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): DefaultState{ when=0 what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out( 3528): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3528): Tagging socket 423 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3528, getuid(): 1000
,I/System.out( 3528): (HTTPLog)-Static: isSBSettingEnabled false
,E/WifiStateMachine( 3528): [1,449,681,519,810 ms] noteScanEnd no scan source
D/WifiScanningService( 3528): SCAN_AVAILABLE : 1
D/WifiP2pService( 3528): InactiveState{ what=131204 }
,D/WifiScanningService( 3528): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 3528): P2pEnabledState{ what=131204 }
D/RttService( 3528): SCAN_AVAILABLE : 1
,D/RttService( 3528): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService( 3528): sending p2p connection changed broadcast: FAILED
,D/LocalBluetoothProfileManager(11990): PANU : true
D/LocalBluetoothProfileManager(11990): Adding local MAP profile
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/BluetoothMap(11990): Create BluetoothMap proxy object
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3528): NetworkAgent: NetworkAgent channel lost
,D/WifiDisplayController( 3528): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3528): onP2pDisconnected
,D/IpRemoteDisplayController( 3528): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3528): WfdBridgeServer is already null
,D/WifiP2pService( 3528): sending p2p connection changed broadcast: DISCONNECTED
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 3528): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 3528): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/EntConnectivity( 3528): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): Validated
D/WifiDisplayController( 3528): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3528): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3528): disconnect
D/WifiDisplayController( 3528): updateConnection
D/WifiDisplayController( 3528): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/ConnectivityService( 3528): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3528): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 3984): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiP2pService( 3528): P2pDisablingState
D/ConnectivityManager.CallbackHandler( 6826): CM callback handler got msg 524292
,D/WifiP2pService( 3528): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 3528): p2p socket connection lost
D/CSLegacyTypeTracker( 3528): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3528): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiP2pService( 3528): P2pDisabledState
,E/WifiStateMachine( 3528): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,E/WifiStateMachine( 3528): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3528): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3528): do suspend true
,D/AllShareCastTile( 3693): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3528): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3693): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/WifiDisplayController( 3528): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3528): onP2pDisconnected
D/IpRemoteDisplayController( 3528): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3528): WfdBridgeServer is already null
,D/WifiP2pService( 3528): P2pDisabledState{ what=143375 }
D/WifiP2pService( 3528): DefaultState{ what=143375 }
,D/EntConnectivity( 3528): Not allowed due to - mEnabled false
E/ConnectivityService( 3528): updateNetworkInfo()
D/ConnectivityService( 3528): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3528): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
E/ConnectivityService( 3528): updateNetworkInfo()
D/Tethering( 3528): MasterInitialState.processMessage what=3
,V/NetworkStats( 3528): updateIfacesLocked()
V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,V/NetworkStats( 3528): performPollLocked() took 6ms
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
V/NetworkStats( 3528): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,W/bt-l2cap( 5609): btif_mce_execute_service enable:0
,W/bt-l2cap( 5609): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5609): L2CAP - PSM: 0x001b not found for deregistration
,W/bt-l2cap( 5609): L2CAP - PSM: 0x0019 not found for deregistration
D/SmartBondingService( 3528): getNetworkEnabled : wifi : true mobile : false
W/bt-l2cap( 5609): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5609): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5609): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5609): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5609): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5609): HC lpm_result_cb 0
W/bt-btif ( 5609): ag scb idx 2 not allocated
E/bt-btif ( 5609): BTA AG is already disabled, ignoring ...
D/bt_userial( 5609): RX termination
W/bt_userial( 5609): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 5609): Leaving userial_read_thread()
,D/bt_userial( 5609): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 5609): hw_epilog_process
I/bt_userial_vendor( 5609): device fd = 65 close
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
I/GKI_LINUX( 5609): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 5609): GKI_exit_task 0 done
I/GKI_LINUX( 5609): GKI_shutdown(): task [BTU] terminated
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/BluetoothAdapterState( 5609): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5609): isSecureModeOn:false
D/BluetoothAdapterService( 5609): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/StatusBar.NetworkController( 3693): applyOpen
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.gatt.GattService
,E/WifiStateMachine( 3528): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/StatusBar.NetworkController( 3693): applyOpen
W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
E/WifiStateMachine( 3528): stopping supplicant
I/wpa_supplicant( 3833): p2p0: State: DISCONNECTED -> DISCONNECTED
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 5609): handleDebugAction() action=null
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/BtGatt.GattService( 5609): Received stop request...Stopping profile...
D/BtGatt.GattService( 5609): stop()
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
D/BtGatt.AdvertiseManager( 5609): advertise clients cleared
W/ContextImpl(11990): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,E/WifiStateMachine( 3528): setWifiState: disabling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller( 3528): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,D/Bluetoothsap(11990): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager(11990): LocalBluetoothProfileManager construction complete
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SecContentProvider2( 3528): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3528): mCursor = null
D/SmartBondingService( 3528): getNetworkEnabled : wifi : false mobile : false
,D/SLocation( 3528): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(0)
,D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
,D/HotspotTile( 3693): onReceive : 0, 0
,D/HeadsetService( 5609): Received stop request...Stopping profile...
,W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.hid.HidService
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,D/DockEventReceiver(11990): finishStartingService: stopping service
,D/AudioService( 3528): onServiceDisconnected: Bluetooth profile: 1
W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/BluetoothPan(11990): BluetoothPAN Proxy object connected
D/PanProfile(11990): Bluetooth service connected
W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5609): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothNotiBroadcastReceiver(11990): onReceive
,D/BluetoothMap(11990): Proxy object connected
D/MapProfile(11990): Bluetooth service connected
D/Bluetoothsap(11990): BluetoothSAP Proxy object connected
,W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5609): Not skipping com.broadcom.bt.service.sap.SapService
,D/SapProfile(11990): Bluetooth service connected
D/Bluetoothsap(11990): getConnectedDevices()
,W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5609): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5609): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5609): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5609): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5609): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5609): Stopping profile services that were post enabled
E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 5609): Received stop request...Stopping profile...
V/Avrcp   ( 5609): doQuit
,D/A2dpStateMachine( 5609): Exit Disconnected: -1
,D/Avrcp   ( 5609): Unregistering previous receiver
,D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,D/BluetoothA2dp( 3528): Proxy object disconnected
D/AudioService( 3528): onServiceDisconnected: Bluetooth profile: 2
,D/HidService( 5609): Received stop request...Stopping profile...
D/BluetoothA2dp( 5027): Proxy object disconnected
,D/HidService( 5609): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5609): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5609): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5609): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,I/wpa_supplicant( 3833): Blacklist: Clear (all) 
,E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5609): Profile still running: com.android.bluetooth.hid.HidService
,D/HealthService( 5609): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,W/BluetoothHeadsetServiceJni( 5609): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5609): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 5609): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,D/BluetoothPan(11990): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 3528): BluetoothPAN Proxy object disconnected
,D/BluetoothMapService( 5609): Received stop request...Stopping profile...
D/PanProfile(11990): Bluetooth service disconnected
,D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,D/BluetoothMap(11990): Proxy object disconnected
,D/MapProfile(11990): Bluetooth service disconnected
,D/SapService( 5609): Received stop request...Stopping profile...
D/SapService( 5609): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5609): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@259846c7
,D/AuthorizationBluetoothService( 4615): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/Bluetoothsap(11990): BluetoothSAP Proxy object disconnected
D/SapProfile(11990): Bluetooth service disconnected
D/BluetoothAdapterService( 5609): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5609): Proxy object disconnected
D/BluetoothAdapterService( 5609): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 5609): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 5609): GKI_exit_task 2 done
I/GKI_LINUX( 5609): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5609): cleanup
E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5609): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5609): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5609): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5609): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5609): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5609): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5609): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5609): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5609): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(630736583)( 5609): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 5609): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5609): Setting state to 10
I/BluetoothAdapterState( 5609): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5609): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5609): updateAdapterState state is 10
W/BluetoothSAPServiceJni( 5609): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5609): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService( 5609): Autoconnection is available 
D/BluetoothAdapterService( 5609): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5609): Entering OffState
D/BluetoothMap(11990): onBluetoothStateChange: up=false
,D/Bluetoothsap(11990): onBluetoothStateChange: up=false
D/Bluetoothsap(11990): Unbinding service...
I/Hs20UtilService( 4072): Starting #14
,I/Hs20UtilService( 4072): Message received 5007
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 5609): onBluetoothStateChange: up=false
,D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/BluetoothA2dp( 3528): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/BluetoothPbap(11990): onBluetoothStateChange: up=false
I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
,V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,I/wpa_supplicant( 3833): p2p0: CTRL-EVENT-TERMINATING 
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,I/wpa_supplicant( 3833): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3833): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3833): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3833): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/BluetoothA2dp( 5027): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 3528): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BluetoothManagerService( 3528): Broadcasting onBluetoothServiceUp() to 0 receivers.
,V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
,W/InputMethodManagerService( 3528): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3528): [BT Setting State] State =10
I/InputMethodManagerService( 3528): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 3693): 878267129: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3693):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 3693): 878267129: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 3693): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3693): 878267129: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3693): 878267129: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3693): 878267129: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 3528): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/STATUSBAR-QSTileView( 3693): onStateChanged: Bluetooth
,D/StatusBarManagerService( 3528): setIconVisibility slot=bluetooth visible=false
I/SamsungIME( 4506): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothAdapter( 4615): 588547424: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4615): 588547424: getState() :  mService = null. Returning STATE_OFF
,D/PhoneStatusBar( 3693): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,V/BluetoothEventManager(11990): Received android.bluetooth.adapter.action.STATE_CHANGED
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12805): MountEmulatedStorage()
E/Zygote  (12805): v2
I/libpersona(12805): KNOX_SDCARD checking this for 10079
I/libpersona(12805): KNOX_SDCARD not a persona
,I/SELinux (12805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12805 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/GKI_LINUX( 5609): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 5609): GKI_exit_task 1 done
I/GKI_LINUX( 5609): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5609): cleanupNative: return from cleanup
E/SELinux (12805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3833): Blacklist: Clear (all) 
,I/art     ( 5609): System.exit called, status: 0
I/AndroidRuntime( 5609): VM exiting with result code 0, cleanup skipped.
,D/TimaKeyStoreProvider(12805): TimaSignature is unavailable
,D/ActivityThread(12805): Added TimaKeyStore provider
,I/ActivityManager( 3528): Process com.android.bluetooth (pid 5609)(adj 0) has died(122,1200)
,D/ResourcesManager(12805): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(12805): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3528): Killing 11709:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/Hs20UtilService( 4072): Starting #15
,I/Hs20UtilService( 4072): Message received 5007
,D/NearbySettings(11990): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings(11990): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11990): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11990): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11990): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11990): MountReceiver.mPrefHandler - 7002
,I/SignOutReceiver(11604): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4072): Starting #16
,I/Hs20UtilService( 4072): Message received 5011
,D/KeyguardWallpaperUpdator(12292): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12292): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12292): stopCheckCategoryVersion
,I/SignOutReceiver(11604): WIFI_STATE_CHANGED_ACTION
,W/ContextImpl(11990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver(11990): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver(11990): onReceive
,E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12823): MountEmulatedStorage()
E/Zygote  (12823): v2
I/libpersona(12823): KNOX_SDCARD checking this for 1002
I/libpersona(12823): KNOX_SDCARD not a persona
,I/SELinux (12823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3528): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12823 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
I/SELinux (12823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12823): TimaSignature is unavailable
,D/ActivityThread(12823): Added TimaKeyStore provider
,D/ResourcesManager(12823): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(12823): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager(12823): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ConnectivityService( 3528): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3528): updateDataUsageMap
,I/ApplicationPolicy( 3528): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3528): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
D/SmartBondingService( 3528): getSBEnabled() enabled =false
,D/GpsLocationProvider( 3528): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : false mobile : false
,W/SLocation( 3528): No Active Data Connection
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/BluetoothA2dpSinkServiceJni(12823): register_com_android_bluetooth_a2dp_sink
,I/DBG_DM  ( 6230): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/NetworkMonitor(12077): type=WIFI subType= reason=null isConnected=false
,D/BtSettings.ProfileConfig(12823): Adding GattService
,D/BtSettings.ProfileConfig(12823): Adding HeadsetService
D/BtSettings.ProfileConfig(12823): Adding A2dpService
D/BtSettings.ProfileConfig(12823): Adding HidService
D/BtSettings.ProfileConfig(12823): Adding HealthService
,D/BtSettings.ProfileConfig(12823): Adding PanService
D/BtSettings.ProfileConfig(12823): Adding BluetoothMapService
D/BtSettings.ProfileConfig(12823): Adding SapService
D/BtSettings.ProfileConfig(12823): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12823): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12823): Adding SapClientService
,D/BtSettings.ProfileConfig(12823): Adding HidDevService
I/BtSettings.ProfileConfig(12823): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,D/SettingsProvider( 3528): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 3528): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3528): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3528): selectionArgs: false
D/SettingsProvider( 3528): selectionArgs: 1002
D/SecContentProvider( 3528): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3528): ret = -1
,I/ActivityManager( 3528): Killing 11106:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,D/AuthorizationBluetoothService( 4615): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/PCWCLIENTTRACE_PushUtil(12054): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(12054): sales region : global
I/PCWCLIENTTRACE_PushUtil(12054): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(12054): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(12054): noConnectivity : true
,I/DIAGMON_AGENT(12131): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12131): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/Tethering( 3528): InitialState.processMessage what=4
,I/wpa_supplicant( 3833): wlan0: CTRL-EVENT-TERMINATING 
,E/Tethering( 3528): No numeric data
,E/WifiStateMachine( 3528): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3528): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/FOTA_Client(12150): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/Tethering( 3528): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 3528): Supplicant connection lost
,V/NetworkStats( 3528): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/HotspotTile( 3693): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3693): updateTetherState():false, false
D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,V/NetworkStats( 3528): performPollLocked() took 6ms
D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,I/FOTA_Client(12150): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/WifiStateMachine( 3528): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL( 3528): callSECApiBoolean - ID [21]
E/WifiStateMachine( 3528): setWifiState: disabled
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3528): currentTimeMillis() cache hit
,D/SmartBondingService( 3528): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService( 3528): getNetworkEnabled : wifi : false mobile : false
D/SLocation( 3528): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=false enabledDesc:null
,I/FOTA_Client(12150): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
D/STATUSBAR-WifiQuickSettingButton( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3693): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 3693): onStateChanged: Wi-Fi
D/HotspotTile( 3693): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 3693): onReceive : 1, 0
,W/Settings( 4615): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:18:40 GMT+01:00 2015
,I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12166): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/art     ( 3528): Explicit concurrent mark sweep GC freed 82156(4MB) AllocSpace objects, 22(400KB) LOS objects, 24% free, 49MB/65MB, paused 2.275ms total 152.231ms
,I/KLMS-2.4.521: (12166): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12166): StateImplV2(): networkChangeListener().END
,I/SO_AGENT(12183): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,I/KLMS-2.4.521: (12166): KLMSIntentService(): onDestroy()
,E/SPPClientService(12225): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      (11437): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11437): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11437): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11437): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11437): [OR] == isSIMCardReady false ==
E/SPPClientService(12225): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11437): [SCU] == networkStateCheck == false
I/SA      (11437): [OR] onReceive END
,V/DownloadManager( 3715): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SCloudBackupReceiver(12245): Other Intent
,D/accuweather( 5225): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 5225): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5225): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5225): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5225): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5225): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5225): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12261): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12261): premStatus:2
,I/KnoxUsageLogPro(12261): isEulaShown : false
I/KnoxUsageLogPro(12261): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12292): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12292): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12292): stopCheckCategoryVersion
,D/QuickConnect(12376): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12376): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12376): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,D/RCPManagerService( 3528): exchangeData() failure , invalid userId
,E/WifiStateMachine( 3528): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/iu.Environment( 6826): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6826): num queued entries: 0
,I/iu.UploadsManager( 6826): num updated entries: 0
,I/iu.SyncManager( 6826): NEXT; no task
,I/Hs20UtilService( 4072): Starting #17
,I/Hs20UtilService( 4072): Message received 5011
,D/KeyguardWallpaperUpdator(12292): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12292): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12292): stopCheckCategoryVersion
,I/SignOutReceiver(11604): WIFI_STATE_CHANGED_ACTION
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 245, CUR = 30,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 245, CUR = 29
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :8
,E/Watchdog( 3528): !@Sync 14
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 245, CUR = 29
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 245, CUR = 26,
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 390s ago
,I/PowerManagerService( 3528): [PWL]   PowerManagerService.WakeLocks: ref count=1,
,I/PowerManagerService( 3528): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 3528): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3528, ws=null) (elapsedTime=42835),
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 245, CUR = 25
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 15
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 242, CUR = 24
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService( 3528): Failed to find a new network - expiring NetTransition Wakelock
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 241, CUR = 24
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3528): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 16
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 23
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 22
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 21
,I/PowerManagerService( 3528): [PWL] Off : 455s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 17
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 19
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 19,
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 18
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 19
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 18
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 19
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 18
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3528): [PWL] Off : 525s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 240, PST = 240, CUR = 18
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 239, CUR = 18,
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3528): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 238, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 237, CUR = 16
,W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 237, CUR = 17
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 21
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 236, CUR = 16
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 18
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 600s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 17
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 22
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 235, CUR = 17
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 234, CUR = 17,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 15
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 23
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 14,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 233, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 13
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 24
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 232, CUR = 15
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 680s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 25
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 231, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 26
,V/AlarmManager( 3528): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/LightsService( 3528): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3528): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3528): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3528): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3528): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3528): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3528): unregisterListener ::   
D/LightsService( 3528): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 14
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 27
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,I/PowerManagerService( 3528): [PWL] Off : 765s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11,
,V/AlarmManager( 3528): waitForAlarm result :8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 28
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 29
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 30
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3528): [PWL] Off : 855s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 13,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 31
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3528): Skipping unknown process pid 13210
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 32
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 33
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 950s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 12
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 34
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3528): !@Sync 35
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,E/Watchdog( 3528): !@Sync 36
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,I/PowerManagerService( 3528): [PWL] Off : 1050s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3528): !@Sync 37
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3528): !@Sync 38
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,E/Watchdog( 3528): !@Sync 39
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3528): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3528): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3528): Updating Usage Statistics in DB @ 1449682321205
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3528): 	at com.android.server,.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB,
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
,W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3528): ::getAppControlDB: Exception to create DB
W/System.err( 3528): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3528): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3528): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3528): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3528): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3528): Done Updating Usage Statistics in DB @ 1449682321265
,E/Watchdog( 3528): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3528): [PWL] Off : 1155s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3528): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 11,
,E/Watchdog( 3528): !@Sync 41
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 10
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3528): !@Sync 42
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,E/Watchdog( 3528): !@Sync 43
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,I/PowerManagerService( 3528): [PWL] Off : 1265s ago
,E/Watchdog( 3528): !@Sync 44
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8,
,E/Watchdog( 3528): !@Sync 45
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,E/Watchdog( 3528): !@Sync 46
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 47
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 9
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 1380s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 48
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 49
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3528): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ProcessCpuTracker( 3528): Skipping unknown process pid 13524
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 51
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 8,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3528): stay LED for fully charged
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 52
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 53
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 54
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 7
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-15
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 55
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,I/PowerManagerService( 3528): [PWL] Off : 1625s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 56
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 57
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,I/art     ( 3528): Background sticky concurrent mark sweep GC freed 79805(9MB) AllocSpace objects, 401(6MB) LOS objects, 13% free, 49MB/57MB, paused 3.184ms total 113.204ms
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 58
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 59
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5,
,V/AlarmManager( 3528): waitForAlarm result :4
,D/NetworkStatsFactory( 3528): UpdateStatsForKnox
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/LightsService( 3528): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3528): stay LED for fully charged
,I/Sensors ( 3528): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3528): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 6826): Aggregate from 1449680594667 (log), 1449680594667 (data)
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4615): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Sensors ( 3528): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/LightsService( 3528): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3528): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3528): unregisterListener ::   
D/LightsService( 3528): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3528): stay LED for fully charged
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3528): waitForAlarm result :8
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3528): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,I/PowerManagerService( 3528): [PWL] Off : 1755s ago
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 6
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 61
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-15
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 62
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 63
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 64
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 1890s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 65
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-11
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 66
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,D/BatteryService( 3528): stay LED for fully charged
I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-16
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 67
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4,
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged,
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:5, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 68
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 5
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3528): !@Sync 69
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3528): [PWL] Off : 2030s ago
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:4, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/TimaService( 3528): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3528): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3528): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3528): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3528): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3528): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 4
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,E/Watchdog( 3528): !@Sync 71
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/BatteryService( 3528): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 2
,D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3528): online:4, current avg:3, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3528): stay LED for fully charged
,I/MotionRecognitionService( 3528): Plugged
,I/MotionRecognitionService( 3528): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3528): SIOP:: AP = 230, PST = 230, CUR = 3
,TIME-OUT KILL (timeout was 1800000ms),E/Watchdog( 3528): !@Sync 72
D/BatteryService( 3528): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3528): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3528): online:4, current avg:2, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3528): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3528): Plugged
I/MotionRecognitionService( 3528): setPowerConnected  = true
D/BatteryService( 3528): stay LED for fully charged
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(13940): 
D/AndroidRuntime(13940): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13940): CheckJNI is OFF
D/AndroidRuntime(13940): readGMSProperty: start
D/AndroidRuntime(13940): readGMSProperty: already setted!!
D/AndroidRuntime(13940): readGMSProperty: end
D/AndroidRuntime(13940): addProductProperty: start
E/AffinityControl(13940): AffinityControl: registerfunction enter
D/AndroidRuntime(13940): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3528): START PACKAGE DELETE: observer{680608879}
D/PackageManager( 3528): pkg{<packageName>}
D/PackageManager( 3528): user{0}
D/PackageManager( 3528): caller{2000}
D/PackageManager( 3528): flags{3}
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3528): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3528): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3528): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3528): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3528): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3528): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3528): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3528): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3528): !@killApplicatoin: 10474, uninstall pkg
I/ActivityManager( 3528): Force stopping com.test.thalitest appid=10474 user=-1: uninstall pkg
I/ActivityManager( 3528): Killing 11922:com.test.thalitest/u0a474 (adj 0): stop com.test.thalitest
I/ActivityManager( 3528): Killing 12414:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1813s
I/ActivityManager( 3528): Killing 10439:com.android.vending/u0a31 (adj 15): empty for 1958s
I/ActivityManager( 3528):   Force finishing activity ActivityRecord{12fd51c6 u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3528): mDVFSHelper.acquire()
W/PackageSettings( 3528): Skipping PackageSetting{d6a8160 com.example.hello/10462} due to missing metadata
I/WindowState( 3528): WIN DEATH: Window{1f1b827c u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 2849): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
D/WifiService( 3528): Client connection lost with reason: 4
I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 3528): Force stopping com.test.thalitest appid=10474 user=0: pkg removed
I/ActivityManager( 3528):   Force finishing activity ActivityRecord{12fd51c6 u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3528): Duplicate finish request for ActivityRecord{12fd51c6 u0 com.test.thalitest/.MainActivity t26 f}
I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
I/ProcessStatsService( 3528): Prepared write state in 17ms
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/art     ( 8995): Explicit concurrent mark sweep GC freed 30939(1714KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.124ms total 51.169ms
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/ProcessStatsService( 3528): Prepared write state in 16ms
I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 7
W/libprocessgroup( 3528): failed to open /acct/uid_10031/pid_10439/cgroup.procs: No such file or directory
W/libprocessgroup( 3528): failed to open /acct/uid_10082/pid_12414/cgroup.procs: No such file or directory
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/art     ( 4057): Explicit concurrent mark sweep GC freed 33366(2MB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 1.288ms total 59.651ms
I/ProcessStatsService( 3528): Prepared write state in 16ms
I/art     ( 6826): Explicit concurrent mark sweep GC freed 32734(1891KB) AllocSpace objects, 5(80KB) LOS objects, 20% free, 31MB/39MB, paused 1.109ms total 98.036ms
I/DBG_DM  ( 6230): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/ProcessStatsService( 3528): Prepared write state in 13ms
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/InputReader( 3528): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 4506): mOCRHelper is null
D/SecContentProvider2( 3528): uri = 14 selection = getSealedState
D/SecContentProvider2( 3528): mCursor = null
W/GeofencerStateMachine( 4615): Ignoring removeGeofence because network location is disabled.
D/ApplicationPolicy( 3528): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3528): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/LWLocationManager(11676): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11676): getLastUiLocationId() : mLastUiLocationId = -100
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 7
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 6230): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6230): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6230): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6230): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
E/Zygote  (13959): MountEmulatedStorage()
I/libpersona(13959): KNOX_SDCARD checking this for 10063
E/Zygote  (13959): v2
I/libpersona(13959): KNOX_SDCARD not a persona
I/SELinux (13959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13959 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourceType( 5310): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5310): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/SELinux (13959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 3528): post active user change for 0
D/KnoxTimeoutHandler( 3528): postActiveUserChange for user 0
I/DBG_DM  ( 6230): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/SurfaceFlinger( 2849): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3528): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3528): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3528): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3528): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3528): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6230): updateVisibility : ActivityRecord{25101564 token=android.os.BinderProxy@3368b411 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 3528): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/TimaKeyStoreProvider(13959): TimaSignature is unavailable
D/ActivityThread(13959): Added TimaKeyStore provider
W/InputMethodManagerService( 3528): Got RemoteException sending setActive(false) notification to pid 11922 uid 10474
W/ContextImpl( 3528): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/art     ( 3528): Explicit concurrent mark sweep GC freed 46520(4MB) AllocSpace objects, 139(2MB) LOS objects, 24% free, 49MB/65MB, paused 1.928ms total 228.056ms
I/art     ( 3528): WaitForGcToComplete blocked for 224.884ms for cause Explicit
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/Timeline( 6230): Timeline: Activity_idle id: android.os.BinderProxy@3368b411 time:2175956
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/ActivityManager( 3528): mDVFSHelper.release()
I/Timeline( 3528): Timeline: Activity_windows_visible id: ActivityRecord{336525c6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:2175979
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(13959): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
D/VRSetupWizardStub/PackageIntentReceiver(13959): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13959): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13959): packagename:com.test.thalitest
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/SecContentProvider2( 3528): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3528): mCursor = null
I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 09 18:48:05 GMT+01:00 2015
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/KLMS-2.4.521: (12166): KLMSAbstractReciever(): onReceive().END.
D/RegisteredServicesCache( 3969): empty dynamic service
I/splitIntent( 3528): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3528): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12166): KLMSIntentService(): onCreate()
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.521: (12166): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.521: (12166): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/Zygote  (13980): MountEmulatedStorage()
E/Zygote  (13980): v2
I/libpersona(13980): KNOX_SDCARD checking this for 10106
I/libpersona(13980): KNOX_SDCARD not a persona
I/KLMS-2.4.521: (12166): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux (13980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/KLMS-2.4.521: (12166): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (12166): KLMSIntentService(): listeningToPackageRemoved().START
I/SELinux (13980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13980 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (13980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (12166): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider(13980): TimaSignature is unavailable
D/ActivityThread(13980): Added TimaKeyStore provider
D/RCPManager(12261):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3528):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3528): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
E/Zygote  (13996): MountEmulatedStorage()
E/Zygote  (13996): v2
I/libpersona(13996): KNOX_SDCARD checking this for 10050
I/libpersona(13996): KNOX_SDCARD not a persona
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/SELinux (13996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3528): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13996 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (13996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/SELinux (13996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/art     ( 3528): Explicit concurrent mark sweep GC freed 11098(626KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.580ms total 184.515ms
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(11676): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/Zygote  (14010): MountEmulatedStorage()
E/Zygote  (14010): v2
I/libpersona(14010): KNOX_SDCARD checking this for 10183
I/libpersona(14010): KNOX_SDCARD not a persona
I/SELinux (14010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=14010 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
E/SELinux (14010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/TimaKeyStoreProvider(13996): TimaSignature is unavailable
D/ResourcesManager( 3528): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Books/Books.apk
D/ActivityThread(13996): Added TimaKeyStore provider
I/KLMS-2.4.521: (12166): KLMSIntentService(): listeningToPackageRemoved().END
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/PackageManager( 3528): delete codoeFile: 
D/TimaKeyStoreProvider(14010): TimaSignature is unavailable
D/ActivityThread(14010): Added TimaKeyStore provider
D/ResourcesManager(13980): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/AASAUninstall( 3528):  com.test.thalitest not target!
D/PackageManager( 3528): result of delete: 1{680608879}
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/AndroidRuntime(13940): Shutting down VM
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/KLMS-2.4.521: (12166): KLMSIntentService(): onDestroy()
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(14010): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/elm:14491(13980): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(13980): ELMEngine.ELMEngine( context ).
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/elm:14491(13980): MDMBridge.setEnterpriseBridge()
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
E/Zygote  (14026): MountEmulatedStorage()
E/Zygote  (14026): v2
I/libpersona(14026): KNOX_SDCARD checking this for 10101
I/libpersona(14026): KNOX_SDCARD not a persona
I/SELinux (14026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/ActivityManager( 3528): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=14026 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager(11676): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11676): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11676): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11676): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/SELinux (14026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
E/SELinux (14026): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/SQLiteLog(14010): (284) automatic index on shooting_modes(title_id)
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/elm:14491(13980): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14491(13980): ElmAgentService : onCreate()
D/elm:14491(13980): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(13980): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13980): MDMBridge.getInstance()
D/elm:14491(13980): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(13980): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3528): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager(13996): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3528): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager(13996): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13996): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13996): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13996): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13996): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(14026): TimaSignature is unavailable
D/ActivityThread(14026): Added TimaKeyStore provider
W/ResourcesManager(13996): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13996): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13996): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/RCPManagerService( 3528): PackageReceiver onReceive()
I/HarmonyEASService( 3528): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3528): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/Zygote  (14043): MountEmulatedStorage()
I/libpersona(14043): KNOX_SDCARD checking this for 10019
E/Zygote  (14043): v2
I/libpersona(14043): KNOX_SDCARD not a persona
V/EnterpriseBillingPolicy( 3528): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3528): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3528): uID is 10474
D/JobSchedulerService( 3528): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3528): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3528): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3528): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3528): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3528): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3528): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3528): getBillingProfileForVpnEngine - end - null
I/SELinux (14043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=14043 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (14043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:14491(13980): ElmAgentService : onDestroy().
D/ResourcesManager(11676): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/KnoxTimeoutHandler( 3528): handleActiveUserChange for user 0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3528): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(14026): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(11676): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/TimaKeyStoreProvider(14043): TimaSignature is unavailable
D/ActivityThread(14043): Added TimaKeyStore provider
E/Zygote  (14059): MountEmulatedStorage()
E/Zygote  (14059): v2
I/libpersona(14059): KNOX_SDCARD checking this for 10190
I/libpersona(14059): KNOX_SDCARD not a persona
I/SELinux (14059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (14059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3528): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=14059 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (14059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar( 3693): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/ResourcesManager(11676): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/TaskPersister( 3528): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3528): removeObsoleteFile: deleting file=24_task.xml
D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
I/ActivityManager( 3528): Killing 12805:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##31
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider(14059): TimaSignature is unavailable
D/ActivityThread(14059): Added TimaKeyStore provider
D/DocsApplication(14026): Installing DEX configuration.
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(14043): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/DexInstaller(14026): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
I/PackageInfoHelper(14026): Provided clientMode=RELEASE, packageInfo=PackageInfo{fa6365c com.google.android.apps.docs}
D/TAG     (14026): onCreate()
D/CrossAppStateProvider(14026): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/com.sec.android.service.health.upgrade.UninstallReceiver(14043): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(14043): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(14043): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(14059): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/ResourcesManager(11676): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/LocationWidgetApplication(11676): getLastUiLocationId() : mLastUiLocationId = -100

```
