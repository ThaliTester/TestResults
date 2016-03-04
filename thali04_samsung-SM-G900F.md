#### Test 61703351a2a4153_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
D/AndroidRuntime( 7838): 
D/AndroidRuntime( 7838): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7838): CheckJNI is OFF
D/AndroidRuntime( 7838): setted country_code = Poland
D/AndroidRuntime( 7838): setted countryiso_code = PL
D/AndroidRuntime( 7838): setted sales_code = XEO
D/AndroidRuntime( 7838): readGMSProperty: start
D/AndroidRuntime( 7838): readGMSProperty: already setted!!
D/AndroidRuntime( 7838): readGMSProperty: end
D/AndroidRuntime( 7838): addProductProperty: start
E/AffinityControl( 7838): AffinityControl: registerfunction enter
D/AndroidRuntime( 7838): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  890): inState():  stateMachine is null !!
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager(  890): mDVFSHelper.acquire()
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  890): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=7853 uid=10192 gids={50192, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
E/Zygote  ( 7853): MountEmulatedStorage()
E/Zygote  ( 7853): v2
I/libpersona( 7853): KNOX_SDCARD checking this for 10192
D/AndroidRuntime( 7838): Shutting down VM
I/libpersona( 7853): KNOX_SDCARD not a persona
I/SELinux ( 7853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
I/SELinux ( 7853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7853): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7853): TimaSignature is unavailable
D/ActivityThread( 7853): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3248): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3248): getDatabaseLocked(b,b,pwd)...
D/ResourcesManager( 7853): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/WebViewFactory( 7853): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7853): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7853): Loading: webviewchromium
,I/LibraryLoader( 7853): Time to load native libraries: 3 ms (timestamps 6572-6575)
,I/LibraryLoader( 7853): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7853): Binding Chromium to main looper Looper (main, tid 1) {7627c8d}
,I/LibraryLoader( 7853): Expected native library version number "",actual native library version number ""
I/chromium( 7853): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7853): Initializing chromium process, renderers=0
,W/art     ( 7853): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7853): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7853): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7853): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7853): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7853): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7853): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7853): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7853): Remote Branch: 
I/Adreno-EGL( 7853): Local Patches: 
I/Adreno-EGL( 7853): Reconstruct Branch: 
,I/ServiceManager(  360): Waiting for service AtCmdFwd...
,W/chromium( 7853): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 7853): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager(  890): Activity pause timeout for ActivityRecord{32d007e6 u0 com.example.hello/.MainActivity t15}
,W/art     ( 7853): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7853): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7853): CordovaWebView is running on device made by: samsung
,W/art     ( 7853): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7853): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7853): performCreate Call secproduct feature valuefalse
,D/Activity( 7853): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7853): Render dirty regions requested: true
,D/ActivityManager(  890): post active user change for 0
,D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,I/OpenGLRenderer( 7853): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7853): HWUI protection enabled for context ,  &this =0xa1953060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7853): Enabling debug mode 0
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{32d007e6 u0 com.example.hello/.MainActivity t15} time:187305
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/IInputConnectionWrapper( 7853): showStatusIcon on inactive InputConnection
I/Timeline( 7853): Timeline: Activity_idle id: android.os.BinderProxy@26433354 time:187319
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1182): value : false
,I/chromium( 7853): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 7853): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 7853): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7853): 
,E/SMD     (  293): DCD ON
,D/JsMessageQueue( 7853): Set native->JS mode to OnlineEventsBridgeMode
,W/Atfwd_Sendcmd(  360): AtCmdFwd service not published, waiting... retryCnt : 5
,D/jxcore_app_log( 7853): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259442176
,W/jxcore-log( 7853): Initializing JXcore engine
W/jxcore-log( 7853): JXcore engine is ready
,E/auditd  ( 2248): In denial and Property audit_ondenial is set to 1 
,W/jxcore-log( 7853): Starting JXcore engine
,D/SecurityLogAgent:SEDenialService(  890): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  890): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7916): MountEmulatedStorage()
I/libpersona( 7916): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7916): v2
I/libpersona( 7916): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7916 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7916): TimaSignature is unavailable
,D/ActivityThread( 7916): Added TimaKeyStore provider
,D/ResourcesManager( 7916): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7853): Platform android
W/jxcore-log( 7853): 
,W/jxcore-log( 7853): Process ARCH arm
W/jxcore-log( 7853): 
,I/jxcore-log( 7853): JXcore Cordova bridge is ready!
I/jxcore-log( 7853): 
,D/SecurityLogAgent( 7916):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7916):  SeDenialReceiver : File path = null
W/jxcore-log( 7853): JXcore engine is started
,I/ActivityManager(  890): Killing 6873:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,E/jxcore-log( 7853): >> samsung-SM-G900F
E/jxcore-log( 7853): 
,I/jxcore-log( 7853): Total memory 1787449344
I/jxcore-log( 7853): 
,I/jxcore-log( 7853): Free memory 61423616
I/jxcore-log( 7853): 
,I/jxcore-log( 7853): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7853): 
,I/jxcore-log( 7853): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7853): 
,W/libprocessgroup(  890): failed to open /acct/uid_10011/pid_6873/cgroup.procs: No such file or directory
,I/jxcore-log( 7853): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log( 7853): 
,I/jxcore-log( 7853): Size 1080 1920
I/jxcore-log( 7853): 
,I/jxcore-log( 7853): Screen Brightness 134
I/jxcore-log( 7853): 
,E/jxcore-log( 7853): Dummy Error Log.
E/jxcore-log( 7853): 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  890): stay LED for fully charged
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3874): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3874): Disconnected process message: 10
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 335, CUR = 450
,I/jxcore-log( 7853): getBuffer is called!!!!
I/jxcore-log( 7853): 
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 6
,E/SMD     (  293): DCD ON
,D/BluetoothAdapter( 7853): disable()
,D/SettingsProvider(  890): name = bluetooth_on
,D/BluetoothAdapterState( 3874): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 3874): Setting state to 13
,I/BluetoothAdapterState( 3874): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 3874): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3874): updateAdapterState state is 13
,D/BluetoothAdapterService( 3874): Autoconnection is available 
,D/BluetoothAdapterService( 3874): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 3874): terminating service from this receiver
,D/BluetoothAdapterProperties( 3874): onBluetoothDisable()
,D/SecContentProvider(  890): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 3874): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3874): Scan Mode:20
,D/bt_vendor( 3874): op for 7
,D/BluetoothAdapterState( 3874): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/bt_upio ( 3874): proc btwrite assertion
,E/bt-btif ( 3874): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3874): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 3874): cmd socket is not created
,D/btif_config_util( 3874): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/BtOppRfcommListener( 3874): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,I/BluetoothPbapService( 3874): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothSocket( 3874): close() in, this: android.bluetooth.BluetoothSocket@3adfe4d, channel: 19, state: LISTENING
D/BluetoothSocket( 3874): close() this: android.bluetooth.BluetoothSocket@3adfe4d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b83195, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@111eed02mSocket: android.net.LocalSocket@7edb613 impl:android.net.LocalSocketImpl@33628050 fd:FileDescriptor[72]
D/BluetoothSocket( 3874): Closing mSocket: android.net.LocalSocket@7edb613 impl:android.net.LocalSocketImpl@33628050 fd:FileDescriptor[72]
,E/bt-btm  ( 3874): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 3874): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 3874): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3874): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x001b not found for deregistration
,D/bt_vendor( 3874): op for 7
D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,D/bt_vendor( 3874): op for 7
,D/bt_upio ( 3874): BT_WAKE is asserted already
,E/ActivityThread( 3874): Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@1add0f20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3874): android.app.IntentReceiverLeaked: Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@1add0f20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3874): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:960)
E/ActivityThread( 3874): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:761)
E/ActivityThread( 3874): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1945)
E/ActivityThread( 3874): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1925)
E/ActivityThread( 3874): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1919)
E/ActivityThread( 3874): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 3874): 	at com.samsung.ble.BleAutoConnectService.onCreate(BleAutoConnectService.java:139)
E/ActivityThread( 3874): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 3874): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 3874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 3874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3874): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3874): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3874): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3874): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/InputMethodManagerService(  890): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  890): [BT Setting State] State =13
,D/BluetoothSocket( 3874): close() in, this: android.bluetooth.BluetoothSocket@3b12d74e, channel: 5, state: LISTENING
,D/BluetoothSocket( 3874): close() this: android.bluetooth.BluetoothSocket@3b12d74e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22c6b2aa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38f3a06fmSocket: android.net.LocalSocket@3f77517c impl:android.net.LocalSocketImpl@2289aa05 fd:FileDescriptor[74]
,D/BluetoothSocket( 3874): Closing mSocket: android.net.LocalSocket@3f77517c impl:android.net.LocalSocketImpl@2289aa05 fd:FileDescriptor[74]
,I/BtOppRfcommListener( 3874): stopping Accept Thread
,D/BluetoothSocket( 3874): close() in, this: android.bluetooth.BluetoothSocket@2b491a5a, channel: 12, state: LISTENING
,D/BluetoothSocket( 3874): close() this: android.bluetooth.BluetoothSocket@2b491a5a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@432a9e4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2fc3d48bmSocket: android.net.LocalSocket@2fa60968 impl:android.net.LocalSocketImpl@effe181 fd:FileDescriptor[78]
,D/BluetoothSocket( 3874): Closing mSocket: android.net.LocalSocket@2fa60968 impl:android.net.LocalSocketImpl@effe181 fd:FileDescriptor[78]
,I/BtOppRfcommListener( 3874): BluetoothSocket listen thread finished
,D/BluetoothTile( 1182): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothPbap( 1320): Proxy object disconnected
,D/STATUSBAR-QSTileView( 1182): onStateChanged: Bluetooth
D/PbapServerProfile( 1320): Bluetooth service disconnected
V/BluetoothEventManager( 1320): Received android.bluetooth.adapter.action.STATE_CHANGED
I/SamsungIME( 1873): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/WifiService(  890): New client listening to asynchronous messages
,I/WifiManager( 7853): packageName : com.example.hello
,D/SecContentProvider(  890): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  890): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  890): mCursor = null
,W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiService(  890): setWifiEnabled: false pid=7853, uid=10192
,E/WifiService(  890): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  890): name = wifi_on
,I/jxcore-log( 7853): ****TEST TOOK:  5293  ms ****
I/jxcore-log( 7853): 
,D/DockEventReceiver( 1320): finishStartingService: stopping service
,I/jxcore-log( 7853): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7853): 
,E/WifiStateMachine(  890): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1271): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1271): wlan0: Setting scan request: 0 sec 0 usec
D/BluetoothNotiBroadcastReceiver( 1320): onReceive
I/wpa_supplicant( 1271): P2P: Current p2p state = IDLE
E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  890): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 1271): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  890): do suspend true
,D/AuthorizationBluetoothService( 2297): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1182): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/NativeCrypto( 2297): Read error: ssl=0xaef7ce00: I/O error during system call, Connection timed out
,D/bt_vendor( 3874): op for 6
D/bt_vendor( 3874): op for 7
D/bt_upio ( 3874): BT_WAKE is asserted already
D/bt_userial( 3874): RX termination
W/bt_userial( 3874): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3874): Leaving userial_read_thread()
W/bt-l2cap( 3874): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3874): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 3874): ag scb idx 1 not allocated
W/bt-btif ( 3874): ag scb idx 2 not allocated
E/bt-btif ( 3874): BTA AG is already disabled, ignoring ...
D/bt_userial( 3874): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 3874): op for 9
D/bt_hwcfg( 3874): hw_epilog_process
D/bt_vendor( 3874): op for 4
I/bt_userial_vendor( 3874): device fd = 65 close
V/NativeCrypto( 2297): SSL shutdown failed: ssl=0xaef7ce00: I/O error during system call, Broken pipe
,D/bt_vendor( 3874): op for 0
,D/bt_upio ( 3874): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 3874): is_emulator_context : 0
D/bt_upio ( 3874): is_rfkill_disabled ? [0]
,D/bt_vendor( 3874): cleanup
I/GKI_LINUX( 3874): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3874): GKI_exit_task 0 done
,I/GKI_LINUX( 3874): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3874): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 3874): isSecureModeOn:false
D/BluetoothAdapterService( 3874): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtGatt.DebugUtils( 3874): handleDebugAction() action=null
,D/BtGatt.GattService( 3874): Received stop request...Stopping profile...
D/BtGatt.GattService( 3874): stop()
D/BtGatt.AdvertiseManager( 3874): advertise clients cleared
,D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/HeadsetService( 3874): Received stop request...Stopping profile...
W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,D/AudioService(  890): onServiceDisconnected: Bluetooth profile: 1
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): ignoring duplicate network state non-change
,D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/GCM     ( 2297): Wifi connection closed with errorCode 20
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadsetProfile( 1320): Bluetooth service disconnected
,D/A2dpService( 3874): Received stop request...Stopping profile...
,V/Avrcp   ( 3874): doQuit
D/A2dpStateMachine( 3874): Exit Disconnected: -1
,W/BluetoothAdapterService( 3874): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/Avrcp   ( 3874): Unregistering previous receiver
,D/ConnectivityService(  890): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,D/BluetoothA2dp(  890): Proxy object disconnected
D/BluetoothA2dp( 1320): Proxy object disconnected
D/A2dpProfile( 1320): Bluetooth service disconnected
,D/AudioService(  890): onServiceDisconnected: Bluetooth profile: 2
,W/BluetoothAdapterService( 3874): Not skipping com.broadcom.bt.service.sap.SapService
,D/HidService( 3874): Received stop request...Stopping profile...
D/HidService( 3874): Stopping Bluetooth HidService
,D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,D/BluetoothInputDevice( 1320): Proxy object disconnected
,D/HidProfile( 1320): Bluetooth service disconnected
,E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothA2dp( 3248): Proxy object disconnected
,W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 3874): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
W/BluetoothAdapterService( 3874): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 3874): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 3874): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 3874): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 3874): Stopping profile services that were post enabled
E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/HealthService( 3874): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  890): scanCount==0 - aborting
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/PanService( 3874): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,D/WifiScanningService(  890): SCAN_AVAILABLE : 1
,D/WifiScanningService(  890): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  890): SCAN_AVAILABLE : 1
D/RttService(  890): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  890): [1,457,094,257,967 ms] noteScanEnd no scan source
,D/WifiP2pService(  890): InactiveState{ what=131204 }
,D/WifiP2pService(  890): P2pEnabledState{ what=131204 }
,D/BluetoothPan(  890): BluetoothPAN Proxy object disconnected
,E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3874): Profile still running: com.android.bluetooth.hid.HidService
,W/BluetoothHeadsetServiceJni( 3874): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3874): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothMapService( 3874): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3874): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 3874): Proxy object disconnected
D/BluetoothAdapterService( 3874): Bluetooth A2dp source service disconnected
D/WifiP2pService(  890): sending p2p connection changed broadcast: FAILED
,I/GKI_LINUX( 3874): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3874): GKI_exit_task 2 done
I/GKI_LINUX( 3874): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 3874): cleanup
E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3874): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/WifiStateMachine(  890): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  890): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,W/BluetoothHidServiceJni( 3874): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3874): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3874): Cleaning up Bluetooth GID callback object
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/SapService( 3874): Received stop request...Stopping profile...
D/SapService( 3874): Stopping Bluetooth SapService
D/BluetoothAdapterService( 3874): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f6c390
,D/WifiDisplayController(  890): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter(  890): onP2pDisconnected
,E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 3874): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3874): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3874): Cleaning up Bluetooth Health object
D/IpRemoteDisplayController(  890): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  890): WfdBridgeServer is already null
E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3874): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3874): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3874): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3874): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3874): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(66503568)( 3874): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 3874): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3874): Setting state to 10
I/BluetoothAdapterState( 3874): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3874): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3874): updateAdapterState state is 10
,W/BluetoothSAPServiceJni( 3874): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 3874): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService( 3874): Autoconnection is available 
,D/BluetoothAdapterService( 3874): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 3874): Entering OffState
D/ConnectivityService(  890): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890): calling update connectivity
,D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/BluetoothMap( 1320): onBluetoothStateChange: up=false
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Hs20UtilService( 1320): Starting #6
D/WifiP2pService(  890): sending p2p connection changed broadcast: DISCONNECTED
I/Hs20UtilService( 1320): Message received 5007
,D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  890): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  890): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  890): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1182): CM callback handler got msg 524292
D/ConnectivityService(  890): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  890): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  890): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Disconnected - quitting
D/CSLegacyTypeTracker(  890): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1489): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothA2dp( 3874): onBluetoothStateChange: up=false
,D/ConnectivityManager.CallbackHandler( 2473): CM callback handler got msg 524292
D/BluetoothPan( 1320): BluetoothPAN Proxy object disconnected
D/PanProfile( 1320): Bluetooth service disconnected
,E/WifiStateMachine(  890): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/Bluetoothsap( 1320): BluetoothSAP Proxy object disconnected
D/SapProfile( 1320): Bluetooth service disconnected
D/WifiDisplayController(  890): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController(  890): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  890): disconnect
D/WifiDisplayController(  890): updateConnection
,D/WifiDisplayController(  890): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  890): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
,D/WifiP2pService(  890): P2pDisablingState
D/WifiP2pService(  890): P2pDisablingState{ what=147458 }
,D/WifiP2pService(  890): p2p socket connection lost
V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
D/WifiP2pService(  890): P2pDisabledState
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WifiDisplayController(  890): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  890): onP2pDisconnected
D/IpRemoteDisplayController(  890): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  890): WfdBridgeServer is already null
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,V/NetworkStats(  890): updateIfacesLocked()
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked(flags=0x1)
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  890): UpdateStatsForKnox
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityService(  890): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.102/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): ignoring duplicate network state non-change
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - enter - invokeEnterMethods
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1182): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1182): updateDataNetType()
D/StatusBar.NetworkController( 1182): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1182): updateLTEICONDataNetType:0
,V/NetworkStats(  890): performPollLocked() took 11ms
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  890): do suspend true
D/StatusBar.NetworkController( 1182): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1182): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
,D/AllShareCastTile( 1182): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiP2pService(  890): P2pDisabledState{ what=143375 }
,D/WifiP2pService(  890): DefaultState{ what=143375 }
D/WifiDisplayAdapter(  890): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1182): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  890): stopping supplicant
I/wpa_supplicant( 1271): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/BluetoothPbap( 1320): onBluetoothStateChange: up=false
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/WifiStateMachine(  890): setWifiState: disabling
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
D/BluetoothA2dp( 1320): onBluetoothStateChange: up=false
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  890): getNetworkEnabled : wifi : false mobile : true
D/SLocation(  890): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/StatusBar.NetworkController( 1182): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1182): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1182): Wifi onReceive(0)
D/HotspotTile( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1182): onStateChanged: Wi-Fi
D/HotspotTile( 1182): onReceive : 0, 0
D/WifiCredService( 1320): Action received :android.net.wifi.WIFI_STATE_CHANGED
V/BitmapFactory( 1182): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_dim.png
D/FileShare-Server( 7643): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/Bluetoothsap( 1320): onBluetoothStateChange: up=false
D/Bluetoothsap( 1320): Unbinding service...
E/WifiStateMachine(  890): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/BluetoothA2dp(  890): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3248): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1320): onBluetoothStateChange: up=false
,I/Hs20UtilService( 1320): Starting #7
,I/Hs20UtilService( 1320): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/AndroidRuntime( 7973): 
D/AndroidRuntime( 7973): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,D/AndroidRuntime( 7973): CheckJNI is OFF
,D/BluetoothManagerService(  890): Broadcasting onBluetoothServiceDown() to 14 receivers.
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
D/AndroidRuntime( 7973): setted country_code = Poland
V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
D/AndroidRuntime( 7973): setted countryiso_code = PL
,D/AndroidRuntime( 7973): setted sales_code = XEO
D/AndroidRuntime( 7973): readGMSProperty: start
D/AndroidRuntime( 7973): readGMSProperty: already setted!!
D/AndroidRuntime( 7973): readGMSProperty: end
D/AndroidRuntime( 7973): addProductProperty: start
,D/BluetoothManagerService(  890): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/EntConnectivity(  890): Not allowed due to - mEnabled false
,W/InputMethodManagerService(  890): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  890): [BT Setting State] State =10
I/InputMethodManagerService(  890): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 1182): 515899699: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1182): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 1182): 515899699: getState() :  mService = null. Returning STATE_OFF
D/STATUSBAR-QSTileView( 1182): onStateChanged: Bluetooth
D/BluetoothAdapter( 1182): 515899699: getState() :  mService = null. Returning STATE_OFF
I/wpa_supplicant( 1271): Blacklist: Clear (all) 
,I/SamsungIME( 1873): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,V/BluetoothEventManager( 1320): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/GKI_LINUX( 3874): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3874): GKI_exit_task 1 done
,I/GKI_LINUX( 3874): GKI_shutdown(): task [BTIF] terminated
D/[CarModeFW]( 7347): ConnectivityManager-handleMessage INITIAL_STATE_OFF
,I/BluetoothServiceJni( 3874): cleanupNative: return from cleanup
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7916): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7916): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7916): StateMachine : Current State = 1
,D/BluetoothAdapter( 2297): 385121025: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2297): 385121025: getState() :  mService = null. Returning STATE_OFF
I/art     ( 3874): System.exit called, status: 0
,I/AndroidRuntime( 3874): VM exiting with result code 0, cleanup skipped.
D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/SecurityLogAgent( 7916): StateMachine : Changed Current State = 1
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1271): p2p0: CTRL-EVENT-TERMINATING 
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1271): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,I/wpa_supplicant( 1271): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1271): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 1271): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1489): FileWriteThread : threadType = 3
,W/ContextImpl( 1320): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  890): Process com.android.bluetooth (pid 3874)(adj 0) has died(53,641)
,D/DockEventReceiver( 1320): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1320): onReceive
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8007): MountEmulatedStorage()
E/Zygote  ( 8007): v2
I/libpersona( 8007): KNOX_SDCARD checking this for 1002
I/libpersona( 8007): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8007 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/AffinityControl( 7973): AffinityControl: registerfunction enter
,I/wpa_supplicant( 1271): Blacklist: Clear (all) 
,D/AndroidRuntime( 7973): Calling main entry com.android.commands.pm.Pm
,I/SELinux ( 8007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/PackageManager(  890): START PACKAGE DELETE: observer{896843527}
D/PackageManager(  890): pkg{<packageName>}
D/PackageManager(  890): user{0}
D/PackageManager(  890): caller{2000}
D/PackageManager(  890): flags{3}
D/PersonaManagerService(  890): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  890): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  890): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
I/SELinux ( 8007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/PackageManager(  890): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  890): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  890): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  890): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  890): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  890): !@killApplicatoin: 10192, uninstall pkg
,I/ActivityManager(  890): Force stopping com.example.hello appid=10192 user=-1: uninstall pkg
,I/ActivityManager(  890): Killing 7853:com.example.hello/u0a192 (adj 0): stop com.example.hello
,E/SELinux ( 8007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  890):   Force finishing activity ActivityRecord{32d007e6 u0 com.example.hello/.MainActivity t15}
,W/ActivityManager(  890): mDVFSHelper.acquire()
,I/WindowState(  890): WIN DEATH: Window{168ac19c u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  890): Client connection lost with reason: 4
,I/SurfaceFlinger(  257): id=15 Removed com.example.hello/com.example.hello.MainActivity (5/8)
,I/SurfaceFlinger(  257): id=15 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/TimaKeyStoreProvider( 8007): TimaSignature is unavailable
,D/ActivityThread( 8007): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/PackageSettings(  890): Skipping PackageSetting{14f9be5f com.test.thalitest/10191} due to missing metadata
,I/wpa_supplicant( 1271): wlan0: CTRL-EVENT-TERMINATING 
,E/WifiStateMachine(  890): Supplicant connection lost
,D/Tethering(  890): InitialState.processMessage what=4
,E/Tethering(  890): No numeric data
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/SQLiteSecureOpenHelper( 3248): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3248): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,E/WifiStateMachine(  890): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL(  890): callSECApiBoolean - ID [21]
E/WifiStateMachine(  890): setWifiState: disabled
,D/Tethering(  890): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  890): Force stopping com.example.hello appid=10192 user=0: pkg removed
,I/DBG_DM  ( 4343): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,I/ActivityManager(  890):   Force finishing activity ActivityRecord{32d007e6 u0 com.example.hello/.MainActivity t15 f}
W/ActivityManager(  890): Duplicate finish request for ActivityRecord{32d007e6 u0 com.example.hello/.MainActivity t15 f}
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 51
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ResourcesManager( 8007): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 8007): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 8007): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4343): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 51
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 30286(1891KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 16MB/21MB, paused 830us total 74.694ms
,I/DBG_DM  ( 4343): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/art     ( 2473): Explicit concurrent mark sweep GC freed 34054(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 21MB/28MB, paused 1.135ms total 91.397ms
,D/BluetoothAdapterApp( 8007): Load D/L JNI Library
,D/FocusedStackFrame(  890): Set to : 0
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 3323): Explicit concurrent mark sweep GC freed 33840(1837KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 14MB/24MB, paused 594us total 55.395ms
,I/BluetoothA2dpSinkServiceJni( 8007): register_com_android_bluetooth_a2dp_sink
,D/HotspotTile( 1182): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1182): updateTetherState():false, false
,V/NetworkStats(  890): performPollLocked(flags=0x1)
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/BluetoothAdapterApp( 8007): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@67dbd78 Instance Count = 1
,D/NetworkStatsFactory(  890): UpdateStatsForKnox
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1182): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1182): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1182): onStateChanged: Wi-Fi
,D/HotspotTile( 1182): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1182): onReceive : 1, 0
,V/BitmapFactory( 1182): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_off.png
,D/WifiCredService( 1320): Action received :android.net.wifi.WIFI_STATE_CHANGED
,V/NetworkStats(  890): performPollLocked() took 37ms
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,W/Settings( 2297): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,E/SamsungIME( 1873): mOCRHelper is null
,W/GeofencerStateMachine( 2297): Ignoring removeGeofence because network location is disabled.
,E/WifiStateMachine(  890): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,E/WifiStateMachine(  890): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  890): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/BluetoothAdapterApp( 8007): onCreate
,D/BtSettings.ProfileConfig( 8007): Adding GattService
,D/BtSettings.ProfileConfig( 8007): Adding HeadsetService
,D/BtSettings.ProfileConfig( 8007): Adding A2dpService
D/BtSettings.ProfileConfig( 8007): Adding HidService
,D/BtSettings.ProfileConfig( 8007): Adding HealthService
,D/BtSettings.ProfileConfig( 8007): Adding PanService
,D/BtSettings.ProfileConfig( 8007): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 8007): Adding SapService
,D/BtSettings.ProfileConfig( 8007): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 8007): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 8007): Adding SapClientService
,D/BtSettings.ProfileConfig( 8007): Adding HidDevService
,I/BtSettings.ProfileConfig( 8007): *********Initializing Bluetooth Profile Settings*******
,D/accuweather( 2214): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,I/art     (  890): Explicit concurrent mark sweep GC freed 52632(3MB) AllocSpace objects, 14(224KB) LOS objects, 31% free, 35MB/51MB, paused 1.976ms total 219.866ms
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/SLocation(  890): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     (  890): WaitForGcToComplete blocked for 55.120ms for cause Explicit
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/SmartBondingService(  890): getNetworkEnabled : wifi : false mobile : true
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 51
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/DBG_DM  ( 4343): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4343): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/DBG_DM  ( 4343): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 4343): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  890): post active user change for 0
D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
I/DBG_DM  ( 4343): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/SurfaceFlinger(  257): id=16 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/SettingsProvider(  890): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/LockPatternUtilsCache( 1182): value : false
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/SettingsProvider(  890): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1002
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
D/BluetoothAdapterApp( 8007): checkSWUpdate
,D/BluetoothAdapterApp( 8007): sw version in prop is 1431675920
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/BluetoothAdapterApp( 8007): sw version in file is 1431675920
D/BluetoothAdapterApp( 8007): sw version is same
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/DBG_DM  ( 4343): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RegisteredServicesCache( 1483): empty dynamic service
I/DBG_DM  ( 4343): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/ActivityManager(  890): Killing 7034:com.sec.enterprise.knox.cloudmdm.smdms/u0a178 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/AuthorizationBluetoothService( 2297): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/SecurityLogAgent( 7916): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 7916): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7916): StateMachine : Current State = 1
D/SecurityLogAgent( 7916): StateMachine : Changed Current State = 1
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/SurfaceWidgetView( 1495): destroyHardwareResources():178421822
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  890): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/Launcher( 1495): onRestart, Launcher: 694824111
,D/Launcher( 1495): onStart, Launcher: 694824111
D/Launcher.HomeView( 1495): onStart
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2214): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/Launcher.HomeView( 1495): onStop
D/SurfaceWidget.Renderer( 2214): [237392/6] SurfaceWidget drawing first frame
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/talkback/talkback.apk
,I/SurfaceFlinger(  257): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/Zygote  ( 8028): MountEmulatedStorage()
I/libpersona( 8028): KNOX_SDCARD checking this for 10018
E/Zygote  ( 8028): v2
I/libpersona( 8028): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8028 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SELinux ( 8028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  890): failed to open /acct/uid_10178/pid_7034/cgroup.procs: No such file or directory
,I/SELinux ( 8028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  890): Got RemoteException sending setActive(false) notification to pid 7853 uid 10192
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 8028): TimaSignature is unavailable
,I/SurfaceFlinger(  257): id=16 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/9)
,D/ActivityThread( 8028): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=16 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/9)
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/Timeline( 4343): Timeline: Activity_idle id: android.os.BinderProxy@d99aa21 time:195100
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager( 8028): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1182): value : false
D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/EnterpriseDeviceManagerService(  890): Package has changed for user 0
D/EnterpriseDeviceManagerService(  890): Admin package name: com.google.android.gms
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{253b6730 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:195143
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
,I/KLMS-2.4.503: ( 8028): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/KLMS-2.4.503: ( 8028): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1457094259093
,I/KLMS-2.4.503: ( 8028): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.503: ( 8028): MainReciver(): REPLACING: false | pkgName: com.example.hello
,D/RCPManagerService(  890): PackageReceiver onReceive()
,I/art     (  890): Explicit concurrent mark sweep GC freed 14820(797KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 2.100ms total 309.716ms
,I/HarmonyEASService(  890): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  890): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  890): Receieved: android.intent.action.PACKAGE_REMOVED
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  890): uID is 10192
V/EnterpriseBillingPolicy(  890): Removed Packageuid is0
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - end - null
,D/Tethering(  890): MasterInitialState.processMessage what=3
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): getNetworkEnabled : wifi : false mobile : true
,I/CLocInfoService(  890): CLoinfo wifi false
,D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,W/SLocation(  890): No Active Data Connection
,D/TaskPersister(  890): removeObsoleteFile: deleting file=15_task.xml
,D/TaskPersister(  890): removeObsoleteFile: deleting file=13_task.xml
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/PackageManager(  890): delete codoeFile: 
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/PackageManager(  890): result of delete: 1{896843527}
,D/AndroidRuntime( 7973): Shutting down VM
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/ApplicationPolicy(  890): updateDataUsageMap
,D/StatusBar( 1182): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1182): Icon Only
,D/LockPatternUtilsCache( 1182): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1182): value : false
D/PanelView( 1182): There is/are notification(s) 
D/PanelView( 1182): There is/are notification(s) 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8046): MountEmulatedStorage()
E/Zygote  ( 8046): v2
I/libpersona( 8046): KNOX_SDCARD checking this for 10103
I/libpersona( 8046): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8046 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  890): Killing 7131:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  326): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 424us total 15.967ms
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 449us total 13.305ms
,I/SELinux ( 8046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8046): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 465us total 14.520ms
,D/TimaKeyStoreProvider( 8046): TimaSignature is unavailable
,W/libprocessgroup(  890): failed to open /acct/uid_10014/pid_7131/cgroup.procs: No such file or directory
,D/ActivityThread( 8046): Added TimaKeyStore provider
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 8046): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/elm:14451( 8046): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14451( 8046): ELMEngine.ELMEngine( context ).
,D/elm:14451( 8046): MDMBridge.setEnterpriseBridge()
,D/elm:14451( 8046): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/elm:14451( 8046): ElmAgentService : onCreate()
,D/elm:14451( 8046): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8046): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8046): MDMBridge.getInstance()
D/elm:14451( 8046): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14451( 8046): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Zygote  ( 8062): MountEmulatedStorage()
E/Zygote  ( 8062): v2
I/libpersona( 8062): KNOX_SDCARD checking this for 10016
I/libpersona( 8062): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8062 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,I/SELinux ( 8062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/elm:14451( 8046): ElmAgentService : onDestroy().
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux ( 8062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  890): Killing 7149:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  890): clearDefaults: com.example.hello
,I/CrashAnrDetector(  890): onPackageRemoved : com.example.hello
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8062): TimaSignature is unavailable
,D/ActivityThread( 8062): Added TimaKeyStore provider
,D/ResourcesManager( 8062): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10015/pid_7149/cgroup.procs: No such file or directory
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 8062): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8062): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8062): onReceive() : package name is not s health. Return !!!
,I/PCWCLIENTTRACE_PushUtil( 7164): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7164): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7164): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7164): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/EventHub(  890): Removing device '/dev/input/event4' due to inotify event
,I/EventHub(  890): Removing device '/dev/input/event5' due to inotify event
,F/libc    ( 5003): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77d75118 in tid 5003 (oid.app.shealth)
,F/libc    ( 5003): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2248): File locking failed. error= Bad file number
,E/audit_log( 2248): File locking failed. error= Bad file number
,F/libc    ( 5508): Fatal signal 7 (SIGBUS), code 2, fault addr 0x773d9ac1 in tid 5508 (om.sec.spp.push)
,F/libc    ( 5508): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2248): File locking failed. error= Bad file number
,I/ActivityManager(  890): Process com.sec.android.app.shealth (pid 5003)(adj 0) has died(101,639)
,I/EventHub(  890): Removing device '/dev/input/event6' due to inotify event
,W/ActivityManager(  890): Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 1000ms
,I/ActivityManager(  890): Process com.sec.spp.push (pid 5508)(adj 0) has died(106,638)
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8080): MountEmulatedStorage()
I/libpersona( 8080): KNOX_SDCARD checking this for 10037
E/Zygote  ( 8080): v2
I/libpersona( 8080): KNOX_SDCARD not a persona
,I/Zygote  (  326): Process 5003 exited due to signal (7)
,I/Zygote  (  326): Process 5508 exited due to signal (7)
,I/EventHub(  890): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8080 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8080): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0014
I/EventHub(  890): Removing device '/dev/input/event8' due to inotify event
E/SELinux ( 8080): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/EventHub(  890): Removing device '/dev/input/event9' due to inotify event
,D/TimaKeyStoreProvider( 8080): TimaSignature is unavailable
,D/ActivityThread( 8080): Added TimaKeyStore provider
,E/SharedPreferencesImpl( 6471): Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,I/EventHub(  890): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager( 8080): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ContextImpl( 8080): Unable to create files subdir /data/data/com.sec.spp.push/cache
E/ActivityThread( 8080): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  890): Removing device '/dev/input/event11' due to inotify event
,E/SPPClientService( 8080): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8080): [PushClientApplication] Push log off : This is Ship build version
,W/ContextImpl( 8080): Unable to create files subdir /data/data/com.sec.spp.push/files
D/SPPClientService( 8080): PushLog.txt file is not deleted.
,W/ContextImpl( 8080): Unable to create files subdir /data/data/com.sec.spp.push/files
D/SPPClientService( 8080): PushLog.txt file is not deleted.
,D/SPPClientService( 8080): ============PushLog. stop!
,F/libc    ( 8080): Fatal signal 7 (SIGBUS), code 2, fault addr 0x77288b4c in tid 8080 (moteNotiProcess)
,F/libc    ( 8080): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2248): File locking failed. error= Bad file number
,I/ActivityManager(  890): Process com.sec.spp.push:RemoteNotiProcess (pid 8080)(adj 0) has died(106,637)
,I/SA      ( 7204): [SUR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
I/SA      ( 7204): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10192 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/qdhwcomposer(  257): handle_blank_event: dpy:0 panel power state: 0
,I/Zygote  (  326): Process 8080 exited due to signal (7)
,F/libc    ( 1831): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7726a44c in tid 1831 (d.process.acore)
,F/libc    ( 1831): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2248): File locking failed. error= Bad file number
,E/audit_log( 2248): File locking failed. error= Bad file number

```
