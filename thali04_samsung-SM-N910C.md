#### Test 61703351a2a4153_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,V/AlarmManager( 3522): waitForAlarm result :4
D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:105, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:100
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
D/BatteryService( 3522): stay LED for fully charged
D/SSRM:n  ( 3522): SIOP:: AP = 290, PST = 332, CUR = 105
D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5605): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5605): Disconnected process message: 10
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PowerManagerService( 3522): [PWL] Off : 30s ago
D/AndroidRuntime(11910): 
D/AndroidRuntime(11910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11910): CheckJNI is OFF
D/AndroidRuntime(11910): readGMSProperty: start
D/AndroidRuntime(11910): readGMSProperty: already setted!!
D/AndroidRuntime(11910): readGMSProperty: end
D/AndroidRuntime(11910): addProductProperty: start
E/AffinityControl(11910): AffinityControl: registerfunction enter
D/AndroidRuntime(11910): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
D/FocusedStackFrame( 3522): Set to : 0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (11925): MountEmulatedStorage()
E/Zygote  (11925): v2
I/libpersona(11925): KNOX_SDCARD checking this for 10671
I/libpersona(11925): KNOX_SDCARD not a persona
I/SELinux (11925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11925 uid=10671 gids={50671, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (11925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(11910): Shutting down VM
E/SELinux (11925): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11925): TimaSignature is unavailable
D/ActivityThread(11925): Added TimaKeyStore provider
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3522): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(11925): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger( 2854): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2854): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4004): updateVisibility : ActivityRecord{12cf4399 token=android.os.BinderProxy@53f647d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4004): onTrimMemory. Level: 20
I/WebViewFactory(11925): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11925): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11925): Loading: webviewchromium
I/LibraryLoader(11925): Time to load native libraries: 4 ms (timestamps 4835-4839)
I/LibraryLoader(11925): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11925): Binding Chromium to main looper Looper (main, tid 1) {2d0a91ea}
I/LibraryLoader(11925): Expected native library version number "",actual native library version number ""
I/chromium(11925): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11925): Initializing chromium process, renderers=0
W/art     (11925): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11925): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11925): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11925): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11925): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11925): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11925): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11925): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(11925): CordovaWebView is running on device made by: samsung
,W/art     (11925): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11925): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(11925): performCreate Call secproduct feature valuefalse
D/Activity(11925): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11925): Render dirty regions requested: true
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2854): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer(11925): Initialized EGL, version 1.4
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11925): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279942384 
,D/OpenGLRenderer(11925): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11925): Enabling debug mode 0
,D/mali_winsys(11925): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11925): updateVisibility : ActivityRecord{26e3499a token=android.os.BinderProxy@29817119 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{1f42f73b u0 com.example.hello/.MainActivity t25} time:125292
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 57989(3MB) AllocSpace objects, 21(336KB) LOS objects, 24% free, 48MB/64MB, paused 1.574ms total 152.041ms
,W/IInputConnectionWrapper(11925): showStatusIcon on inactive InputConnection
I/Timeline(11925): Timeline: Activity_idle id: android.os.BinderProxy@29817119 time:125438
,I/chromium(11925): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(11925): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue(11925): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(11925): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11925): 
,D/jxcore_app_log(11925): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1360571904
,W/jxcore-log(11925): Initializing JXcore engine
W/jxcore-log(11925): JXcore engine is ready
,E/auditd  ( 4571): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11925): Starting JXcore engine
,W/jxcore-log(11925): Platform android
W/jxcore-log(11925): 
W/jxcore-log(11925): Process ARCH arm
W/jxcore-log(11925): 
,I/jxcore-log(11925): JXcore Cordova bridge is ready!
I/jxcore-log(11925): 
W/jxcore-log(11925): JXcore engine is started
,E/jxcore-log(11925): >> samsung-SM-N910C
E/jxcore-log(11925): 
,I/jxcore-log(11925): Total memory 2970812416
I/jxcore-log(11925): 
,I/jxcore-log(11925): Free memory 75800576
I/jxcore-log(11925): 
I/jxcore-log(11925): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11925): 
I/jxcore-log(11925): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11925): 
,I/jxcore-log(11925): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log(11925): 
,I/jxcore-log(11925): Size 1440 2560
I/jxcore-log(11925): 
,I/jxcore-log(11925): Screen Brightness 134
I/jxcore-log(11925): 
,E/jxcore-log(11925): Dummy Error Log.
E/jxcore-log(11925): 
,I/jxcore-log(11925): getBuffer is called!!!!
I/jxcore-log(11925): 
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter(11925): disable(),
,D/SettingsProvider( 3522): name = bluetooth_on
,D/BluetoothAdapterState( 5605): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5605): Setting state to 13
,I/BluetoothAdapterState( 5605): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5605): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5605): updateAdapterState state is 13
,I/BluetoothPbapService( 5605): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 5605): Autoconnection is available 
,D/BluetoothSocket( 5605): close() in, this: android.bluetooth.BluetoothSocket@4490f95, channel: 19, state: LISTENING
,D/BluetoothAdapterService( 5605): updateAdapterState prevState = 12newState = 13
,D/BluetoothSocket( 5605): close() this: android.bluetooth.BluetoothSocket@4490f95, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@af281dd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@381938aamSocket: android.net.LocalSocket@f7d1c9b impl:android.net.LocalSocketImpl@31de9838 fd:FileDescriptor[72]
,D/BluetoothAdapterService( 5605): terminating service from this receiver
,D/BluetoothSocket( 5605): Closing mSocket: android.net.LocalSocket@f7d1c9b impl:android.net.LocalSocketImpl@31de9838 fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 5605): onBluetoothDisable()
,D/SecContentProvider( 3522): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 5605): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5605): Scan Mode:20
,D/BluetoothAdapterState( 5605): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 5605): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 5605): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 5605): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 5605): cmd socket is not created
,D/btif_config_util( 5605): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 5605): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 5605): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 5605): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 5605): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x001b not found for deregistration
,W/InputMethodManagerService( 3522): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 3522): [BT Setting State] State =13
,D/BluetoothTile( 3691):  onBluetoothStateChange:
,D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3691): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 4485): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/StatusBarManagerService( 3522): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3522): setIconVisibility slot=bluetooth visible=false
,D/BluetoothTile( 3691):  handleUpdatestate:false name:null
,D/PhoneStatusBar( 3691): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,D/BluetoothSocket( 5605): close() in, this: android.bluetooth.BluetoothSocket@332a3576, channel: 5, state: LISTENING
D/BluetoothSocket( 5605): close() this: android.bluetooth.BluetoothSocket@332a3576, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ac0d152, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3486e777mSocket: android.net.LocalSocket@3500ffe4 impl:android.net.LocalSocketImpl@2dbc9c4d fd:FileDescriptor[74]
D/BluetoothSocket( 5605): Closing mSocket: android.net.LocalSocket@3500ffe4 impl:android.net.LocalSocketImpl@2dbc9c4d fd:FileDescriptor[74]
I/BtOppRfcommListener( 5605): stopping Accept Thread
D/BluetoothTile( 3691):  handleUpdatestate:false name:null
D/BluetoothSocket( 5605): close() in, this: android.bluetooth.BluetoothSocket@217c3302, channel: 12, state: LISTENING
D/BluetoothSocket( 5605): close() this: android.bluetooth.BluetoothSocket@217c3302, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@745934c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ef88413mSocket: android.net.LocalSocket@11c03650 impl:android.net.LocalSocketImpl@3143b049 fd:FileDescriptor[77]
D/BluetoothSocket( 5605): Closing mSocket: android.net.LocalSocket@11c03650 impl:android.net.LocalSocketImpl@3143b049 fd:FileDescriptor[77]
,I/BtOppRfcommListener( 5605): BluetoothSocket listen thread finished
,D/STATUSBAR-QSTileView( 3691): onStateChanged: Bluetooth
,D/WifiService( 3522): New client listening to asynchronous messages
,I/WifiManager(11925): packageName : com.example.hello
,D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3522): mCursor = null
,D/WifiService( 3522): setWifiEnabled: false pid=11925, uid=10671
E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3522): name = wifi_on
,W/ContextImpl(11614): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log(11925): ****TEST TOOK:  5183  ms ****
I/jxcore-log(11925): 
,I/jxcore-log(11925): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11925): 
E/WifiStateMachine( 3522): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 3834): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
E/WifiStateMachine( 3522): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3522): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/WifiP2pService( 3522): InactiveState{ what=143375 }
,D/LocalBluetoothProfileManager(11614): PANU : true
D/LocalBluetoothProfileManager(11614): Adding local MAP profile
,D/BluetoothMap(11614): Create BluetoothMap proxy object
,D/WifiP2pService( 3522): P2pEnabledState{ what=143375 }
,D/CommandListener( 2850): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 3691): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/Netd    ( 2850): ifc_reset_connections failed on iface wlan0 for address 192.168.1.103/24 (Unknown error -1)
,E/WifiStateMachine( 3522): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling,
E/WifiConfigStore( 3522): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,E/WifiStateMachine( 3522): scanCount==0 - aborting
,E/WifiStateMachine( 3522): [1,457,094,263,468 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,D/WifiP2pService( 3522): InactiveState{ what=131204 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=131204 }
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3691): applyOpen
,E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,W/ContextImpl(11614): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2137 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/WifiP2pService( 3522): sending p2p connection changed broadcast: FAILED
,D/Bluetoothsap(11614): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager(11614): LocalBluetoothProfileManager construction complete
,E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/WifiNetworkAgent( 3522): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService( 3522): SCAN_AVAILABLE : 1
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/RttService( 3522): SCAN_AVAILABLE : 1
,D/WifiDisplayController( 3522): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 3522): onP2pDisconnected
,D/WifiScanningService( 3522): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 3522): sending p2p connection changed broadcast: DISCONNECTED
D/IpRemoteDisplayController( 3522): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3522): WfdBridgeServer is already null
,D/RttService( 3522): EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService( 3522): P2pDisablingState
,D/WifiP2pService( 3522): P2pDisablingState{ what=147458 }
D/WifiP2pService( 3522): p2p socket connection lost
,D/WifiP2pService( 3522): P2pDisabledState
,E/WifiStateMachine( 3522): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3522): do suspend true
,D/WifiDisplayController( 3522): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
E/WifiStateMachine( 3522): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 3522): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3522): disconnect
D/WifiDisplayController( 3522): updateConnection
D/WifiDisplayController( 3522): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/DockEventReceiver(11614): finishStartingService: stopping service
D/WifiDisplayController( 3522): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3522): onP2pDisconnected
D/IpRemoteDisplayController( 3522): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3522): WfdBridgeServer is already null
,D/BluetoothNotiBroadcastReceiver(11614): onReceive
,D/BluetoothPan(11614): BluetoothPAN Proxy object connected
D/PanProfile(11614): Bluetooth service connected
,W/bt-l2cap( 5605): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5605): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5605): ag scb idx 1 not allocated
W/bt-btif ( 5605): ag scb idx 2 not allocated
E/bt-btif ( 5605): BTA AG is already disabled, ignoring ...
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/CommandListener( 2850): Clearing all IP addresses on wlan0
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService( 3522): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/bt_userial( 5605): RX termination
W/bt_userial( 5605): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 5605): Leaving userial_read_thread()
D/bt_userial( 5605): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 5605): hw_epilog_process
E/WifiStateMachine( 3522): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/AllShareCastTile( 3691): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
I/bt_userial_vendor( 5605): device fd = 65 close
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3522): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 3522): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 3691): CM callback handler got msg 524292
,D/CSLegacyTypeTracker( 3522): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.103/24,fe80::92b6:86ff:fe43:731c/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3522): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/EntConnectivity( 3522): Not allowed due to - mEnabled false
D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3691): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,E/ConnectivityService( 3522): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/EntConnectivity( 3522): Not allowed due to - mEnabled false
V/NetworkStats( 3522): updateIfacesLocked()
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked(flags=0x1)
D/TelephonyNetworkFactory( 3984): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering( 3522): MasterInitialState.processMessage what=3
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,I/GKI_LINUX( 5605): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 5605): GKI_exit_task 0 done
I/GKI_LINUX( 5605): GKI_shutdown(): task [BTU] terminated
D/WifiP2pService( 3522): P2pDisabledState{ what=143375 }
D/BluetoothAdapterState( 5605): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
E/WifiStateMachine( 3522): stopping supplicant
D/WifiP2pService( 3522): DefaultState{ what=143375 }
D/BtConfig.SecureMode( 5605): isSecureModeOn:false
D/BluetoothAdapterService( 5605): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/wpa_supplicant( 3834): p2p0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 3522): setWifiState: disabling
D/SmartBondingService( 3522): getSBEnabled() enabled =false
E/ConnectivityService( 3522): updateNetworkInfo()
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
E/ConnectivityService( 3522): updateNetworkInfo()
D/ConnectivityService( 3522): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3522): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/SmartBondingService( 3522): getSBEnabled() enabled =false
I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.gatt.GattService
,D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3691): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3691): updateDataNetType()
D/StatusBar.NetworkController( 3691): NoService, mRoamingIconId = 0
D/ConnectivityManager.CallbackHandler( 6732): CM callback handler got msg 524292
E/StatusBar.NetworkController( 3691): updateLTEICONDataNetType:0
,V/NetworkStats( 3522): performPollLocked() took 12ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : false mobile : false
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/BluetoothMap(11614): Proxy object connected
,D/MapProfile(11614): Bluetooth service connected
,D/Bluetoothsap(11614): BluetoothSAP Proxy object connected
,D/StatusBar.NetworkController( 3691): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 3691): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/SapProfile(11614): Bluetooth service connected
D/Bluetoothsap(11614): getConnectedDevices()
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=true enabledDesc:null
D/BtGatt.DebugUtils( 5605): handleDebugAction() action=null
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 5605): Received stop request...Stopping profile...
D/BtGatt.GattService( 5605): stop()
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.AdvertiseManager( 5605): advertise clients cleared
,W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3522): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : false mobile : false
D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
D/StatusBar.NetworkController( 3691): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3691): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3691): Wifi onReceive(0)
,D/HotspotTile( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 3691): onStateChanged: Wi-Fi
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/SecContentProvider2( 3522): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 3522): mCursor = null
,D/HotspotTile( 3691): onReceive : 0, 0
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.hid.HidService
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/HeadsetService( 5605): Received stop request...Stopping profile...
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
,W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.hdp.HealthService
,D/AudioService( 3522): onServiceDisconnected: Bluetooth profile: 1
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.pan.PanService
,D/A2dpService( 5605): Received stop request...Stopping profile...
V/Avrcp   ( 5605): doQuit
D/A2dpStateMachine( 5605): Exit Disconnected: -1
,D/Avrcp   ( 5605): Unregistering previous receiver
,D/AuthorizationBluetoothService( 4651): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5605): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
,D/BluetoothA2dp( 5014): Proxy object disconnected
,D/BluetoothA2dp( 3522): Proxy object disconnected
D/AudioService( 3522): onServiceDisconnected: Bluetooth profile: 2
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5605): Not skipping com.broadcom.bt.service.sap.SapService
I/Hs20UtilService( 4184): Starting #8
,I/Hs20UtilService( 4184): Message received 5007
,W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5605): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5605): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5605): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5605): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5605): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5605): Stopping profile services that were post enabled
E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HidService( 5605): Received stop request...Stopping profile...
D/HidService( 5605): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5605): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5605): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5605): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
I/wpa_supplicant( 3834): Blacklist: Clear (all) 
D/NearbySettings(11614): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings(11614): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings(11614): MountReceiver.onReceive - Create mPrefHandler
,E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5605): Profile still running: com.android.bluetooth.hid.HidService
D/NearbySettings(11614): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11614): DMSUtil.isNetworkConnected - flag-null, state-null
W/BluetoothHeadsetServiceJni( 5605): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5605): Cleaning up Bluetooth Handsfree callback object
I/NearbySettings(11614): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/HealthService( 5605): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
D/PanService( 5605): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
D/WifiService( 3522): New client listening to asynchronous messages
I/NearbySettings(11614): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/BluetoothPan( 3522): BluetoothPAN Proxy object disconnected
I/NearbySettings(11614): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11614): MountReceiver.onReceive - Set preference state off
E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.hid.HidService
V/NearbySettings(11614): MountReceiver.mPrefHandler - 7002
D/BluetoothAdapterService( 5605): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5605): Proxy object disconnected
D/BluetoothAdapterService( 5605): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 5605): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5605): GKI_exit_task 2 done
I/GKI_LINUX( 5605): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5605): cleanup
D/BluetoothMapService( 5605): Received stop request...Stopping profile...
D/BluetoothPan(11614): BluetoothPAN Proxy object disconnected
D/PanProfile(11614): Bluetooth service disconnected
D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
I/SignOutReceiver(11084): NETWORK_STATE_CHANGED_ACTION
D/BluetoothMap(11614): Proxy object disconnected
D/MapProfile(11614): Bluetooth service disconnected
D/SapService( 5605): Received stop request...Stopping profile...
D/SapService( 5605): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5605): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2d0a91ea
E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/Bluetoothsap(11614): BluetoothSAP Proxy object disconnected
D/SapProfile(11614): Bluetooth service disconnected
D/BluetoothAdapterService( 5605): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5605): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5605): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5605): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5605): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5605): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5605): Cleaning up Bluetooth PAN callback object
E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5605): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5605): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(755667434)( 5605): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 5605): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5605): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 5605): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5605): Setting state to 10
I/BluetoothAdapterState( 5605): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5605): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5605): updateAdapterState state is 10
D/BluetoothAdapterService( 5605): Autoconnection is available 
D/BluetoothAdapterService( 5605): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5605): Entering OffState
D/NearbySettings(11614): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BluetoothMap(11614): onBluetoothStateChange: up=false
I/wpa_supplicant( 3834): p2p0: CTRL-EVENT-TERMINATING 
V/NearbySettings(11614): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings(11614): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/wpa_supplicant( 3834): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
I/NearbySettings(11614): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11614): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11614): MountReceiver.onReceive - Set preference state off
I/wpa_supplicant( 3834): wlan0: State: COMPLETED -> DISCONNECTED
V/NearbySettings(11614): MountReceiver.mPrefHandler - 7002
I/wpa_supplicant( 3834): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 3834): wlan0: State: DISCONNECTED -> DISCONNECTED
D/BluetoothA2dp( 3522): onBluetoothStateChange: up=false
D/Bluetoothsap(11614): onBluetoothStateChange: up=false
D/Bluetoothsap(11614): Unbinding service...
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (12058): MountEmulatedStorage()
E/Zygote  (12058): v2
I/libpersona(12058): KNOX_SDCARD checking this for 10079
I/libpersona(12058): KNOX_SDCARD not a persona
I/SELinux (12058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (12058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12058 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (12058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(12039): 
D/AndroidRuntime(12039): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(12039): CheckJNI is OFF
D/AndroidRuntime(12039): readGMSProperty: start
D/AndroidRuntime(12039): readGMSProperty: already setted!!
D/AndroidRuntime(12039): readGMSProperty: end
D/AndroidRuntime(12039): addProductProperty: start
D/BluetoothPbap(11614): onBluetoothStateChange: up=false
D/BluetoothA2dp( 5605): onBluetoothStateChange: up=false
D/BluetoothA2dp( 5014): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/BluetoothManagerService( 3522): Broadcasting onBluetoothServiceDown() to 11 receivers.
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/BluetoothManagerService( 3522): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/TimaKeyStoreProvider(12058): TimaSignature is unavailable
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/ActivityThread(12058): Added TimaKeyStore provider
W/InputMethodManagerService( 3522): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3522): [BT Setting State] State =10
I/InputMethodManagerService( 3522): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/BluetoothAdapter( 3691): 657666692: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3691):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 3691): 657666692: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3691): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 3691): 657666692: getState() :  mService = null. Returning STATE_OFF
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/STATUSBAR-QSTileView( 3691): onStateChanged: Bluetooth
D/BluetoothAdapter( 3691): 657666692: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3691): 657666692: getState() :  mService = null. Returning STATE_OFF
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/StatusBarManagerService( 3522): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,I/SamsungIME( 4485): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
I/wpa_supplicant( 3834): Blacklist: Clear (all) 
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
,D/StatusBarManagerService( 3522): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 3691): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/PhoneStatusBar( 3691): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
,I/GKI_LINUX( 5605): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 5605): GKI_exit_task 1 done
I/GKI_LINUX( 5605): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 5605): cleanupNative: return from cleanup
,I/art     ( 5605): System.exit called, status: 0
,I/AndroidRuntime( 5605): VM exiting with result code 0, cleanup skipped.
D/FileWriteThread_Telephony( 3984): FileWriteThread : threadType = 3
D/BluetoothAdapter( 4651): 184133572: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4651): 184133572: getState() :  mService = null. Returning STATE_OFF
,V/BluetoothEventManager(11614): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/ResourcesManager(12058): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server(12058): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 3522): Killing 10978:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,I/Hs20UtilService( 4184): Starting #9
,E/AffinityControl(12039): AffinityControl: registerfunction enter
,I/ActivityManager( 3522): Process com.android.bluetooth (pid 5605)(adj 0) has died(84,1263)
D/NearbySettings(11614): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings(11614): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings(11614): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings(11614): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings(11614): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings(11614): MountReceiver.onReceive - Set preference state off
V/NearbySettings(11614): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 4184): Message received 5007
,D/AndroidRuntime(12039): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3522): START PACKAGE DELETE: observer{260863719}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3522): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3522): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3522): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
I/SignOutReceiver(11084): NETWORK_STATE_CHANGED_ACTION
,D/PackageManager( 3522): !@killApplicatoin: 10671, uninstall pkg
I/ActivityManager( 3522): Force stopping com.example.hello appid=10671 user=-1: uninstall pkg
I/ActivityManager( 3522): Killing 11925:com.example.hello/u0a671 (adj 0): stop com.example.hello
,I/ActivityManager( 3522):   Force finishing activity ActivityRecord{1f42f73b u0 com.example.hello/.MainActivity t25}
,W/PackageSettings( 3522): Skipping PackageSetting{36673b8d com.test.thalitest/10670} due to missing metadata
,I/ActivityManager( 3522): Force stopping com.example.hello appid=10671 user=0: pkg removed
,I/ActivityManager( 3522):   Force finishing activity ActivityRecord{1f42f73b u0 com.example.hello/.MainActivity t25 f}
W/ActivityManager( 3522): Duplicate finish request for ActivityRecord{1f42f73b u0 com.example.hello/.MainActivity t25 f}
,I/WindowState( 3522): WIN DEATH: Window{2f842559 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger( 2854): id=13 Removed NainActivit (6/8)
,D/WifiService( 3522): Client connection lost with reason: 4
,I/SurfaceFlinger( 2854): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger( 2854): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/Hs20UtilService( 4184): Starting #10
,I/Hs20UtilService( 4184): Message received 5011
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ConnectivityService( 3522): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 8807): Explicit concurrent mark sweep GC freed 24971(1454KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.117ms total 54.531ms
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 6732): Explicit concurrent mark sweep GC freed 2844(163KB) AllocSpace objects, 1(16KB) LOS objects, 20% free, 31MB/39MB, paused 2.436ms total 73.673ms
,E/SamsungIME( 4485): mOCRHelper is null
,W/GeofencerStateMachine( 4651): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/LWLocationManager(11239): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11239): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/DBG_DM  ( 6228): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,W/ResourceType( 5163): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5163): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/DBG_DM  ( 6228): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12099): MountEmulatedStorage()
E/Zygote  (12099): v2
I/libpersona(12099): KNOX_SDCARD checking this for 10127
I/libpersona(12099): KNOX_SDCARD not a persona
,I/SELinux (12099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/ActivityManager( 3522): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12099 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 37807(2MB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 8.364ms total 185.458ms
,I/art     ( 3522): WaitForGcToComplete blocked for 152.665ms for cause Explicit
I/art     ( 2883): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 784us total 16.438ms
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 452us total 13.277ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/TimaKeyStoreProvider(12099): TimaSignature is unavailable
,D/ActivityThread(12099): Added TimaKeyStore provider
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/art     ( 2883): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 790us total 13.950ms
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(12099): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,W/fb4a(:<default>):UserScope(10674): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/wpa_supplicant( 3834): wlan0: CTRL-EVENT-TERMINATING 
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
E/WifiStateMachine( 3522): Supplicant connection lost
,D/Tethering( 3522): InitialState.processMessage what=4
,W/fb4a(:<default>):QeInternalImpl(10674): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,E/WifiStateMachine( 3522): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL( 3522): callSECApiBoolean - ID [21]
,E/WifiStateMachine( 3522): setWifiState: disabled
,W/Settings(11395): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Tethering( 3522): No numeric data
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/fb4a(:<default>):QeInternalImpl(10674): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/Tethering( 3522): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkStats( 3522): performPollLocked(flags=0x1)
D/HotspotTile( 3691): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3691): updateTetherState():false, false
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 3522): UpdateStatsForKnox
,D/KeyguardWallpaperUpdator(12099): cancelUpdateWallpaper
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked() took 5ms
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/StatusBar.NetworkController( 3691): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3691): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 3691): Wifi onReceive(1)
D/HotspotTile( 3691): onReceive : android.net.wifi.WIFI_STATE_CHANGED
W/Settings( 4651): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/STATUSBAR-QSTileView( 3691): onStateChanged: Wi-Fi
,D/HotspotTile( 3691): onReceive : 1, 0
D/KeyguardWallpaperUpdator(12099): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12099): stopCheckCategoryVersion
,D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
,D/RegisteredServicesCache( 3968): empty dynamic service
,I/SignOutReceiver(11084): WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,E/Zygote  (12118): MountEmulatedStorage()
E/Zygote  (12118): v2
I/libpersona(12118): KNOX_SDCARD checking this for 1000
I/libpersona(12118): KNOX_SDCARD not a persona
D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/SELinux (12118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12118 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Killing 10995:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,E/SELinux (12118): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11239): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(12118): TimaSignature is unavailable
,D/ActivityThread(12118): Added TimaKeyStore provider
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 9293(544KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.605ms total 164.737ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(12118): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 3522): delete codoeFile: 
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,I/AASAUninstall( 3522):  com.example.hello not target!
,D/PackageManager( 3522): result of delete: 1{260863719}
,D/AndroidRuntime(12039): Shutting down VM
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/ActivityManager( 3522): Killing 11010:com.samsung.helphub/1000 (adj 13): bgCount ##31
,W/ResourcesManager(11239): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11239): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11239): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ContextImpl(11614): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver(11614): finishStartingService: stopping service
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BluetoothNotiBroadcastReceiver(11614): onReceive
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11239): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/Zygote  (12135): MountEmulatedStorage()
E/Zygote  (12135): v2
I/libpersona(12135): KNOX_SDCARD checking this for 1002
I/libpersona(12135): KNOX_SDCARD not a persona
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux (12135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux (12135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/SELinux (12135): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager( 3522): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12135 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/WifiStateMachine( 3522): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine( 3522): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3522): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/TimaKeyStoreProvider(12135): TimaSignature is unavailable
,D/ActivityThread(12135): Added TimaKeyStore provider
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3522): clearDefaults: com.example.hello
I/CrashAnrDetector( 3522): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager(12135): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,D/RCPManagerService( 3522): PackageReceiver onReceive()
,I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/ResourcesManager(12135): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager(12135): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10671
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
,D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=25_task.xml
D/SmartBondingService( 3522): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): getSBEnabled() enabled =false
D/SmartBondingService( 3522): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3522): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
W/SLocation( 3522): No Active Data Connection
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11239): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/SmartBondingService( 3522): getNetworkEnabled : wifi : false mobile : false
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Books/Books.apk
,I/BluetoothA2dpSinkServiceJni(12135): register_com_android_bluetooth_a2dp_sink
D/ResourcesManager(11239): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/BtSettings.ProfileConfig(12135): Adding GattService
D/BtSettings.ProfileConfig(12135): Adding HeadsetService
D/BtSettings.ProfileConfig(12135): Adding A2dpService
D/BtSettings.ProfileConfig(12135): Adding HidService
D/BtSettings.ProfileConfig(12135): Adding HealthService
,D/BtSettings.ProfileConfig(12135): Adding PanService
D/BtSettings.ProfileConfig(12135): Adding BluetoothMapService
D/BtSettings.ProfileConfig(12135): Adding SapService
D/BtSettings.ProfileConfig(12135): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12135): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12135): Adding SapClientService
D/BtSettings.ProfileConfig(12135): Adding HidDevService
I/BtSettings.ProfileConfig(12135): *********Initializing Bluetooth Profile Settings*******
D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
I/ApplicationPolicy( 3522): updateDataUsageMap
,I/ApplicationPolicy( 3522): updateDataUsageMap  idList is null 
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
,D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
,D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/SettingsProvider( 3522): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
,D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/SettingsProvider( 3522): name = bt_svcst_com.android.bluetooth.hid.HidDevService,
,D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1002
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/ActivityManager( 3522): Killing 11033:com.sec.android.app.samsungapps/u0a13 (adj 13): bgCount ##31
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/AuthorizationBluetoothService( 4651): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/Zygote  (12151): MountEmulatedStorage()
E/Zygote  (12151): v2
I/libpersona(12151): KNOX_SDCARD checking this for 10063
I/libpersona(12151): KNOX_SDCARD not a persona
,I/SELinux (12151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12151 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/TimaKeyStoreProvider(12151): TimaSignature is unavailable
,D/ActivityThread(12151): Added TimaKeyStore provider
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(12151): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12151): onReceive()
,D/VRSetupWizardStub/PackageIntentReceiver(12151): Action Package Remove
,D/VRSetupWizardStub/PackageIntentReceiver(12151): packagename:com.example.hello
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11239): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(11239): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,E/Zygote  (12167): MountEmulatedStorage()
E/Zygote  (12167): v2
I/libpersona(12167): KNOX_SDCARD checking this for 10021
I/libpersona(12167): KNOX_SDCARD not a persona
,I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12167 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 11105:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,I/SELinux (12167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(11239): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
E/SELinux (12167): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(12167): TimaSignature is unavailable
,D/ActivityThread(12167): Added TimaKeyStore provider
,D/ResourcesManager(12167): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
,I/KLMS-2.4.521: (12167): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 04 13:24:24 GMT+01:00 2016
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,I/KLMS-2.4.521: (12167): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/MtpClient(11599): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(11599): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12167): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12167): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12167): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (12167): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (12167): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (12167): KLMSIntentService(): listeningToPackageRemoved().START
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/KLMS-2.4.521: (12167): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,E/Zygote  (12190): MountEmulatedStorage()
E/Zygote  (12190): v2
,I/libpersona(12190): KNOX_SDCARD checking this for 10106
I/libpersona(12190): KNOX_SDCARD not a persona
D/ResourcesManager(11239): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/SELinux (12190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12190 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3522): Removing device '/dev/input/event10' due to inotify event
,D/TimaKeyStoreProvider(12190): TimaSignature is unavailable
,D/ActivityThread(12190): Added TimaKeyStore provider
,E/Zygote  (12205): MountEmulatedStorage()
E/Zygote  (12205): v2
I/libpersona(12205): KNOX_SDCARD checking this for 1000
I/libpersona(12205): KNOX_SDCARD not a persona
,I/SELinux (12205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3522): Removing device '/dev/input/event7' due to inotify event
,I/SELinux (12205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=12205 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (12205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3522): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(12190): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(12205): TimaSignature is unavailable
,D/ActivityThread(12205): Added TimaKeyStore provider
,I/EventHub( 3522): Removing device '/dev/input/event9' due to inotify event
,I/KLMS-2.4.521: (12167): KLMSIntentService(): listeningToPackageRemoved().END
,E/SharedPreferencesImpl(11599): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/elm:14491(12190): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(12190): ELMEngine.ELMEngine( context ).
,D/elm:14491(12190): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(12205): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/EventHub( 3522): Removing device '/dev/input/event11' due to inotify event
,W/ResourcesManager(12205): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (12167): KLMSIntentService(): onDestroy()
,D/elm:14491(12190): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12190): ElmAgentService : onCreate()
,D/elm:14491(12190): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/RCPManager(12205):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 3522):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
,D/elm:14491(12190): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12190): MDMBridge.getInstance()
D/elm:14491(12190): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(12190): MDMBridge.getAllLicenseInfoFromSDK()
,I/EventHub( 3522): Removing device '/dev/input/event12' due to inotify event
,D/Mms/FreeMessageStatusReceiver(11665): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/elm:14491(12190): ElmAgentService : onDestroy().
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/EventHub( 3522): Removing device '/dev/input/event13' due to inotify event
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService(11665): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(11665): onHandleIntent: ACTION_PACKAGE_REMOVED
,E/Zygote  (12225): MountEmulatedStorage()
E/Zygote  (12225): v2
,I/libpersona(12225): KNOX_SDCARD checking this for 10019
I/libpersona(12225): KNOX_SDCARD not a persona
,I/EventHub( 3522): Removing device '/dev/input/event14' due to inotify event
,I/SELinux (12225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12225 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux (12225): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11145): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11145): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11145): Clear T&P info.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TapandpayWidget:TanpandpayAppWidgetProvider(11145): Widget is not attached.
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(12225): TimaSignature is unavailable
,D/ActivityThread(12225): Added TimaKeyStore provider
,E/Watchdog( 3522): !@Sync 4
,E/Zygote  (12240): MountEmulatedStorage()
E/Zygote  (12240): v2
I/libpersona(12240): KNOX_SDCARD checking this for 10101
I/libpersona(12240): KNOX_SDCARD not a persona
,I/SELinux (12240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12240 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12240): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12225): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,I/ActivityManager( 3522): Killing 11163:com.google.android.gm/u0a122 (adj 13): bgCount ##31

```
