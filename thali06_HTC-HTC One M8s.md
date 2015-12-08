#### Test 52971095c7b67a5_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
I/ActivityManager(  969): Killing 5275:com.htc.musicenhancer/u0a49 (adj 15): empty #17
--------- beginning of main
D/Process (  969): killProcessQuiet, pid=5275
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  969): Recipient 5275
D/PMS     (  969): acquireWL(3d3f3d15): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{2bc7982a: PendingIntentRecord{ed4c61b android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449576514047, Int=0
D/PMS     (  969): acquireWL(38d6c3b8): PARTIAL_WAKE_LOCK  *backup* 0x1 969 1000 null
D/PMS     (  969): releaseWL(3d3f3d15): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  969): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  969): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  969): releaseWL(38d6c3b8): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,E/cutils-trace( 6231): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6231): ====startRecUseTime====
D/htc.customization.log.level( 6231):  is 
W/CustomizationLogLevel( 6231): Level value is invalid, use default level 2
D/CustomizationManager( 6231):  Read ACC file spent 0.067 (s)
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6231): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6231): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6231): Parsing tag category name = system
I/CustomizationCIDLoader( 6231): Parsing tag category name = application
I/CustomizationCIDLoader( 6231): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6231): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6231): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6231): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6231): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6231): add string-array item, value = 42507
I/CustomizationCIDLoader( 6231): add string-array item, value = 21902
I/CustomizationCIDLoader( 6231): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6231): add string-array item, value = 23420
I/CustomizationCIDLoader( 6231): add string-array item, value = 22299
I/CustomizationCIDLoader( 6231): add string-array item, value = 24002
I/CustomizationCIDLoader( 6231): add string-array item, value = 23210
I/CustomizationCIDLoader( 6231): add string-array item, value = 23205
I/CustomizationCIDLoader( 6231): add string-array item, value = 23806
I/CustomizationCIDLoader( 6231): add string-array item, value = 23430
I/CustomizationCIDLoader( 6231): add string-array item, value = 23408
I/CustomizationCIDLoader( 6231): add string-array item, value = 27205
I/CustomizationCIDLoader( 6231): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6231): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6231):  Read CID file spent 0.127 (s)
D/CustomizationManager( 6231):  All configurations done spent 0.127 (s)
I/ActivityManager(  969): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6231 on display 0
D/PMS     (  969): acquireHCC(3b639591): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 969 1000 null
D/PMS     (  969): acquireHCC(201f0cf6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 969 1000 null
W/asset   (  969): Copying FileAsset 0x5584f85cf0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  969): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6249 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  969): Display changed displayId=0
W/asset   ( 6249): Copying FileAsset 0xab923f98 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1542): [trimMemory] 20
I/WebViewFactory( 6249): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6249): Time to load native libraries: 10 ms (timestamps 6388-6398)
I/LibraryLoader( 6249): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6249): Binding Chromium to main looper Looper (main, tid 1) {31084e39},
I/LibraryLoader( 6249): Expected native library version number "",actual native library version number ""
,I/chromium( 6249): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6249): Initializing chromium process, singleProcess=true,
,W/art     ( 6249): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6249): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6249): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 6249): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6249): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6249): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6249): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6249): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6249): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6249): Local Branch: 
I/Adreno-EGL( 6249): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6249): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
,I/Adreno-EGL( 6249):                  d74aa161a12b9c6fc6332151
,W/System.err(  969): java.lang.Throwable: stack dump,
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@270e5fda:true
,D/BluetoothAdapter( 6249): 169252085: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 6249): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6249): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6249): CordovaWebView is running on device made by: HTC
,W/art     ( 6249): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6249): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6249): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/HtcSystemUPManager(  969): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/StatusBarManagerService(  969): setSystemUiVisibility(0x0),
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
,D/FindExtension( 6249): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6249): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@3857aeeb, mServedView=org.apache.cordova.engine.SystemWebView{29634448 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@35c232e1,
I/InputMethodManagerService(  969): Disable input method client, pid=1542
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6249): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  969): Displayed com.test.thalitest/.MainActivity: +627ms (total +672ms),
,W/BindingManager( 6249): Cannot call determinedVisibility() - never saw a connection for the pid: 6249,
,D/JsMessageQueue( 6249): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6249): JniHelper::setJavaVM(0xab8b18f8), pthread_self() = -1396834792
D/JX-Cordova( 6249): jxcore cordova android initializing
,W/jxcore-log( 6249): Initializing JXcore engine
W/jxcore-log( 6249): JXcore engine is ready
,W/jxcore-log( 6249): Starting JXcore engine
,W/jxcore-log( 6249): Platform android,
W/jxcore-log( 6249): 
W/jxcore-log( 6249): Process ARCH arm
W/jxcore-log( 6249): 
,D/PMS     (  969): releaseHCC(3b639591): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  969): releaseHCC(201f0cf6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6249): JXcore Cordova bridge is ready!,
I/jxcore-log( 6249): 
W/jxcore-log( 6249): JXcore engine is started
,I/Choreographer( 6249): Skipped 98 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6249): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6249): Toggling radios to true
I/jxcore-log( 6249): 
,D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,D/BluetoothManagerService(  969): checking for enable restriction...
D/BluetoothManagerService(  969): checkBTEasState, ret=true
I/BluetoothManagerService(  969): isBluetoothRestricted(): false
D/BluetoothManagerService(  969): enable(): region ID = 6
D/BluetoothManagerService(  969): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  969): MONITOR_LOG
W/Settings:Agent(  969): name: bluetooth_on
W/Settings:Agent(  969): value: 1
,W/Settings:Agent(  969): >> traceCallingStack()
W/Settings:Agent(  969): Process.myPid(): 969
W/Settings:Agent(  969): Process.myTid(): 1701
W/Settings:Agent(  969): Process.myUid(): 1000
W/Settings:Agent(  969): 
W/Settings:Agent(  969): 
W/System.err(  969): java.lang.Throwable: stack dump
,W/System.err(  969): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  969): ,	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  969): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  969): ,	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  969): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  969): 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598),
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  969): ,
W/Settings:Agent(  969): << traceCallingStack(): 3(ms)
,D/BluetoothManagerService(  969): Message: MESSAGE_ENABLE,
,D/BluetoothManagerService(  969): MESSAGE_ENABLE: mBluetooth = null
,E/WifiTrafficPoller(  969): ADD_CLIENT: 7,
D/WifiService(  969): New client listening to asynchronous messages
D/WifiManager( 6249): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  969): setWifiEnabled: true pid=6249, uid=10366
,E/WifiService(  969): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  969): isSprintWifiRestricted(): false
,I/WifiService(  969): isMdmWifiRestricted(): false
,W/Settings:Agent(  969): MONITOR_LOG
W/Settings:Agent(  969): name: wifi_on
W/Settings:Agent(  969): value: 2
W/Settings:Agent(  969): >> traceCallingStack()
W/Settings:Agent(  969): Process.myPid(): 969
W/Settings:Agent(  969): Process.myTid(): 1565
W/Settings:Agent(  969): Process.myUid(): 1000
W/Settings:Agent(  969): 
W/Settings:Agent(  969): 
W/System.err(  969): java.lang.Throwable: stack dump
,W/System.err(  969): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  969): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  969): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  969): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  969): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  969): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  969): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  969): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  969): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  969): 
W/Settings:Agent(  969): << traceCallingStack(): 8(ms)
,I/ActivityManager(  969): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6303 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiController(  969): handleMessage: E msg.what=155656
D/WifiController(  969): processMsg: ApStaDisabledState
,D/WifiManager( 6249): disconnect: Base Package Name=com.test.thalitest, uid=10366,
D/WifiController(  969): transitionTo: destState=DeviceActiveState
D/WifiController(  969): handleMessage: new destination call exit/enter
D/PMS     (  969): acquireWL(2ee1e9e2): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 969 1000 null
E/WifiStateMachine(  969): handleMessage: E msg.what=131145
E/WifiStateMachine(  969): processMsg: InitialState
D/WifiManager( 6249): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  969):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
D/WifiController(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  969):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  969): handleMessage: X
D/WifiController(  969): invokeExitMethods: ApStaDisabledState
E/WifiStateMachine(  969): handleMessage: E msg.what=131146
E/WifiStateMachine(  969): processMsg: InitialState
D/WifiController(  969): moveTempStackToStateStack: i=1,j=1
D/WifiController(  969): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  969):  InitialState CMD_RECONNECT 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
D/WifiController(  969): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
E/WifiStateMachine(  969):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  969): handleMessage: X
D/WifiController(  969): invokeEnterMethods: StaEnabledState
D/WifiController(  969): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  969): setting operational mode to 1
D/WifiController(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131083
E/WifiStateMachine(  969): processMsg: InitialState
I/jxcore-log( 6249): Radios toggled
I/jxcore-log( 6249): 
E/WifiStateMachine(  969):  InitialState CMD_START_SUPPLICANT 0 0
,W/ResourcesManager( 6303): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 6303): Adding HeadsetService,
D/AdapterServiceConfig( 6303): Adding A2dpService
,D/AdapterServiceConfig( 6303): Adding HidService
D/AdapterServiceConfig( 6303): Adding HealthService,
,D/AdapterServiceConfig( 6303): Adding PanService,
,D/AdapterServiceConfig( 6303): Adding GattService
,W/linker  ( 6303): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  969): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27da7ca9:true
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 6303): make
,I/BluetoothAdapterState( 6303): Entering OffState
,E/bt_osi_config( 6303): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,D/BluetoothManagerService(  969): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService,
D/BluetoothManagerService(  969): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  969): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6303): Address is:90:E7:C4:F6:69:77
,D/BluetoothManagerService(  969): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  969): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 6249): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@29db46ae
D/BluetoothAdapter( 6249): onBluetoothServiceUp done
D/BluetoothAdapter(  969): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@29b53a65
,D/BluetoothAdapter(  969): onBluetoothServiceUp done
D/BluetoothAdapter( 1221): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@21bbecbd
D/BluetoothAdapter( 1221): onBluetoothServiceUp done
,D/BluetoothAdapter( 1513): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@176e2473
D/BluetoothAdapter( 1513): onBluetoothServiceUp done
D/BluetoothAdapter( 1805): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2bdd2fbb
D/BluetoothAdapter( 1805): onBluetoothServiceUp done
,D/BluetoothAdapter( 6303): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@177e428a
D/BluetoothAdapter( 6303): onBluetoothServiceUp done
D/BluetoothAdapter( 1490): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2fcc58d5
,D/BluetoothAdapter( 1490): onBluetoothServiceUp done
D/BluetoothAdapter( 3724): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1a7c9e5c
D/BluetoothAdapter( 3724): onBluetoothServiceUp done
D/BluetoothAdapter( 2393): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@175d0794
D/BluetoothAdapter( 2393): onBluetoothServiceUp done
D/BluetoothManagerService(  969): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6303): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 6303): Setting state to 11
I/BluetoothAdapterState( 6303): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  969): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  969): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  969): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  969): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1221): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 6303): make,
,V/BluetoothPbapReceiver( 6303): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6303): ***********state = 11
,D/BluetoothAdapterService( 6303): checkA2dpState: isA2dpSinkEnabled = false
I/BluetoothBondStateMachine( 6303): StableState(): Entering Off State
E/BluetoothAdapterService( 6303): checkA2dpState: returning
D/BluetoothAdapterService( 6303): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6303): checkHfpState: returning
,D/NGFService( 3724): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothAdapterState( 6303): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/PMS     (  969): releaseWL(2ee1e9e2): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
,D/Tethering(  969): interfaceAdded wlan0
I/ActivityManager(  969): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6338 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothHeadset( 1490): Proxy object connected
D/BluetoothHeadset(  969): Proxy object connected
D/HeadsetService( 6303): Received start request. Starting profile...
D/BluetoothHeadset( 1221): Proxy object connected
,D/HeadsetStateMachine( 6303): Version 1.5
D/HeadsetStateMachine( 6303): make
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
,D/Tethering(  969): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  969): TetherInterfaceSM: wlan0: enter InitialState
D/Tethering(  969): interfaceAdded p2p0
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  969): p2p0 is not a tetherable iface, ignoring
D/Tethering(  969): interfaceLinkStateChanged p2p0, false
D/Tethering(  969): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  969): sendTetherStateChangedBroadcast 0, 0, 0
D/PMS     (  969): acquireWL(348286d5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
D/Tethering(  969): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  969): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  969): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothHeadset( 1490): Proxy object connected
D/Tethering(  969): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkPolicy(  969): updateNetworkEnabledLocked()
V/NetworkPolicy(  969): updateNotificationsLocked()
D/PMS     (  969): releaseWL(348286d5): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
D/PMS     (  969): acquireWL(2f1bb51): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
,D/TetherSettings( 5662): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5662): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5662): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5662): Cust_ConnectToPC   : spcsc>false
D/        ( 5662): Cust_ConnectToPC   : IPT>true
D/        ( 5662): Cust_ConnectToPC   : Singel_USB>false
,D/HeadsetStateMachine( 6303): max_hf_connections = 2
D/PMS     (  969): releaseWL(2f1bb51): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  969): updateNetworkEnabledLocked()
V/NetworkPolicy(  969): updateNotificationsLocked()
,D/BluetoothPhoneService( 1490): BluetoothHeadset onServiceConnected
W/Settings( 5662): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/BluetoothHeadset( 1490): Proxy object connected
,E/SmartNS_Utility( 5662): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5662): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5662): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
,W/ContextImpl( 5662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5662): setISNotification
D/BluetoothAdapter(  969): 642104205: getState(). Returning 11
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
,D/SmartNS_Utility( 5662): usb_cable_connect = 1
,D/SmartNS_Utility( 5662): usb_denied = 0
,I/SmartNS_PSService( 5662): usb notificaiton:true
,D/BluetoothAdapter( 1490): 1021749211: getState(). Returning 11
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
,D/HeadsetPhoneState( 6303): listenForPhoneState..for service and signal 
,D/UsbnetService(  969): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false,
D/UsbDeviceManager(  969): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  969): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbnetService(  969): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HeadsetDualPhoneStateListener_SLOT1( 6303): listen phone state by slot:SLOT1  id:-1
D/HeadsetDualPhoneStateListener_SLOT2( 6303): listen phone state by slot:SLOT2  id:-100
D/HeadsetStateMachine( 6303): Enter Disconnected: -2, size: 0
,D/HeadsetDualPhoneStateListener_SLOT1( 6303): listen phone state by slot:SLOT1  id:-1
,D/BluetoothAdapterService( 6303): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2174dc7e
D/HeadsetDualPhoneStateListener_SLOT2( 6303): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6303): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6303): BTHF: set_current_device
,D/BluetoothA2dp(  969): Proxy object connected
D/A2dpService( 6303): Received start request. Starting profile...
I/ActionCombine( 5662): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
V/Avrcp   ( 6303): make
I/QuickSettingMiniLite( 1221): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@3ff3e203
D/BluetoothAdapter(  969): 642104205: getState(). Returning 11
,D/HtcBtWidget_BTWidgetProvider( 6338): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6338): updateWidget(context) for widget: 
E/RemoteController( 6303): Cannot set synchronization mode on an unregistered RemoteController
D/SmartNS_Utility( 5662): usb_cable_connect = 1
D/A2dpStateMachine( 6303): make
D/SmartNS_Utility( 5662): usb_denied = 0
I/SmartNS_PSService( 5662): usb notificaiton:true
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/bt-btif ( 6303): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/QuickSettingBluetooth( 1221): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/A2dpService( 6303): setA2dpService(): set to: null
D/BluetoothAdapterService( 6303): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2174dc7e
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/A2dpStateMachine( 6303): Enter Disconnected: -2
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 5662): Tethered state change:false isNSOpening:false
E/WifiStateMachine(  969): setWifiState: enabling
E/WifiStateMachine(  969): Supplicant start successful
D/WifiMonitor(  969): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  969): connecting to supplicant
,D/TetherSettings( 5662): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5662): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5662): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5662): Cust_ConnectToPC   : spcsc>false
D/        ( 5662): Cust_ConnectToPC   : IPT>true
W/ContextImpl( 5662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5662): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5662): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5662): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5662): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5662): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiHW  (  969): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/HidService( 6303): Received start request. Starting profile...
D/BluetoothAdapterService( 6303): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2174dc7e
I/IntentController( 1221): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/SmartNS_Utility( 5662): setISNotification
D/HealthService( 6303): Received start request. Starting profile...
D/SmartNS_Utility( 5662): usb_cable_connect = 1
,D/SmartNS_Utility( 5662): usb_denied = 0
I/SmartNS_PSService( 5662): usb notificaiton:true
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/BluetoothAdapterService( 6303): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2174dc7e
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/WIFI_ICON( 1221): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PanService( 6303): Received start request. Starting profile...
,D/SmartNS_Utility( 5662): usb_cable_connect = 1
,D/SmartNS_Utility( 5662): usb_denied = 0
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/SmartNS_PSService( 5662): usb notificaiton:true
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/PanService( 6303): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 6303): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2174dc7e
,D/SmartNS_NSReceiver( 5662): Tethered state change:false isNSOpening:false,
D/BtGatt.DebugUtils( 6303): handleDebugAction() action=null
D/BtGatt.GattService( 6303): Received start request. Starting profile...
D/BtGatt.GattService( 6303): start()
,D/BtGatt.AdvertiseManager( 6303): advertise manager created
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/wpa_supplicant( 6366): wpa_supplicant v2.3-devel-5.0.2
D/wpa_supplicant( 6366): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6366): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 6366): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6366): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6366): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6366): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6366): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6366): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6366): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6366): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6366): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6366): update_config=1
D/wpa_supplicant( 6366): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6366): device_name='Android_608e'
D/wpa_supplicant( 6366): manufacturer='HTC'
D/wpa_supplicant( 6366): model_name='HTC_PHONE'
D/wpa_supplicant( 6366): model_number='1234'
D/wpa_supplicant( 6366): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6366): p2p_oper_reg_class=126
D/wpa_supplicant( 6366): p2p_oper_channel=149
D/wpa_supplicant( 6366): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6366): persistent_reconnect=1
D/wpa_supplicant( 6366): key_mgmt_offload=1
I/wpa_supplicant( 6366): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6366): nl80211: RFKILL status not available
D/wpa_supplicant( 6366): nl80211: Using driver-based roaming
D/wpa_supplicant( 6366): nl80211: TDLS supported
D/wpa_supplicant( 6366): nl80211: TDLS external setup
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:1
,D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6366): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  969): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6371 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  969): Killing 5933:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6366): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6366): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6366): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6366): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6366): nl80211: Subscribe to mgmt frames with non-AP handle 0x5580dedfd0
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=0104
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=040a
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=040b
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=040c
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=040d
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=090a
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=090b
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=090c
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=090d
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=0409506f9a09
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=7f506f9a09
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=0801
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=040e
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=06
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=0a07
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=0a11
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580dedfd0 match=0a1a
D/wpa_supplicant( 6366): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  969): interfaceLinkStateChanged p2p0, false
D/Tethering(  969): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6366): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6366): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6366): htc_wext_command_init +
E/wpa_supplicant( 6366): htc_wext_command_init: ifname=p2p0, ignore
D/Tethering(  969): interfaceLinkStateChanged p2p0, false
D/Tethering(  969): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6366): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
D/Process (  969): killProcessQuiet, pid=5933
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/QuickSettingWifi( 1221): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
D/BluetoothAdapter( 1221): 735526803: getState(). Returning 11
I/QuickSettingMiniLite( 1221): updateLiteState:no connect device!
,I/ActivityManager(  969): Recipient 5933,
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
D/BluetoothAdapterService( 6303): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2174dc7e,
,I/RemoteViews( 1221): reapply : com.android.settings 4 36
,D/BluetoothAdapter( 1490): 1021749211: getState(). Returning 11
,W/BluetoothHeadset( 1490): Proxy not attached to service
,I/wpa_supplicant( 6366): wapi_supplicant_init: Init WAI packet p2p0,
D/wpa_supplicant( 6366):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6366):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6366):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6366): nl80211: Flush PMKIDs
D/wpa_supplicant( 6366): p2p0: State: DISCONNECTED -> INACTIVE
D/BluetoothHeadset( 1490): java.lang.Throwable,
D/BluetoothHeadset( 1490): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1490): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1490): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1490): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1490): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1490): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1490): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1490): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1490): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1490): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1490): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/HeadsetPhoneState( 6303): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 6303): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/BluetoothAdapterState( 6303): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/HeadsetStateMachine( 6303): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6303): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6303): Disconnected process message: 11, size: 0
I/bt-btu  ( 6303): btu_task pending for preload complete event
,E/bt_vendor( 6303): get_bt_soc_type: Failed to get soc type
,D/BluetoothMasReceiver( 6303): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 6303): SapReceiver onReceive 
V/BluetoothSapReceiver( 6303): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6303):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6303): startService = false
,D/AuthorizationBluetoothService( 1881): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/qcom-bluetooth( 6396): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,D/HtcWiFiWidget_WiFiWidgetProvider( 6371): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6371): updateWidget(context) for widget: 
,D/wpa_supplicant( 6366): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6366): TDLS: Driver uses external link setup
D/wpa_supplicant( 6366): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/Process (  969): killProcessQuiet, pid=4801
I/ActivityManager(  969): Killing 4801:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/wpa_supplicant( 6366): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6366): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6366): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6366): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6366): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6366): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6366): Using existing control interface directory.
D/wpa_supplicant( 6366): P2P: Add operating class 81
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
,D/wpa_supplicant( 6366): P2P: Own listen channel: 81:1
D/wpa_supplicant( 6366): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6366): P2P: initialized
D/wpa_supplicant( 6366): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6366): P2P: cli_channels:
D/wpa_supplicant( 6366): p2p0: Added interface p2p0
D/wpa_supplicant( 6366): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6366): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6366): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6366): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6366): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6366): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6366): disable_scan_offload=1
D/wpa_supplicant( 6366): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6366): update_config=1
D/wpa_supplicant( 6366): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6366): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6366): manufacturer='HTC'
D/wpa_supplicant( 6366): model_name='HTC One M8s'
D/wpa_supplicant( 6366): model_number='HTC One M8s'
D/wpa_supplicant( 6366): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6366): hs20=1
D/wpa_supplicant( 6366): interworking=1
D/wpa_supplicant( 6366): external_sim=1
D/wpa_supplicant( 6366): key_mgmt_offload=1
,I/qcom-bluetooth( 6402): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd ,
,I/qcom-bluetooth( 6403): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 6366): Priority group 242
I/ActivityManager(  969): Recipient 4801
D/wpa_supplicant( 6366):    id=0 ssid='NG700'
I/wpa_supplicant( 6366): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6366): nl80211: RFKILL status not available
D/wpa_supplicant( 6366): nl80211: Using driver-based roaming
D/wpa_supplicant( 6366): nl80211: TDLS supported
D/wpa_supplicant( 6366): nl80211: TDLS external setup,
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6366): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6366): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplic,ant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key m,anagment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6366): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6366): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6366): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6366): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6366): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6366): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6366): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6366): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6366): nl80211: Subscribe to mgmt frames with non-AP handle 0x5580e0d100
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=0104
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=040a
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=040b
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=040c
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=040d
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=090a
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=090b
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=090c
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=090d
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=0409506f9a09
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=7f506f9a09
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=0801
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=040e
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=06
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=0a07
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=0a11
D/wpa_supplicant( 6366): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5580e0d100 match=0a1a
D/wpa_supplicant( 6366): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6366): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6366): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6366): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6366): htc_wext_command_init +
I/wpa_supplicant( 6366): htc_wext_command_init -
I/wpa_supplicant( 6366): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
D/Tethering(  969): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 6366): Don't set 00 to countryID.conf
D/Tethering(  969): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6366): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6366): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6366): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6366): P2P: Add operating class 81
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6366): P2P: Update channel list
D/wpa_supplicant( 6366): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6366): P2P: cli_channels:
D/wpa_supplicant( 6366): p2p0: Updating hw mode
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6366): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6366): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6366): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
I/qcom-bluetooth( 6405): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6406): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6407): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6408): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/wpa_supplicant( 6366): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 6366):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6366):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6366):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6366): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6366): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6366): nl80211: Flush PMKIDs
,D/wpa_supplicant( 6366): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 6366): TDLS: Driver uses external link setup
D/wpa_supplicant( 6366): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6366): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6366): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6366): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6366): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6366): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6366): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6366): Using existing control interface directory.
I/wpa_supplicant( 6366): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6366): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6366): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6366): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6366): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6366): P2P: Add operating class 81
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6366): P2P: Add operating class 115
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6366): P2P: Add operating class 116
,D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6366): P2P: Add operating class 117
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6366): P2P: Update channel list
D/wpa_supplicant( 6366): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6366): P2P: cli_channels:
D/wpa_supplicant( 6366): p2p0: Updating hw mode
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6366): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6366): Auto country group 1: ch36
D/wpa_supplicant( 6366): wlan0: Added interface wlan0
D/wpa_supplicant( 6366): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6366): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6366): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
I/qcom-bluetooth( 6411): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
D/wpa_supplicant( 6366): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 6366): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6366): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6366): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6366): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6366): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6366): nl80211: Regulatory domain change
D/wpa_supplicant( 6366):  * initiator=1
D/wpa_supplicant( 6366):  * type=0
D/wpa_supplicant( 6366):  * alpha2=DE
D/wpa_supplicant( 6366): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6366): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6366): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6366): P2P: Add operating class 81
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6366): P2P: Add operating class 115
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6366): P2P: Add operating class 116
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6366): P2P: Add operating class 117
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=2): 28 30
,D/wpa_supplicant( 6366): P2P: Update channel list
D/wpa_supplicant( 6366): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6366): P2P: cli_channels:
D/wpa_supplicant( 6366): p2p0: Updating hw mode
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6366): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
,I/qcom-bluetooth( 6412): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 6303): btu_task received preload complete event
,W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x1487
D/PMS     (  969): acquireWL(2bb36266): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6303 1002 null
D/bt-btm  ( 6303): btm_acl_device_down
,D/bt-btm  ( 6303): btm_acl_reset_paging
D/bt-btm  ( 6303): btm_acl_set_discing
,I/bt-btm  ( 6303): btm_reset_complete,
I/bt-btm  ( 6303): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 6303): Start reading local supported commands,
,D/bt-btm  ( 6303): btm_read_local_supported_cmds_complete status (0x00),
,D/bt-btm  ( 6303): BTM reads next extended features page (1),
,D/bt-btm  ( 6303): BTM reads next extended features page (2)
,D/bt-btm  ( 6303): BTM reached last extended features page (2),
D/bt-btm  ( 6303): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,D/bt-btm  ( 6303): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d,
,D/bt-btm  ( 6303): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
,I/bt-btm  ( 6303): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 6303): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11,
I/bt-btm  ( 6303): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 6303): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 6303): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6303): btm_read_ble_wl_size 
,D/bt-btm  ( 6303): btm_read_white_list_size_complete ,
D/bt-btm  ( 6303): btm_get_ble_buffer_size 
,D/bt-btm  ( 6303): btm_read_ble_buf_size_complete ,
D/bt-btm  ( 6303): btm_read_ble_local_supported_states 
,D/bt-btm  ( 6303): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 6303): btm_read_ble_local_supported_features 
D/wpa_supplicant( 6366): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/bt-btm  ( 6303): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 6303): btm_reset_ctrlr_complete: max_page_number: 2
,D/bt-btm  ( 6303): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6303): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6303): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6303): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
D/Tethering(  969): interfaceLinkStateChanged p2p0, false
I/bt-btm  ( 6303):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6303): btm_sec_dev_reset sec mode: 4
D/Tethering(  969): interfaceStatusChanged p2p0, false
I/bt-btm  ( 6303): BTM_SetInquiryMode
I/bt-btm  ( 6303): BTM_SetPageScanType
I/bt-btm  ( 6303): BTM_SetInquiryScanType
E/WifiStateMachine(  969): WiFiDisplay: getWifidisplayApEnabled=false
D/bt-btm  ( 6303): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6303): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6303): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6303): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6303): BTM_BleLoadLocalKeys
D/bt-btm  ( 6303): BTM_BleLoadLocalKeys
,I/bt-btm  ( 6303): BTM_Sec: application registered
E/bt-btm  ( 6303): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf9294d5 
I/bt-btm  ( 6303): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6303): SMP_Register state=0
E/bt-btm  ( 6303): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf9294d5 
,I/bt-btm  ( 6303): BTM_Sec: application registered
D/bt-btm  ( 6303): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6303): BTM: BTM_WritePageTimeout: Timeout: 8192.
,D/bt-btm  ( 6303): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6303): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6303): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6303): BTM_RegBusyLevelNotif
,D/bt-btm  ( 6303): BTM_BleReadControllerFeatures
I/bt-btm  ( 6303): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6303): GATT_Register
D/bt-att  ( 6303): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6303): allocated gatt_if=3
I/bt-att  ( 6303): GATT_StartIf gatt_if=3
D/bt-att  ( 6303): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6303): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 6303): btm_ble_vendor_capability_vsc_cmpl_cback,
D/bt-btm  ( 6303): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6303): BTM Register For VSEvents is successfully
D/bt-btm  ( 6303): BTM_BleGetVendorCapabilities
I/bt-btif ( 6303): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 6303): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6303): bta_dm_set_dev_name: name: HTC One M8s 
E/bt-btif ( 6303): Calling BTA_HhEnable
I/bt-btif ( 6303): BTA_MceEnable
E/bt-btif ( 6303): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 6303): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6303): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btm  ( 6303):  BTM_BleConfigPrivacy
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 6303): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6303): BTM_AllocateSCN
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6303): BTM_AllocateSCN
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btm  ( 6303): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6303):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6303):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6303): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6303): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6303):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6303):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6303): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6303):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6303):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6303): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6303): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6303):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6303):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 6303): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6303): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
D/bt-btif ( 6303):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6303): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btm  ( 6303): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6303):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6303):                : sec: 0xb6, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6303): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6303):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6303): GATT_Register
D/bt-att  ( 6303): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6303): allocated gatt_if=4
,I/bt-att  ( 6303): GATT_StartIf gatt_if=4
D/bt-att  ( 6303): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6303): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 6303): Scan Mode:21
D/BluetoothAdapterProperties( 6303): Discoverable Timeout:120
I/bt-btif ( 6303): BTA_JvEnable
I/bt-btif ( 6303): BTA_JvRegisterL2cCback
I/bt-btm  ( 6303): BTM_ReadConnectability
I/bt-btm  ( 6303): BTM_ReadDiscoverability
I/bt-btm  ( 6303): BTM_SetDiscoverability
I/bt-btm  ( 6303): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6303): disc_mode 0002
D/bt-btm  ( 6303): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6303): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6303): BTM_SetConnectability
I/bt-btm  ( 6303): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6303): disc_mode 0002
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6303): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6303): BTM_SetDiscoverability
I/bt-btm  ( 6303): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6303): disc_mode 0000
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6303): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6303): BTM_SetConnectability
I/bt-btm  ( 6303): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6303): disc_mode 0000
D/bt-btm  ( 6303): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6303): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
I/bt-btm  ( 6303): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6303): bta_pan_co_init
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6303): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6303):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6303):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btm  ( 6303): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6303):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6303): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6303):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 6303): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6303): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6303): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6303): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6303): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
,D/BluetoothAdapterState( 6303): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6303): ScanMode =  21
D/BluetoothAdapterProperties( 6303): State =  11
D/BluetoothAdapterProperties( 6303): Setting state to 12
I/BluetoothAdapterState( 6303): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  969): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  969): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  969): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  969): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp(  969): onBluetoothStateChange: up=true
D/BluetoothHeadset(  969): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6303): Entering On State
D/BluetoothHeadset( 1490): onBluetoothStateChange: up=true
I/bt-btif ( 6303): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset( 1490): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 6303): Discoverable Timeout:120
D/BluetoothHeadset( 1490): onBluetoothStateChange: up=true
E/bt_mct  ( 6303): hci lib postload completed
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
D/BluetoothManagerService(  969): Bluetooth State Change Intent: 11 -> 12
I/IntentController( 1221): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3724): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3724): Bluetooth Adapter: ON
D/BluetoothManagerService(  969): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/bt-btm  ( 6303): btm_ble_rand_enc_complete
,I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 6a 58 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 99 e2 56 57 07 ae c3 b6 b8 4a dc 39 a1 43 bf e6 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  969): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  969): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapReceiver( 6303): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6303): ***********state = 12
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = ab a1 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 83 07 18 90 16 c6 83 90 11 5f 9e 6b 48 80 cb fa 
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
D/PMS     (  969): acquireWL(14e9a1fd): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5662 1000 null
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 89 d9 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = fd f1 d5 91 46 d1 51 97 53 03 db 4e 59 50 38 ac 
,W/ContextImpl( 5662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothPbapService( 6303): Pbap Service onCreate
,V/BluetoothPbapService( 6303): Starting PBAP service
D/BluetoothAdapter( 6303): 949243768: getState(). Returning 12
,V/BluetoothPbapService( 6303): Handler(): got msg=1
D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 20 88 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = fb 25 40 f8 6a 69 e9 1e 8e 9c ca 0f 35 82 a2 fb 
V/BluetoothPbapService( 6303): Pbap Service startRfcommSocketListener
,D/PMS     (  969): releaseWL(14e9a1fd): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6338): onBTStateChanged() for widget: 
V/BluetoothPbapService( 6303): Pbap Service initSocket
D/PMS     (  969): acquireWL(2f3bb943): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5662 1000 null
D/HtcBtWidget_BTWidgetProvider( 6338): updateWidget(context) for widget: 
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 80 05 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 50 1d d8 67 4f 54 36 61 5e 58 92 d0 44 2f 6e 68 
D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6303): getBluetoothService() called with no BluetoothManagerCallback
,W/System.err(  969): java.lang.Throwable: stack dump
W/System.err(  969): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  969): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  969): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  969): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  969): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e02583e:true
I/bt-btm  ( 6303): BTM_SetDiscoverability
I/bt-btm  ( 6303): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6303): disc_mode 0000
I/bt-btm  ( 6303): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6303): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6303): BTM_SetConnectability
I/bt-btm  ( 6303): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6303): disc_mode 0000
D/bt-btm  ( 6303): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6303): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6303): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6303): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 6303): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): BTA_JvRfcommStartServer
I/bt-btm  ( 6303): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19,
,I/bt-btm  ( 6303):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6303): Succeed to create listening socket 
V/BluetoothPbapService( 6303): Accepting socket connection...
D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 98 e8 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 4a 2b 3a a2 e3 df 7b fd 99 ba 11 fa b4 e5 9a 2f 
D/BluetoothAdapterProperties( 6303): Scan Mode:21
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 32 3d 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 48 d8 e5 7b 0a ce 5b d4 b5 b5 02 34 8d c4 05 2c 
,D/BluetoothAdapter( 1221): 735526803: getState(). Returning 12
D/BluetoothAdapter( 5662): 908891729: getState(). Returning 12
D/BluetoothAdapter( 1221): 735526803: getState(). Returning 12
,I/QuickSettingBluetooth( 1221): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
,I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 66 cb 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 4d 50 4f a7 03 c9 71 a7 52 59 78 77 73 b4 3d f1 
D/BluetoothInputDevice( 5662): BluetoothInputDevice()
,D/BluetoothManagerService(  969): registerStateChangeCallback+
,D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  969): Registered receivers: 7
D/PhoneStatusBar( 1221): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
,I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 2a c0 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = bd 2b cd 75 1c 99 81 6d 9e ba d2 4e 64 b0 3d b4 
,D/BluetoothPan( 5662): BluetoothPan()
,D/BluetoothManagerService(  969): registerStateChangeCallback+
,D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  969): Registered receivers: 8
,D/BluetoothMap( 5662): Create BluetoothMap proxy object
D/BluetoothManagerService(  969): registerStateChangeCallback+
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  969): Registered receivers: 9
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 2e 0d 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 73 ea 0e 8e 7f fd c9 9a e3 dc f5 91 cc ba a0 a9 
,E/BluetoothMap( 5662): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  969): registerStateChangeCallback+
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 5662): BluetoothSap() call bindService
D/BluetoothManagerService(  969): Registered receivers: 10
,W/ContextImpl( 5662): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/BluetoothPbap( 5662): BluetoothPbap()
,D/BluetoothManagerService(  969): registerStateChangeCallback+
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  969): Registered receivers: 11
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
,I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 94 da 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = 4a 51 42 e8 a9 73 86 e6 b1 36 30 56 a6 79 9a c6 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  969): registerStateChangeCallback+
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  969): Registered receivers: 12
,D/BluetoothHeadset( 5662): BluetoothHeadset()
,D/BluetoothManagerService(  969): registerStateChangeCallback+
D/BluetoothManagerService(  969): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  969): Registered receivers: 13
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = ad 29 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = e1 81 53 6b df 1a 7c b5 79 87 64 33 5e d3 69 d2 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
,D/LocalBluetoothProfileManager( 5662): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 6303): Pbap Service onBind
,D/wpa_supplicant( 6366): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_969-3\x00
D/DockEventReceiver( 5662): finishStartingService: stopping service
D/BluetoothA2dp( 5662): Proxy object connected
D/A2dpProfile( 5662): Bluetooth service connected
E/WifiStateMachine(  969): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  969): invokeExitMethods: InitialState
E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  969): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131144
E/WifiStateMachine(  969): processMsg: SupplicantStartingState
D/BluetoothAdapter( 5662): 908891729: getState(). Returning 12
E/WifiStateMachine(  969):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  969): deferMessage: msg=131144
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131085
E/WifiStateMachine(  969): processMsg: SupplicantStartingState
E/WifiStateMachine(  969):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  969): deferMessage: msg=131085
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131149
E/WifiStateMachine(  969): processMsg: SupplicantStartingState
E/WifiStateMachine(  969):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine(  969):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  969): setSuspendOptimizations: 2 true
E/WifiStateMachine(  969): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131101
E/WifiStateMachine(  969): processMsg: SupplicantStartingState
E/WifiStateMachine(  969):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  969): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131101
E/WifiStateMachine(  969): processMsg: SupplicantStartingState
E/WifiStateMachine(  969):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
E/WifiStateMachine(  969): processMsg: DefaultState
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 66 6a 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = f1 16 71 3b ad d7 fa c9 f9 03 a2 4f ca 1a 75 0b 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
E/WifiStateMachine(  969):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  969): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147457
E/WifiStateMachine(  969): processMsg: SupplicantStartingState
E/WifiStateMachine(  969):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,E/WifiStateMachine(  969): Supplicant connection established
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6366): set wifi ON
E/WifiStateMachine(  969): setWifiState: enabled
E/WifiStateMachine(  969): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  969):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6366): SET_SCREEN_ON:Off
I/wpa_supplicant( 6366): htc_wext_set_keepalive +
I/wpa_supplicant( 6366): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6366): getPrivFuncNum +	
I/wpa_supplicant( 6366): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6366): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
I/wpa_supplicant( 6366): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6366): get_ip_address source addr = ffffffff,
I/wpa_supplicant( 6366): htc_wext_set_keepalive gateway addr = 00000000
D/WIFI_ICON( 1221): updateWifiState: WIFI_STATE_CHANGED enabled
I/wpa_supplicant( 6366): htc_wext_set_keepalive - ret = 0
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/WifiNative-HAL(  969): startHal
E/wifi    (  969): getStaticLongField sWifiHalHandle 0x7f9642f300
I/WifiNative-HAL(  969): Could not start hal
E/WifiStateMachine(  969): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  969): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  969): handleScreenStateChanged Exit: false
D/BluetoothAdapter( 6303): 949243768: getState(). Returning 12
D/BluetoothFtpService( 6303): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 6303): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6303):  call MAP start service
W/BluetoothAdapter( 6303): getBluetoothService() called with no BluetoothManagerCallback
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER MACADDR'
D/BluetoothHeadset( 5662): Proxy object connected
I/IntentController( 1221): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/HeadsetProfile( 5662): Bluetooth service connected
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6366): update_config=1
D/wpa_supplicant( 6366): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/bt-btm  ( 6303): btm_ble_rand_enc_complete
I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 05 bd 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = de 15 35 8d 4a ae 64 09 47 29 1f 67 f1 ee 33 89 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
D/WifiConfigStore(  969): Loading config and enabling all networks 
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6366): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6366): wpa_supplicant_ctrl_iface_list_networks: return size = 47
D/BluetoothAdapter( 5662): 908891729: getState(). Returning 12
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
I/bt-btif ( 6303): BTA_JvCreateRecordByUser
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): BTA_JvRfcommStartServer
I/bt-btm  ( 6303): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6303):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
,I/BtOppRfcommListener( 6303): Accept thread started.
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6366): Do not allow key_data field to be exposed
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
,D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/BluetoothFtpService( 6303): htc sense version is 6.0
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/BluetoothInputDevice( 5662): Proxy object connected
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
,D/HidProfile( 5662): Bluetooth service connected
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/BluetoothAdapter( 5662): 908891729: getState(). Returning 12
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='engine'
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6366): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6366): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
W/BluetoothAdapter( 6303): getBluetoothService() called with no BluetoothManagerCallback
,D/HtcWiFiWidget_WiFiWidgetProvider( 6371): onWiFiStateChanged() for widget: 
,E/WifiConfigStore(  969): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/bt-btif ( 6303): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): BTA_JvRfcommStartServer
I/bt-btm  ( 6303): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6303):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothPan( 5662): BluetoothPAN Proxy object connected
D/HtcWiFiWidget_WiFiWidgetProvider( 6371): updateWidget(context) for widget: 
,D/PanProfile( 5662): Bluetooth service connected
D/BluetoothPbap( 5662): Proxy object connected
,D/PbapServerProfile( 5662): Bluetooth service connected
E/BluetoothMasService( 6303): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/PMS     (  969): releaseWL(2f3bb943): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6366): device_name='m8qlul_htc_europe'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6366): manufacturer='HTC'
V/BluetoothFtpService:RfcommSocketAcceptThread( 6303): Run Accept thread
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET model_name HTC One M8s'
,D/wpa_supplicant( 6366): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6366): model_name='HTC One M8s'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6366): model_number='HTC One M8s'
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6366): config_methods='physical_display virtual_push_button'
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/BluetoothMasService( 6303): Add permission for SmsProvider.
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'device_type'='10-0050F204-5'
V/BluetoothMasService( 6303): Starting MAS instances
E/WifiStateMachine(  969): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  969): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  969): moveTempStackToStateStack: i=1,j=1
,E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
D/BluetoothAdapter( 6303): 949243768: getState(). Returning 12
E/WifiStateMachine(  969): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6366): wlan0: Setting scan interval: 15 sec,
,W/Settings( 6014): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiP2pService(  969): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-HAL(  969): Setting external_sim to 1
D/WifiP2pService(  969): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6366): external_sim=1
,D/WifiStateMachine(  969): Setting OUI to DA-A1-19
I/WifiNative-HAL(  969): startHal
E/wifi    (  969): getStaticLongField sWifiHalHandle 0x7f9642f360
I/WifiNative-HAL(  969): Could not start hal
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6366): wlan0: Control interface command 'STA_AUTOCONNECT 0'
I/MailMessageReceiver( 6303): reg:com.android.bluetooth.btservice.AdapterApp@22babe89 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@16870e8e
E/WifiStateMachine(  969): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  969): Driverstarted State enter
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  969): DriverStartedState call setCountryCode()
E/WifiStateMachine(  969): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  969): NetworkAgent == null
I/MailManager( 6303): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@16870e8e
V/EmailUtils( 6303): Manager Instance is not NULL
,E/WifiStateMachine(  969): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/ActivityManager(  969): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6430 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP",
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiTrafficPoller(  969): ENABLE_TRAFFIC_STATS_POLL false Token 0
I/QuickSettingWifi( 1221): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
,W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
,D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  969): setDhcpActive: false
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/WifiP2pService(  969): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6366): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  969): transitionTo: destState=DisconnectedState
E/native  (  969): do suspend false
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  969): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  969): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  969): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6366): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/WifiStateMachine(  969): Driverstarted State enter done
E/WifiStateMachine(  969): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  969): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  969): handleMessage: new destination call exit/enter
E/WifiStateMachine(  969): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  969): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  969): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  969): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  969): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  969): invokeEnterMethods: DisconnectedState,
E/WifiStateMachine(  969): DisconnectedState call setCountryCode()
E/WifiStateMachine(  969):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiScanningService(  969): SCAN_AVAILABLE : 3
D/wpa_supplicant( 6366): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'pno'='1'
D/RttService(  969): SCAN_AVAILABLE : 3
D/wpa_supplicant( 6366): wlan0: nl80211: sched_scan request
D/WifiScanningService(  969): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  969): startHal
D/RttService(  969): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wpa_supplicant( 6366): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6366): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6366): wlan0: nl80211: Sched scan started
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
E/wifi    (  969): getStaticLongField sWifiHalHandle 0x7f9429d520
,I/WifiNative-HAL(  969): Could not start hal
E/WifiScanningService(  969): could not start HAL
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131144
E/WifiStateMachine(  969): processMsg: DisconnectedState
D/libc    (  969): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  969):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131085
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
,E/WifiStateMachine(  969):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131154
E/WifiStateMachine(  969): processMsg: DisconnectedState
,E/WifiStateMachine(  969):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131323
E/WifiStateMachine(  969): processMsg: DisconnectedState
,E/WifiStateMachine(  969):  DisconnectedState what:131323 0 0
D/WifiMonitor(  969): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  969): P2pEnablingState
E/WifiStateMachine(  969): processMsg: ConnectModeState
D/WISPrService( 5662): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  969):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState what:131323 0 0
E/WifiStateMachine(  969): setOperatorSSID enter
D/WifiP2pService(  969): P2pEnablingState{ when=-4ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  969): handleMessage: X
D/WifiP2pService(  969): P2p socket connection successful
E/WifiStateMachine(  969): handleMessage: E msg.what=131104
D/WifiP2pService(  969): P2pEnabledState
E/WifiStateMachine(  969): processMsg: DisconnectedState
,E/WifiStateMachine(  969):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
D/WifiP2pService(  969): sending p2p connection changed broadcast
E/WifiStateMachine(  969):  ConnectModeState what:131104 0 0
W/Settings(  969): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6366): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6366): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6366): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
,E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=131162
E/WifiStateMachine(  969): processMsg: DisconnectedState
W/WifiHW  (  969): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
E/WifiStateMachine(  969):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  969): processMsg: ConnectModeState
D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6366): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6366): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6366): persistent_reconnect=1
,D/wpa_supplicant( 6366): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6366): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6366): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  969):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/WifiDisplayController(  969): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
E/WifiStateMachine(  969): set frequency band 0
D/WifiDisplayController(  969): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/WifiDisplayController(  969): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 6366): wlan0: Control interface command 'DRIVER SETBAND 0'
D/WifiDisplayAdapter(  969): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  969):     Client/Owner: Client
D/WifiDisplayAdapter(  969):     GroupId: 
D/WifiDisplayAdapter(  969):     Passphrase: 
D/WifiDisplayAdapter(  969):     SessionId: 0
D/WifiDisplayAdapter(  969):     IP Address: }
D/wpa_supplicant( 6366): SETBAND: 0
D/wpa_supplicant( 6366): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6366): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6366): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  969): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  969): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6366): nl80211: 2402-2482 @ 40 MHz 20 mBm
E/WifiMonitor(  969): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6366): P2P: Add operating class 81
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6366): P2P: Add operating class 115
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6366): P2P: Add operating class 116
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6366): P2P: Add operating class 117
D/wpa_supplicant( 6366): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6366): P2P: Update channel list
D/wpa_supplicant( 6366): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6366): P2P: cli_channels:
D/wpa_supplicant( 6366): p2p0: Updating hw mode
D/wpa_supplicant( 6366): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6366): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6366): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6366): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6366): nl80211: Added 802.11b mode based on 802.11g information
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0
,W/WifiHW  (  969): QCOM Debug wifi_send_command "SET device_name Android_608e"
V/AudioService(  969): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  969):     Client/Owner: Client
V/AudioService(  969):     GroupId: 
V/AudioService(  969):     Passphrase: 
V/AudioService(  969):     SessionId: 0
V/AudioService(  969):     IP Address: }
D/HtcEffectManagerBase(  969): onEventChanged id=5 status=false
D/HtcEffectManager(  969): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6366): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/HtcEffectManager(  969): convertEffect before=902
D/wpa_supplicant( 6366): p2p0: Control interface command 'SET device_name Android_608e'
D/HtcEffectManager(  969): convertEffect after=902
D/wpa_supplicant( 6366): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6366): device_name='Android_608e'
D/WISPrService( 5662): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiMonitor(  969): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiStateMachine(  969): did set frequency band 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6366): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6366): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6366): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6366): P2P: New SSID postfix: -Android_608e
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6366): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  969): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6366): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6366): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  969): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6366): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6366): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6366): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6366): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  969): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6366): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6366): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6366): wlan0: Cancelling sched scan
D/wpa_supplicant( 6366): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6366): wlan0: ,Setting scan request: 0.000000 sec
I/wpa_supplicant( 6366): wpa_supplicant_scan enter
D/wpa_supplicant( 6366): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6366): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6366): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6366): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  969): done set frequency band 0
W/WifiHW  (  969): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6366): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6366): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6366): Single channel concurrency preference: sta
D/WifiNative-HAL(  969): p2pGetDeviceAddress
W/WifiHW  (  969): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  969): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
D/WifiP2pService(  969): DeviceAddress: 92:e7:c4:e6:4c:f8
W/WifiHW  (  969): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 6366): p2p0: Control interface command 'P2P_FLUSH'
D/WifiDisplayController(  969): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  969):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  969):  primary type: 10-0050F204-5
D/WifiDisplayController(  969):  secondary type: null
D/WifiDisplayController(  969):  wps: 0
D/WifiDisplayController(  969):  grpcapab: 0
D/WifiDisplayController(  969):  devcapab: 0
D/WifiDisplayController(  969):  status: 3
D/WifiDisplayController(  969):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  969):  WFD CtrlPort: 0
D/WifiDisplayController(  969):  WFD MaxThroughput: 0
I/wpa_supplicant( 6366): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6366): P2P: Stopping find
D/wpa_supplicant( 6366): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6366): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6366): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6366): P2P: Stopping find
D/wpa_supplicant( 6366): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6366): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6366): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  969): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6366): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6366): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  969): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6366): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6366): wpa_supplicant_ctrl_iface_list_networks: return size = 34
,W/WifiHW  (  969): QCOM Debug wifi_send_command "SAVE_CONFIG"
,D/wpa_supplicant( 6366): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6366): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/HtcAdjCursorFactory( 6430): Set CursorWindow size to: 4194304 KB, Tid: 6451
,D/wpa_supplicant( 6366): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6366): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6366): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6366): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6366): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  969): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  969): InactiveState
D/WifiStateMachine(  969): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  969): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=147462
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=130405  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  969): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  969): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  969): processMsg: ConnectModeState
E/WifiStateMachine(  969):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=130406  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  969): handleMessage: X
E/WifiStateMachine(  969): handleMessage: E msg.what=143371
E/WifiStateMachine(  969): processMsg: DisconnectedState
E/WifiStateMachine(  969):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  969): processMsg: ConnectModeState
,E/WifiStateMachine(  969):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  969): processMsg: DriverStartedState
E/WifiStateMachine(  969):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  969): processMsg: SupplicantStartedState
E/WifiStateMachine(  969):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  969): processMsg: DefaultState
E/WifiStateMachine(  969):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  969): handleMessage: X
,D/EmailUtils( 6303): ============NULL aList========,
V/EmailUtils( 6303): <-getEmailAccountIdList
V/BluetoothMasService( 6303): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 6303): 949243768: getState(). Returning 12
V/BluetoothMasService( 6303): parseIntent 1: mIsEmailEnabled: true
,V/EmailUtils( 6303): Manager Instance is not NULL
,D/EmailUtils( 6303): ============NULL aList========
V/EmailUtils( 6303): <-getEmailAccountIdList
V/BluetoothSapReceiver( 6303): SapReceiver onReceive 
V/BluetoothSapReceiver( 6303): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6303):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6303): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6303): handleMessage: mIsEmailEnabledtrue,
,V/BtMns   ( 6303): BluetoothMns: isEmailEnabled: true
D/AuthorizationBluetoothService( 1881): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
W/BluetoothAdapter( 6303): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6303): BTA_JvCreateRecordByUser
D/bt-btm  ( 6303): BTM_AllocateSCN
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): BTA_JvRfcommStartServer
I/bt-btm  ( 6303): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 6303):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6303): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6303): BTA_JvCreateRecordByUser
D/bt-btm  ( 6303): BTM_AllocateSCN
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): BTA_JvRfcommStartServer
I/bt-btm  ( 6303): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6303):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  969): killProcessQuiet, pid=5964
I/ActivityManager(  969): Killing 5964:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/art     (  969): Explicit concurrent mark sweep GC freed 29148(1535KB) AllocSpace objects, 2(204KB) LOS objects, 33% free, 16MB/24MB, paused 1.513ms total 155.466ms,
E/WifiTrafficPoller(  969): ADD_CLIENT: 8
D/WifiService(  969): New client listening to asynchronous messages
D/wpa_supplicant( 6366): EAPOL: disable timer tick
,I/ActivityManager(  969): Recipient 5964
,V/BluetoothSapService( 6303): Sap Service onCreate,
V/BluetoothSapService( 6303): initBinder
,V/BluetoothSapService( 6303): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@1e87ba45
V/BluetoothSapService( 6303): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@293efecb
,V/BluetoothSapService( 6303): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6303): state: 12
V/BluetoothSapService( 6303): Starting SAP server process
V/BluetoothSapService( 6303): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6303): Sap Service initRfcommSocket
D/SapServerProfile( 5662): Bluetooth service connected
D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6303): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6303): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6303): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6303): Write Extended Inquiry Response to controller
I/bt-btif ( 6303): BTA_JvRfcommStartServer
I/bt-btm  ( 6303): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6303):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6303): Succeed to create listening socket 
V/BluetoothSapService( 6303): Accepting socket connection...
,D/A2dpService( 6303): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@366eb5c1,
D/A2dpSinkService( 6303): getA2dpSinkService(): service is NULL
,D/wpa_supplicant( 6366): EAPOL: disable timer tick,
,D/BluetoothManagerService(  969): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6249): Got Device Bluetooth address: 90:E7:C4:F6:69:77,
,I/jxcore-log( 6249): 
I/jxcore-log( 6249): my name is : HTC-HTC One M8s_PT112
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): attempting to connect to test coordinator
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): check test folder
I/jxcore-log( 6249): 
I/jxcore-log( 6249): found test : ./testFindPeers.js
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): found test : ./testReConnect.js
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): found test : ./testSendData.js,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): Test app app.js loaded,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/chromium( 6249): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/ContactMessageStore( 1490): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1490): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,D/PMS     (  969): releaseWL(2bb36266): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/BluetoothAdapter( 6249): 169252085: getState(). Returning 12,
I/jxcore-log( 6249): BLE supported!!
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  969): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  969): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  969): acquireWL(55cf276): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10024},
V/AlarmManager(  969): sending alarm PendingIntent{17b76077: PendingIntentRecord{b8284e4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143881, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{dba8a11: PendingIntentRecord{8a42776 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=147005, Int=0
,D/libc    (  969): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/PMS     (  969): releaseWL(55cf276): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  969): [NET] android_getaddrinfofornet-, err=8
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  969): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  969): [NET] android_getaddrinfo_proxy+
D/libc    (  969): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  969): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/ContextImpl(  969): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(17683d4d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(17683d4d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbnetService(  969): onReceive BATTERY_CHANGED
,D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/HtcPowerSaver(  969): updateBatteryInfo
D/WifiController(  969): handleMessage: X
D/PMS     (  969): runPSCheck
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
,D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/TelephonyReceiver( 1490): switchBindHtcMsgCursor: null
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(309dc002): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=151414, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{dba8a11: PendingIntentRecord{8a42776 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=207022, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{7378d13: PendingIntentRecord{2f550b50 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208107, Int=0
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  969): sending alarm PendingIntent{20886149: PendingIntentRecord{39f13930 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=179057, Int=0
D/libc    (  969): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  969): sending alarm PendingIntent{2f2bda4e: PendingIntentRecord{1883e76f com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186010, Int=0
D/libc    (  969): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  969): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  969): [NET] android_getaddrinfo_proxy+
D/libc    (  969): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  969): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  969): acquireWL(f878c7c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  969): acquireWL(d6cc905): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  969): releaseWL(309dc002): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/PMS     (  969): releaseWL(f878c7c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  969): releaseWL(d6cc905): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(1b6f4d5a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(1b6f4d5a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  969): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(5918b8b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(5918b8b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  969): >> updateStatus
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): << updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/art     ( 1881): Explicit concurrent mark sweep GC freed 16259(919KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 1.001ms total 64.211ms,
,I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
,W/GLSActivity( 1881): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1881): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1881): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1881): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1881): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1881): ,	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1881): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5686): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 5686): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5686): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5686): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5686): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5686): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5686): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5686): Ignoring header User-Agent because its value was null.,
,D/libc    ( 5686): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5686): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5686): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5686): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5686): [NET] android_getaddrinfo_proxy+
D/libc    ( 5686): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7,
D/libc    ( 5686): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(3d0afd75): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=211414, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{7e06d7b: PendingIntentRecord{240c4798 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1449576731269, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{e9afbf1: PendingIntentRecord{39f13930 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=364804, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{3e26e3d6: PendingIntentRecord{1d7e6657 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449576766377, Int=1800000
D/PMS     (  969): acquireWL(104a4544): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  969): acquireWL(2752662d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4441 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(104a4544): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  969): acquireWL(89910f3): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4441 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(2752662d): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(3d0afd75): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,I/EventLogService( 4441): Aggregate from 1449574966343 (log), 1449574966343 (data)
,D/PMS     (  969): releaseWL(89910f3): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1455): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@13608d52
D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  969): Killing 5755:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  969): killProcessQuiet, pid=5755
,D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5755
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,W/Atfwd_Sendcmd(  425): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): acquireWL(27a9c94f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  969): releaseWL(27a9c94f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
D/WifiController(  969): handleMessage: E msg.what=155652
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: StaEnabledState
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): processMsg: DefaultState
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/ContactMessageStore( 1490): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1490): mDeleteTask = null, bDeleting = false,
D/AccFlag ( 1490): sku_id=118
D/ContactMessageStore( 1490): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1490): start background delete task...,
,D/ContactMessageStore( 1490): size: 0 , 0,
D/ContactMessageStore( 1490): Background delete complete
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1881): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1881): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1881): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1881): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1881): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1881): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1881): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5686): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5686): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5686): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5686): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5686): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5686): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5686): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5686): Ignoring header User-Agent because its value was null.
D/libc    ( 5686): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5686): [NET] android_getaddrinfofornet-, err=8
I/RemoteViews( 1221): reapply : com.google.android.gms 3 40
D/libc    ( 5686): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5686): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5686): [NET] android_getaddrinfo_proxy+
D/libc    ( 5686): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5686): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6249): ,
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(18d67d99): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  969): releaseWL(18d67d99): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/NotificationService(  969): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(2aee485e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
I/BatteryService(  969): n_update end
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  969): releaseWL(2aee485e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  969): plugged=true pluggin=true
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
,D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(3835a43f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(3835a43f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  969): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(e9c510c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=391414, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1cd8869b: PendingIntentRecord{3816ba38 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=807004, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{14885a55: PendingIntentRecord{39f13930 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=691142, Int=0
,I/ActivityManager(  969): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6477 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  969): sending alarm PendingIntent{3c528c6a: PendingIntentRecord{19ea455b com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1449577140108, Int=0
,I/ActivityManager(  969): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=6490 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  969): sending alarm PendingIntent{294371f8: PendingIntentRecord{3c4146d1 com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,D/PMS     (  969): acquireWL(22050536): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/PMS     (  969): releaseWL(e9c510c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/PMS     (  969): releaseWL(22050536): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/ImageRamCache( 6490): create image Cache, size: 31457280.,
I/ImageRamCache( 6490): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 6490): create image Cache, size: 31457280.
,I/FeedSettings( 6490): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true,
,I/FeedSettings( 6490): GroupBudget 0.500000 0.380000
I/FeedSettings( 6490): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 6490): changeLocale(): en_GB,
,I/Prism.AllAppsOptionsMa_( 6490): loadSortType() with Custom,
I/Prism.AllAppsOptionsMa_( 6490): loadGridSize() with Alternative
,E/cutils-trace( 6527): Error opening trace file: Permission denied (13),
I/dex2oat ( 6527): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6527): dex2oat: override thread count:4
,D/libc    ( 6490): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
D/libc    ( 6490): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6490): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 6490): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 6490): [NET] android_getaddrinfo_proxy+
,D/libc    ( 6490): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6490): [NET] android_getaddrinfo_proxy-, NODATA
,E/[CSBICLIENT][v12][BiLogUploadService]( 6490): Exception on getConfig(),
,I/ActivityManager(  969): Killing 5612:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17,
D/Process (  969): killProcessQuiet, pid=5612
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5612,
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6249): 
,I/dex2oat ( 6527): dex2oat took 936.199ms (threads: 4),
,I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): VersionCode:             148001224,
I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6477): ApplicationMonitor {39c490fb}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6477): PnsModel {177e428a}: update(): Update registration caused by: alarm,
,I/PushClient( 6477): PnsConfigModel {28bc37a9}: <init>(): Use dm-client for provisioning.
,W/System.err( 6477): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6477): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6477): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6477): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  969): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6537 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6537): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6537 dbg=false s=true
,I/DeviceManagement( 6537): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6537): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6537): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6537): WorkflowService: Starting workflow service
,I/DeviceManagement( 6537): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@a1694f5] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6537): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6537): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6537): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6537): SessionStateController: Checking invariants...
,I/DeviceManagement( 6537): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6537): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6537): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6537): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@a1694f5],
,I/DeviceManagement( 6537): WorkflowService: Stopping workflow service,
,D/Process (  969): killProcessQuiet, pid=5876
I/ActivityManager(  969): Killing 5876:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6477): PnsModel {177e428a}: update(): Start updating since the registration has expired.
,I/ActivityManager(  969): Recipient 5876
,W/PushClient( 6477): GCMRegistrator {58c5460}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.
W/PushClient( 6477):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6477):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6477):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6477):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6477):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6477):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6477):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6477):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6477):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6477):   
,D/GCM     ( 1881): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6477): PnsModel {177e428a}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE
E/PushClient( 6477):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6477):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6477):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6477):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6477):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6477):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6477):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 6477):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6477):   	,at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6477):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6477):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6477):   	... 6 more
E/PushClient( 6477):   
,I/PushClient( 6477): CentralClientRetryPolicy {31084e39}: scheduleUpdateRetry(): Waiting for network connectivity...
,I/PackageManager(  969):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6477, uid=10071, userID:0,
,D/Process (  969): killProcessQuiet, pid=5686,
I/ActivityManager(  969): Killing 5686:com.android.vending/u0a72 (adj 15): empty #17
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  969): Recipient 5686
,W/SQLiteConnectionPool( 6490): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(635a735): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(635a735): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  969): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
,D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/PMS     (  969): runPSCheck
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  969): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(5c887ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=931414, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1ffd8d3b: PendingIntentRecord{1883e76f com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=937414, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{169f4c58: PendingIntentRecord{1d4d94c4 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449577350115, Int=0
,D/PMS     (  969): acquireWL(f2681b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms},
W/ContextImpl( 6147): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6147): MY_DEBUG = false
D/PMS     (  969): releaseWL(5c887ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PowerUsageService( 6147): repeat time = 1449578250159,
,D/PMS     (  969): acquireWL(28adc217): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(f2681b1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(28adc217): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(a7087ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms},
,I/PowerUsageList:PowerUsageHelper( 6147): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6147): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  969): releaseWL(a7087ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(9a24622): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(9a24622): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(2bc268b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(b1f4e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): acquireWL(37a89146): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(2bc268b3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/Procstats( 4441): User is not opted-in to Usage & Diagnostics.
,D/Batterystats( 4441): User is not opted-in to Usage & Diagnostics.
D/PMS     (  969): releaseWL(b1f4e70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): releaseWL(37a89146): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  969): acquireWL(312d5f07): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(312d5f07): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  969): acquireWL(9afc834): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  969): releaseWL(9afc834): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): acquireWL(3b10465d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1881 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  969): releaseWL(3b10465d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(244c7bd2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000}
,V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=991414, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{18b6e4a3: PendingIntentRecord{389b33a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449577402362, Int=0
,D/SmartSyncUtils( 6147): isEpsOn(), nState = 0
,D/PMS     (  969): acquireWL(318feb59): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6147 1000 null
,D/PMS     (  969): releaseWL(244c7bd2): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/SmartSyncScreenOnOffTimeReceiver( 6147): [updateNmRange] bManual = false
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6147): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6147): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6147): SettingOnTime = 1449640800000, randomSettingOnTime = 1449638964000
D/SmartSyncScreenOnOffTimeReceiver( 6147): SettingOffTime = 1449619200000, randomSettingOffTime = 1449620830000
,D/SmartSyncScreenOnOffTimeReceiver( 6147): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6147): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 6147): bNightModeTurnOffOnce = false
,D/PMS     (  969): releaseWL(318feb59): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(13d2831e): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{1002}
I/bt-btm  ( 6303): Received oneshot timer event complete
V/AlarmManager(  969): sending alarm PendingIntent{1bc927ff: PendingIntentRecord{d0fe9cc com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1029996, Int=0,
I/bt-btm  ( 6303): btm_ble_timeout
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
D/PMS     (  969): releaseWL(13d2831e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
D/PMS     (  969): acquireWL(8cae415): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6303 1002 null
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete,
I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 81 1f 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = f0 32 b5 e7 5f 08 49 20 6c 2a 43 33 b3 80 55 a2 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  969): releaseWL(8cae415): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(d1fb32a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null,
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(d1fb32a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  969): updateBatteryInfo
D/PMS     (  969): runPSCheck
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
,D/PowerUI ( 1221): closing low battery warning: level=100
,D/WifiController(  969): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(3b92451b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): releaseWL(3b92451b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  969): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): Checking...
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/UsageStatsService(  969): User[0] Flushing usage stats to disk
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(3c37d6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(3c37d6b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck,
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): acquireWL(3182ac91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  969): releaseWL(3182ac91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(2e5dd7f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(2e5dd7f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  969): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): runPSCheck
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
,D/WifiController(  969): handleMessage: E msg.what=155652
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(140617f7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(140617f7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
,D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
,D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): runPSCheck
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  969): >> updateStatus
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  969): battery changed pluggedType: 2
D/UsbnetService(  969): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): handleMessage: E msg.what=155652
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  969): acquireWL(21efa664): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  969): n_update end
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  969): releaseWL(21efa664): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: E msg.what=155652
D/PMS     (  969): runPSCheck
D/WifiController(  969): processMsg: DeviceActiveState
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: StaEnabledState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): handleMessage: X
,I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/PMS     (  969): acquireWL(d1480cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
D/UsbnetService(  969): onReceive BATTERY_CHANGED
,I/BatteryService(  969): n_update end
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  969): releaseWL(d1480cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  969): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  969): plugged=true pluggin=true
D/PMS     (  969): runPSCheck
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  969): Checking...
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  969): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  969): handleMessage: E msg.what=155652
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  969): processMsg: StaEnabledState
I/HtcPowerSaver(  969): << updateStatus
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: X
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(227a3c93): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(227a3c93): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  969): updateBatteryInfo
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969): BroadcastReceiver::onReceive+
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
D/HtcPowerSaver(  969): Checking...
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
D/WifiController(  969): processMsg: DeviceActiveState
D/WifiController(  969): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=100
D/WifiController(  969): processMsg: DefaultState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): handleMessage: X
I/HtcPowerSaver(  969): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  969): << updateStatus
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(1932c4d0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1051415, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1cd8869b: PendingIntentRecord{3816ba38 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1620093, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{3298de27: PendingIntentRecord{17f0a8d4 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825251, Int=1800000,
V/AlarmManager(  969): sending alarm PendingIntent{3b755cc9: PendingIntentRecord{39f13930 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1526711, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1fb3efce: PendingIntentRecord{1a020eef com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1854636, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{2f475dfc: PendingIntentRecord{cedfc85 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1866258, Int=0
,V/AlarmManager(  969): sending alarm PendingIntent{18233ada: PendingIntentRecord{1d4d94c4 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449578250159, Int=0
,I/ProcessStatsService(  969): Prepared write state in 25ms
D/PMS     (  969): acquireWL(218aab0b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 969 1000 null
,D/PMS     (  969): releaseWL(218aab0b): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
,V/NetworkPolicy(  969): updateNetworkEnabledLocked(),
V/NetworkPolicy(  969): updateNotificationsLocked()
D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  969): acquireWL(1daa5de8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1881 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1881): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1881): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1881): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1881): [NET] android_getaddrinfo_proxy+
D/libc    ( 1881): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1881): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  969): releaseWL(1daa5de8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 6147): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
D/PMS     (  969): releaseWL(1932c4d0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/LocationManagerService(  969): getAllProviders()=[passive, gps, network]
,D/PowerUsageList:PowerUsageHelper( 6147): MY_DEBUG = false,
,D/PowerUsageService( 6147): repeat time = 1449579154955
,I/GLSUser ( 1881): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1881): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1881): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1881): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1881): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6147): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6147): gen(), null == sipper.uidObj, userId = 0,
,I/ProcessStatsService(  969): Pruning old procstats: /data/system/procstats/state-2015-12-07-14-36-44.bin
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(207eddd7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 969 1000 null
,I/BatteryService(  969): n_update end
D/PMS     (  969): releaseWL(207eddd7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  969): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  969): updateBatteryInfo
D/UsbnetService(  969): onReceive BATTERY_CHANGED
D/NotificationService(  969): plugged=true pluggin=true
D/UsbnetService(  969):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  969): BroadcastReceiver::onReceive-
D/PMS     (  969): runPSCheck
D/WifiController(  969): handleMessage: E msg.what=155652
D/HtcPowerSaver(  969): Checking...
D/WifiController(  969): processMsg: DeviceActiveState
I/HtcPowerSaver(  969): >> updateStatus
D/WifiController(  969): processMsg: StaEnabledState
D/WifiController(  969): battery changed pluggedType: 2
D/WifiController(  969): processMsg: DefaultState
D/PowerUI ( 1221): closing low battery warning: level=98
D/WifiController(  969): handleMessage: X
I/ActivityManager(  969): Killing 6204:com.htc.calendar/u0a10 (adj 13): empty for 1803s
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/Process (  969): killProcessQuiet, pid=6204
I/HtcPowerSaver(  969): updateStatus (8000,98,-1,false,false,false,-1)
D/HeadsetStateMachine( 6303): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  969): << updateStatus
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/HeadsetPhoneState( 6303): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 6303): Disconnected process message: 11, size: 0
,D/DotMatrix( 1306): [EventService] reorderNotification, total:1
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true,
,I/ActivityManager(  969): Recipient 6204
,I/ActivityManager(  969): Killing 6179:com.htc.mobiledata/u0a46 (adj 13): empty for 1804s,
D/Process (  969): killProcessQuiet, pid=6179
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  969): Recipient 6179,
,D/Process (  969): killProcessQuiet, pid=6119
I/ActivityManager(  969): Killing 6119:com.htc.bgp/u0a11 (adj 13): empty for 1804s
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/ActivityManager(  969): Recipient 6119,
,D/Process (  969): killProcessQuiet, pid=6095
,I/ActivityManager(  969): Killing 6095:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1810s
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  969): Recipient 6095,
,D/Process (  969): killProcessQuiet, pid=6043
I/ActivityManager(  969): Killing 6043:com.htc.sense.mms/u0a64 (adj 15): empty for 1815s
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/ActivityManager(  969): Recipient 6043
,W/ContextImpl( 6147): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,I/art     (  969): Explicit concurrent mark sweep GC freed 34831(1908KB) AllocSpace objects, 15(1212KB) LOS objects, 33% free, 16MB/24MB, paused 2.072ms total 197.275ms
,D/TetherSettings( 5662): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5662): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5662): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5662): Cust_ConnectToPC   : spcsc>false
D/        ( 5662): Cust_ConnectToPC   : IPT>true
D/        ( 5662): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5662): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5662): Index of the first 1 = -1
,W/ContextImpl( 5662): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
,W/ContextImpl( 5662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 ,
,W/Settings( 5662): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5662): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5662): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5662): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5662): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5662): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6249): 
,D/PMS     (  969): acquireWL(96669ad): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 969 1000 WorkSource{1000},
V/AlarmManager(  969): sending alarm PendingIntent{70cf520: PendingIntentRecord{29f44ed9 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1891414, Int=0
V/AlarmManager(  969): sending alarm PendingIntent{1d9be4e2: PendingIntentRecord{3e98073 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1930008, Int=0
I/bt-btm  ( 6303): Received oneshot timer event complete,
I/bt-btm  ( 6303): btm_ble_timeout
I/bt-btm  ( 6303): btm_gen_resolvable_private_addr
,D/PMS     (  969): acquireWL(1b80eb30): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6303 1002 null,
,D/bt-btm  ( 6303): btm_ble_rand_enc_complete,
I/bt-btm  ( 6303): btm_gen_resolve_paddr_low
D/bt-smp  ( 6303): smp_encrypt_data
W/bt-smp  ( 6303): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6303): Plain text(LSB ~ MSB) = 5b 6a 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6303): Encrypted text(LSB ~ MSB) = a0 7c 9f f2 5f a6 ce a1 a9 a1 4b c0 79 36 41 e0 
I/bt-btm  ( 6303): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6303): Stopping oneshot timer
D/bt-btm  ( 6303): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  969): releaseWL(96669ad): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  969): releaseWL(1b80eb30): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6249): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6249): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 6592): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6592): ====startRecUseTime====
D/htc.customization.log.level( 6592):  is 
W/CustomizationLogLevel( 6592): Level value is invalid, use default level 2
D/CustomizationManager( 6592):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6592): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6592): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6592): Parsing tag category name = system
I/CustomizationCIDLoader( 6592): Parsing tag category name = application
I/CustomizationCIDLoader( 6592): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6592): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6592): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6592): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6592): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6592): add string-array item, value = 42507
I/CustomizationCIDLoader( 6592): add string-array item, value = 21902
I/CustomizationCIDLoader( 6592): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6592): add string-array item, value = 23420
I/CustomizationCIDLoader( 6592): add string-array item, value = 22299
I/CustomizationCIDLoader( 6592): add string-array item, value = 24002
I/CustomizationCIDLoader( 6592): add string-array item, value = 23210
I/CustomizationCIDLoader( 6592): add string-array item, value = 23205
I/CustomizationCIDLoader( 6592): add string-array item, value = 23806
I/CustomizationCIDLoader( 6592): add string-array item, value = 23430
I/CustomizationCIDLoader( 6592): add string-array item, value = 23408
I/CustomizationCIDLoader( 6592): add string-array item, value = 27205
I/CustomizationCIDLoader( 6592): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6592): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6592):  Read CID file spent 0.097 (s)
D/CustomizationManager( 6592):  All configurations done spent 0.097 (s)
D/PackageManager(  969): deletePackageAsUser: pkg=com.test.thalitest, pid=6592, uid=2000 userid=0
I/ActivityManager(  969): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  969): killProcessQuiet, pid=6249
I/ActivityManager(  969): Killing 6249:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  969): Skipping PackageSetting{aa46d48 com.example.hello/10373} due to missing metadata
I/ActivityManager(  969): Recipient 6249
I/WindowState(  969): WIN DEATH: Window{312e738a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  969): Client connection lost with reason: 4
E/InputEventReceiver( 1365): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{27083e56 uid 10366 pid 6249} (c)'
E/libprocessgroup(  969): failed to kill 1 processes for processgroup 6249
I/ActivityManager(  969): Killing 6371:com.htc.widget.hmsproc2/u0a40 (adj 15): empty for 1807s
D/Process (  969): killProcessQuiet, pid=6371
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  969): Recipient 6371
D/Process (  969): killProcessQuiet, pid=6338
I/ActivityManager(  969): Killing 6338:com.htc.widget.hmsproc3/u0a34 (adj 15): empty for 1807s
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6163 
I/ActivityManager(  969): Recipient 6338
I/ActivityManager(  969):   Force finishing activity ActivityRecord{1f6fa8f7 u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  969): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  969):   Force finishing activity ActivityRecord{1f6fa8f7 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  969): Duplicate finish request for ActivityRecord{1f6fa8f7 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  969): Spurious death for ProcessRecord{14acf3a9 6249:com.test.thalitest/u0a366}, curProc for 6249: null
D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  969): Cannot find grip_rejection_width, use default value instead
D/PMS     (  969): acquireWL(1c18a5c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1805 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
D/PMS     (  969): releaseWL(1c18a5c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/InputMethodManagerService(  969): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1683): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 6490): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 6490): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1644): Cleaning up data for package: com.test.thalitest
D/AccTypeManager( 1683): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/ResourcesManager(  969): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/PhoneApp( 1490): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/art     ( 1542): Explicit concurrent mark sweep GC freed 6482(367KB) AllocSpace objects, 8(532KB) LOS objects, 34% free, 29MB/45MB, paused 1.075ms total 98.007ms
D/Prism.PackageStateRece_( 1542): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1542): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1542): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1455): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/Launcher( 1542): Deferring update until onResume
D/Launcher( 1542): waitUntilResume // bindAppsRemoved
I/[PluginManager]RegisterService( 1455): handle notify Blinkfeed plugin client changed
I/ActivityManager(  969): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6613 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/AccTypeManager( 1683): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 1683): Unsupported attribute readOnly
I/art     (  969): Explicit concurrent mark sweep GC freed 15223(1280KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.750ms total 215.732ms
I/art     (  969): WaitForGcToComplete blocked for 212.768ms for cause Explicit
W/ContextImpl( 6613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  969): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
D/StatusBarManagerService(  969): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  969): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  969): hiding MENU key
D/FindExtension( 1542): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1542): Defer allocateBuffers to drawing time
W/PackageManager(  969): Unable to load service info ResolveInfo{34d1f6ec com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  969): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  969): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  969): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  969): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  969): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  969): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  969): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  969): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  969): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  969): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  969): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  969): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  969): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6639 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
W/InputMethodManagerService(  969): Got RemoteException sending setActive(false) notification to pid 6249 uid 10366
D/StatusBarManagerService(  969): swetImeWindowStatus vis=0 backDisposition=0
D/Process (  969): killProcessQuiet, pid=6430
I/ActivityManager(  969): Killing 6430:com.htc.android.mail:sync/u0a62 (adj 15): empty for 1807s
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/art     (  969): Explicit concurrent mark sweep GC freed 5133(283KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.447ms total 174.600ms
W/asset   (  969): Copying FileAsset 0x558510e710 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/JobSchedulerService(  969): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  969): Recipient 6430
D/TaskPersister(  969): removeObsoleteFile: deleting file=8_task.xml
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
I/PackageManager(  969):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6639, uid=10072, userID:0
W/global  ( 6639): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6639): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 6639): [apache-http] Connection GC has been deprecated!
W/global  ( 6639): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6639): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  969): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6678 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 6639): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6639): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6639): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 6639): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6639): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6639): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6639): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6639): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 6639): Process: com.android.vending, PID: 6639
E/AndroidRuntime( 6639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6639): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 6639): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 6639): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 6639): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6639): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6639): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6639): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  969): App crashed! Process: com.android.vending
E/SQLiteDatabase( 6639): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 6639): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6639): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6639): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 6639): killProcess, pid=6639
I/PackageManager(  969):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6639, uid=10072, userID:0
E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
E/AndroidRuntime_2_crash( 6639): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 6639): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 6639): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 6639): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 6639): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 6639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 6639): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 6639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 6639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 6639): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6639): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 6639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 6639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 6639): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 6639): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 6639): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 6639): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 6639): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 6639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 6639): 	... 4 more
E/SQLiteDatabase( 6639): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 6639): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 6639): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6639): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6639): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 6639): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime_3_crash( 6639): crash in the same process: AsyncTask #2
E/AndroidRuntime_3_crash( 6639): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 6639): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 6639): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 6639): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 6639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 6639): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 6639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 6639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 6639): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 6639): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 6639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 6639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 6639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 6639): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 6639): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 6639): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 6639): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 6639): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 6639): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 6639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 6639): 	... 4 more
W/ResourcesManager( 6678): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6678): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6678): VM with version 2.1.0 has multidex support
I/MultiDex( 6678): install
I/MultiDex( 6678): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6678): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 6678): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6678): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30e9859a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6678): Installed default security provider GmsCore_OpenSSL
E/SQLiteLog( 1881): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1881): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5584c30640
E/AndroidRuntime( 1881): FATAL EXCEPTION: main
E/AndroidRuntime( 1881): Process: com.google.process.gapps, PID: 1881
E/AndroidRuntime( 1881): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1881): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1881): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1881): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1881): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1881): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1881): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1881): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1881): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1881): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1881): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1881): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1881): 	... 9 more
E/ActivityManager(  969): App crashed! Process: com.google.process.gapps
D/Process ( 1881): killProcess, pid=1881
D/Process ( 1881): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
I/ActivityManager(  969): Recipient 6639
W/NativeLibraryUtils( 6678): Failed to open lock file
W/NativeLibraryUtils( 6678): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6678): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6678): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6678): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6678): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6678): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6678): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6678): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6678): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6678): 	... 3 more
I/ActivityManager(  969): Process com.android.vending (pid 6639) has died
E/JavaBinder( 6678): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 6678): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 6678): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 6678): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 6678): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  969): Recipient 1881
I/ActivityManager(  969): Process com.google.process.gapps (pid 1881) has died
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
W/ActivityManager(  969): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
I/ActivityThread( 6678): Removing dead content provider:android.content.ContentProviderProxy@366eb5c1
I/ActivityManager(  969): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6711 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/GservicesProvider( 6711): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 6711): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 6711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6711): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 6711): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 6711): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 6711): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 6711): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 6711): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 6711): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 6711): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 6711): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 6711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6711): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6711): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6711): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6711): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6711): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6711): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6711): FATAL EXCEPTION: main
E/AndroidRuntime( 6711): Process: com.google.process.gapps, PID: 6711
E/AndroidRuntime( 6711): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6711): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 6711): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 6711): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 6711): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 6711): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 6711): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6711): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6711): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6711): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6711): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6711): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6711): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6711): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6711): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 6711): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 6711): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 6711): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 6711): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 6711): 	... 11 more
E/ActivityManager(  969): App crashed! Process: com.google.process.gapps
D/Process ( 6711): killProcess, pid=6711
D/Process ( 6711): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
I/ActivityManager(  969): Recipient 6711
I/ActivityManager(  969): Process com.google.process.gapps (pid 6711) has died
W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{33ad5ef8 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{26def2e4 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
W/ActivityManager(  969): Service crashed 2 times, stopping: ServiceRecord{17a4ff43 u0 com.google.android.gms/.gcm.GcmService}
I/ActivityManager(  969): Start proc com.google.process.gapps for restart com.google.process.gapps: pid=6733 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
I/GservicesProvider( 6733): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 6733): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 6733): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6733): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 6733): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 6733): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 6733): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 6733): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 6733): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 6733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 6733): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 6733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 6733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6733): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6733): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6733): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6733): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6733): FATAL EXCEPTION: main
E/AndroidRuntime( 6733): Process: com.google.process.gapps, PID: 6733
E/AndroidRuntime( 6733): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6733): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 6733): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 6733): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 6733): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 6733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 6733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6733): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6733): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6733): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6733): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6733): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6733): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6733): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6733): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6733): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 6733): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 6733): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 6733): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 6733): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 6733): 	... 11 more
E/ActivityManager(  969): App crashed! Process: com.google.process.gapps
W/ActivityManager(  969): Process com.google.process.gapps has crashed too many times: killing!
D/Process (  969): killProcessQuiet, pid=6733
I/ActivityManager(  969): Killing 6733:com.google.process.gapps/u0a24 (adj 0): crash
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12134 
E/DropBoxManagerService(  969): Can't write: system_app_crash
E/DropBoxManagerService(  969): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  969): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  969): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  969): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  969): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  969): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  969): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  969): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  969): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  969): 	... 5 more
I/Prism.ItemManager( 6490): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 6490): loadItems() com.htc.launcher.pageview.WidgetManager@2405fd56 +
I/Prism.WidgetManager( 6490): onLoadItems() +
I/ActivityManager(  969): Recipient 6733
D/Process (  969): killProcessQuiet, pid=6678
I/ActivityManager(  969): Killing 6678:com.google.android.gms:car/u0a24 (adj 0): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
D/Process (  969): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeDyingProviderLocked:15264 com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked:15341 
W/ActivityManager(  969): Unable to launch app com.google.android.gsf/10024 for provider com.google.android.gsf.gservices: launching app became null
I/Prism.ItemManager( 1542): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1542): loadItems() com.htc.launcher.pageview.WidgetManager@1eca9356 +
I/Prism.WidgetManager( 1542): onLoadItems() +
W/ResourcesManager( 6490): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1542): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  969): Recipient 6678
W/ActivityManager(  969): Spurious death for ProcessRecord{e464b0 6733:com.google.process.gapps/u0a24}, curProc for 6733: null
I/ActivityManager(  969): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6755 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
D/PMS     (  969): acquireWL(80caf29): PARTIAL_WAKE_LOCK  *alarm* 0x1 969 1000 WorkSource{10072}
V/AlarmManager(  969): sending alarm PendingIntent{2d7b42ae: PendingIntentRecord{f102b4f com.android.vending startService}}, i=null, t=0, cnt=1, w=1449578328243, Int=0
D/PMS     (  969): releaseWL(80caf29): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
W/ResourcesManager( 6490): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1542): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,

```
