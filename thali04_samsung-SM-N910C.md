#### Test 50388019aa1a16d_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3496): !@Sync 3
,--------- beginning of main
D/AndroidRuntime(11961): 
D/AndroidRuntime(11961): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11961): CheckJNI is OFF
D/AndroidRuntime(11961): readGMSProperty: start
D/AndroidRuntime(11961): readGMSProperty: already setted!!
D/AndroidRuntime(11961): readGMSProperty: end
D/AndroidRuntime(11961): addProductProperty: start
E/AffinityControl(11961): AffinityControl: registerfunction enter
D/AndroidRuntime(11961): Calling main entry com.android.commands.am.Am
D/BatteryService( 3496): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3496): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3496): online:4, current avg:86, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:79
D/BatteryService( 3496): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3496): stay LED for fully charged
I/MotionRecognitionService( 3496): Plugged
I/MotionRecognitionService( 3496): setPowerConnected  = true
E/PersonaManagerService( 3496): inState():  stateMachine is null !!
I/PersonaManagerService( 3496): PersonaId don't exist
I/ActivityManager( 3496): do not start freezing screen for locked container getKeyguardshowstate = false
D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5686): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5686): Disconnected process message: 10
V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3496): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager( 3496): mDVFSHelper.acquire()
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/Zygote  (11980): MountEmulatedStorage()
E/Zygote  (11980): v2
I/libpersona(11980): KNOX_SDCARD checking this for 10408
I/libpersona(11980): KNOX_SDCARD not a persona
I/SELinux (11980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3496): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=11980 uid=10408 gids={50408, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (11980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11980): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11961): Shutting down VM
D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2876): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 2.336ms total 35.967ms
D/TimaKeyStoreProvider(11980): TimaSignature is unavailable
D/ActivityThread(11980): Added TimaKeyStore provider
V/ActivityManager( 3496): Display changed displayId=0
I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 827us total 20.816ms
I/art     ( 2876): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 637us total 20.429ms
D/ResourcesManager(11980): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
V/ActivityThread( 6398): updateVisibility : ActivityRecord{16470ee9 token=android.os.BinderProxy@3d66dda2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
I/WebViewFactory(11980): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(11980): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(11980): Loading: webviewchromium
I/LibraryLoader(11980): Time to load native libraries: 4 ms (timestamps 4265-4269)
I/LibraryLoader(11980): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(11980): Binding Chromium to main looper Looper (main, tid 1) {14a7ac00}
I/LibraryLoader(11980): Expected native library version number "",actual native library version number ""
I/chromium(11980): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(11980): Initializing chromium process, renderers=0
W/art     (11980): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(11980): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(11980): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(11980): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/chromium(11980): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(11980): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (11980): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(11980): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(11980): CordovaWebView is running on device made by: samsung
W/art     (11980): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11980): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(11980): performCreate Call secproduct feature valuefalse
D/Activity(11980): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(11980): Render dirty regions requested: true
D/ActivityManager( 3496): post active user change for 0
D/KnoxTimeoutHandler( 3496): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3496): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3496): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3496): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11980): Initialized EGL, version 1.4
I/OpenGLRenderer(11980): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1279938288 
D/OpenGLRenderer(11980): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11980): Enabling debug mode 0
D/mali_winsys(11980): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(11980): updateVisibility : ActivityRecord{38fe1530 token=android.os.BinderProxy@2810dee7 {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 3496): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3496): mDVFSHelper.release()
I/Timeline( 3496): Timeline: Activity_windows_visible id: ActivityRecord{ffd3753 u0 com.example.hello/.MainActivity t25} time:104746
W/IInputConnectionWrapper(11980): showStatusIcon on inactive InputConnection
I/Timeline(11980): Timeline: Activity_idle id: android.os.BinderProxy@2810dee7 time:104758
I/chromium(11980): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler(11980): Unable to open asset URL: file:///android_asset/www/jxcore.js
V/AlarmManager( 3496): waitForAlarm result :4
I/chromium(11980): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11980): 
D/JsMessageQueue(11980): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log(11980): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1358540800
D/JX-Cordova(11980): jxcore cordova android initializing
V/GLSActivity( 4189): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 4189): Vacuum at: now=1448020296929 tag=VacuumService
W/jxcore-log(11980): Initializing JXcore engine
W/jxcore-log(11980): JXcore engine is ready
W/jxcore-log(11980): Starting JXcore engine
D/SSRM:n  ( 3496): SIOP:: AP = 270, PST = 310, CUR = 86
E/auditd  ( 4618): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3496): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3496): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
D/UdcCache:FPQuery( 6807): Bootstrapping UDC settings cache for all accounts
W/jxcore-log(11980): Platform android
W/jxcore-log(11980): 
W/jxcore-log(11980): Process ARCH arm
W/jxcore-log(11980): 
I/jxcore-log(11980): JXcore Cordova bridge is ready!
I/jxcore-log(11980): 
W/jxcore-log(11980): JXcore engine is started
V/GLSActivity( 4189): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4189): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/jxcore-log(11980): >> samsung-SM-N910C
E/jxcore-log(11980): 
I/jxcore-log(11980): Total memory 2970812416
I/jxcore-log(11980): 
I/jxcore-log(11980): Free memory 74280960
I/jxcore-log(11980): 
I/jxcore-log(11980): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11980): 
I/jxcore-log(11980): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(11980): 
I/jxcore-log(11980): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(11980): 
I/jxcore-log(11980): Size 1440 2560
I/jxcore-log(11980): 
I/jxcore-log(11980): Screen Brightness 134
I/jxcore-log(11980): 
E/jxcore-log(11980): Dummy Error Log.
E/jxcore-log(11980): 
D/GetConfigurationSnapshotOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/PhenotypeFlagCommitter( 4189): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 4189): Using platform SSLCertificateSocketFactory
I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4189): (HTTPLog)-Static: isShipBuild true
I/System.out( 4189): (HTTPLog)-Thread-229-187159655: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
I/System.out( 4189): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4189): Tagging socket 64 with tag 1000040100000000{268436481,0} uid 10014, pid: 4189, getuid(): 10014
I/qtaguid ( 4189): Tagging socket 68 with tag 1000040100000000{268436481,0} uid 10014, pid: 4189, getuid(): 10014
,I/jxcore-log(11980): getBuffer is called!!!!
I/jxcore-log(11980): 
,D/GetCommittedConfigurationOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4189): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4189): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,I/qtaguid ( 4189): Tagging socket 72 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,D/GetCommittedConfigurationOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4189): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,D/GetCommittedConfigurationOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4189): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,W/Uploader( 4189):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4189): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,D/GetCommittedConfigurationOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4189): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,D/GetCommittedConfigurationOperation( 4189): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/System.out( 4189): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4189): Tagging socket 69 with tag 1000120100000000{268440065,0} uid -1, pid: 4189, getuid(): 10014
,W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ProcessCpuTracker( 3496): Skipping unknown process pid 12091
,D/BluetoothAdapter(11980): disable()
,D/SettingsProvider( 3496): name = bluetooth_on
,D/BluetoothAdapterState( 5686): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 5686): Setting state to 13
,I/BluetoothAdapterState( 5686): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 5686): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5686): updateAdapterState state is 13
,I/BluetoothPbapService( 5686): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 5686): close() in, this: android.bluetooth.BluetoothSocket@222593f2, channel: 19, state: LISTENING
,D/BluetoothSocket( 5686): close() this: android.bluetooth.BluetoothSocket@222593f2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b752b9a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c3fea43mSocket: android.net.LocalSocket@336958c0 impl:android.net.LocalSocketImpl@216579f9 fd:FileDescriptor[72]
,D/BluetoothSocket( 5686): Closing mSocket: android.net.LocalSocket@336958c0 impl:android.net.LocalSocketImpl@216579f9 fd:FileDescriptor[72]
D/BluetoothAdapterService( 5686): Autoconnection is available 
,D/BluetoothAdapterService( 5686): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 5686): terminating service from this receiver
,D/BluetoothAdapterProperties( 5686): onBluetoothDisable()
,D/SecContentProvider( 3496): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 5686): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 5686): Scan Mode:20
,D/BluetoothPbap( 8995): Proxy object disconnected
D/PbapServerProfile( 8995): Bluetooth service disconnected
,D/BluetoothAdapterState( 5686): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 5686): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 5686): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 5686): cmd socket is not created
E/BtOppRfcommListener( 5686): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btm  ( 5686): btm_ble_start_auto_conn start : 0, 0
W/InputMethodManagerService( 3496): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
W/bt-btif ( 5686): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
I/InputMethodManagerService( 3496): [BT Setting State] State =13
W/bt-l2cap( 5686): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x001b not found for deregistration
D/btif_config_util( 5686): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothTile( 3690):  onBluetoothStateChange:
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiService( 3496): New client listening to asynchronous messages
,I/WifiManager(11980): packageName : com.example.hello
,D/SecContentProvider( 3496): uri = 18 selection = isWifiEnabled
,I/SamsungIME( 4497): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 3690):  handleUpdatestate:false name:null
D/SecContentProvider2( 3496): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3496): mCursor = null
,D/WifiService( 3496): setWifiEnabled: false pid=11980, uid=10408
,E/WifiService( 3496): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3496): name = wifi_on
,D/StatusBarManagerService( 3496): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/StatusBarManagerService( 3496): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
,D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
D/BluetoothTile( 3690):  handleUpdatestate:false name:null
,E/WifiStateMachine( 3496): WifiStateMachine: Leaving Connected state
,V/BluetoothEventManager( 8995): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/wpa_supplicant( 3822): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3822): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3822): P2P: Current p2p state = IDLE
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
I/jxcore-log(11980): ****TEST TOOK:  5132  ms ****
I/jxcore-log(11980): 
I/jxcore-log(11980): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11980): 
E/WifiStateMachine( 3496): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - exit - invokeExitMethods
I/wpa_supplicant( 3822): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiStateMachine( 3496): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine( 3496): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore( 3496): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine( 3496): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
W/ContextImpl( 8995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
E/WifiStateMachine( 3496): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3496): do suspend true
V/[CarModeFW](11187): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
D/WifiP2pService( 3496): InactiveState{ what=143375 }
D/WifiP2pService( 3496): P2pEnabledState{ what=143375 }
D/CommandListener( 2845): Clearing all IP addresses on wlan0
D/BluetoothSocket( 5686): close() in, this: android.bluetooth.BluetoothSocket@336ce79f, channel: 5, state: LISTENING
D/BluetoothSocket( 5686): close() this: android.bluetooth.BluetoothSocket@336ce79f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@748accb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17eb40ecmSocket: android.net.LocalSocket@3f7abcb5 impl:android.net.LocalSocketImpl@15bfaf4a fd:FileDescriptor[74]
D/BluetoothSocket( 5686): Closing mSocket: android.net.LocalSocket@3f7abcb5 impl:android.net.LocalSocketImpl@15bfaf4a fd:FileDescriptor[74]
E/Netd    ( 2845): ifc_reset_connections failed on iface wlan0 for address 192.168.1.113/24 (Unknown error -1)
I/BtOppRfcommListener( 5686): stopping Accept Thread
D/BluetoothSocket( 5686): close() in, this: android.bluetooth.BluetoothSocket@7425ebb, channel: 12, state: LISTENING
D/BluetoothSocket( 5686): close() this: android.bluetooth.BluetoothSocket@7425ebb, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19fc2afd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@fc17fd8mSocket: android.net.LocalSocket@23676f31 impl:android.net.LocalSocketImpl@7d17616 fd:FileDescriptor[79]
D/BluetoothSocket( 5686): Closing mSocket: android.net.LocalSocket@23676f31 impl:android.net.LocalSocketImpl@7d17616 fd:FileDescriptor[79]
I/BtOppRfcommListener( 5686): BluetoothSocket listen thread finished
E/WifiStateMachine( 3496): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/ConnectivityService( 3496): updateNetworkInfo()
D/ConnectivityService( 3496): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 3496): updateNetworkInfo()
D/ConnectivityService( 3496): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/WifiConfigStore( 3496): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/DockEventReceiver( 8995): finishStartingService: stopping service
,I/WifiTrafficPoller( 3496): evaluateTrafficStatsPolling
,E/WifiStateMachine( 3496): scanCount==0 - aborting
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,E/WifiStateMachine( 3496): [1,448,020,302,397 ms] noteScanEnd no scan source
,D/WifiP2pService( 3496): InactiveState{ what=131204 }
,D/WifiP2pService( 3496): P2pEnabledState{ what=131204 }
D/WifiScanningService( 3496): SCAN_AVAILABLE : 1
,D/WifiScanningService( 3496): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 3496): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3496): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/RttService( 3496): SCAN_AVAILABLE : 1
,D/RttService( 3496): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 3496): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3496): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent( 3496): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService( 3496): sending p2p connection changed broadcast: FAILED
,D/WifiDisplayController( 3496): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3496): onP2pDisconnected
,D/IpRemoteDisplayController( 3496): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3496): WfdBridgeServer is already null
,D/WifiP2pService( 3496): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine( 3496): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController( 3496): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 3496): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 3496): disconnect
D/WifiDisplayController( 3496): updateConnection
D/WifiDisplayController( 3496): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 3496): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/ConnectivityService( 3496): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 3496): Not allowed due to - mEnabled false
,D/ConnectivityManager.CallbackHandler( 3690): CM callback handler got msg 524292
D/ConnectivityService( 3496): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 3979): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 3496): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 3496): P2pDisablingState
,D/WifiP2pService( 3496): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 3496): p2p socket connection lost
,E/WifiStateMachine( 3496): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11300 - enter - invokeEnterMethods
D/WifiP2pService( 3496): P2pDisabledState
,E/WifiStateMachine( 3496): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/CSLegacyTypeTracker( 3496): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::92b6:86ff:fe43:731c/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 3496): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,E/WifiStateMachine( 3496): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  ( 3496): do suspend true
D/ConnectivityService( 3496): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiDisplayController( 3496): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 3496): onP2pDisconnected
D/IpRemoteDisplayController( 3496): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 3496): WfdBridgeServer is already null
,D/ConnectivityManager.CallbackHandler( 6807): CM callback handler got msg 524292
,D/WifiP2pService( 3496): P2pDisabledState{ what=143375 }
,D/AllShareCastTile( 3690): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 3496): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 3690): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/CommandListener( 2845): Clearing all IP addresses on wlan0
,D/EntConnectivity( 3496): Not allowed due to - mEnabled false
,E/WifiStateMachine( 3496): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiP2pService( 3496): DefaultState{ what=143375 }
,E/ConnectivityService( 3496): updateNetworkInfo()
D/ConnectivityService( 3496): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 3496): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,E/WifiStateMachine( 3496): stopping supplicant
E/ConnectivityService( 3496): updateNetworkInfo()
,I/wpa_supplicant( 3822): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 3496): MasterInitialState.processMessage what=3
,E/WifiStateMachine( 3496): setWifiState: disabling
,D/SmartBondingService( 3496): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService( 3496): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats( 3496): updateIfacesLocked()
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
V/NetworkStats( 3496): performPollLocked(flags=0x1)
D/SmartBondingService( 3496): getSBEnabled() enabled =false
D/SmartBondingService( 3496): getSBEnabled() enabled =false
D/SmartBondingService( 3496): getSBEnabled() enabled =false
,D/NetworkStatsFactory( 3496): UpdateStatsForKnox
,D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 3690): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 3690): updateDataNetType()
D/StatusBar.NetworkController( 3690): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 3690): updateLTEICONDataNetType:0
,V/NetworkStats( 3496): performPollLocked() took 9ms
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,D/SmartBondingService( 3496): getNetworkEnabled : wifi : false mobile : false
,D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 3690): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength: hasService=false ss=null
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
V/NetworkStats( 3496): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 3690): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
I/WifiTrafficPoller( 3496): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020584/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020160/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:null
,W/bt-l2cap( 5686): btif_mce_execute_se not  enable:0
W/bt-l2cap( 5686): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 5686): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 5686): ag scb idx 1 not allocated
W/bt-btif ( 5686): ag scb idx 2 not allocated
E/bt-btif ( 5686): BTA AG is already disabled, ignoring ...
,D/bt_userial( 5686): RX termination
W/bt_userial( 5686): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 5686): Leaving userial_read_thread()
D/bt_userial( 5686): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 5686): hw_epilog_process
,I/bt_userial_vendor( 5686): device fd = 65 close
,D/BluetoothNotiBroadcastReceiver( 8995): onReceive
,I/GKI_LINUX( 5686): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 5686): GKI_exit_task 0 done
,I/GKI_LINUX( 5686): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 5686): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 5686): isSecureModeOn:false
D/BluetoothAdapterService( 5686): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.gatt.GattService
,D/SecContentProvider2( 3496): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 3496): mCursor = null
D/SmartBondingService( 3496): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SLocation( 3496): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/SmartBondingService( 3496): getNetworkEnabled : wifi : false mobile : false
,D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(0)
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 3690): onReceive : 0, 0
,D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,E/WifiStateMachine( 3496): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine( 3496): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 5686): handleDebugAction() action=null
,W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService( 5686): Received stop request...Stopping profile...
D/BtGatt.GattService( 5686): stop()
D/BtGatt.AdvertiseManager( 5686): advertise clients cleared
,D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.a2dp.A2dpService
D/AuthorizationBluetoothService( 4189): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.hdp.HealthService
,I/Hs20UtilService( 4105): Starting #8
W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/Hs20UtilService( 4105): Message received 5007
W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.pan.PanService
,D/NearbySettings( 8995): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 8995): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 8995): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 8995): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5686): Not skipping com.android.bluetooth.map.BluetoothMapService
V/NearbySettings( 8995): DMSUtil.isNetworkConnected - flag-null, state-null
,I/wpa_supplicant( 3822): Blacklist: Clear (all) 
,I/NearbySettings( 8995): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5686): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/WifiService( 3496): New client listening to asynchronous messages
,I/NearbySettings( 8995): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
W/BluetoothAdapterService( 5686): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
I/NearbySettings( 8995): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
I/NearbySettings( 8995): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8995): MountReceiver.mPrefHandler - 7002
W/BluetoothAdapterService( 5686): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5686): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5686): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5686): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 5686): Stopping profile services that were post enabled
,E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HeadsetService( 5686): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,D/AudioService( 3496): onServiceDisconnected: Bluetooth profile: 1
D/HeadsetProfile( 8995): Bluetooth service disconnected
,D/A2dpService( 5686): Received stop request...Stopping profile...
V/Avrcp   ( 5686): doQuit
D/A2dpStateMachine( 5686): Exit Disconnected: -1
,D/Avrcp   ( 5686): Unregistering previous receiver
,I/SignOutReceiver(11451): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,D/BluetoothA2dp( 3496): Proxy object disconnected
D/AudioService( 3496): onServiceDisconnected: Bluetooth profile: 2
,D/BluetoothA2dp( 5133): Proxy object disconnected
D/BluetoothA2dp( 8995): Proxy object disconnected
D/A2dpProfile( 8995): Bluetooth service disconnected
,D/HidService( 5686): Received stop request...Stopping profile...
,D/HidService( 5686): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 5686): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 5686): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 5686): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,D/NearbySettings( 8995): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 8995): DMSUtil.isNetworkConnected - flag-null, state-null
,I/wpa_supplicant( 3822): p2p0: CTRL-EVENT-TERMINATING 
I/NearbySettings( 8995): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 8995): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8995): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8995): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 8995): MountReceiver.mPrefHandler - 7002
I/wpa_supplicant( 3822): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/BluetoothInputDevice( 8995): Proxy object disconnected
D/HidProfile( 8995): Bluetooth service disconnected
I/wpa_supplicant( 3822): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 3822): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3822): wlan0: State: DISCONNECTED -> DISCONNECTED
D/HealthService( 5686): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,D/PanService( 5686): Received stop request...Stopping profile...
D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12125): MountEmulatedStorage()
I/libpersona(12125): KNOX_SDCARD checking this for 10079
E/Zygote  (12125): v2
I/libpersona(12125): KNOX_SDCARD not a persona
,I/SELinux (12125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3496): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=12125 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (12125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothPan( 3496): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 8995): BluetoothPAN Proxy object disconnected
D/PanProfile( 8995): Bluetooth service disconnected
,D/BluetoothMapService( 5686): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,D/BluetoothMap( 8995): Proxy object disconnected
,D/MapProfile( 8995): Bluetooth service disconnected
,D/SapService( 5686): Received stop request...Stopping profile...
D/SapService( 5686): Stopping Bluetooth SapService
D/BluetoothAdapterService( 5686): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14a7ac00
,E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5686): Profile still running: com.android.bluetooth.hid.HidService
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,W/BluetoothHeadsetServiceJni( 5686): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 5686): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 5686): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 5686): Proxy object disconnected
D/BluetoothAdapterService( 5686): Bluetooth A2dp source service disconnected
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,I/GKI_LINUX( 5686): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 5686): GKI_exit_task 2 done
I/GKI_LINUX( 5686): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 5686): cleanup
E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5686): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5686): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 5686): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 5686): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 5686): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 5686): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 5686): Cleaning up Bluetooth PAN callback object
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/Bluetoothsap( 8995): BluetoothSAP Proxy object disconnected
D/SapProfile( 8995): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 5686): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5686): Profile still running: com.broadcom.bt.service.sap.SapService
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
E/BluetoothAdapterService(346532864)( 5686): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,D/BluetoothAdapterState( 5686): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 5686): Setting state to 10
I/BluetoothAdapterState( 5686): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 5686): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5686): updateAdapterState state is 10
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/BluetoothAdapterService( 5686): Autoconnection is available 
D/BluetoothAdapterService( 5686): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 5686): Entering OffState
,D/BluetoothA2dp( 5133): onBluetoothStateChange: up=false
W/BluetoothSAPServiceJni( 5686): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 5686): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothA2dp( 5686): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/AndroidRuntime(12116): 
D/AndroidRuntime(12116): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/AndroidRuntime(12116): CheckJNI is OFF
D/AndroidRuntime(12116): readGMSProperty: start
D/AndroidRuntime(12116): readGMSProperty: already setted!!
,D/AndroidRuntime(12116): readGMSProperty: end
D/AndroidRuntime(12116): addProductProperty: start
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
D/BluetoothMap( 8995): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/TimaKeyStoreProvider(12125): TimaSignature is unavailable
D/BluetoothInputDevice( 8995): onBluetoothStateChange: up=false
,D/ActivityThread(12125): Added TimaKeyStore provider
,D/FileWriteThread_Telephony( 3979): FileWriteThread : threadType = 3
,D/BluetoothA2dp( 8995): onBluetoothStateChange: up=false
,D/Bluetoothsap( 8995): onBluetoothStateChange: up=false
D/Bluetoothsap( 8995): Unbinding service...
,D/BluetoothPbap( 8995): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3496): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 3496): Broadcasting onBluetoothServiceDown() to 14 receivers.
,D/ResourcesManager(12125): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/BluetoothManagerService( 3496): Broadcasting onBluetoothServiceUp() to 0 receivers.
,I/GKI_LINUX( 5686): gki_task task_id=1 [BTIF] terminating
W/InputMethodManagerService( 3496): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 3496): [BT Setting State] State =10
I/InputMethodManagerService( 3496): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/GKI_LINUX( 5686): GKI_exit_task 1 done
I/GKI_LINUX( 5686): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 5686): cleanupNative: return from cleanup
,I/art     ( 5686): System.exit called, status: 0
I/AndroidRuntime( 5686): VM exiting with result code 0, cleanup skipped.
,D/BluetoothAdapter( 3690): 920588010: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3690):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 3690): 920588010: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 3690): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 3690): 920588010: getState() :  mService = null. Returning STATE_OFF
,I/wpa_supplicant( 3822): Blacklist: Clear (all) 
D/STATUSBAR-QSTileView( 3690): onStateChanged: Bluetooth
D/BluetoothAdapter( 3690): 920588010: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3690): 920588010: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 3496): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=true num=0 )
D/StatusBarManagerService( 3496): setIconVisibility slot=bluetooth visible=false
V/BluetoothEventManager( 8995): Received android.bluetooth.adapter.action.STATE_CHANGED
D/PhoneStatusBar( 3690): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020363 level=0 visible=false num=0 )
I/SamsungIME( 4497): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/FileShare-Server(12125): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BluetoothAdapter( 4636): 43636615: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4636): 43636615: getState() :  mService = null. Returning STATE_OFF
,V/[CarModeFW](11187): BTEventsHandlerService-onHandleIntent: Action = android.bluetooth.adapter.action.STATE_CHANGED State = -2147483648 Previous = -2147483648
,D/[CarModeFW](11187): ConnectivityManager-handleMessage INITIAL_STATE_OFF
I/Hs20UtilService( 4105): Starting #9
I/Hs20UtilService( 4105): Message received 5007
I/ActivityManager( 3496): Killing 11152:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
D/NearbySettings( 8995): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 8995): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 8995): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 8995): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 8995): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 8995): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 8995): MountReceiver.mPrefHandler - 7002
I/SignOutReceiver(11451): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 4105): Starting #10
I/Hs20UtilService( 4105): Message received 5011
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/AffinityControl(12116): AffinityControl: registerfunction enter
,D/AndroidRuntime(12116): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 3496): START PACKAGE DELETE: observer{496420176}
D/PackageManager( 3496): pkg{<packageName>}
D/PackageManager( 3496): user{0}
D/PackageManager( 3496): caller{2000}
D/PackageManager( 3496): flags{3}
D/PersonaManagerService( 3496): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3496): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3496): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3496): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3496): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3496): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 3496): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3496): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3496): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3496): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3496): !@killApplicatoin: 10408, uninstall pkg
,E/Zygote  (12165): MountEmulatedStorage()
,E/Zygote  (12165): v2
I/libpersona(12165): KNOX_SDCARD checking this for 10127
I/libpersona(12165): KNOX_SDCARD not a persona
,I/SELinux (12165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3496): Start proc com.samsung.android.keyguardwallpaperupdator for broadcast com.samsung.android.keyguardwallpaperupdator/.manager.WallpaperBroadcastReceiver: pid=12165 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3496): Process com.android.bluetooth (pid 5686)(adj 0) has died(79,1265)
,I/ActivityManager( 3496): Force stopping com.example.hello appid=10408 user=-1: uninstall pkg
,I/ActivityManager( 3496): Killing 11980:com.example.hello/u0a408 (adj 0): stop com.example.hello
,I/ActivityManager( 3496):   Force finishing activity ActivityRecord{ffd3753 u0 com.example.hello/.MainActivity t25}
,W/ActivityManager( 3496): mDVFSHelper.acquire()
,D/TimaKeyStoreProvider(12165): TimaSignature is unavailable
,D/ActivityThread(12165): Added TimaKeyStore provider
,W/PackageSettings( 3496): Skipping PackageSetting{3a0495c7 com.test.thalitest/10407} due to missing metadata
,D/WifiService( 3496): Client connection lost with reason: 4
I/WindowState( 3496): WIN DEATH: Window{39262831 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
,D/ConnectivityService( 3496): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 3496): Force stopping com.example.hello appid=10408 user=0: pkg removed
,I/ActivityManager( 3496):   Force finishing activity ActivityRecord{ffd3753 u0 com.example.hello/.MainActivity t25 f}
W/ActivityManager( 3496): Duplicate finish request for ActivityRecord{ffd3753 u0 com.example.hello/.MainActivity t25 f}
,D/ResourcesManager(12165): creating new AssetManager and set to /system/app/KeyguardWallpaperUpdator/KeyguardWallpaperUpdator.apk
,I/DBG_DM  ( 6398): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/art     ( 9172): Explicit concurrent mark sweep GC freed 24001(1410KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.073ms total 41.043ms
,I/art     ( 4053): Explicit concurrent mark sweep GC freed 32957(2027KB) AllocSpace objects, 2(103KB) LOS objects, 21% free, 28MB/36MB, paused 1.998ms total 56.041ms
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 3
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,W/GeofencerStateMachine( 4636): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 3496): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4497): mOCRHelper is null
,D/ResourcesManager( 3979): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3979): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/LWLocationManager(11505): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11505): getLastUiLocationId() : mLastUiLocationId = -100
I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6398): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 3
,W/ResourcesManager( 3979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SystemBroadcastReceiver(11642): [#DCM#] [DCM_Performance] onReceive completed in time  792 microsec. 
,I/SystemBroadcastReceiver(11642): [#DCM#] Calling notifyListeners. 
,I/DCMController(11642): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController(11642): [#DCM#] setIsConnectedForExtractors 
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/NetworkMonitor(11564): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 6398): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/KeyguardWallpaperUpdator(12165): cancelUpdateWallpaper
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/KeyguardWallpaperUpdator(12165): cancelUpdateCategory
D/KeyguardWallpaperUpdator(12165): stopCheckCategoryVersion
,D/SecContentProvider2( 3496): uri = 14 selection = getSealedState
I/SignOutReceiver(11451): WIFI_STATE_CHANGED_ACTION
,D/SecContentProvider2( 3496): mCursor = null
,D/ApplicationPolicy( 3496): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 3
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,E/Zygote  (12183): MountEmulatedStorage()
E/Zygote  (12183): v2
I/libpersona(12183): KNOX_SDCARD checking this for 1000
I/libpersona(12183): KNOX_SDCARD not a persona
,I/SELinux (12183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 6398): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6398): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6398): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/ActivityManager( 3496): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=12183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (12183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/DBG_DM  ( 6398): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6398): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
E/SELinux (12183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3496): Killing 10982:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/ActivityManager( 3496): post active user change for 0
D/KnoxTimeoutHandler( 3496): postActiveUserChange for user 0
,D/EnterpriseDeviceManagerService( 3496): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3496): Admin package name: com.google.android.gms
,I/DBG_DM  ( 6398): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
I/art     ( 3496): Explicit concurrent mark sweep GC freed 85832(5MB) AllocSpace objects, 25(400KB) LOS objects, 24% free, 49MB/65MB, paused 2.215ms total 168.736ms
,I/art     ( 3496): WaitForGcToComplete blocked for 165.250ms for cause Explicit
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/SurfaceFlinger( 2849): id=14 createSurf (1440x2560),2 flag=404, YUIInstallC
D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/wpa_supplicant( 3822): wlan0: CTRL-EVENT-TERMINATING 
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/StatusBarManagerService( 3496): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3496): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/WifiStateMachine( 3496): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine( 3496): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
,D/TimaKeyStoreProvider(12183): TimaSignature is unavailable
,D/ActivityThread(12183): Added TimaKeyStore provider
,I/DBG_DM  ( 6398): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,I/DBG_DM  ( 6398): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,V/ActivityThread( 6398): updateVisibility : ActivityRecord{16470ee9 token=android.os.BinderProxy@3d66dda2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,E/WifiStateMachine( 3496): Supplicant connection lost
,D/Tethering( 3496): InitialState.processMessage what=4
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/Tethering( 3496): No numeric data
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourceType( 5433): For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
W/ResourceType( 5433): Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
W/ResourceType( 5433): For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
W/ResourceType( 5433): Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,E/WifiStateMachine( 3496): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL( 3496): callSECApiBoolean - ID [21]
,E/WifiStateMachine( 3496): setWifiState: disabled
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/StatusBar.NetworkController( 3690): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 3690): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 3690): onStateChanged: Wi-Fi
,D/HotspotTile( 3690): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 3690): onReceive : 1, 0
,W/ResourceType( 5433): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5433): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,W/Settings( 4636): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Tethering( 3496): sendTetherStateChangedBroadcast 0, 0, 0
,D/ResourcesManager(12183): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/HotspotTile( 3690): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 3690): updateTetherState():false, false
,V/NetworkStats( 3496): performPollLocked(flags=0x1)
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NetworkStatsFactory( 3496): UpdateStatsForKnox
,D/InputMethodManagerService( 3496): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,V/NetworkStats( 3496): performPollLocked() took 9ms
D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,D/NtpTrustedTime( 3496): currentTimeMillis() cache hit
,W/InputMethodManagerService( 3496): Got RemoteException sending setActive(false) notification to pid 11980 uid 10408
,W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Timeline( 6398): Timeline: Activity_idle id: android.os.BinderProxy@3d66dda2 time:111371
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ActivityManager( 3496): mDVFSHelper.release()
I/Timeline( 3496): Timeline: Activity_windows_visible id: ActivityRecord{177e3512 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:111378
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/ActivityManager( 3496): Killing 11221:com.wsomacp/u0a28 (adj 13): bgCount ##31
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11505): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/art     ( 3496): Explicit concurrent mark sweep GC freed 11261(579KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 49MB/65MB, paused 1.804ms total 188.096ms
,I/art     ( 3496): WaitForGcToComplete blocked for 205.040ms for cause Explicit
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/RegisteredServicesCache( 3963): empty dynamic service
,D/PackageManager( 3496): delete codoeFile: 
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(11505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AASAUninstall( 3496):  com.example.hello not target!
W/ResourcesManager(11505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11505): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/PackageManager( 3496): result of delete: 1{496420176}
,D/AndroidRuntime(12116): Shutting down VM
D/SecContentProvider2( 3496): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3496): mCursor = null
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/ContextImpl( 8995): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/DockEventReceiver( 8995): finishStartingService: stopping service
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/BluetoothNotiBroadcastReceiver( 8995): onReceive
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,E/Zygote  (12204): MountEmulatedStorage()
E/Zygote  (12204): v2
I/libpersona(12204): KNOX_SDCARD checking this for 1002
E/WifiStateMachine( 3496): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
I/libpersona(12204): KNOX_SDCARD not a persona
,I/SELinux (12204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3496): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=12204 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
I/SELinux (12204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/TimaKeyStoreProvider(12204): TimaSignature is unavailable
,D/ActivityThread(12204): Added TimaKeyStore provider
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/art     ( 3496): Explicit concurrent mark sweep GC freed 3916(265KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.913ms total 151.814ms
,D/ResourcesManager(12204): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager(12204): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/ResourcesManager(12204): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/BluetoothA2dpSinkServiceJni(12204): register_com_android_bluetooth_a2dp_sink
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/BtSettings.ProfileConfig(12204): Adding GattService
,D/BtSettings.ProfileConfig(12204): Adding HeadsetService
D/BtSettings.ProfileConfig(12204): Adding A2dpService
D/BtSettings.ProfileConfig(12204): Adding HidService
D/BtSettings.ProfileConfig(12204): Adding HealthService
D/BtSettings.ProfileConfig(12204): Adding PanService
D/BtSettings.ProfileConfig(12204): Adding BluetoothMapService
,D/BtSettings.ProfileConfig(12204): Adding SapService
D/BtSettings.ProfileConfig(12204): Adding HeadsetClientService
D/BtSettings.ProfileConfig(12204): Adding A2dpSinkService
D/BtSettings.ProfileConfig(12204): Adding SapClientService
D/BtSettings.ProfileConfig(12204): Adding HidDevService
,I/BtSettings.ProfileConfig(12204): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
,D/SettingsProvider( 3496): selectionArgs: 1002
W/ResourceType( 3496): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
D/SettingsProvider( 3496): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 3496): ret = -1
D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
,D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
D/SettingsProvider( 3496): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 3496): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3496): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3496): selectionArgs: false
D/SettingsProvider( 3496): selectionArgs: 1002
,D/SecContentProvider( 3496): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3496): ret = -1
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager( 3496): Killing 11237:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/AuthorizationBluetoothService( 4189): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/ResourcesManager(11505): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
W/ResourcesManager( 3496): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 3496): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
W/ResourcesManager( 3496): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3496): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  (12220): MountEmulatedStorage()
,E/Zygote  (12220): v2
I/libpersona(12220): KNOX_SDCARD checking this for 10063
I/libpersona(12220): KNOX_SDCARD not a persona
,I/SELinux (12220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/ActivityManager( 3496): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=12220 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/SELinux (12220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12220): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TimaKeyStoreProvider(12220): TimaSignature is unavailable
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ActivityThread(12220): Added TimaKeyStore provider
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Music2/Music2.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(12220): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3496): clearDefaults: com.example.hello
I/CrashAnrDetector( 3496): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 3496): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/VRSetupWizardStub/PackageIntentReceiver(12220): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(12220): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(12220): packagename:com.example.hello
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 3496): PackageReceiver onReceive()
I/HarmonyEASService( 3496): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 3496): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3496): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3496): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3496): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3496): uID is 10408
V/EnterpriseBillingPolicy( 3496): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3496): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3496): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3496): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3496): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3496): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3496): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  (12237): MountEmulatedStorage()
E/Zygote  (12237): v2
I/libpersona(12237): KNOX_SDCARD checking this for 10021
I/libpersona(12237): KNOX_SDCARD not a persona
I/SELinux (12237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
I/SELinux (12237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3496): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=12237 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3496): Killing 11279:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
D/SmartBondingService( 3496): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService( 3496): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService( 3496): getSBEnabled() enabled =false
D/SmartBondingService( 3496): getSBEnabled() enabled =false
D/SmartBondingService( 3496): getSBEnabled() enabled =false
D/KnoxTimeoutHandler( 3496): handleActiveUserChange for user 0
D/SmartBondingService( 3496): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation( 3496): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/TaskPersister( 3496): removeObsoleteFile: deleting file=25_task.xml
D/SmartBondingService( 3496): getNetworkEnabled : wifi : false mobile : false
D/TaskPersister( 3496): removeObsoleteFile: deleting file=24_task.xml
,D/SmartBondingService( 3496): getNetworkEnabled : wifi : false mobile : false
,W/SLocation( 3496): No Active Data Connection
,W/System.err( 3496): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
,W/System.err( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3496): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
W/System.err( 3496): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3496): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3496): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3496): 	at com.android.server.SystemServer.run(SystemServer.java:427)
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/System.err( 3496): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3496): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3496): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3496): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3496): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3496): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3496): 	... 12 more
W/System.err( 3496): java.io.FileNotFoundException: /data/system/harmony_third_party_apps.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 3496): 	at com.android.server.HarmonyEASService.saveHash(HarmonyEASService.java:303)
W/System.err( 3496): 	at com.android.server.HarmonyEASService.access$000(HarmonyEASService.java:60)
W/System.err( 3496): 	at com.android.server.HarmonyEASService$PackageHandler.handleMessage(HarmonyEASService.java:100)
W/System.err( 3496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3496): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3496): 	at com.android.server.SystemServer.run(SystemServer.java:427)
W/System.err( 3496): 	at com.android.server.SystemServer.main(SystemServer.java:312)
W/System.err( 3496): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3496): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 3496): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 3496): 	at libcore.io.Posix.open(Native Method)
W/System.err( 3496): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 3496): 	... 12 more
I/ApplicationPolicy( 3496): updateDataUsageMap
I/ApplicationPolicy( 3496): updateDataUsageMap  idList is null 
,D/StatusBar( 3690): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
D/TimaKeyStoreProvider(12237): TimaSignature is unavailable
D/ActivityThread(12237): Added TimaKeyStore provider
D/ResourcesManager(11505): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(12237): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/KLMS-2.4.521: (12237): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Nov 20 12:51:43 GMT+01:00 2015
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3496): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3496): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3496): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3496): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3496): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3496): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3496): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3496): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/FactoryTest(10784): Not factory mode
D/FactoryTest(10784): Not factory mode. isFactoryMode() returend false
,D/ResourcesManager(11505): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/MTPRx   (10784): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   (10784): still no open session command from host, so toast
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
W/ContextImpl(10784): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
W/ContextImpl(10784): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
I/Timeline(10784): Timeline: Activity_launch_request id:com.android.settings time:111907
,E/PersonaManagerService( 3496): inState():  stateMachine is null !!
I/PersonaManagerService( 3496): PersonaId don't exist
I/ActivityManager( 3496): do not start freezing screen for locked container getKeyguardshowstate = false
,I/KLMS-2.4.521: (12237): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3496): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
I/splitIntent( 3496): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/MtpClient(11707): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(11707): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (12237): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (12237): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (12237): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/UsbHostManager( 3496): usbDeviceRemoved : /dev/bus/usb/001/001
,E/UsbHostManager( 3496): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,I/KLMS-2.4.521: (12237): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  (12260): MountEmulatedStorage()
I/libpersona(12260): KNOX_SDCARD checking this for 10106
E/Zygote  (12260): v2
I/libpersona(12260): KNOX_SDCARD not a persona
,I/SELinux (12260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/KLMS-2.4.521: (12237): KLMSIntentService(): PACKAGE_REMOVED
,I/ActivityManager( 3496): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=12260 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/SELinux (12260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (12237): KLMSIntentService(): listeningToPackageRemoved().START
I/EventHub( 3496): Removing device '/dev/input/event10' due to inotify event
,I/KLMS-2.4.521: (12237): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3496): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager( 3496): mDVFSHelper.acquire()
,I/EventHub( 3496): Removing device '/dev/input/event7' due to inotify event
,D/TimaKeyStoreProvider(12260): TimaSignature is unavailable
,D/ActivityThread(12260): Added TimaKeyStore provider
,I/EventHub( 3496): Removing device '/dev/input/event8' due to inotify event
,E/MTPRx   (10784): started activity for popup
,D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (12237): KLMSIntentService(): listeningToPackageRemoved().END
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5133): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 5133): (3850) statement aborts at 31: [INSERT INTO use_app(place_category,app_sub_id,longitude,start_time,app_id,verification,timestamp,place_name,compat_device_status,duration,stop_time,time_zone,launcher_type,starttime,la
,E/SQLiteDatabase( 5133): Error inserting place_category=0 app_sub_id=com.android.settings.SettingsReceiverActivity longitude=-200.0 start_time=2015-11-20 11:51:43.987 app_id=com.android.settings verification=0 timestamp=1448020304014 place_name= compat_device_status=128 duration=21 stop_time=2015-11-20 11:51:44.008 time_zone=+0100 launcher_type=0 starttime=1448020303987 latitude=-200.0 stoptime=1448020304008 timestamp_utc=2015-11-20 11:51:44.014
E/SQLiteDatabase( 5133): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5133): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5133): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5133): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5133): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5133): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
E/SQLiteDatabase( 5133): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.log.BaseLogProvider.insertLog(BaseLogProvider.java:615)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.log.BaseLogProvider.insert(BaseLogProvider.java:210)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.util.ContextLogger.logLocalProvider(ContextLogger.java:45)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.status.AppUsageMonitor.loggingUseApp(AppUsageMonitor.java:290)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.status.AppUsageMonitor.insertItem(AppUsageMonitor.java:227)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.status.AppUsageMonitor.handleMessage(AppUsageMonitor.java:341)
E/SQLiteDatabase( 5133): 	at com.samsung.android.providers.context.ContextService$ServiceHandler.handleMessage(ContextService.java:326)
E/SQLiteDatabase( 5133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5133): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5133): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase( 5133): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5133): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/EventHub( 3496): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (12275): MountEmulatedStorage()
I/libpersona(12275): KNOX_SDCARD checking this for 10101
E/Zygote  (12275): v2
I/libpersona(12275): KNOX_SDCARD not a persona
,I/SELinux (12275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12275): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3496): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12275 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/EventHub( 3496): Removing device '/dev/input/event11' due to inotify event
,D/ResourcesManager(10784): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10784): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10784): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (12237): KLMSIntentService(): onDestroy()
,I/EventHub( 3496): Removing device '/dev/input/event12' due to inotify event
,I/EventHub( 3496): Removing device '/dev/input/event13' due to inotify event
,E/SettingsReceiverActivity(10784): PREF_DONT_ASK_AGAIN : true
,D/ResourcesManager(12260): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(12275): TimaSignature is unavailable
,D/ActivityThread(12275): Added TimaKeyStore provider
,D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService( 3496): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 3496): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1b218ec9 attribute=null, token = android.os.BinderProxy@20f5ac1a
,D/elm:14491(12260): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/EventHub( 3496): Removing device '/dev/input/event14' due to inotify event
D/elm:14491(12260): ELMEngine.ELMEngine( context ).
,D/elm:14491(12260): MDMBridge.setEnterpriseBridge()
,E/SharedPreferencesImpl(11707): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,D/elm:14491(12260): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(12260): ElmAgentService : onCreate()
,D/elm:14491(12260): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(12275): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14491(12260): MainReceiver.listeningToPackageRemoved()
D/elm:14491(12260): MDMBridge.getInstance()
D/elm:14491(12260): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/elm:14491(12260): MDMBridge.getAllLicenseInfoFromSDK()
,D/SettingsReceiverActivity(10784): dev.kiessupport is : TRUE
,E/Zygote  (12295): MountEmulatedStorage()
,E/Zygote  (12295): v2
I/libpersona(12295): KNOX_SDCARD checking this for 10190
,I/libpersona(12295): KNOX_SDCARD not a persona
,I/SELinux (12295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3496): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=12295 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (12295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
