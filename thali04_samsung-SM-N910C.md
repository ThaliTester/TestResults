#### Test 56151093f3290d6_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime(11855): 
D/AndroidRuntime(11855): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11855): CheckJNI is OFF
D/AndroidRuntime(11855): readGMSProperty: start
D/AndroidRuntime(11855): readGMSProperty: already setted!!
D/AndroidRuntime(11855): readGMSProperty: end
D/AndroidRuntime(11855): addProductProperty: start
E/AffinityControl(11855): AffinityControl: registerfunction enter
D/AndroidRuntime(11855): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3529): inState():  stateMachine is null !!
I/PersonaManagerService( 3529): PersonaId don't exist
I/ActivityManager( 3529): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3529): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3529): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3529): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3529): mDVFSHelper.acquire()
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/Zygote  (11877): MountEmulatedStorage()
I/libpersona(11877): KNOX_SDCARD checking this for 10575
E/Zygote  (11877): v2
I/libpersona(11877): KNOX_SDCARD not a persona
I/SELinux (11877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3529): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11877 uid=10575 gids={50575, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (11877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11855): Shutting down VM
E/SELinux (11877): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3529): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3529): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3529): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3529): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11877): TimaSignature is unavailable
D/ActivityThread(11877): Added TimaKeyStore provider
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2848): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11877): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6224): updateVisibility : ActivityRecord{3d70c24a token=android.os.BinderProxy@1ddc071f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11877): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11877): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11877): Loading: webviewchromium
I/LibraryLoader(11877): Time to load native libraries: 4 ms (timestamps 5230-5234)
I/LibraryLoader(11877): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11877): Binding Chromium to main looper Looper (main, tid 1) {189d8a05}
I/LibraryLoader(11877): Expected native library version number "",actual native library version number ""
I/chromium(11877): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11877): Initializing chromium process, renderers=0
W/art     (11877): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11877): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11877): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11877): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11877): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11877): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11877): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11877): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11877): CordovaWebView is running on device made by: samsung
W/art     (11877): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11877): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11877): performCreate Call secproduct feature valuefalse
D/Activity(11877): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11877): Render dirty regions requested: true
D/ActivityManager( 3529): post active user change for 0
D/KnoxTimeoutHandler( 3529): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3529): handleActiveUserChange for user 0
I/SurfaceFlinger( 2848): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3529): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3529): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3529): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3529): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3529): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3529): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11877): Initialized EGL, version 1.4
I/OpenGLRenderer(11877): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278631664 
D/OpenGLRenderer(11877): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11877): Enabling debug mode 0
D/mali_winsys(11877): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11877): updateVisibility : ActivityRecord{a6dfe75 token=android.os.BinderProxy@1d23e050 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/InputMethodManagerService( 3529): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3529): mDVFSHelper.release()
I/Timeline( 3529): Timeline: Activity_windows_visible id: ActivityRecord{3dcfe6da u0 com.test.thalitest/.MainActivity t26} time:135572
W/IInputConnectionWrapper(11877): showStatusIcon on inactive InputConnection
I/Timeline(11877): Timeline: Activity_idle id: android.os.BinderProxy@1d23e050 time:135581
D/JsMessageQueue(11877): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(11877): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11877): 
D/jxcore_app_log(11877): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361622400
D/JX-Cordova(11877): jxcore cordova android initializing
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/art     (11877): Background sticky concurrent mark sweep GC freed 72015(7MB) AllocSpace objects, 14(2MB) LOS objects, 15% free, 35MB/42MB, paused 3.306ms total 125.553ms
,W/jxcore-log(11877): Initializing JXcore engine
W/jxcore-log(11877): JXcore engine is ready
,W/jxcore-log(11877): Starting JXcore engine
,E/auditd  ( 4592): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3529): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3529): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11877): Platform android
W/jxcore-log(11877): 
W/jxcore-log(11877): Process ARCH arm
W/jxcore-log(11877): 
,I/jxcore-log(11877): JXcore Cordova bridge is ready!
I/jxcore-log(11877): 
W/jxcore-log(11877): JXcore engine is started
,I/jxcore-log(11877): Toggling radios to true
I/jxcore-log(11877): 
,D/BluetoothAdapter(11877): enable()
,D/BluetoothAdapter(11877): enable(): BT is already enabled..!
,D/WifiService( 3529): New client listening to asynchronous messages
,I/WifiManager(11877): packageName : com.test.thalitest
,D/SecContentProvider( 3529): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3529): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3529): mCursor = null
,D/WifiService( 3529): setWifiEnabled: true pid=11877, uid=10575
E/WifiService( 3529): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3529): Permission Denial: getCurrentUser() from pid=11877, uid=10575 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3529): Failed getting userId using ActivityManagerNative
W/WifiService( 3529): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=11877, uid=10575 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3529): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3529): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3529): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3529): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3529): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3529): name = wifi_on
I/WifiService( 3529): disconnect: pid=11877, uid=10575
,I/wpa_supplicant( 3829): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log(11877): Radios toggled
I/jxcore-log(11877): 
,I/jxcore-log(11877): My device name is: samsung-SM-N910C
I/jxcore-log(11877): 
,I/wpa_supplicant( 3829): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3829): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3529): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 3829): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): Disconnected - do not scan
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine( 3529): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3529): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3529): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3529): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3529): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3529): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3529): do suspend true
,D/WifiP2pService( 3529): InactiveState{ what=143375 }
D/WifiP2pService( 3529): P2pEnabledState{ what=143375 }
,D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,V/NativeCrypto( 4634): Read error: ssl=0x9c20fe00: I/O error during system call, Connection timed out
,E/WifiStateMachine( 3529): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3529): updateNetworkInfo()
D/ConnectivityService( 3529): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 3529): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/ConnectivityService( 3529): updateNetworkInfo()
,D/ConnectivityService( 3529): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3529): evaluateTrafficStatsPolling
,V/NativeCrypto( 4634): SSL shutdown failed: ssl=0x9c20fe00: I/O error during system call, Broken pipe
,D/ConnectivityService( 3529): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
,I/Hs20UtilService( 4082): Starting #8
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): ValidatedState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): DefaultState{ when=-1ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine( 3529): Start Disconnecting Watchdog 1
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
I/wpa_supplicant( 3829): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3829): P2P: Current p2p state = IDLE
I/wpa_supplicant( 3829): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3829): First Scan Start
,I/wpa_supplicant( 3829): Scan requested (ret=0) - scan timeout 30 seconds
I/Hs20UtilService( 4082): Message received 5007
E/WifiStateMachine( 3529): ConnectModeState: Network connection lost 
,E/WifiStateMachine( 3529): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - processMessage - processMsg
E/WifiStateMachine( 3529): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3529): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3529): do suspend true
D/NearbySettings( 8775): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8775): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8775): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 8775): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
,V/NearbySettings( 8775): DMSUtil.isNetworkConnected - flag-null, state-null
,D/WifiP2pService( 3529): InactiveState{ what=143375 }
,D/WifiP2pService( 3529): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,I/System.out( 3529): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 3529): Tagging socket 419 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3529, getuid(): 1000
,I/System.out( 3529): (HTTPLog)-Static: isSBSettingEnabled false
,I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiService( 3529): New client listening to asynchronous messages
,I/NearbySettings( 8775): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8775): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8775): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener( 2844): Clearing all IP addresses on wlan0
,D/ConnectivityService( 3529): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
E/WifiStateMachine( 3529): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Validated
,D/EntConnectivity( 3529): Not allowed due to - mEnabled false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524292
D/WifiStateMachine( 3529): updateConfiguredNetworkExpiration - currTime: 1452862965523
D/ConnectivityService( 3529): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/SignOutReceiver(11531): NETWORK_STATE_CHANGED_ACTION
D/WifiStateMachine( 3529): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine( 3529): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine( 3529): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 3529): evaluateTrafficStatsPolling
E/WifiStateMachine( 3529): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3529): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/CSLegacyTypeTracker( 3529): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 3985): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 3529): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 3529): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3529): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3529): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3529): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 6642): CM callback handler got msg 524292
E/WifiStateMachine( 3529): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine( 3529): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine( 3529): setDetailed state send new extra info"NG700"
D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,D/Tethering( 3529): MasterInitialState.processMessage what=3
D/EntConnectivity( 3529): Not allowed due to - mEnabled false
D/ConnectivityService( 3529): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/SmartBondingService( 3529): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3529): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
,D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
V/NetworkStats( 3529): updateIfacesLocked()
V/NetworkStats( 3529): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 3529): UpdateStatsForKnox
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
V/NetworkStats( 3529): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/SmartBondingService( 3529): getNetworkEnabled : wifi : true mobile : false
,D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
,I/Hs20UtilService( 4082): Starting #9
V/NetworkStats( 3529): performPollLocked() took 7ms
,D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
I/Hs20UtilService( 4082): Message received 5007
,D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
,D/NearbySettings( 8775): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 8775): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8775): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8775): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8775): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
,I/SignOutReceiver(11531): NETWORK_STATE_CHANGED_ACTION
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/ConnectivityService( 3529): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 3529): updateDataUsageMap
I/ApplicationPolicy( 3529): updateDataUsageMap  idList is null 
,D/SmartBondingService( 3529): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3529): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getNetworkEnabled : wifi : true mobile : false
D/GpsLocationProvider( 3529): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation( 3529): No Active Data Connection
,I/DBG_DM  ( 6224): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 6224): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  (11968): MountEmulatedStorage()
E/Zygote  (11968): v2
I/libpersona(11968): KNOX_SDCARD checking this for 10110
I/libpersona(11968): KNOX_SDCARD not a persona
,I/SELinux (11968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3529): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.iorg.vpn.cleanup.NetworkStateMonitor: pid=11968 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (11968): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11968): TimaSignature is unavailable
,D/ActivityThread(11968): Added TimaKeyStore provider
,D/ResourcesManager(11968): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,I/PowerManagerService( 3529): [PWL] Off : 75s ago
I/PowerManagerService( 3529): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3529): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3529): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=3529, ws=null) (elapsedTime=607)
,D/ACRA    (11968): ACRA is enabled for com.facebook.appmanager, intializing...
,I/DexLibLoader(11968): not using cross-dex optimization: ART in use
,I/art     (11968): Thread[1,tid=11968,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.appmanager-2/lib/arm/libfbjni.so"
,V/DexLibLoader(11968): about to lock: /data/data/com.facebook.appmanager/mdex_lock
,V/DexLibLoader(11968): locking /data/data/com.facebook.appmanager/mdex_lock took 1 ms
V/DexLibLoader(11968): Secondary program dex metadata: classes2.dex 29f80981f469a774a4884b3db2df17e0be227159 secondary.dex01.Canary
D/DexLibLoader(11968): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex" is valid
,D/DexLibLoader(11968): directory "/data/data/com.facebook.appmanager/app_secondary_program_dex_opt" is valid
,W/art     (11968): Attempt to remove local handle scope entry from IRT, ignoring
,D/DexLibLoader(11968): loading pre-built fallback odex files
V/MultiDexClassLoader(11968): installing MultiDexClassLoader before application classloader
,D/DexLibLoader(11968): released odex store lock
D/DexLibLoader(11968): DexLibLoader.loadAll took 16 ms
,W/ca      (11968): Verify
,W/LightSharedPreferencesImpl(11968): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(11968): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11968): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(11968): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(11968): 	at com.facebook.crudolib.b.k.a(LightSharedPreferencesStorage.java:56)
W/LightSharedPreferencesImpl(11968): 	at com.facebook.crudolib.b.g.run(LightSharedPreferencesImpl.java:61)
W/LightSharedPreferencesImpl(11968): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(11968): 	at com.facebook.common.executors.dj.run(WrappingExecutorService.java:77)
W/LightSharedPreferencesImpl(11968): 	at com.facebook.common.executors.u.run(DefaultConstrainedListeningExecutorService.java:327)
W/LightSharedPreferencesImpl(11968): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(11968): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(11968): 	at com.facebook.common.executors.cc.run(NamedThreadFactory.java:42)
W/LightSharedPreferencesImpl(11968): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(11968): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(11968): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(11968): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(11968): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(11968): 	... 10 more
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11993): MountEmulatedStorage()
E/Zygote  (11993): v2
I/libpersona(11993): KNOX_SDCARD checking this for 1000
I/libpersona(11993): KNOX_SDCARD not a persona
,I/SELinux (11993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11993 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3529): Killing 9843:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
,W/appmanager(:<default>):b(11968): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b(11968): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(11993): TimaSignature is unavailable
,D/ActivityThread(11993): Added TimaKeyStore provider
,D/ResourcesManager(11993): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG(11993): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11993): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11993): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil(11993): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11993): sales region : global
I/PCWCLIENTTRACE_PushUtil(11993): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11993): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver(11993): noConnectivity : true
,W/appmanager(:<default>):QuickExperimentControllerImpl(11968): Exposure of experiment com.facebook.common.network.l@275ada3 occurred when no user was logged in
,W/BroadcastQueue( 3529): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2f3a8778 u0 ReceiverList{ea240db 11968 com.facebook.appmanager/10110/u0 remote:2c4745ea}}
,W/BroadcastQueue( 3529): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2f3a8778 u0 ReceiverList{ea240db 11968 com.facebook.appmanager/10110/u0 remote:2c4745ea}}
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12015): MountEmulatedStorage()
I/libpersona(12015): KNOX_SDCARD checking this for 10135
E/Zygote  (12015): v2
I/libpersona(12015): KNOX_SDCARD not a persona
I/SELinux (12015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12015): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=12015 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3529): Killing 11149:com.policydm/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12015): TimaSignature is unavailable
,D/ActivityThread(12015): Added TimaKeyStore provider
,D/ResourcesManager(12015): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/BroadcastQueue( 3529): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2a2f32bc u0 ReceiverList{26853eaf 11968 com.facebook.appmanager/10110/u0 remote:3e0b068e}}
,I/MusicStore(12015): Database version: 104
,D/ResourcesManager(12015): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (12015): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(12015): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (12015): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@234b009: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(12015): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(12015): GMSCore installation verified
,I/ConfigStore(12015): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12015): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11968): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
,W/ContextImpl(12015): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11968): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12015): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3529): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3529): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3529): getStreamVolume 3 index 0
,I/MediaRouter(12015): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,W/appmanager(:<default>):QuickExperimentControllerImpl(11968): Exposure of experiment com.facebook.imagepipeline.a.g@b8e2220 occurred when no user was logged in
,W/appmanager(:<default>):QuickExperimentControllerImpl(11968): Exposure of experiment com.facebook.imagepipeline.a.d@1e41b895 occurred when no user was logged in
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12050): MountEmulatedStorage()
I/libpersona(12050): KNOX_SDCARD checking this for 10002
E/Zygote  (12050): v2
I/libpersona(12050): KNOX_SDCARD not a persona
I/SELinux (12050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/wpa_supplicant( 3829): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 3829): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3829): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3829): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,I/SELinux (12050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12050): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine( 3529): [1,452,862,966,580 ms] noteScanEnd no scan source
,I/ActivityManager( 3529): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=12050 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (11968): Explicit concurrent mark sweep GC freed 47942(2MB) AllocSpace objects, 6(96KB) LOS objects, 22% free, 27MB/35MB, paused 2.430ms total 25.714ms
W/appmanager(:<default>):m(11968): No feature status reporters found; is this dead code?
,E/WifiStateMachine( 3529): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@2f0bae5e sup_state=SCANNING debouncing=false
,E/WifiStateMachine( 3529): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3529): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3529): setDetailed state send new extra info
,D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 611us total 11.577ms
,D/WifiDisplayAdapter( 3529): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 448us total 8.058ms
,I/NetworkMonitor(12015): type=WIFI subType= reason=null isConnected=false
,D/TimaKeyStoreProvider(12050): TimaSignature is unavailable
,D/ActivityThread(12050): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 402us total 8.659ms
,I/ActivityManager( 3529): Killing 11164:com.sec.android.provider.badge/u0a82 (adj 15): bgCount ##31
,D/ResourcesManager(12050): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager( 3529): Killing 11013:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12071): MountEmulatedStorage()
I/libpersona(12071): KNOX_SDCARD checking this for 1000
E/Zygote  (12071): v2
I/libpersona(12071): KNOX_SDCARD not a persona
I/SELinux (12071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/wpa_supplicant( 3829): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/ActivityManager( 3529): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=12071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 3829): Associated with C0.AA.48
,E/WifiStateMachine( 3529): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine( 3529): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine( 3529): setDetailed state send new extra info"NG700"
,D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
,D/TimaKeyStoreProvider(12071): TimaSignature is unavailable
,D/ActivityThread(12071): Added TimaKeyStore provider
,D/ResourcesManager(12071): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/wpa_supplicant( 3829): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3529): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3529): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 3829): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine( 3529): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine( 3529): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 3829): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3829): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 3829): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3829): Blacklist: Clear (temp) 
I/wpa_supplicant( 3829): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/art     ( 3529): Explicit concurrent mark sweep GC freed 59113(3MB) AllocSpace objects, 15(288KB) LOS objects, 24% free, 49MB/65MB, paused 1.634ms total 88.232ms
,E/WifiStateMachine( 3529): Network connection established
,D/WifiNative-HAL( 3529): callSECApiVoid - ID [50]
E/WifiStateMachine( 3529): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,E/WifiStateMachine( 3529): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/ConnectivityService( 3529): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine( 3529): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
D/ConnectivityService( 3529): hsengiv:checkWhatTypeOfNetwork and the value is false
E/WifiStateMachine( 3529): L2ConnectedState "NG700" nid=0
E/ConnectivityService( 3529): updateNetworkInfo()
E/WifiConfigStore( 3529): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService( 3529): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3529): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine( 3529): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3529): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore( 3529): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener( 2844): Setting iface cfg
,E/WifiStateMachine( 3529): Start Dhcp Watchdog 2
,D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
,I/DIAGMON_AGENT(12071): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/WifiStateMachine( 3529): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3529): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,I/DIAGMON_AGENT(12071): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(12071): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(12071): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT(12071): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/WifiStateMachine( 3529): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  ( 3529): do suspend false
,D/SecContentProvider2( 3529): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3529): mCursor = null
D/WifiP2pService( 3529): InactiveState{ what=143375 }
,D/WifiP2pService( 3529): P2pEnabledState{ what=143375 }
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12090): MountEmulatedStorage()
I/libpersona(12090): KNOX_SDCARD checking this for 10012
E/Zygote  (12090): v2
I/libpersona(12090): KNOX_SDCARD not a persona
I/SELinux (12090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12090): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=12090 uid=10012 gids={50012, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12090): TimaSignature is unavailable
,D/ActivityThread(12090): Added TimaKeyStore provider
,D/ResourcesManager(12090): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager( 3529): Killing 11204:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,I/FOTA_Client(12090): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/lowmemorykiller( 2827): Error writing /proc/11204/oom_score_adj; errno=22
I/FOTA_Client(12090): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12090): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12106): MountEmulatedStorage()
I/libpersona(12106): KNOX_SDCARD checking this for 10021
E/Zygote  (12106): v2
I/libpersona(12106): KNOX_SDCARD not a persona
,I/SELinux (12106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3529): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12106 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (12106): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Killing 11186:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11186/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12106): TimaSignature is unavailable
,D/ActivityThread(12106): Added TimaKeyStore provider
,D/ResourcesManager(12106): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12106): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:02:46 GMT+01:00 2016
,I/KLMS-2.4.521: (12106): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12106): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12106): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12106): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12106): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12106): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12106): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.521: (12106): StateImplV2(): networkChangeListener().END
,E/Zygote  (12122): MountEmulatedStorage()
E/Zygote  (12122): v2
I/libpersona(12122): KNOX_SDCARD checking this for 10038
I/libpersona(12122): KNOX_SDCARD not a persona
,I/SELinux (12122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12122): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3529): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=12122 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12106): KLMSIntentService(): onDestroy()
,I/ActivityManager( 3529): Killing 11246:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11246/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12122): TimaSignature is unavailable
,D/ActivityThread(12122): Added TimaKeyStore provider
,D/ResourcesManager(12122): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT(12122): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12138): MountEmulatedStorage()
I/libpersona(12138): KNOX_SDCARD checking this for 1000
E/Zygote  (12138): v2
I/libpersona(12138): KNOX_SDCARD not a persona
I/SELinux (12138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/dhcpcd  (12137): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/SELinux (12138): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  (12137): version 5.5.6 starting
,I/ActivityManager( 3529): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=12138 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3529): Killing 11281:com.wsomacp/u0a28 (adj 15): bgCount ##31
E/dhcpcd  (12137): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/TimaKeyStoreProvider(12138): TimaSignature is unavailable
,D/ActivityThread(12138): Added TimaKeyStore provider
,D/ResourcesManager(12138): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/dhcpcd  (12137): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  (12137): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  (12137): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  (12137): bssid match
I/dhcpcd  (12137): wlan0: rebinding lease of 192.168.1.124
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12164): MountEmulatedStorage()
,I/libpersona(12164): KNOX_SDCARD checking this for 10039
E/Zygote  (12164): v2
I/libpersona(12164): KNOX_SDCARD not a persona
I/SELinux (12164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12164): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=12164 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3529): Killing 11296:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/11296/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(12164): TimaSignature is unavailable
,D/ActivityThread(12164): Added TimaKeyStore provider
,D/ResourcesManager(12164): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(12164): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(12164): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService(12164): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/SPPClientService(12164): PushLog.txt file is not deleted.
D/SPPClientService(12164): PushLog.txt file is not deleted.
D/SPPClientService(12164): ============PushLog. stop!
,I/SA      (11340): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11340): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      (11340): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      (11340): [SLFUCHKMGR] constructor called
,E/SPPClientService(12164): [[SystemStateMonitorService]] No Active Internet
,I/SA      (11340): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11340): [OR] == isSIMCardReady false ==
,I/SA      (11340): [SCU] == networkStateCheck == false
I/SA      (11340): [OR] onReceive END
,I/ActivityManager( 3529): Killing 11220:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,V/DownloadManager( 5483): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12184): MountEmulatedStorage()
I/libpersona(12184): KNOX_SDCARD checking this for 10067
E/Zygote  (12184): v2
I/libpersona(12184): KNOX_SDCARD not a persona
,I/SELinux (12184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3529): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=12184 uid=10067 gids={50067, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (12184): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12184): TimaSignature is unavailable
,D/ActivityThread(12184): Added TimaKeyStore provider
,D/ResourcesManager(12184): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp(12184): sCloudBackupApp Version Info : 4.00.4.KK_APP
I/SCloudBackupReceiver(12184): Other Intent
,I/ActivityManager( 3529): Killing 11264:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
,D/accuweather( 5172): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5172): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 5172): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5172): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5172): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5172): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5172): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12200): MountEmulatedStorage()
E/Zygote  (12200): v2
I/libpersona(12200): KNOX_SDCARD checking this for 1000
I/libpersona(12200): KNOX_SDCARD not a persona
,I/SELinux (12200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=12200 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12200): TimaSignature is unavailable
,D/ActivityThread(12200): Added TimaKeyStore provider
,D/ResourcesManager(12200): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12200): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro(12200): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro(12200): premStatus:2
,I/KnoxUsageLogPro(12200): isEulaShown : false
I/KnoxUsageLogPro(12200): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12215): MountEmulatedStorage()
E/Zygote  (12215): v2
I/libpersona(12215): KNOX_SDCARD checking this for 10090
I/libpersona(12215): KNOX_SDCARD not a persona
,I/SELinux (12215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12215): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=12215 uid=10090 gids={50090, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3529): Killing 11379:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12215): TimaSignature is unavailable
,D/ActivityThread(12215): Added TimaKeyStore provider
,D/ResourcesManager(12215): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12231): MountEmulatedStorage()
I/libpersona(12231): KNOX_SDCARD checking this for 10127
E/Zygote  (12231): v2
I/libpersona(12231): KNOX_SDCARD not a persona
,I/SELinux (12231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3529): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12231 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3529): Killing 11412:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12231): TimaSignature is unavailable
,D/ActivityThread(12231): Added TimaKeyStore provider
,D/ResourcesManager(12231): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(12231): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12231): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12231): stopCheckCategoryVersion
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12247): MountEmulatedStorage()
,E/Zygote  (12247): v2
I/libpersona(12247): KNOX_SDCARD checking this for 10136
I/libpersona(12247): KNOX_SDCARD not a persona
I/SELinux (12247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12247): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3529): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=12247 uid=10136 gids={50136, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3529): Killing 11429:com.samsung.helphub/1000 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8747(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 294us total 10.479ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 248us total 7.433ms
,D/TimaKeyStoreProvider(12247): TimaSignature is unavailable
,D/ActivityThread(12247): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 257us total 8.218ms
,D/ResourcesManager(12247): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12247): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12247): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12247): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(12247): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory(12247): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(12247): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(12247): Loading: webviewchromium
,I/LibraryLoader(12247): Time to load native libraries: 3 ms (timestamps 9544-9547)
I/LibraryLoader(12247): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(12247): Binding Chromium to main looper Looper (main, tid 1) {1d6f43c5}
,I/LibraryLoader(12247): Expected native library version number "",actual native library version number ""
,I/chromium(12247): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(12247): Initializing chromium process, renderers=0
,W/art     (12247): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(12247): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(12247): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/chromium(12247): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid(12247): Requires BLUETOOTH permission
,I/NSApplication(12247): Starting up...
,I/Choreographer(11877): Skipped 136 frames!  The application may be doing too much work on its main thread.
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,I/chromium(11877): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Zygote  (12315): MountEmulatedStorage()
E/Zygote  (12315): v2
I/libpersona(12315): KNOX_SDCARD checking this for 10150
I/libpersona(12315): KNOX_SDCARD not a persona
,I/SELinux (12315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/chromium(11877): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/SELinux (12315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=12315 uid=10150 gids={50150, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3529): Killing 11361:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(12315): TimaSignature is unavailable
,D/ActivityThread(12315): Added TimaKeyStore provider
,D/ResourcesManager(12315): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager(12315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12315): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12315): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect(12315): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12315): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect(12315): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12330): MountEmulatedStorage()
I/libpersona(12330): KNOX_SDCARD checking this for 10178
E/Zygote  (12330): v2
I/libpersona(12330): KNOX_SDCARD not a persona
,I/SELinux (12330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3529): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=12330 uid=10178 gids={50178, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux (12330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Killing 11447:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12330): TimaSignature is unavailable
,D/ActivityThread(12330): Added TimaKeyStore provider
,D/ResourcesManager(12330): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(12330): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager(12330): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12330): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12330): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12330): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12330): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,E/Zygote  (12353): MountEmulatedStorage()
,I/libpersona(12353): KNOX_SDCARD checking this for 10082
E/Zygote  (12353): v2
I/libpersona(12353): KNOX_SDCARD not a persona
I/SELinux (12353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12353): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=12353 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12353): TimaSignature is unavailable
,D/ActivityThread(12353): Added TimaKeyStore provider
,E/Zygote  (12369): MountEmulatedStorage()
E/Zygote  (12369): v2
I/libpersona(12369): KNOX_SDCARD checking this for 1000
I/libpersona(12369): KNOX_SDCARD not a persona
,I/SELinux (12369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3529): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12369 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3529): Killing 11554:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/ActivityManager( 3529): Killing 11571:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(12369): TimaSignature is unavailable
,D/ActivityThread(12369): Added TimaKeyStore provider
,D/ResourcesManager(12353): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/ResourcesManager(12369): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/BadgeProvider(12353): onCreate
D/BadgeProvider(12353): DatabaseHelper
,I/ActivityManager( 3529): Killing 11589:com.sec.android.widgetapp.tapandpay/u0a190 (adj 13): bgCount ##31
,D/BadgeProvider(12353): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider(12353): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider(12353): sendNotify, [notify] : null
D/BadgeProvider(12353): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider(12353): update, [BadgeCount] : badgecount=0
D/BadgeProvider(12353): update, [UpdateCount] : 1
,D/Launcher.Model( 4001): reloadBadges entered.
,I/iu.Environment( 6642): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6642): num queued entries: 0
,I/iu.UploadsManager( 6642): num updated entries: 0
I/iu.SyncManager( 6642): NEXT; no task
,W/ActivityManager( 3529): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12386): MountEmulatedStorage()
I/libpersona(12386): KNOX_SDCARD checking this for 10013
E/Zygote  (12386): v2
I/libpersona(12386): KNOX_SDCARD not a persona
,I/SELinux (12386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12386): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3529): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=12386 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider(12386): TimaSignature is unavailable
,D/ActivityThread(12386): Added TimaKeyStore provider
,D/ResourcesManager(12386): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/ActivityManager( 3529): Killing 11638:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,I/Hs20UtilService( 4082): Starting #10
,D/NearbySettings( 8775): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8775): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8775): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8775): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 4082): Message received 5007
,I/SignOutReceiver(11531): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  (12137): wlan0: acknowledged 192.168.1.124 from 192.168.1.1
,I/dhcpcd  (12137): wlan0: leased 192.168.1.124 for 86400 seconds
,E/WifiStateMachine( 3529): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3529): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine( 3529): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine( 3529): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  ( 3529): do suspend true
D/WifiP2pService( 3529): InactiveState{ what=143375 }
D/WifiP2pService( 3529): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 3529): WifiStateMachine DHCP successful
E/WifiStateMachine( 3529): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine( 3529): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine( 3529): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine( 3529): Not connected state, yet.
E/WifiStateMachine( 3529): VerifyingLinkState enter
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiStateMachine( 3529): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine( 3529): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine( 3529): false / false / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL( 3529): callSECApiInt - ID [210]
E/WifiStateMachine( 3529): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
E/ConnectivityService( 3529): updateNetworkInfo()
D/ConnectivityService( 3529): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 3529): Adding iface wlan0 to network 503
D/WifiWatchdogStateMachine( 3529): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 3529): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 3529): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 3529): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 3529): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
E/WifiStateMachine( 3529): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine( 3529): Now, connected state.
E/WifiStateMachine( 3529): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
I/Hs20UtilService( 4082): Starting #11
E/WifiStateMachine( 3529): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
I/WifiTrafficPoller( 3529): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 3693): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:null
D/NearbySettings( 8775): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8775): MountReceiver.onReceive - Keep current state
I/WifiTrafficPoller( 3529): evaluateTrafficStatsPolling
D/WifiNative-HAL( 3529): callSECApiVoid - ID [212]
E/WifiStateMachine( 3529): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/Hs20UtilService( 4082): Message received 5007
D/ConnectivityService( 3529): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine( 3529): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService( 3529): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
I/WifiStateMachine( 3529): REQUEST_POWER_SAVE_ON
D/ConnectivityService( 3529): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
E/ConnectivityService( 3529): Unexpected mtu value: 0, wlan0
V/        ( 2844): QcRouteController
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
V/        ( 2844): QcRouteController
I/SignOutReceiver(11531): NETWORK_STATE_CHANGED_ACTION
V/        ( 2844): QcRouteController
I/Hs20UtilService( 4082): Starting #12
I/Hs20UtilService( 4082): Message received 5007
D/NearbySettings( 8775): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8775): DMSUtil.isNetworkConnected - flag-null, state-null
V/        ( 2844): QcRouteController
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 8775): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8775): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8775): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11531): NETWORK_STATE_CHANGED_ACTION
V/        ( 2844): QcRouteController
I/Hs20UtilService( 4082): Starting #13
I/Hs20UtilService( 4082): Message received 5007
D/NearbySettings( 8775): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 8775): MountReceiver.onReceive - Keep current state
V/        ( 2844): QcRouteController
V/        ( 2844): QcRouteController
I/WifiStateMachine( 3529): callSECApi what=220
D/WifiStateMachine( 3529): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
I/SignOutReceiver(11531): NETWORK_STATE_CHANGED_ACTION
V/        ( 2844): QcRouteController
D/ConnectivityService( 3529): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 3529): LTETest block dns file not exists
D/ConnectivityService( 3529): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 3529): updateNetworkInfo()
E/ConnectivityService( 3529): updateNetworkInfo()
D/ConnectivityService( 3529): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3529): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
I/SurfaceFlinger( 2848): id=14 createSurf (1x1),1 flag=4, Uoast
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Checking http://clients3.google.com/generate_204 on "NG700"
I/System.out( 3529): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 3529): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3529):    accepting network in place of null
D/TelephonyNetworkFactory( 3985): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 3529): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 3529): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 3529): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PowerManagerService( 3529): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3529
D/ConnectivityService( 3529): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering( 3529): MasterInitialState.processMessage what=3
D/SmartBondingService( 3529): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3529): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
V/NetworkStats( 3529): updateIfacesLocked()
D/ConnectivityService( 3529): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity( 3529): Not allowed due to - mEnabled false
V/NetworkStats( 3529): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NetworkStatsFactory( 3529): UpdateStatsForKnox
D/SmartBondingService( 3529): getNetworkEnabled : wifi : true mobile : false
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
V/NetworkStats( 3529): performPollLocked() took 7ms
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/ConnectivityManager.CallbackHandler( 6642): CM callback handler got msg 524290
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
V/NetworkStats( 3529): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 3529): currentTimeMillis() cache hit
D/mali_winsys( 3693): new_window_surface returns 0x3000,  [1120x201]-format:1
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
D/StatusBar.NetworkController( 3693): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3693): applyOpen
I/System.out( 3529): KnoxVpnUidStorageknoxVpnSupported API value returned is false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:02:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452862969413], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452862969391]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3529): Validated
D/ConnectivityService( 3529): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3529): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 3529): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 3529): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524290
D/ConnectivityService( 3529): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 6642): CM callback handler got msg 524290
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3693): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3693): updateDataNetType()
D/StatusBar.NetworkController( 3693): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3693): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 3693): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength: hasService=false ss=null
D/StatusBar.NetworkController( 3693): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3693): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3693): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService( 3529): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3529): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3529): SmartBondingReceiver: wifi is connected
,D/SmartBondingService( 3529): SmartBondingReceiver: wifi ap is not changed
,D/SmartBondingService( 3529): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
,D/SmartBondingService( 3529): getNetworkEnabled : wifi : true mobile : false
,D/GpsLocationProvider( 3529): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor(12015): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 6224): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 6224): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,W/ResourceType( 5369): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5369): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/PCWCLIENTTRACE_PushUtil(11993): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11993): sales region : global
I/PCWCLIENTTRACE_PushUtil(11993): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11993): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12071): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT(12071): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 3529): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3529): mCursor = null
,I/FOTA_Client(12090): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client(12090): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client(12090): [IIIllIIllIlIllIlllII(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.521: (12106): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:02:50 GMT+01:00 2016
,I/KLMS-2.4.521: (12106): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.4.521: (12106): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12106): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12106): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12106): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12106): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.4.521: (12106): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/SO_AGENT(12122): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/KLMS-2.4.521: (12106): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.521: (12106): NetworkChangeOperations(): uploadRequestLog().START 
,E/WifiStateMachine( 3529): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService( 3529): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,V/        ( 2844): QcRouteController
E/WifiStateMachine( 3529): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService( 3529): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/SmartBondingService( 3529): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
D/SmartBondingService( 3529): getSBEnabled() enabled =false
,V/        ( 2844): QcRouteController
,I/KLMS-2.4.521: (12106): NetworkChangeOperations(): uploadRequestLog().END 
,W/NetworkManagementService( 3529): route cmd failed: 
W/NetworkManagementService( 3529): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '76 route replace src v6 wlan0 fe80::92b6:86ff:fe43:731c 2 ::' failed with '400 76 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService( 3529): '
W/NetworkManagementService( 3529): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService( 3529): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService( 3529): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService( 3529): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService( 3529): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService( 3529): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5738)
W/NetworkManagementService( 3529): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5545)
W/NetworkManagementService( 3529): 	at com.android.server.ConnectivityService.access$2600(ConnectivityService.java:231)
W/NetworkManagementService( 3529): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2436)
W/NetworkManagementService( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ConnectivityService( 3529): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,I/KLMS-2.4.521: (12106): StateImplV2(): networkChangeListener().END
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
D/ConnectivityService( 3529): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 6642): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 3693): CM callback handler got msg 524295
,I/KLMS-2.4.521: (12106): KLMSIntentService(): onDestroy()
,D/ConnectivityManager.CallbackHandler( 6642): CM callback handler got msg 524295
,E/SPPClientService(12164): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      (11340): [OR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      (11340): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      (11340): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      (11340): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      (11340): [OR] == isSIMCardReady false ==
,I/SA      (11340): [SCU] == networkStateCheck == true
I/SA      (11340): [DM] getCountryCodeFromCSC : PL
I/SA      (11340): isChinaCountryCode : false
I/SA      (11340): [SCU] is ChinestModel Data Restricted   : false
I/SA      (11340): [OR] == networkStateCheck true ==
,I/SA      (11340): [OR] GetMyCountryZoneTask
I/SA      (11340): [OR] onReceive END
,I/SA      (11340): [SRS] prepareGetMyCountryZone
,I/SA      (11340): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,V/DownloadManager( 5483): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/SA      (11340): [SSP] query invoked
,I/SA      (11340): [TPMU] GetMccFromDB : null
,I/SCloudBackupReceiver(12184): Other Intent
,I/SA      (11340): [SCU] getMccFromPreferece mcc = 260
I/SA      (11340): [TPM] isNoProxy(default) : true
,D/accuweather( 5172): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 3774): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5172): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5172): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5172): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5172): [KK AccuPhone]>>> UIM:311 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5172): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 5172): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro(12200): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro(12200): premStatus:2
,I/KnoxUsageLogPro(12200): isEulaShown : false
I/KnoxUsageLogPro(12200): KnoxUsageReceiver onReceive : not Processible, just return
,D/KeyguardWallpaperUpdator(12231): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(12231): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12231): stopCheckCategoryVersion
,D/QuickConnect(12315): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect(12315): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect(12315): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,D/RCPManagerService( 3529): exchangeData() failure , invalid userId
,I/iu.Environment( 6642): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6642): num queued entries: 0
,I/iu.UploadsManager( 6642): num updated entries: 0
,I/iu.SyncManager( 6642): NEXT; no task
,D/ConnectivityService( 3529): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/WaitQueueForNetworkActivate(12386): notifyNetworkActivated
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10014
,W/ContextImpl(12386): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 3529): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/hcjo    (12386): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine(12386): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine(12386): exit::IDLE
D/InitializeManagerStateMachine(12386): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine(12386): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine(12386): exit::NETWORK_CHECK
D/InitializeManagerStateMachine(12386): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12386): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine(12386): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine(12386): entry::SUCCESS
D/hcjo    (12386): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    (12386): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    (12386): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine(12386): exit::SUCCESS
D/InitializeManagerStateMachine(12386): entry::IDLE
,I/SA      (11340): [RC New] Execute method=[GET] start
,I/SA      (11340): [RC New] Security=[true]
,I/System.out(11340): Thread-1550(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out(11340): Thread-1550(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11340): Thread-1550(ApacheHTTPLog):isShipBuild true
I/System.out(11340): Thread-1550(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2844): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2844): getNetworkForDns: using netid 503 for uid 10045
,D/SSRM:n  ( 3529): SIOP:: AP = 280, PST = 273, CUR = 63
,I/SA      (11340): [RC New] [v2liruge] api execute + 756
I/SA      (11340): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out(11340): AsyncTask #1 calls detatch()
,I/dhcpcd  (12137): wlan0: sending IPv6 Router Solicitation
,I/SA      (11340): [TPMU] getNetworkMcc : 
,I/SA      (11340): [SCU] saveMccToPreferece Start
,I/SA      (11340): [SCU] RegionMCC : 260
I/SA      (11340): [SSP] query invoked
,I/SA      (11340): [TPMU] GetMccFromDB : null
,I/SA      (11340): [SCU] getMccFromPreferece mcc = 260
,I/SA      (11340): [SCU] saveMccToPreferece End
,I/SA      (11340): [RC New] executeRequest [v2liruge] end. 848
,I/SA      (11340): [RC New] Execute end
,I/SA      (11340): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      (11340): [OR] GetMyCountryZoneTask Success
,D/WearableService( 4634): callingUid 10014, callindPid: 4634
,D/ResourcesManager(12015): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager(12015): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(12015): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory(12015): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(12015): Conditions not met for autocaching.
I/MusicLeanback(12015): Stop autocaching.
,D/WearableClient(12015): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12015): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12015): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(12015): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(12015): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(12015): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(12015): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@b45d40b that was originally bound here
E/ActivityThread(12015): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@b45d40b that was originally bound here
E/ActivityThread(12015): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(12015): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(12015): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(12015): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(12015): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(12015): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(12015): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12015): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12015): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(12015): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(12015): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(12015): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(12015): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(12015): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(12015): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(12015): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(12015): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(12015): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(12015): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(12015): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(12015): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(12015): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(12015): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(12015): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(12015): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:-72, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:96
D/BatteryService( 3529): stay LED for fully charged
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/WifiStateMachine( 3529): REQUEST_POWER_SAVE_ON
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/WifiStateMachine( 3529): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/art     ( 3529): Explicit concurrent mark sweep GC freed 51542(3MB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 1.925ms total 144.462ms
,I/GAV4    (12247): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger( 2848): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 3529): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3529) eventTime = 144688
,D/PowerManagerService( 3529): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3529 (0x0)
D/PowerManagerService( 3529): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3529, ws=WorkSource{10060}) (elapsedTime=3467)
,D/PackageManager( 3529): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/PCWCLIENTTRACE_SYSTEMReceiver(11993): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil(11993): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE(11993): ================================================
,I/CSTORAGE(11993):  CSTORAGE_SKM_LIB v1.0.15
I/CSTORAGE(11993): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI(11993): [GetString-S]
,E/art     (11993): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI(11993): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI(11993): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil(11993): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil(11993): sales region : global
,I/PCWCLIENTTRACE_PushUtil(11993): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler(11993): [ensureRegistration] - No Samsung account
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  (12137): wlan0: sending IPv6 Router Solicitation
,W/ProcessCpuTracker( 3529): Skipping unknown process pid 12586
,I/dhcpcd  (12137): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  (12137): wlan0: no IPv6 Routers available
,V/AlarmManager( 3529): waitForAlarm result :8
,D/PreloadUpdateManagerStateMachine(12386): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine(12386): exit::IDLE
,D/PreloadUpdateManagerStateMachine(12386): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    (12386): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    (12386): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine(12386): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine(12386): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine(12386): entry::IDLE
,D/SSRM:n  ( 3529): SIOP:: AP = 260, PST = 268, CUR = -72
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:77
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 5
,D/SSRM:n  ( 3529): SIOP:: AP = 250, PST = 263, CUR = 19
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3529): [PWL] Off : 105s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 250, PST = 262, CUR = 49
,I/art     ( 4634): Explicit concurrent mark sweep GC freed 73134(3MB) AllocSpace objects, 32(1255KB) LOS objects, 34% free, 30MB/46MB, paused 1.996ms total 73.285ms
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:71
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4634): disconnect managed GoogleApiClient,
,D/SSRM:n  ( 3529): SIOP:: AP = 250, PST = 262, CUR = 57
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3529): !@Sync 6
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 260, CUR = 57
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:56, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:54
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3529): [PWL] Off : 140s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 254, CUR = 56
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:54, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 252, CUR = 54
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:62
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3529): !@Sync 7
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 251, CUR = 52
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:48, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 250, CUR = 48
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3529): [PWL] Off : 180s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 247, CUR = 47
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42,
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3529): !@Sync 8
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 246, CUR = 46
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 245, CUR = 45
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3529): waitForAlarm result :8
,D/SSRM:n  ( 3529): SIOP:: AP = 240, PST = 243, CUR = 42
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 9
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 242, CUR = 40
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3529): [PWL] Off : 225s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 240, CUR = 39
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 239, CUR = 40
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3529): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3529): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3529): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3529): initializing...
,I/TLC_TIMA_PKM_initialize( 3529): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3529): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3529): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3529): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3529): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3529): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3529): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3529): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3529): device_id = 0x0
,I/TZ: mc_tlc_communication( 3529): tlc_open() was called
I/TZ: mc_tlc_communication( 3529): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3529): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3529): Opening the session
,I/TZ: mc_tlc_communication( 3529): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3529): Trustlet response is completed
,E/Watchdog( 3529): !@Sync 10
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 238, CUR = 38
,I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:59
,D/BatteryService( 3529): stay LED for fully charged
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 236, CUR = 38
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 236, CUR = 36
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3529): [PWL] Off : 275s ago
,E/Watchdog( 3529): !@Sync 11
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 235, CUR = 37
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 235, CUR = 35
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 234, CUR = 34
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3529): !@Sync 12
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 234, CUR = 34
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 233, CUR = 34
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3529): [PWL] Off : 330s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 233, CUR = 33
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3529): !@Sync 13
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 232, CUR = 33
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 232, CUR = 31
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 231, CUR = 29
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3529): !@Sync 14
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 231, CUR = 30
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 231, CUR = 30
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :8
,I/PowerManagerService( 3529): [PWL] Off : 390s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 29
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 15
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 30
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3529): stay LED for fully charged
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 29
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 27
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 16
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 29
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 28
,V/AlarmManager( 3529): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :8
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 29
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3529): [PWL] Off : 455s ago
,E/Watchdog( 3529): !@Sync 17
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 26
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 27
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 26
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 18
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 28,
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 27
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 26,
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 19
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 25,
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3529): [PWL] Off : 525s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 230, PST = 230, CUR = 24
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 229, CUR = 24
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3529): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3529): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3529): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3529): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 229, CUR = 24
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 229, CUR = 23
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 228, CUR = 23
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 21
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 228, CUR = 23
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 228, CUR = 25
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3529): [PWL] Off : 600s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 227, CUR = 25
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 22
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 227, CUR = 24
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 227, CUR = 22
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 226, CUR = 22
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3529): !@Sync 23
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 226, CUR = 22
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 226, CUR = 21,
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3529): stay LED for fully charged
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 225, CUR = 20
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 24
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 225, CUR = 20,
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3529): [PWL] Off : 680s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 225, CUR = 20
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 224, CUR = 20
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 3529): stay LED for fully charged
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 25
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 224, CUR = 19,
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 224, CUR = 20
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:45
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 223, CUR = 21
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 26
,V/AlarmManager( 3529): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/LightsService( 3529): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,I/Sensors ( 3529): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3529): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3529): #>LightSensor r=59 g=57 b=48 c=122 atime=238 again=64 lux=19.000000
,D/LightsService( 3529): [SvcLED]  onSensorChanged::light value = 19
,I/Sensors ( 3529): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3529): unregisterListener ::   
,D/lights  ( 3529): led_pattern : 5 +
,D/lights  ( 3529): led_pattern : 5 -
,D/LightsService( 3529): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 223, CUR = 19
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 223, CUR = 20
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :8
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 222, CUR = 21
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 27
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 222, CUR = 19
,I/PowerManagerService( 3529): [PWL] Off : 765s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 222, CUR = 19
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 221, CUR = 18
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 28
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 221, CUR = 17
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 221, CUR = 17
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 19
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 29
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,V/AlarmManager( 3529): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ChimeraCfgMgr( 6642): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6642): Module APK com.google.android.play.games already loaded
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GamesSyncServiceMain( 6642): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 6642): Failed to execute periodic sync, missing client context - aborting
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
D/BatteryService( 3529): stay LED for fully charged
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,D/TimaService( 3529): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3529): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3529): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 30
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 16
,I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3529): [PWL] Off : 855s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:29
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :8
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 31
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 18
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 16
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 32
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 16
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 17
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 16
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 33
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 16
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3529): [PWL] Off : 950s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 15
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 15
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 34
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 15
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 35
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 15
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 16
,E/Watchdog( 3529): !@Sync 36
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12,
,I/PowerManagerService( 3529): [PWL] Off : 1050s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,E/Watchdog( 3529): !@Sync 37
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 15
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,E/Watchdog( 3529): !@Sync 38
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3529): stay LED for fully charged
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14,
,E/Watchdog( 3529): !@Sync 39
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 14
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged,
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/TimaService( 3529): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3529): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3529): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService( 3529): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3529): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3529): Updating Usage Statistics in DB @ 1452864039519
,I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
,W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
,W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
,W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.a,ndroid.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3529): ::getAppControlDB: Exception to create DB
W/System.err( 3529): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3529): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3529): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3529): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3529): Done Updating Usage Statistics in DB @ 1452864039585
,E/Watchdog( 3529): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3529): [PWL] Off : 1155s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19,
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,E/Watchdog( 3529): !@Sync 41
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,E/Watchdog( 3529): !@Sync 42
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 13
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
D/BatteryService( 3529): stay LED for fully charged
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,E/Watchdog( 3529): !@Sync 43
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12,
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,I/PowerManagerService( 3529): [PWL] Off : 1265s ago
,E/Watchdog( 3529): !@Sync 44
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12,
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 45
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 46
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,I/art     ( 3529): Background sticky concurrent mark sweep GC freed 88430(9MB) AllocSpace objects, 385(6MB) LOS objects, 13% free, 49MB/57MB, paused 3.236ms total 120.493ms
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 47
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3529): [PWL] Off : 1380s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 48
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
D/BatteryService( 3529): stay LED for fully charged
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 49
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3529): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3529): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 3529): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3529): !@Sync 50
,V/AlarmManager( 3529): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/LightsService( 3529): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3529): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3529): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,I/EventLogService( 6642): Aggregate from 1452862344005 (log), 1452862344005 (data)
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3529): #>LightSensor r=44 g=43 b=37 c=93 atime=238 again=64 lux=14.000000
,D/LightsService( 3529): [SvcLED]  onSensorChanged::light value = 14
I/Sensors ( 3529): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3529): unregisterListener ::   
D/LightsService( 3529): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 3529): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :8
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 51
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10,
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3529): [PWL] Off : 1500s ago
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 52
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 53
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3529): stay LED for fully charged
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 54
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8,
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 55
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 11
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,I/PowerManagerService( 3529): [PWL] Off : 1625s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 56
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 12
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 57
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 10
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 58
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 59
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 6
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3693): handleTimeUpdate
,W/ProcessCpuTracker( 3529): Skipping unknown process pid 13552
,D/NetworkStatsFactory( 3529): UpdateStatsForKnox
,D/KeyguardEffectViewController( 3693): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3693): *** don't update sliding image ***
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3693): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3529): waitForAlarm result :4
,V/AlarmManager( 3529): OOI=Alarm{3362280f type 0 when 1452866428076 com.google.android.gms}
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3529): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3529): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3529): TimaServiceHandler.handleMessage what =1,
,E/Watchdog( 3529): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3529): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3529): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,I/PowerManagerService( 3529): [PWL] Off : 1755s ago
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3529): waitForAlarm result :8
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 61
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 8
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-6
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 62
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 6
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/BatteryService( 3529): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 9
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 63
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 6
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 6
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3529): !@Sync 64
,I/MMD     ( 2870): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 7
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3529): online:4, current avg:6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/BatteryService( 3529): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3529): SIOP:: AP = 220, PST = 220, CUR = 6
,D/BatteryService( 3529): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3529): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 237, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3529): online:4, current avg:7, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3529): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3529): stay LED for fully charged
,I/MotionRecognitionService( 3529): Plugged
,I/MotionRecognitionService( 3529): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3693): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3693): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3693):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5652): Disconnected process message: 10
,D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3693): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms),I/PowerManagerService( 3529): [PWL] Off : 1890s ago
D/AndroidRuntime(13661): 
D/AndroidRuntime(13661): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13661): CheckJNI is OFF
D/AndroidRuntime(13661): readGMSProperty: start
D/AndroidRuntime(13661): readGMSProperty: already setted!!
D/AndroidRuntime(13661): readGMSProperty: end
D/AndroidRuntime(13661): addProductProperty: start
E/AffinityControl(13661): AffinityControl: registerfunction enter
D/AndroidRuntime(13661): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3529): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3529): START PACKAGE DELETE: observer{328847516}
D/PackageManager( 3529): pkg{<packageName>}
D/PackageManager( 3529): user{0}
D/PackageManager( 3529): caller{2000}
D/PackageManager( 3529): flags{3}
D/PersonaManagerService( 3529): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3529): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3529): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3529): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3529): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3529): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3529): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3529): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3529): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3529): !@killApplicatoin: 10575, uninstall pkg
I/ActivityManager( 3529): Force stopping com.test.thalitest appid=10575 user=-1: uninstall pkg
I/ActivityManager( 3529): Killing 11877:com.test.thalitest/u0a575 (adj 0): stop com.test.thalitest
I/ActivityManager( 3529): Killing 11340:com.osp.app.signin/u0a45 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 12138:com.policydm/1000 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 12122:com.sec.android.soagent/u0a38 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 12106:com.samsung.klmsagent/u0a21 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 12090:com.sec.android.fotaclient/u0a12 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 12071:com.sec.android.diagmonagent/1000 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 12050:com.sec.android.cloudagent/u0a2 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 11993:com.sec.pcw.device/1000 (adj 13): empty for 1811s
I/ActivityManager( 3529): Killing 11531:com.samsung.android.snote/u0a160 (adj 15): empty for 1812s
I/ActivityManager( 3529): Killing 8775:com.android.settings/1000 (adj 15): empty for 1812s
I/ActivityManager( 3529): Killing 12353:com.sec.android.provider.badge/u0a82 (adj 15): empty for 1813s
I/ActivityManager( 3529): Killing 11770:com.android.vending/u0a31 (adj 15): empty for 1839s
I/ActivityManager( 3529): Killing 10936:com.android.defcontainer/u0a5 (adj 15): empty for 1844s
I/ActivityManager( 3529): Killing 11621:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): empty for 1852s
I/ActivityManager( 3529): Killing 11656:com.android.calendar/u0a164 (adj 15): empty for 1852s
I/ActivityManager( 3529):   Force finishing activity ActivityRecord{3dcfe6da u0 com.test.thalitest/.MainActivity t26}
W/ActivityManager( 3529): mDVFSHelper.acquire()
W/PackageSettings( 3529): Skipping PackageSetting{19e65a02 com.example.hello/10563} due to missing metadata
D/WifiService( 3529): Client connection lost with reason: 4
I/WindowState( 3529): WIN DEATH: Window{362bf730 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 2848): id=13 Removed NainActivit (5/8)
I/SurfaceFlinger( 2848): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger( 2848): id=13 Removed NainActivit (-2/8)
D/WifiService( 3529): Client connection lost with reason: 4
D/PointerIcon( 3529): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3529): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3529): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3529): setHoveringSpenCustomIcon IconType is same.1
I/ProcessStatsService( 3529): Prepared write state in 12ms
W/libprocessgroup( 3529): failed to open /acct/uid_10045/pid_11340/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10082/pid_12353/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10002/pid_12050/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10021/pid_12106/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10164/pid_11656/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_1000/pid_12071/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10012/pid_12090/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_1000/pid_8775/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_1000/pid_11993/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10022/pid_11621/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10005/pid_10936/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_1000/pid_12138/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10038/pid_12122/cgroup.procs: No such file or directory
W/libprocessgroup( 3529): failed to open /acct/uid_10160/pid_11531/cgroup.procs: No such file or directory
I/ActivityManager( 3529): Force stopping com.test.thalitest appid=10575 user=0: pkg removed
I/ActivityManager( 3529):   Force finishing activity ActivityRecord{3dcfe6da u0 com.test.thalitest/.MainActivity t26 f}
W/ActivityManager( 3529): Duplicate finish request for ActivityRecord{3dcfe6da u0 com.test.thalitest/.MainActivity t26 f}
I/DBG_DM  ( 6224): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
I/ProcessStatsService( 3529): Prepared write state in 30ms
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
W/libprocessgroup( 3529): failed to open /acct/uid_10031/pid_11770/cgroup.procs: No such file or directory
I/art     ( 4056): Explicit concurrent mark sweep GC freed 33276(2041KB) AllocSpace objects, 1(39KB) LOS objects, 21% free, 28MB/36MB, paused 6.444ms total 49.194ms
I/art     ( 8833): Explicit concurrent mark sweep GC freed 24483(1438KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.106ms total 60.436ms
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6224): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 9
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader( 3529): Reconfiguring input devices.  changes=0x00000010
I/DBG_DM  ( 6224): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
E/SamsungIME( 4460): mOCRHelper is null
W/GeofencerStateMachine( 4634): Ignoring removeGeofence because network location is disabled.
I/art     ( 6642): Explicit concurrent mark sweep GC freed 30366(1774KB) AllocSpace objects, 7(112KB) LOS objects, 20% free, 31MB/39MB, paused 1.100ms total 96.377ms
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
W/ResourceType( 5369): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5369): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
E/Zygote  (13680): MountEmulatedStorage()
E/Zygote  (13680): v2
I/libpersona(13680): KNOX_SDCARD checking this for 10063
I/libpersona(13680): KNOX_SDCARD not a persona
I/SELinux (13680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3529): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=13680 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (13680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/SecContentProvider2( 3529): uri = 14 selection = getSealedState
D/SecContentProvider2( 3529): mCursor = null
D/ApplicationPolicy( 3529): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3529): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/TimaKeyStoreProvider(13680): TimaSignature is unavailable
D/ActivityThread(13680): Added TimaKeyStore provider
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 9
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 6224): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6224): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6224): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6224): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6224): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
I/art     ( 3529): Explicit concurrent mark sweep GC freed 54715(5MB) AllocSpace objects, 169(2MB) LOS objects, 24% free, 49MB/65MB, paused 2.574ms total 196.591ms
I/art     ( 3529): WaitForGcToComplete blocked for 185.291ms for cause Background
I/art     ( 3529): WaitForGcToComplete blocked for 194.308ms for cause Explicit
D/ResourcesManager( 3529): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ActivityManager( 3529): post active user change for 0
D/KnoxTimeoutHandler( 3529): postActiveUserChange for user 0
I/DBG_DM  ( 6224): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
I/SurfaceFlinger( 2848): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
D/StatusBarManagerService( 3529): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/StatusBarManagerService( 3529): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/PointerIcon( 3529): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3529): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3529): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3529): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
V/ActivityThread( 6224): updateVisibility : ActivityRecord{3d70c24a token=android.os.BinderProxy@1ddc071f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService( 3529): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 3529): Got RemoteException sending setActive(false) notification to pid 11877 uid 10575
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/ProcessStatsService( 3529): Pruning old procstats: /data/system/procstats/state-2016-01-14-13-49-12.bin
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(13680): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/SecContentProvider2( 3529): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3529): mCursor = null
D/VRSetupWizardStub/PackageIntentReceiver(13680): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(13680): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(13680): packagename:com.test.thalitest
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/Zygote  (13698): MountEmulatedStorage()
E/Zygote  (13698): v2
I/libpersona(13698): KNOX_SDCARD checking this for 10021
I/libpersona(13698): KNOX_SDCARD not a persona
I/SELinux (13698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (13698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13698): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3529): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=13698 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3529): Killing 12184:com.samsung.android.scloud.backup/u0a67 (adj 15): empty for 1812s
D/RegisteredServicesCache( 3967): empty dynamic service
I/Timeline( 6224): Timeline: Activity_idle id: android.os.BinderProxy@1ddc071f time:1954290
D/TimaKeyStoreProvider(13698): TimaSignature is unavailable
W/ActivityManager( 3529): mDVFSHelper.release()
I/Timeline( 3529): Timeline: Activity_windows_visible id: ActivityRecord{1844857d u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:1954313
D/ActivityThread(13698): Added TimaKeyStore provider
D/ResourcesManager(13698): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/art     ( 3529): Explicit concurrent mark sweep GC freed 8791(493KB) AllocSpace objects, 1(72KB) LOS objects, 24% free, 48MB/64MB, paused 2.025ms total 163.319ms
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/KLMS-2.4.521: (13698): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:33:02 GMT+01:00 2016
W/libprocessgroup( 3529): failed to open /acct/uid_10067/pid_12184/cgroup.procs: No such file or directory
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
I/KLMS-2.4.521: (13698): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3529): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3529): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/PackageManager( 3529): delete codoeFile: 
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (13698): KLMSIntentService(): onCreate()
I/AASAUninstall( 3529):  com.test.thalitest not target!
D/PackageManager( 3529): result of delete: 1{328847516}
I/KLMS-2.4.521: (13698): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/AndroidRuntime(13661): Shutting down VM
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
I/KLMS-2.4.521: (13698): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/KLMS-2.4.521: (13698): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/Zygote  (13714): MountEmulatedStorage()
E/Zygote  (13714): v2
I/libpersona(13714): KNOX_SDCARD checking this for 10106
I/libpersona(13714): KNOX_SDCARD not a persona
I/SELinux (13714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/KLMS-2.4.521: (13698): KLMSIntentService(): PACKAGE_REMOVED
I/SELinux (13714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3529): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=13714 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/SELinux (13714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/KLMS-2.4.521: (13698): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
I/KLMS-2.4.521: (13698): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/EnterpriseDeviceManagerService( 3529): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3529): Admin package name: com.google.android.gms
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/Zygote  (13729): MountEmulatedStorage()
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/Zygote  (13729): v2
I/libpersona(13729): KNOX_SDCARD checking this for 10160
I/libpersona(13729): KNOX_SDCARD not a persona
D/RCPManager(12200):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3529):  in createShortcut() for packageName: com.test.thalitest userId0
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/RCPManagerService( 3529): queryAllProviders():  providerCallBack is not register for 0
I/SELinux (13729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3529): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=13729 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/SELinux (13729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/TimaKeyStoreProvider(13714): TimaSignature is unavailable
E/SELinux (13729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread(13714): Added TimaKeyStore provider
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  (13743): MountEmulatedStorage()
I/libpersona(13743): KNOX_SDCARD checking this for 10050
E/Zygote  (13743): v2
I/libpersona(13743): KNOX_SDCARD not a persona
I/SELinux (13743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3529): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=13743 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux (13743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(13729): TimaSignature is unavailable
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
D/ActivityThread(13729): Added TimaKeyStore provider
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
E/Zygote  (13757): MountEmulatedStorage()
E/Zygote  (13757): v2
I/libpersona(13757): KNOX_SDCARD checking this for 10101
I/libpersona(13757): KNOX_SDCARD not a persona
I/SELinux (13757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TimaKeyStoreProvider(13743): TimaSignature is unavailable
I/ActivityManager( 3529): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=13757 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (13757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (13757): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityThread(13743): Added TimaKeyStore provider
D/ResourcesManager(13714): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/RCPManagerService( 3529): PackageReceiver onReceive()
I/HarmonyEASService( 3529): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3529): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3529): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3529): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3529): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3529): uID is 10575
V/EnterpriseBillingPolicy( 3529): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3529): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3529): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3529): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3529): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3529): getBillingProfileForVpnEngine - start - com.test.thalitest
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8747(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 920us total 23.018ms
V/EnterpriseBillingPolicyStorage( 3529): getBillingProfileForVpnEngine - end - null
D/TimaKeyStoreProvider(13757): TimaSignature is unavailable
D/ActivityThread(13757): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 776us total 14.970ms
D/ResourcesManager(13729): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/elm:14491(13714): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(13714): ELMEngine.ELMEngine( context ).
D/elm:14491(13714): MDMBridge.setEnterpriseBridge()
D/KnoxTimeoutHandler( 3529): handleActiveUserChange for user 0
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 742us total 15.538ms
W/ResourcesManager(13729): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(13729): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13729): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/elm:14491(13714): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(13743): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
D/elm:14491(13714): ElmAgentService : onCreate()
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3529): checkUser: useridlist=null, currentuser=0
W/ResourcesManager(13743): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/elm:14491(13714): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
W/ResourcesManager(13743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13743): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(13743): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(13743): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(13743): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(13743): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(13743): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(13757): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14491(13714): MainReceiver.listeningToPackageRemoved()
D/elm:14491(13714): MDMBridge.getInstance()
D/elm:14491(13714): MDMBridge.getAllLicenseInfoFromSDK()
I/libpersona(13775): KNOX_SDCARD checking this for 10019
E/Zygote  (13775): MountEmulatedStorage()
I/libpersona(13775): KNOX_SDCARD not a persona
E/Zygote  (13775): v2
I/SELinux (13775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/KLMS-2.4.521: (13698): KLMSIntentService(): listeningToPackageRemoved().END
I/SELinux (13775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/elm:14491(13714): MDMBridge.getAllLicenseInfoFromSDK()
E/SELinux (13775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3529): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=13775 uid=10019 gids={50019, 9997} abi=armeabi-v7a
W/ResourceType( 3529): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3529): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/TimaKeyStoreProvider(13775): TimaSignature is unavailable
D/ActivityThread(13775): Added TimaKeyStore provider
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TaskPersister( 3529): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister( 3529): removeObsoleteFile: deleting file=24_task.xml
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/StatusBar( 3693): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/elm:14491(13714): ElmAgentService : onDestroy().
D/PersonaManager( 3693): isKioskContainerExistOnDevice
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
D/PanelView( 3693): There is/are notification(s) 
D/PersonaManager( 3693): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3693): Icon Only
I/StatusBar( 3693): Icon Only
D/PanelView( 3693): There is/are notification(s) 
I/ActivityManager( 3529): Killing 12215:com.android.chrome/u0a90 (adj 15): empty for 1812s
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/KLMS-2.4.521: (13698): KLMSIntentService(): onDestroy()
D/ResourcesManager(13775): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
I/ActivityManager( 3529): Killing 12231:com.samsung.android.keyguardwallpaperupdator/u0a127 (adj 15): empty for 1812s
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 3529): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3529): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3529): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3529): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3529): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
V/Common  (13729): getScreenSize 1440 2560
D/ResourcesManager( 3529): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk

```
