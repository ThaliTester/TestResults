#### Test 61248225a3bd1fe_thali04_samsung-SM-N910C Logs


```
--------- beginning of main
I/MMD     ( 2875): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/AndroidRuntime(11781): 
D/AndroidRuntime(11781): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11781): CheckJNI is OFF
D/AndroidRuntime(11781): readGMSProperty: start
D/AndroidRuntime(11781): readGMSProperty: already setted!!
D/AndroidRuntime(11781): readGMSProperty: end
D/AndroidRuntime(11781): addProductProperty: start
E/AffinityControl(11781): AffinityControl: registerfunction enter
D/AndroidRuntime(11781): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3490): inState():  stateMachine is null !!
I/PersonaManagerService( 3490): PersonaId don't exist
I/ActivityManager( 3490): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3490): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager( 3490): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3490): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3490): mDVFSHelper.acquire()
D/FocusedStackFrame( 3490): Set to : 0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/Zygote  (11799): MountEmulatedStorage()
I/libpersona(11799): KNOX_SDCARD checking this for 10656
E/Zygote  (11799): v2
I/libpersona(11799): KNOX_SDCARD not a persona
I/SELinux (11799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3490): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11799 uid=10656 gids={50656, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (11799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11799): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11781): Shutting down VM
D/PointerIcon( 3490): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3490): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3490): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3490): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11799): TimaSignature is unavailable
D/ActivityThread(11799): Added TimaKeyStore provider
V/WindowOrientationListener( 3490): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3490): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3490): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3490): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3490): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager( 3490): Display changed displayId=0
D/ResourcesManager(11799): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger( 2851): id=13 Removed Mauncher (5/8)
I/SurfaceFlinger( 2851): id=13 Removed Mauncher (-2/8)
V/ActivityThread( 4003): updateVisibility : ActivityRecord{1dd3c77b token=android.os.BinderProxy@1d29fd55 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4003): onTrimMemory. Level: 20
I/WebViewFactory(11799): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11799): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11799): Loading: webviewchromium
,I/LibraryLoader(11799): Time to load native libraries: 6 ms (timestamps 6893-6899)
I/LibraryLoader(11799): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11799): Binding Chromium to main looper Looper (main, tid 1) {2076b0e2}
,I/LibraryLoader(11799): Expected native library version number "",actual native library version number ""
,I/chromium(11799): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11799): Initializing chromium process, renderers=0
,W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11799): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11799): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11799): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(11799): 758799475: getState() :  mService = null. Returning STATE_OFF
,W/chromium(11799): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11799): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11799): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11799): CordovaWebView is running on device made by: samsung
,W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11799): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11799): performCreate Call secproduct feature valuefalse
D/Activity(11799): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11799): Render dirty regions requested: true
,D/ActivityManager( 3490): post active user change for 0
D/KnoxTimeoutHandler( 3490): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3490): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2851): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3490): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3490): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3490): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3490): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3490): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3490): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(11799): Initialized EGL, version 1.4
,I/OpenGLRenderer(11799): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278947056 
,D/OpenGLRenderer(11799): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11799): Enabling debug mode 0
,D/mali_winsys(11799): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11799): updateVisibility : ActivityRecord{14f34863 token=android.os.BinderProxy@11748371 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3490): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3490): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3490): mDVFSHelper.release()
I/Timeline( 3490): Timeline: Activity_windows_visible id: ActivityRecord{b84b26a u0 com.example.hello/.MainActivity t26} time:137322
,I/art     ( 3490): Explicit concurrent mark sweep GC freed 64939(3MB) AllocSpace objects, 27(2MB) LOS objects, 23% free, 51MB/67MB, paused 1.555ms total 153.208ms
,W/IInputConnectionWrapper(11799): showStatusIcon on inactive InputConnection
,I/Timeline(11799): Timeline: Activity_idle id: android.os.BinderProxy@11748371 time:137468
,I/chromium(11799): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(11799): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue(11799): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11799): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11799): 
,D/jxcore_app_log(11799): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357424896
D/JX-Cordova(11799): jxcore cordova android initializing
,W/jxcore-log(11799): Initializing JXcore engine
W/jxcore-log(11799): JXcore engine is ready
,W/jxcore-log(11799): Starting JXcore engine
,E/auditd  ( 4627): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3490): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3490): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3490): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11799): Platform android
W/jxcore-log(11799): 
W/jxcore-log(11799): Process ARCH arm
W/jxcore-log(11799): 
,I/jxcore-log(11799): JXcore Cordova bridge is ready!
I/jxcore-log(11799): 
W/jxcore-log(11799): JXcore engine is started
,E/jxcore-log(11799): >> samsung-SM-N910C
E/jxcore-log(11799): 
,I/jxcore-log(11799): Total memory 2970812416
I/jxcore-log(11799): 
,I/jxcore-log(11799): Free memory 76832768
I/jxcore-log(11799): 
I/jxcore-log(11799): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11799): 
I/jxcore-log(11799): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11799): 
,I/jxcore-log(11799): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11799): 
,I/jxcore-log(11799): Size 1440 2560
I/jxcore-log(11799): 
,I/jxcore-log(11799): Screen Brightness 134
I/jxcore-log(11799): 
,E/jxcore-log(11799): Dummy Error Log.
E/jxcore-log(11799): 
,I/jxcore-log(11799): getBuffer is called!!!!
I/jxcore-log(11799): 
,I/PowerManagerService( 3490): [PWL] Off : 15s ago,
,D/BluetoothAdapter(11799): disable()
,E/BluetoothManagerService( 3490): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3490): New client listening to asynchronous messages
,I/WifiManager(11799): packageName : com.example.hello
,D/SecContentProvider( 3490): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3490): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3490): mCursor = null
,D/WifiService( 3490): setWifiEnabled: false pid=11799, uid=10656
,E/WifiService( 3490): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3490): name = wifi_on
,E/WifiStateMachine( 3490): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3827): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3827): wlan0: Setting scan request: 0 sec 0 usec
I/jxcore-log(11799): ****TEST TOOK:  5084  ms ****
I/jxcore-log(11799): 
,I/jxcore-log(11799): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11799): 
,I/wpa_supplicant( 3827): P2P: Current p2p state = IDLE
E/WifiStateMachine( 3490): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3490): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3490): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3490): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 3827): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3490): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3490): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3490): do suspend true
,D/WifiP2pService( 3490): InactiveState{ what=143375 }
,D/WifiP2pService( 3490): P2pEnabledState{ what=143375 }
,D/CommandListener( 2847): Clearing all IP addresses on wlan0
,V/NativeCrypto( 4667): Read error: ssl=0xaf632e00: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 3694): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,V/NativeCrypto( 4667): SSL shutdown failed: ssl=0xaf632e00: I/O error during system call, Broken pipe
,E/WifiStateMachine( 3490): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3490): updateNetworkInfo()
D/ConnectivityService( 3490): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3490): updateNetworkInfo()
D/ConnectivityService( 3490): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore( 3490): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller( 3490): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
,E/GCM     ( 4667): Wifi connection closed with errorCode 20
,D/ConnectivityService( 3490): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10014
,D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
E/WifiStateMachine( 3490): scanCount==0 - aborting
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): ValidatedState{ when=-3ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): DefaultState{ when=-3ms what=532488 arg1=10014 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/System.out( 3490): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 3490): Tagging socket 390 with tag ffffffff00000000{4294967295,0} uid 10014, pid: 3490, getuid(): 1000
,I/System.out( 3490): (HTTPLog)-Static: isSBSettingEnabled false
,E/WifiStateMachine( 3490): [1,456,842,950,587 ms] noteScanEnd no scan source
,D/WifiScanningService( 3490): SCAN_AVAILABLE : 1
,D/WifiScanningService( 3490): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 3490): SCAN_AVAILABLE : 1
D/WifiP2pService( 3490): InactiveState{ what=131204 }
E/WifiStateMachine( 3490): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/RttService( 3490): EnabledState got{ when=-5ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 3490): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiP2pService( 3490): P2pEnabledState{ what=131204 }
,I/Hs20UtilService( 4116): Starting #8
,I/Hs20UtilService( 4116): Message received 5007
,D/WifiP2pService( 3490): sending p2p connection changed broadcast: FAILED
,D/EnterpriseController( 2847): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2847): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 3490): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3490): Not allowed due to - mEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): Validated
,D/ConnectivityManager.CallbackHandler( 3694): CM callback handler got msg 524292
D/ConnectivityService( 3490): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 4825): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 3985): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3490): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 3490): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3490): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/NearbySettings(11606): MountReceiver.onReceive - Create HandlerThread
D/CSLegacyTypeTracker( 3490): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.103/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NearbySettings(11606): MountReceiver.onReceive - Start HandlerThread
D/CSLegacyTypeTracker( 3490): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/WifiStateMachine( 3490): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityService( 3490): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3490): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3490): NetworkAgent: NetworkAgent channel lost
,D/NearbySettings(11606): MountReceiver.onReceive - Create mPrefHandler
,D/WifiDisplayController( 3490): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3490): onP2pDisconnected
,D/IpRemoteDisplayController( 3490): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3490): WfdBridgeServer is already null
D/WifiP2pService( 3490): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiP2pService( 3490): P2pDisablingState
,D/WifiP2pService( 3490): P2pDisablingState{ what=147458 }
D/WifiP2pService( 3490): p2p socket connection lost
,D/EntConnectivity( 3490): Not allowed due to - mEnabled false
,D/ConnectivityService( 3490): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/ConnectivityService( 3490): updateNetworkInfo()
D/ConnectivityService( 3490): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService( 3490): updateNetworkInfo()
D/WifiP2pService( 3490): P2pDisabledState
,E/WifiStateMachine( 3490): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 3490): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3490): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/NearbySettings(11606): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/WifiDisplayController( 3490): disconnect
D/WifiDisplayController( 3490): updateConnection
D/WifiDisplayController( 3490): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3490): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/Tethering( 3490): MasterInitialState.processMessage what=3
,V/NearbySettings(11606): DMSUtil.isNetworkConnected - flag-null, state-null
D/SmartBondingService( 3490): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 3490): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,D/SmartBondingService( 3490): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
V/NetworkStats( 3490): updateIfacesLocked()
V/NetworkStats( 3490): performPollLocked(flags=0x1)
E/WifiStateMachine( 3490): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/SmartBondingService( 3490): getSBEnabled() enabled =false
E/WifiStateMachine( 3490): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
D/SmartBondingService( 3490): getSBEnabled() enabled =false
E/native  ( 3490): do suspend true
D/SmartBondingService( 3490): getSBEnabled() enabled =false
D/NetworkStatsFactory( 3490): UpdateStatsForKnox
,D/WifiP2pService( 3490): P2pDisabledState{ what=143375 }
D/WifiP2pService( 3490): DefaultState{ what=143375 }
,D/SmartBondingService( 3490): getNetworkEnabled : wifi : true mobile : false
,D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3694): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3694): updateDataNetType()
D/StatusBar.NetworkController( 3694): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3694): updateLTEICONDataNetType:0
,V/NetworkStats( 3490): performPollLocked() took 11ms
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
V/NetworkStats( 3490): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/NearbySettings(11606): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiDisplayController( 3490): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3490): onP2pDisconnected
D/StatusBar.NetworkController( 3694): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/IpRemoteDisplayController( 3490): disconnectWfdBridgeServer
D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength: hasService=false ss=null
D/IpRemoteDisplayController( 3490): WfdBridgeServer is already null
,D/StatusBar.NetworkController( 3694): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/CommandListener( 2847): Clearing all IP addresses on wlan0
,D/WifiService( 3490): New client listening to asynchronous messages
I/NearbySettings(11606): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11606): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11606): MountReceiver.onReceive - Set preference state off
D/AllShareCastTile( 3694): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,E/WifiStateMachine( 3490): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
V/NearbySettings(11606): MountReceiver.mPrefHandler - 7002
D/WifiDisplayAdapter( 3490): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 3694): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine( 3490): stopping supplicant
I/wpa_supplicant( 3827): p2p0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3490): setWifiState: disabling
,I/WifiTrafficPoller( 3490): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2( 3490): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3490): mCursor = null
D/SmartBondingService( 3490): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3490): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/StatusBar.NetworkController( 3694): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3694): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(0)
D/SmartBondingService( 3490): getNetworkEnabled : wifi : false mobile : false
,D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
,D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 3694): onReceive : 0, 0
,E/WifiStateMachine( 3490): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3490): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/SignOutReceiver(11125): NETWORK_STATE_CHANGED_ACTION
,D/NearbySettings(11606): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings(11606): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11606): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings(11606): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11606): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11606): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11606): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 3827): Blacklist: Clear (all) 
,E/Zygote  (11935): MountEmulatedStorage()
E/Zygote  (11935): v2
I/libpersona(11935): KNOX_SDCARD checking this for 10079
I/libpersona(11935): KNOX_SDCARD not a persona
,I/SELinux (11935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3490): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=11935 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11935): TimaSignature is unavailable
,D/ActivityThread(11935): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/ResourcesManager(11935): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
I/wpa_supplicant( 3827): p2p0: CTRL-EVENT-TERMINATING 
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileShare-Server(11935): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
I/wpa_supplicant( 3827): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
I/wpa_supplicant( 3827): wlan0: State: COMPLETED -> DISCONNECTED
,D/FileWriteThread_Telephony( 3985): FileWriteThread : threadType = 3
I/wpa_supplicant( 3827): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 3827): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/ActivityManager( 3490): Killing 10879:com.facebook.system/u0a10 (adj 15): bgCount ##31
,I/Hs20UtilService( 4116): Starting #9
,I/Hs20UtilService( 4116): Message received 5007
,D/NearbySettings(11606): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11606): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11606): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11606): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11606): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11606): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11606): MountReceiver.mPrefHandler - 7002
,D/AndroidRuntime(11917): 
D/AndroidRuntime(11917): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(11917): CheckJNI is OFF
,D/AndroidRuntime(11917): readGMSProperty: start
D/AndroidRuntime(11917): readGMSProperty: already setted!!
,D/AndroidRuntime(11917): readGMSProperty: end
,D/AndroidRuntime(11917): addProductProperty: start
,I/SignOutReceiver(11125): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4116): Starting #10
,I/Hs20UtilService( 4116): Message received 5011
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11966): MountEmulatedStorage()
I/libpersona(11966): KNOX_SDCARD checking this for 10127
E/Zygote  (11966): v2
I/libpersona(11966): KNOX_SDCARD not a persona
,I/SELinux (11966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3490): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=11966 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/wpa_supplicant( 3827): Blacklist: Clear (all) 
,D/TimaKeyStoreProvider(11966): TimaSignature is unavailable
,D/ActivityThread(11966): Added TimaKeyStore provider
,D/ResourcesManager(11966): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,D/KeyguardWallpaperUpdator(11966): cancelUpdateWallpaper
,D/KeyguardWallpaperUpdator(11966): cancelUpdateCategory
D/KeyguardWallpaperUpdator(11966): stopCheckCategoryVersion
,I/SignOutReceiver(11125): WIFI_STATE_CHANGED_ACTION
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,E/AffinityControl(11917): AffinityControl: registerfunction enter
,E/Zygote  (11987): MountEmulatedStorage()
,E/Zygote  (11987): v2
I/libpersona(11987): KNOX_SDCARD checking this for 1000
I/libpersona(11987): KNOX_SDCARD not a persona
,I/SELinux (11987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AndroidRuntime(11917): Calling main entry com.android.commands.pm.Pm
,I/SELinux (11987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11987): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3490): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=11987 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3490): Killing 10922:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##31
,D/PersonaManagerService( 3490): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3490): START PACKAGE DELETE: observer{650945648}
D/PackageManager( 3490): pkg{<packageName>}
D/PackageManager( 3490): user{0}
D/PackageManager( 3490): caller{2000}
D/PackageManager( 3490): flags{3}
D/PersonaManagerService( 3490): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3490): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3490): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3490): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3490): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3490): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3490): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3490): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3490): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3490): !@killApplicatoin: 10656, uninstall pkg
I/ActivityManager( 3490): Force stopping com.example.hello appid=10656 user=-1: uninstall pkg
,I/ActivityManager( 3490): Killing 11799:com.example.hello/u0a656 (adj 0): stop com.example.hello
,I/ActivityManager( 3490):   Force finishing activity ActivityRecord{b84b26a u0 com.example.hello/.MainActivity t26}
,D/TimaKeyStoreProvider(11987): TimaSignature is unavailable
,D/ActivityThread(11987): Added TimaKeyStore provider
,I/SurfaceFlinger( 2851): id=15 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2851): id=15 Removed NainActivit (-2/8)
,D/PointerIcon( 3490): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3490): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3490): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3490): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3490): Skipping PackageSetting{2ff6c30 com.test.thalitest/10655} due to missing metadata
,D/WifiService( 3490): Client connection lost with reason: 4
,I/ActivityManager( 3490): Force stopping com.example.hello appid=10656 user=0: pkg removed
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(11987): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/ConnectivityService( 3490): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 8873): Explicit concurrent mark sweep GC freed 25734(1485KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.089ms total 38.619ms
,I/InputReader( 3490): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4667): Ignoring removeGeofence because network location is disabled.
,D/LWLocationManager(11208): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(11208): getLastUiLocationId() : mLastUiLocationId = -100
,E/SamsungIME( 4468): mOCRHelper is null
,I/DBG_DM  ( 6228): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/ActivityManager( 3490): Killing 10898:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
W/fb4a(:<default>):QeInternalImpl(10591): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/EnterpriseDeviceManagerService( 3490): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3490): Admin package name: com.google.android.gms
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/DBG_DM  ( 6228): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourceType( 5359): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5359): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/art     ( 3490): Explicit concurrent mark sweep GC freed 44269(2MB) AllocSpace objects, 6(144KB) LOS objects, 23% free, 50MB/66MB, paused 2.087ms total 166.082ms
,I/art     ( 3490): WaitForGcToComplete blocked for 165.463ms for cause Explicit
,D/ResourcesManager( 3490): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/Zygote  (12009): MountEmulatedStorage()
E/Zygote  (12009): v2
I/libpersona(12009): KNOX_SDCARD checking this for 10063
I/libpersona(12009): KNOX_SDCARD not a persona
I/SELinux (12009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3490): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12009 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/fb4a(:<default>):UserScope(10591): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,W/fb4a(:<default>):QeInternalImpl(10591): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10591): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/SecContentProvider2( 3490): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3490): mCursor = null
,D/TimaKeyStoreProvider(12009): TimaSignature is unavailable
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ActivityThread(12009): Added TimaKeyStore provider
,I/wpa_supplicant( 3827): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine( 3490): Supplicant connection lost
,D/Tethering( 3490): InitialState.processMessage what=4
,E/Tethering( 3490): No numeric data
,D/RegisteredServicesCache( 3967): empty dynamic service
,E/WifiStateMachine( 3490): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/Tethering( 3490): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiNative-HAL( 3490): callSECApiBoolean - ID [21]
D/ResourcesManager(12009): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,E/WifiStateMachine( 3490): setWifiState: disabled
D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,V/NetworkStats( 3490): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
,D/HotspotTile( 3694): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3694): updateTetherState():false, false
,D/NetworkStatsFactory( 3490): UpdateStatsForKnox
D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,V/NetworkStats( 3490): performPollLocked() took 11ms
,D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3694): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3694): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 3694): Wifi onReceive(1)
D/HotspotTile( 3694): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3694): onStateChanged: Wi-Fi
,D/HotspotTile( 3694): onReceive : 1, 0
,W/Settings( 4667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
D/NtpTrustedTime( 3490): currentTimeMillis() cache hit
,W/ResourcesManager(11208): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/VRSetupWizardStub/PackageIntentReceiver(12009): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12009): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12009): packagename:com.example.hello
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 3490): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  (12026): MountEmulatedStorage()
,E/Zygote  (12026): v2
I/libpersona(12026): KNOX_SDCARD checking this for 10021
I/libpersona(12026): KNOX_SDCARD not a persona
,I/SELinux (12026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 3490): Explicit concurrent mark sweep GC freed 8795(487KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 50MB/66MB, paused 2.125ms total 177.680ms
,I/SELinux (12026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/SELinux (12026): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3490): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12026 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3490): Killing 10957:com.samsung.android.app.watchmanagerstub/u0a121 (adj 15): bgCount ##31
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11208): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager(11208): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11208): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3490): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3490): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 3490): delete codoeFile: 
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
D/TimaKeyStoreProvider(12026): TimaSignature is unavailable
,D/ActivityThread(12026): Added TimaKeyStore provider
I/AASAUninstall( 3490):  com.example.hello not target!
,D/PackageManager( 3490): result of delete: 1{650945648}
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/AndroidRuntime(11917): Shutting down VM
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(12026): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.521: (12026): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 01 15:35:51 GMT+01:00 2016
,I/KLMS-2.4.521: (12026): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3490): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3490): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12026): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12026): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12026): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (12026): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12026): KLMSIntentService(): PACKAGE_REMOVED
,E/Zygote  (12042): MountEmulatedStorage()
E/Zygote  (12042): v2
I/libpersona(12042): KNOX_SDCARD checking this for 10106
I/libpersona(12042): KNOX_SDCARD not a persona
,I/SELinux (12042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11208): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/SELinux (12042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/KLMS-2.4.521: (12026): KLMSIntentService(): listeningToPackageRemoved().START
,E/SELinux (12042): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3490): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12042 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (12026): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(11208): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,I/art     ( 2887): Explicit concurrent mark sweep GC freed 8715(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 972us total 21.841ms
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/TimaKeyStoreProvider(12042): TimaSignature is unavailable
,D/ActivityThread(12042): Added TimaKeyStore provider
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/art     ( 2887): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 370us total 17.192ms
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/art     ( 2887): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 332us total 9.626ms
,E/WifiStateMachine( 3490): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine( 3490): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3490): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/Zygote  (12057): MountEmulatedStorage()
E/Zygote  (12057): v2
I/libpersona(12057): KNOX_SDCARD checking this for 1000
I/libpersona(12057): KNOX_SDCARD not a persona
,I/SELinux (12057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12026): KLMSIntentService(): listeningToPackageRemoved().END
,I/SELinux (12057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3490): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12057 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (12057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/KLMS-2.4.521: (12026): KLMSIntentService(): onDestroy()
D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
D/TimaKeyStoreProvider(12057): TimaSignature is unavailable
D/ActivityThread(12057): Added TimaKeyStore provider
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(12042): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(12057): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(12057): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 3490): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/RCPManager(12057):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 3490):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3490): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/elm:14491(12042): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12042): ELMEngine.ELMEngine( context ).
,D/elm:14491(12042): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(11208): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/Mms/FreeMessageStatusReceiver(11688): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/elm:14491(12042): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(11208): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/elm:14491(12042): ElmAgentService : onCreate()
,D/elm:14491(12042): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
W/Resources( 3490): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Books/Books.apk
,D/elm:14491(12042): MainReceiver.listeningToPackageRemoved()
,D/elm:14491(12042): MDMBridge.getInstance()
,D/elm:14491(12042): MDMBridge.getAllLicenseInfoFromSDK()
D/Mms/FreeMessageReceiverService(11688): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(11688): onHandleIntent: ACTION_PACKAGE_REMOVED
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/elm:14491(12042): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/Zygote  (12078): MountEmulatedStorage()
I/libpersona(12078): KNOX_SDCARD checking this for 10101
E/Zygote  (12078): v2
I/libpersona(12078): KNOX_SDCARD not a persona
,I/SELinux (12078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/SELinux (12078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12078): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3490): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12078 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3490): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/elm:14491(12042): ElmAgentService : onDestroy().
I/CrashAnrDetector( 3490): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 3490): clearDefaults: com.example.hello
,D/GpsLocationProvider( 3490): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/RCPManagerService( 3490): PackageReceiver onReceive()
I/HarmonyEASService( 3490): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3490): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3490): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3490): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3490): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3490): uID is 10656
V/EnterpriseBillingPolicy( 3490): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3490): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3490): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3490): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3490): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3490): getBillingProfileForVpnEngine - start - com.example.hello
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11187): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11187): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
V/EnterpriseBillingPolicyStorage( 3490): getBillingProfileForVpnEngine - end - null
,I/TapandpayWidget:Utils(11187): Clear T&P info.
,D/TaskPersister( 3490): removeObsoleteFile: deleting file=26_task.xml
D/SmartBondingService( 3490): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService( 3490): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SLocation( 3490): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService( 3490): getSBEnabled() enabled =false
D/SmartBondingService( 3490): getSBEnabled() enabled =false
D/SmartBondingService( 3490): getSBEnabled() enabled =false
D/SmartBondingService( 3490): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,W/SLocation( 3490): No Active Data Connection
,D/SmartBondingService( 3490): getNetworkEnabled : wifi : false mobile : false
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11187): Widget is not attached.
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/TimaKeyStoreProvider(12078): TimaSignature is unavailable
,D/ActivityThread(12078): Added TimaKeyStore provider
,D/SmartBondingService( 3490): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  (12094): MountEmulatedStorage()
E/Zygote  (12094): v2
I/libpersona(12094): KNOX_SDCARD checking this for 10019
I/libpersona(12094): KNOX_SDCARD not a persona
,I/SELinux (12094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3490): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12094 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (12094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,I/ApplicationPolicy( 3490): updateDataUsageMap
I/ApplicationPolicy( 3490): updateDataUsageMap  idList is null 
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(12078): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider(12094): TimaSignature is unavailable
,I/ActivityManager( 3490): Killing 10974:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,D/ActivityThread(12094): Added TimaKeyStore provider
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/ActivityManager( 3490): Killing 10989:com.samsung.helphub/1000 (adj 15): bgCount ##31
,I/TactileAssist( 3490): enable value -1
I/TactileAssist( 3490): internal enable value -1
I/TactileAssist( 3490): intensity value -1
I/TactileAssist( 3490): saveAppList value true
,I/TactileAssist( 3490): List of disabled apps :
,I/ActivityManager( 3490): Killing 11056:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,D/ResourcesManager(12094): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/BatteryService( 3490): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3490): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3490): online:4, current avg:116, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-191
D/BatteryService( 3490): stay LED for fully charged
D/BatteryService( 3490): Sending ACTION_BATTERY_CHANGED.
,D/ResourcesManager(11208): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/PackageBroadcastService( 4825): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 4825): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 4825): Removing dialog suppression flag for package com.example.hello
,E/SQLiteLog( 4825): (10) POSIX Error : 9 SQLite Error : 3850
D/UsbHostManager( 3490): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
E/SQLiteLog( 4825): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/MotionRecognitionService( 3490): Plugged
I/MotionRecognitionService( 3490): setPowerConnected  = true
D/UsbHostManager( 3490): displayNotification : [02h,02h,01h]
,E/DriveAsyncService( 4825): disk I/O error (code 3850)
E/DriveAsyncService( 4825): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4825): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4825): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/DriveAsyncService( 4825): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4825): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4825): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/DriveAsyncService( 4825): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/DriveAsyncService( 4825): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4825): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4825): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4825): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4825): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4825): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4825): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4825): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4825): 	at java.lang.Thread.run(Thread.java:818)
,D/UsbHostManager( 3490): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3490): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
,D/UsbSettingsManager( 3490): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/SQLiteLog( 4825): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/ResourcesManager(11208): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,E/SQLiteDatabase( 4825): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4825): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 4825): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 4825): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 4825): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4825): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 4825): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4825): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 4825): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 4825): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 4825): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4825): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 4825): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4825): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4825): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 4825): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 4825): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
E/AndroidRuntime( 4825): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 4825): Process: com.google.android.gms, PID: 4825
E/AndroidRuntime( 4825): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4825): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4825): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 4825): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4825): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/UsbHostManager( 3490): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3490): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3490): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3490): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3490): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3490): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3490): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3490): displayNotification : [09h,00h,00h]
D/com.sec.android.service.health.upgrade.UninstallReceiver(12094): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12094): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(12094): onReceive() : package name is not s health. Return !!!
D/DocsApplication(12078): Installing DEX configuration.
V/ApplicationPolicy( 3490): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Zygote  (12119): MountEmulatedStorage()
E/Zygote  (12119): v2
I/libpersona(12119): KNOX_SDCARD checking this for 10059
I/libpersona(12119): KNOX_SDCARD not a persona
D/UsbHostManager( 3490): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3490): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
I/SELinux (12119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3490): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=12119 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux (12119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12119): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/EventHub( 3490): Removing device '/dev/input/event10' due to inotify event
,D/DexInstaller(12078): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12078): Provided clientMode=RELEASE, packageInfo=PackageInfo{3821c8fb com.google.android.apps.docs}
,D/TAG     (12078): onCreate()
,I/EventHub( 3490): Removing device '/dev/input/event7' due to inotify event
,E/DropBoxManagerService( 3490): Can't write: system_app_crash
E/DropBoxManagerService( 3490): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3490): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3490): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3490): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3490): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3490): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3490): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3490): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3490): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3490): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3490): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3490): 	... 5 more
,D/CrossAppStateProvider(12078): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/MtpClient(11591): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/ResourcesManager(11208): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/MtpClient(11591): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/TimaKeyStoreProvider(12119): TimaSignature is unavailable
,D/ActivityThread(12119): Added TimaKeyStore provider
,I/EventHub( 3490): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(11208): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/SQLiteLog( 4825): (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4825): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4825): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4825): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 4825): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 4825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/PhenotypeInitializer( 4825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/PhenotypeInitializer( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 4825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 4825): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 4825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 4825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 4825): 	at android.os.Looper.loop(Looper.java:145)
E/PhenotypeInitializer( 4825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4825): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4825): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 4825): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4825): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ClearPendingStateOp( 4825): Runtime exception while performing operation
E/ClearPendingStateOp( 4825): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 4825): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/ClearPendingStateOp( 4825): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/ClearPendingStateOp( 4825): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 4825): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 4825): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 4825): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 4825): 	at java.lang.Thread.run(Thread.java:818)
,E/GMPM-SVC( 4825): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,F/ClearPendingStateOp( 4825): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 4825): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
F/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
F/ClearPendingStateOp( 4825): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
F/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 4825): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
F/ClearPendingStateOp( 4825): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
F/ClearPendingStateOp( 4825): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 4825): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 4825): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 4825): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 4825): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 4825): 	at java.lang.Thread.run(Thread.java:818)
D/ChimeraCfgMgr( 4825): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4825): Module APK com.google.android.play.games already loaded
,E/SharedPreferencesImpl( 4825): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,I/EventHub( 3490): Removing device '/dev/input/event9' due to inotify event
,I/Process ( 4825): Sending signal. PID: 4825 SIG: 9
,D/ResourcesManager(12119): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(12119): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/EventHub( 3490): Removing device '/dev/input/event11' due to inotify event
,E/DropBoxManagerService( 3490): Can't write: system_app_wtf
E/DropBoxManagerService( 3490): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3490): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3490): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3490): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3490): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3490): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3490): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3490): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3490): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3490): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3490): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3490): 	... 5 more
,E/SQLiteLog( 4667): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4667): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4667): Shutting down VM
,E/AndroidRuntime( 4667): FATAL EXCEPTION: main
E/AndroidRuntime( 4667): Process: com.google.android.gms.persistent, PID: 4667
E/AndroidRuntime( 4667): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4667): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4667): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4667): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4667): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4667): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4667): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4667): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4667): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4667): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4667): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4667): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4667): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4667): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4667): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4667): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4667): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4667): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4667): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4667): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4667): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4667): 	... 9 more
,D/LocationWidgetApplication(11208): getLastUiLocationId() : mLastUiLocationId = -100
,V/ApplicationPolicy( 3490): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,D/Compatibility(12119): onReceive() it will make start service
,I/EventHub( 3490): Removing device '/dev/input/event12' due to inotify event
,W/ActivityManager( 3490): Process com.google.android.gms has crashed too many times: killing!
,E/DropBoxManagerService( 3490): Can't write: system_app_crash
E/DropBoxManagerService( 3490): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3490): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3490): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3490): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3490): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3490): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3490): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3490): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3490): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3490): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3490): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3490): 	... 5 more
,I/ActivityManager( 3490): Killing 4667:com.google.android.gms.persistent/u0a14 (adj 0): crash
,E/JavaBinder( 3490): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 3490): Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@114ebde1 (in com.google.android.gms)
W/ActivityManager( 3490): android.os.TransactionTooLargeException
W/ActivityManager( 3490): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3490): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3490): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager( 3490): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1686)
W/ActivityManager( 3490): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:17705)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6129)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:7561)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:14542)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:14421)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15187)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14695)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14677)
W/ActivityManager( 3490): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1457)
W/ActivityManager( 3490): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3490): 	at android.os.Binder.execTransact(Binder.java:446)
,V/BackupManagerService( 3490): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3490): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,I/EventHub( 3490): Removing device '/dev/input/event13' due to inotify event
,D/Compatibility(12119): onHandleIntent()
,W/BroadcastQueue( 3490): Unable to launch app com.google.android.gms/10014 for broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }: process is bad
,D/ConnectivityService( 3490): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@36d87638)
,D/ConnectivityService( 3490): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager( 3490): Process com.google.android.gms (pid 4825)(adj 0) has died(205,1249)
I/EventHub( 3490): Removing device '/dev/input/event14' due to inotify event
,E/ConnectivityService( 3490): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
D/Compatibility(12119): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10656, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
,W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
,W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20998ms
,W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 30997ms
,D/Compatibility(12119): found: 2
W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30995ms
W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30993ms
W/ActivityManager( 3490): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 40993ms
,D/Compatibility(12119): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(12119): skipping ResolveInfo{1ec13d18 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(12119): considering ResolveInfo{11748371 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(12119): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(12119): enabling receiver ResolveInfo{90e9556 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/SSRM:n  ( 3490): SIOP:: AP = 270, PST = 282, CUR = 116
,E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3490): checkUser: useridlist=null, currentuser=0
,D/Compatibility(12119): enabling receiver ResolveInfo{2339f9d7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/LocationManagerService( 3490): Location listener died
D/GpsStatusListenerHelper( 3490): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@357f9611
I/LocationManagerService( 3490): remove 1f160895 by com.google.android.gms
D/LocationManagerService( 3490): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService( 3490): Location listener died
I/LocationManagerService( 3490): remove 3bd161f5 by com.google.android.gms
D/WifiService( 3490): Client connection lost with reason: 4
D/LocationManagerService( 3490): provider request: passive ProviderRequest[ON interval=0]
,D/Compatibility(12119): enabling receiver ResolveInfo{3d1912c4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility(12119): enabling receiver ResolveInfo{2efce5ad com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility(12119): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default

```
