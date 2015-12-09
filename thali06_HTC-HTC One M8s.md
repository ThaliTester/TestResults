#### Test 50650278d0426ce_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
,D/Process (  953): killProcessQuiet, pid=4976
--------- beginning of system
I/ActivityManager(  953): Killing 4976:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  953): Recipient 4976
E/cutils-trace( 5842): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5842): ====startRecUseTime====
D/htc.customization.log.level( 5842):  is 
W/CustomizationLogLevel( 5842): Level value is invalid, use default level 2
D/CustomizationManager( 5842):  Read ACC file spent 0.048 (s)
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5842): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5842): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5842): Parsing tag category name = system
I/CustomizationCIDLoader( 5842): Parsing tag category name = application
I/CustomizationCIDLoader( 5842): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5842): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5842): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5842): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5842): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5842): add string-array item, value = 42507
I/CustomizationCIDLoader( 5842): add string-array item, value = 21902
I/CustomizationCIDLoader( 5842): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5842): add string-array item, value = 23420
I/CustomizationCIDLoader( 5842): add string-array item, value = 22299
I/CustomizationCIDLoader( 5842): add string-array item, value = 24002
I/CustomizationCIDLoader( 5842): add string-array item, value = 23210
I/CustomizationCIDLoader( 5842): add string-array item, value = 23205
I/CustomizationCIDLoader( 5842): add string-array item, value = 23806
I/CustomizationCIDLoader( 5842): add string-array item, value = 23430
I/CustomizationCIDLoader( 5842): add string-array item, value = 23408
I/CustomizationCIDLoader( 5842): add string-array item, value = 27205
I/CustomizationCIDLoader( 5842): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5842): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5842):  Read CID file spent 0.103 (s)
D/CustomizationManager( 5842):  All configurations done spent 0.103 (s)
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5842 on display 0
D/PMS     (  953): acquireHCC(137a83d4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 953 1000 null
D/PMS     (  953): acquireHCC(294ce97d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 953 1000 null
I/ActivityManager(  953): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5860 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  953): Display changed displayId=0
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1527): [trimMemory] 20
I/WebViewFactory( 5860): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5860): Time to load native libraries: 9 ms (timestamps 4225-4234),
,I/LibraryLoader( 5860): Expected native library version number "",actual native library version number ""
,D/PMS     (  953): acquireWL(2b43a079): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
,V/AlarmManager(  953): sending alarm PendingIntent{1d4661be: PendingIntentRecord{3fb3b21f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449681206388, Int=0
D/PMS     (  953): acquireWL(2c2796c): PARTIAL_WAKE_LOCK  *backup* 0x1 953 1000 null
D/PMS     (  953): releaseWL(2b43a079): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  953): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  953): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  953): releaseWL(2c2796c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
V/WebViewChromiumFactoryProvider( 5860): Binding Chromium to main looper Looper (main, tid 1) {38f55947}
I/LibraryLoader( 5860): Expected native library version number "",actual native library version number ""
I/chromium( 5860): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5860): Initializing chromium process, singleProcess=true
W/art     ( 5860): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5860): ApplicationContext is null in ApplicationStatus,
,W/chromium( 5860): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 5860): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5860): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5860): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5860): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5860): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5860): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5860): Local Branch: 
I/Adreno-EGL( 5860): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5860): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5860):                  d74aa161a12b9c6fc6332151
,W/System.err(  953): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fd02bed:true
W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  953): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 5860): 799294179: getState() :  mService = null. Returning STATE_OFF
I/art     (  953): Explicit concurrent mark sweep GC freed 30521(1699KB) AllocSpace objects, 4(608KB) LOS objects, 33% free, 16MB/24MB, paused 1.459ms total 129.996ms
W/ActivityManager(  953): Activity pause timeout for ActivityRecord{1891b072 u0 com.test.thalitest/.MainActivity t8}
W/HtcSystemUPManager(  953): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/art     ( 5860): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5860): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5860): CordovaWebView is running on device made by: HTC
W/art     ( 5860): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5860): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 5860): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/StatusBarManagerService(  953): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
D/StatusBarManagerService(  953): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  953): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  953): hiding MENU key
D/FindExtension( 5860): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 5860): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@22fe1509, mServedView=org.apache.cordova.engine.SystemWebView{1e8de30e VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@286c212f
I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
I/InputMethodManagerService(  953): Disable input method client, pid=1527
D/StatusBarManagerService(  953): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 5860): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  953): Displayed com.test.thalitest/.MainActivity: +774ms (total +821ms)
W/BindingManager( 5860): Cannot call determinedVisibility() - never saw a connection for the pid: 5860
D/JsMessageQueue( 5860): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5860): JniHelper::setJavaVM(0xab3738f8), pthread_self() = -1402412624
D/JX-Cordova( 5860): jxcore cordova android initializing
,W/jxcore-log( 5860): Initializing JXcore engine
W/jxcore-log( 5860): JXcore engine is ready
,W/jxcore-log( 5860): Starting JXcore engine
,D/PMS     (  953): releaseHCC(137a83d4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  953): releaseHCC(294ce97d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5860): Platform android
W/jxcore-log( 5860): 
W/jxcore-log( 5860): Process ARCH arm
W/jxcore-log( 5860): 
,I/jxcore-log( 5860): JXcore Cordova bridge is ready!
I/jxcore-log( 5860): 
W/jxcore-log( 5860): JXcore engine is started
,I/chromium( 5860): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5860): Toggling radios to true
I/jxcore-log( 5860): 
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  953): checking for enable restriction...
D/BluetoothManagerService(  953): checkBTEasState, ret=true
I/BluetoothManagerService(  953): isBluetoothRestricted(): false
D/BluetoothManagerService(  953): enable(): region ID = 6
D/BluetoothManagerService(  953): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  953): MONITOR_LOG
W/Settings:Agent(  953): name: bluetooth_on
W/Settings:Agent(  953): value: 1
W/Settings:Agent(  953): >> traceCallingStack()
W/Settings:Agent(  953): Process.myPid(): 953
W/Settings:Agent(  953): Process.myTid(): 1681
W/Settings:Agent(  953): Process.myUid(): 1000
W/Settings:Agent(  953): 
W/Settings:Agent(  953): 
W/System.err(  953): java.lang.Throwable: stack dump
,W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  953): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  953): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  953): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  953): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  953): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  953): 
W/Settings:Agent(  953): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  953): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  953): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  953): New client listening to asynchronous messages,
E/WifiTrafficPoller(  953): ADD_CLIENT: 7
D/WifiManager( 5860): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  953): setWifiEnabled: true pid=5860, uid=10366
,E/WifiService(  953): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  953): MONITOR_LOG
I/WifiService(  953): isSprintWifiRestricted(): false
W/Settings:Agent(  953): name: wifi_on
I/WifiService(  953): isMdmWifiRestricted(): false
W/Settings:Agent(  953): value: 2
W/Settings:Agent(  953): >> traceCallingStack()
W/Settings:Agent(  953): Process.myPid(): 953
W/Settings:Agent(  953): Process.myTid(): 985
,W/Settings:Agent(  953): Process.myUid(): 1000
W/Settings:Agent(  953): 
W/Settings:Agent(  953): 
W/System.err(  953): java.lang.Throwable: stack dump
,W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
I/ActivityManager(  953): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5915 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
W/System.err(  953): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  953): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  953): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  953): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  953): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  953): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  953): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  953): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  953): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  953): 
W/Settings:Agent(  953): << traceCallingStack(): 9(ms)
,D/WifiController(  953): handleMessage: E msg.what=155656
D/WifiController(  953): processMsg: ApStaDisabledState
,D/WifiController(  953): transitionTo: destState=DeviceActiveState
D/WifiController(  953): handleMessage: new destination call exit/enter
D/WifiController(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/PMS     (  953): acquireWL(3c4c0815): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 953 1000 null
,D/WifiController(  953): invokeExitMethods: ApStaDisabledState
D/WifiController(  953): moveTempStackToStateStack: i=1,j=1
D/WifiController(  953): moveTempStackToStateStack: i=0,j=2
D/WifiController(  953): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
,D/WifiController(  953): invokeEnterMethods: StaEnabledState
D/WifiController(  953): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  953): setting operational mode to 1
,E/WifiStateMachine(  953): handleMessage: E msg.what=131083
E/WifiStateMachine(  953): processMsg: InitialState
D/WifiController(  953): handleMessage: X
D/WifiManager( 5860): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  953):  InitialState CMD_START_SUPPLICANT 0 0,
D/WifiManager( 5860): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 5860): Radios toggled
I/jxcore-log( 5860): 
,W/ResourcesManager( 5915): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
,D/AdapterServiceConfig( 5915): Adding HeadsetService,
D/AdapterServiceConfig( 5915): Adding A2dpService
D/AdapterServiceConfig( 5915): Adding HidService
D/AdapterServiceConfig( 5915): Adding HealthService
D/AdapterServiceConfig( 5915): Adding PanService
,D/AdapterServiceConfig( 5915): Adding GattService
,W/linker  ( 5915): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  953): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10f64ab8:true
W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  953): ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 5915): make
I/BluetoothAdapterState( 5915): Entering OffState
,E/bt_osi_config( 5915): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,D/BluetoothManagerService(  953): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService,
D/BluetoothManagerService(  953): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  953): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 5915): Address is:90:E7:C4:F6:69:77
,D/BluetoothManagerService(  953): Calling onBluetoothServiceUp callbacks,
D/BluetoothManagerService(  953): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 3490): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1b2cbcc2
D/BluetoothAdapter( 3490): onBluetoothServiceUp done
D/BluetoothAdapter( 2379): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1a8f95f3
D/BluetoothAdapter( 2379): onBluetoothServiceUp done
D/BluetoothAdapter(  953): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@36215a64
D/BluetoothAdapter(  953): onBluetoothServiceUp done,
,D/BluetoothAdapter( 5915): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@33e3d4e0
D/BluetoothAdapter( 5915): onBluetoothServiceUp done
D/BluetoothAdapter( 1498): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3fe12237
D/BluetoothAdapter( 1498): onBluetoothServiceUp done
D/BluetoothAdapter( 1217): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2d41c494
D/BluetoothAdapter( 1217): onBluetoothServiceUp done
D/BluetoothAdapter( 1482): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1ba77640
D/BluetoothAdapter( 1482): onBluetoothServiceUp done
D/BluetoothAdapter( 1798): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@124fcc1e
,D/BluetoothAdapter( 1798): onBluetoothServiceUp done
,D/BluetoothAdapter( 5860): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@e730a42
D/BluetoothAdapter( 5860): onBluetoothServiceUp done
D/BluetoothManagerService(  953): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 5915): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5915): Setting state to 11
I/BluetoothAdapterState( 5915): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  953): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  953): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  953): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  953): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1217): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,V/BluetoothPbapReceiver( 5915): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5915): ***********state = 11
D/BluetoothBondStateMachine( 5915): make
,D/NGFService( 3490): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterService( 5915): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 5915): checkA2dpState: returning
,D/BluetoothAdapterService( 5915): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 5915): checkHfpState: returning
I/BluetoothBondStateMachine( 5915): StableState(): Entering Off State
,D/PMS     (  953): releaseWL(3c4c0815): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
,D/Tethering(  953): interfaceAdded wlan0
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  953): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5950 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,V/Tethering(  953): TetherInterfaceSM: wlan0: enter InitialState
D/BluetoothHeadset(  953): Proxy object connected,
D/Tethering(  953): interfaceLinkStateChanged wlan0, false
D/Tethering(  953): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,D/HeadsetService( 5915): Received start request. Starting profile...
,D/BluetoothHeadset( 1482): Proxy object connected
D/HeadsetStateMachine( 5915): Version 1.5
D/HeadsetStateMachine( 5915): make
D/Tethering(  953): interfaceAdded p2p0
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  953): p2p0 is not a tetherable iface, ignoring
D/Tethering(  953): interfaceLinkStateChanged p2p0, false
D/Tethering(  953): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  953): setWifiState: enabling
I/BluetoothAdapterState( 5915): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/WifiStateMachine(  953): Supplicant start successful
D/WifiMonitor(  953): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  953): connecting to supplicant
E/WifiHW  (  953): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/QuickSettingBluetooth( 1217): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/BluetoothHeadset( 1217): Proxy object connected
,I/IntentController( 1217): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/ActivityManager(  953): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=5972 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/Tethering(  953): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  953): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  953): TetherInterfaceSM: wlan0: exit InitialState,
V/Tethering(  953): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  953): acquireWL(1368b483): PARTIAL_WAKE_LOCK  NetworkStats 0x1 953 1000 null
D/Tethering(  953): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothHeadset( 1482): Proxy object connected
D/PMS     (  953): releaseWL(1368b483): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
V/NetworkPolicy(  953): updateNetworkEnabledLocked()
V/NetworkPolicy(  953): updateNotificationsLocked(),
D/PMS     (  953): acquireWL(ae6f600): PARTIAL_WAKE_LOCK  NetworkStats 0x1 953 1000 null
,D/HeadsetStateMachine( 5915): max_hf_connections = 2
D/PMS     (  953): releaseWL(ae6f600): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  953): updateNetworkEnabledLocked()
,V/NetworkPolicy(  953): updateNotificationsLocked()
D/BluetoothAdapter(  953): 667251244: getState(). Returning 11
,D/BluetoothPhoneService( 1482): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset( 1482): Proxy object connected
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
,D/HeadsetPhoneState( 5915): listenForPhoneState..for service and signal 
,D/HeadsetDualPhoneStateListener_SLOT1( 5915): listen phone state by slot:SLOT1  id:-1
,D/BluetoothAdapter( 1482): 1026430654: getState(). Returning 11
D/HeadsetDualPhoneStateListener_SLOT2( 5915): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 5915): Enter Disconnected: -2, size: 0
,D/HeadsetDualPhoneStateListener_SLOT1( 5915): listen phone state by slot:SLOT1  id:-1
,D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1594d574
,I/QuickSettingMiniLite( 1217): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@2d5dfb3d
D/HeadsetDualPhoneStateListener_SLOT2( 5915): listen phone state by slot:SLOT2  id:-100,
I/HeadsetStateMachine( 5915): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 5915): BTHF: set_current_device
D/UsbDeviceManager(  953): [USBNET] bCheckSuppFunc: cdc_network
D/A2dpService( 5915): Received start request. Starting profile...
,V/Avrcp   ( 5915): make
D/UsbDeviceManager(  953): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  953): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/UsbnetService(  953): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/BluetoothA2dp(  953): Proxy object connected
D/BluetoothAdapter(  953): 667251244: getState(). Returning 11
,E/RemoteController( 5915): Cannot set synchronization mode on an unregistered RemoteController
,D/A2dpStateMachine( 5915): make
,D/bt-btif ( 5915): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/A2dpService( 5915): setA2dpService(): set to: null
D/WIFI_ICON( 1217): updateWifiState: WIFI_STATE_CHANGED disabled
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1594d574
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/A2dpStateMachine( 5915): Enter Disconnected: -2
,D/HtcBtWidget_BTWidgetProvider( 5950): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 5950): updateWidget(context) for widget: 
D/wpa_supplicant( 5962): wpa_supplicant v2.3-devel-5.0.2,
D/Process (  953): killProcessQuiet, pid=5600
I/ActivityManager(  953): Killing 5600:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/wpa_supplicant( 5962): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2),
D/wpa_supplicant( 5962): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 5962): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5962): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 5962): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 5962): Successfully initialized wpa_supplicant
D/wpa_supplicant( 5962): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5962): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5962): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/HidService( 5915): Received start request. Starting profile...
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1594d574
D/wpa_supplicant( 5962): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5962): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5962): update_config=1
D/wpa_supplicant( 5962): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5962): device_name='Android_608e'
D/wpa_supplicant( 5962): manufacturer='HTC'
D/wpa_supplicant( 5962): model_name='HTC_PHONE'
D/wpa_supplicant( 5962): model_number='1234'
D/wpa_supplicant( 5962): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5962): p2p_oper_reg_class=126
D/wpa_supplicant( 5962): p2p_oper_channel=149
D/wpa_supplicant( 5962): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 5962): persistent_reconnect=1
D/wpa_supplicant( 5962): key_mgmt_offload=1
I/QuickSettingWifi( 1217): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
I/wpa_supplicant( 5962): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5962): nl80211: RFKILL status not available
D/wpa_supplicant( 5962): nl80211: Using driver-based roaming
D/wpa_supplicant( 5962): nl80211: TDLS supported
D/wpa_supplicant( 5962): nl80211: TDLS external setup
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5962): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5962): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5962): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5962): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 5962): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 5962): nl80211: Subscribe to mgmt frames with non-AP handle 0x55c078bfd0
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=0104
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=040a
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=040b
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=040c
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=040d
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=090a
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=090b
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=090c
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=090d
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=0409506f9a09
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=7f506f9a09
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=0801
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=040e
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=06
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=0a07
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=0a11
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c078bfd0 match=0a1a
D/wpa_supplicant( 5962): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5962): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5962): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 5962): htc_wext_command_init +
E/wpa_supplicant( 5962): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5962): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/Tethering(  953): interfaceLinkStateChanged p2p0, false
D/Tethering(  953): interfaceStatusChanged p2p0, false
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/HealthService( 5915): Received start request. Starting profile...
D/Tethering(  953): interfaceLinkStateChanged p2p0, false
D/Tethering(  953): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1594d574
D/PanService( 5915): Received start request. Starting profile...
D/PanService( 5915): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1594d574
D/BtGatt.DebugUtils( 5915): handleDebugAction() action=null
D/BtGatt.GattService( 5915): Received start request. Starting profile...
D/BtGatt.GattService( 5915): start()
D/BtGatt.AdvertiseManager( 5915): advertise manager created
,D/BluetoothAdapter( 1217): 579786308: getState(). Returning 11
I/QuickSettingMiniLite( 1217): updateLiteState:no connect device!
,I/ActivityManager(  953): Recipient 5600
,D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1594d574
,D/BluetoothAdapter( 1482): 1026430654: getState(). Returning 11
,W/BluetoothHeadset( 1482): Proxy not attached to service
,I/HeadsetPhoneState( 5915): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 5915): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0,
D/HeadsetStateMachine( 5915): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/BluetoothHeadset( 1482): java.lang.Throwable
D/BluetoothHeadset( 1482): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1482): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1482): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1482): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1482): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1482): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1482): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1482): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1482): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1482): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1482): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,D/BluetoothAdapterState( 5915): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/HeadsetPhoneState( 5915): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5915): Disconnected process message: 11, size: 0
I/bt-btu  ( 5915): btu_task pending for preload complete event
,D/BluetoothMasReceiver( 5915): Bluetooth STATE CHANGED to 11,
,V/BluetoothSapReceiver( 5915): SapReceiver onReceive 
D/HtcWiFiWidget_WiFiWidgetProvider( 5972): onWiFiStateChanged() for widget: 
E/bt_vendor( 5915): get_bt_soc_type: Failed to get soc type
D/HtcWiFiWidget_WiFiWidgetProvider( 5972): updateWidget(context) for widget: 
V/BluetoothSapReceiver( 5915): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5915):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 5915): startService = false
,D/AuthorizationBluetoothService( 1894): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/TetherSettings( 5333): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
D/        ( 5333): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5333): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5333): Cust_ConnectToPC   : spcsc>false
D/        ( 5333): Cust_ConnectToPC   : IPT>true
D/        ( 5333): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5333): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/qcom-bluetooth( 6007): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,E/SmartNS_Utility( 5333): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5333): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5333): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/wpa_supplicant( 5962): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 5962):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5962):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5962):  Initialization: WAPI:set Staues=1 
,D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5962): nl80211: Flush PMKIDs
D/wpa_supplicant( 5962): p2p0: State: DISCONNECTED -> INACTIVE
,W/ContextImpl( 5333): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5333): setISNotification
,D/SmartNS_Utility( 5333): usb_cable_connect = 1
,D/SmartNS_Utility( 5333): usb_denied = 0
I/SmartNS_PSService( 5333): usb notificaiton:true
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5333): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/qcom-bluetooth( 6015): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,D/SmartNS_Utility( 5333): usb_cable_connect = 1
I/qcom-bluetooth( 6016): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
D/SmartNS_Utility( 5333): usb_denied = 0
I/SmartNS_PSService( 5333): usb notificaiton:true
,E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
,I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 5333): Tethered state change:false isNSOpening:false
,I/ActivityManager(  953): Killing 5623:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5623
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
I/qcom-bluetooth( 6018): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/qcom-bluetooth( 6019): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/RemoteViews( 1217): reapply : com.android.settings 1 36
,I/qcom-bluetooth( 6020): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6021): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/wpa_supplicant( 5962): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 5962): TDLS: Driver uses external link setup
D/wpa_supplicant( 5962): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 5962): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5962): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 5962): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5962): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5962): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5962): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5962): Using existing control interface directory.
D/wpa_supplicant( 5962): P2P: Add operating class 81
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 5962): P2P: Own listen channel: 81:1
D/wpa_supplicant( 5962): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 5962): P2P: initialized
D/wpa_supplicant( 5962): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5962): P2P: cli_channels:
D/wpa_supplicant( 5962): p2p0: Added interface p2p0
D/wpa_supplicant( 5962): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 5962): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5962): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5962): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5962): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5962): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 5962): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5962): disable_scan_offload=1
D/wpa_supplicant( 5962): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 5962): update_config=1
D/wpa_supplicant( 5962): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5962): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 5962): manufacturer='HTC'
D/wpa_supplicant( 5962): model_name='HTC One M8s'
D/wpa_supplicant( 5962): model_number='HTC One M8s'
D/wpa_supplicant( 5962): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 5962): hs20=1
D/wpa_supplicant( 5962): interworking=1
D/wpa_supplicant( 5962): external_sim=1
D/wpa_supplicant( 5962): key_mgmt_offload=1
,I/ActivityManager(  953): Recipient 5623
,D/wpa_supplicant( 5962): Priority group 262
D/wpa_supplicant( 5962):    id=0 ssid='NG700'
I/wpa_supplicant( 5962): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5962): nl80211: RFKILL status not available
D/wpa_supplicant( 5962): nl80211: Using driver-based roaming
D/wpa_supplicant( 5962): nl80211: TDLS supported
D/wpa_supplicant( 5962): nl80211: TDLS external setup
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5962): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5962): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0,
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5962): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
,D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5962): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5962): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5962): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5962): nl80211: Enable multi-channel concurrent (driver advertised support)
,D/wpa_supplicant( 5962): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5962): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 5962): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 5962): nl80211: Subscribe to mgmt frames with non-AP handle 0x55c07ab100
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=0104
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=040a
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=040b
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=040c
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=040d
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=090a
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=090b
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=090c
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=090d
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=0409506f9a09
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=7f506f9a09
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=0801
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=040e
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=06
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=0a07
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=0a11
D/wpa_supplicant( 5962): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55c07ab100 match=0a1a
D/wpa_supplicant( 5962): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5962): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 5962): nl80211: Use separate P2P group interface
D/wpa_supplicant( 5962): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 5962): htc_wext_command_init +
I/wpa_supplicant( 5962): htc_wext_command_init -
I/wpa_supplicant( 5962): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 5962): Don't set 00 to countryID.conf
D/Tethering(  953): interfaceLinkStateChanged wlan0, false
D/Tethering(  953): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 5962): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5962): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5962): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5962): P2P: Add operating class 81
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 5962): P2P: Update channel list
D/wpa_supplicant( 5962): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5962): P2P: cli_channels:
D/wpa_supplicant( 5962): p2p0: Updating hw mode
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5962): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5962): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5962): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
,I/wpa_supplicant( 5962): wapi_supplicant_init: Init WAI packet wlan0,
D/wpa_supplicant( 5962):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5962):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5962):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5962): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5962): nl80211: Flush PMKIDs
,I/qcom-bluetooth( 6024): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 ,
,I/qcom-bluetooth( 6025): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 5962): TDLS: TDLS operation supported by driver,
,D/wpa_supplicant( 5962): TDLS: Driver uses external link setup
D/wpa_supplicant( 5962): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5962): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5962): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 5962): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5962): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5962): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5962): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5962): Using existing control interface directory.
I/bt-btu  ( 5915): btu_task received preload complete event
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x001f
,W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0003,
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x1487
D/PMS     (  953): acquireWL(24e6d7a9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5915 1002 null
I/wpa_supplicant( 5962): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 5962): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 5962): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5962): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5962): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
,D/wpa_supplicant( 5962): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5962): P2P: Add operating class 81
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5962): P2P: Add operating class 115
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5962): P2P: Add operating class 116
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5962): P2P: Add operating class 117
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5962): P2P: Update channel list
D/wpa_supplicant( 5962): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5962): P2P: cli_channels:
D/wpa_supplicant( 5962): p2p0: Updating hw mode
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5962): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 5962): Auto country group 1: ch36
D/bt-btm  ( 5915): btm_acl_device_down
D/bt-btm  ( 5915): btm_acl_reset_paging
D/bt-btm  ( 5915): btm_acl_set_discing
D/wpa_supplicant( 5962): wlan0: Added interface wlan0
D/wpa_supplicant( 5962): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 5962): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5962): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5962): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 5962): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5962): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 5962): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5962): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5962): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 5962): nl80211: Regulatory domain change
D/wpa_supplicant( 5962):  * initiator=1
D/wpa_supplicant( 5962):  * type=0
D/wpa_supplicant( 5962):  * alpha2=DE
D/wpa_supplicant( 5962): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5962): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
,D/wpa_supplicant( 5962): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5962): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5962): P2P: Add operating class 81
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5962): P2P: Add operating class 115
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5962): P2P: Add operating class 116
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5962): P2P: Add operating class 117
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5962): P2P: Update channel list
,D/wpa_supplicant( 5962): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5962): P2P: cli_channels:
D/wpa_supplicant( 5962): p2p0: Updating hw mode
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5962): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm,
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
,I/bt-btm  ( 5915): btm_reset_complete,
I/bt-btm  ( 5915): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 5915): Start reading local supported commands
,D/bt-btm  ( 5915): btm_read_local_supported_cmds_complete status (0x00),
D/bt-btm  ( 5915): BTM reads next extended features page (1)
D/bt-btm  ( 5915): BTM reads next extended features page (2)
,D/bt-btm  ( 5915): BTM reached last extended features page (2),
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 5915): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 5915): btm_vendor_capability_vsc_cmpl_cback: status=0
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 5915): btm_read_ble_wl_size 
D/bt-btm  ( 5915): btm_read_white_list_size_complete 
D/bt-btm  ( 5915): btm_get_ble_buffer_size 
,D/bt-btm  ( 5915): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 5915): btm_read_ble_local_supported_states 
,D/bt-btm  ( 5915): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 5915): btm_read_ble_local_supported_features 
,D/bt-btm  ( 5915): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 5915): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 5915): btm_decode_ext_features_page page: 0
D/bt-btm  ( 5915): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 5915): Local supported SCO packet types: 0x038f
I/bt-btm  ( 5915): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 5915): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 5915): BTM_SetInquiryMode
I/bt-btm  ( 5915): BTM_SetPageScanType
I/bt-btm  ( 5915): BTM_SetInquiryScanType
D/bt-btm  ( 5915): btm_decode_ext_features_page page: 1
W/bt-btm  ( 5915): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 5915): btm_decode_ext_features_page page: 2,
W/bt-btm  ( 5915): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 5915): BTM_BleLoadLocalKeys
D/bt-btm  ( 5915): BTM_BleLoadLocalKeys
I/bt-btm  ( 5915): BTM_Sec: application registered
E/bt-btm  ( 5915): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf5184d5 
I/bt-btm  ( 5915): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 5915): SMP_Register state=0
E/bt-btm  ( 5915): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf5184d5 
I/bt-btm  ( 5915): BTM_Sec: application registered
D/bt-btm  ( 5915): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 5915): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 5915): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 5915): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 5915): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 5915): BTM_RegBusyLevelNotif
,D/bt-btm  ( 5915): BTM_BleReadControllerFeatures
I/bt-btm  ( 5915): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 5915): GATT_Register
D/bt-att  ( 5915): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 5915): allocated gatt_if=3
I/bt-att  ( 5915): GATT_StartIf gatt_if=3
D/bt-att  ( 5915): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5915): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 5915): btm_ble_vendor_capability_vsc_cmpl_cback,
D/bt-btm  ( 5915): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 5915): BTM Register For VSEvents is successfully
D/bt-btm  ( 5915): BTM_BleGetVendorCapabilities
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 5915): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
,D/bt-btm  ( 5915): bta_dm_set_dev_name: name: HTC One M8s ,
E/bt-btif ( 5915): Calling BTA_HhEnable
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
,I/bt-btm  ( 5915):  BTM_BleConfigPrivacy
,I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr,
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr,
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr,
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
,D/bt-btif ( 5915): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 5915): BTM_AllocateSCN
,I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 5915): BTM_AllocateSCN
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5915):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 5915): AG evt (hdl 0x0002): State 0, Event 0x0500
,I/bt-btm  ( 5915): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5915):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 5915): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 5915): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 5915): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 5915): A2D_AddRecord uuid: 110a
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/bt-btif ( 5915):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 5915): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_MceEnable
I/bt-btm  ( 5915): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
E/bt-btif ( 5915):                : sec: 0x86, service name [mask:0x2140040
I/bt-btm  ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 5915): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5915):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 5915): GATT_Register
D/bt-att  ( 5915): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 5915): allocated gatt_if=4
D/BluetoothAdapterProperties( 5915): Address is:90:E7:C4:F6:69:77
I/bt-att  ( 5915): GATT_StartIf gatt_if=4
D/bt-att  ( 5915): gatt_find_the_connected_,bda start_idx=0
D/bt-att  ( 5915): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 5915): Scan Mode:21
D/BluetoothAdapterProperties( 5915): Discoverable Timeout:120
I/bt-btif ( 5915): BTA_JvEnable
I/bt-btif ( 5915): BTA_JvRegisterL2cCback
I/bt-btm  ( 5915): BTM_ReadConnectability
I/bt-btm  ( 5915): BTM_ReadDiscoverability
I/bt-btm  ( 5915): BTM_SetDiscoverability
I/bt-btm  ( 5915): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 5915): disc_mode 0002
D/bt-btm  ( 5915): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 5915): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5915): BTM_SetConnectability
I/bt-btm  ( 5915): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5915): disc_mode 0002
,I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 5915): BTM_SetDiscoverability
I/bt-btm  ( 5915): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5915): disc_mode 0000
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5915): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 5915): BTM_SetConnectability
I/bt-btm  ( 5915): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5915): disc_mode 0000
D/bt-btm  ( 5915): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 5915): btm_ble_update_adv_flag old=0x18
,I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5915): bta_pan_co_init
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 5915): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5915):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5915):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5915):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5915):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
,D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 5915): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 5915): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5915): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5915): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 5915): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 5915): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5915): ScanMode =  21
D/BluetoothAdapterProperties( 5915): State =  11
D/BluetoothAdapterProperties( 5915): Setting state to 12
I/BluetoothAdapterState( 5915): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  953): +onBluetoothStateChange prev=11 new=12
E/bt_mct  ( 5915): hci lib postload completed
I/BluetoothAdapterState( 5915): Entering On State
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 5915): Discoverable Timeout:120
D/BluetoothManagerService(  953): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  953): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  953): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1482): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1482): onBluetoothStateChange: up=true
D/BluetoothA2dp(  953): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1482): onBluetoothStateChange: up=true
D/BluetoothHeadset(  953): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  953): Bluetooth State Change Intent: 11 -> 12
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = ea dd 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 0c 7f 45 16 fc 07 25 e3 77 c5 62 bb be 25 3c 05 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
,D/NGFService( 3490): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3490): Bluetooth Adapter: ON
I/IntentController( 1217): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothManagerService(  953): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  953): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapReceiver( 5915): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5915): ***********state = 12
D/BluetoothManagerService(  953): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 54 be 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = ff 96 8c 97 d1 0c 13 5e 84 04 4f d3 75 7b 3f bf 
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = d5 4f 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = d7 be 03 46 02 6d fc b7 5d 52 2d 36 02 d2 cb ea 
D/wpa_supplicant( 5962): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/Tethering(  953): interfaceLinkStateChanged p2p0, false
D/Tethering(  953): interfaceStatusChanged p2p0, false
D/PMS     (  953): acquireWL(121fbe5c): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5333 1000 null
E/WifiStateMachine(  953): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5333): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 1e b6 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 5f fb 0d 2f 4f ab b4 c5 ed 78 3a 81 2c 44 aa 01 
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 46 bc 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 8f 05 26 1c 13 90 28 cb 7f 25 62 61 81 75 85 ad 
V/BluetoothPbapService( 5915): Pbap Service onCreate
V/BluetoothPbapService( 5915): Starting PBAP service
D/BluetoothAdapter( 5915): 146746302: getState(). Returning 12
V/BluetoothPbapService( 5915): Handler(): got msg=1
V/BluetoothPbapService( 5915): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 5915): Pbap Service initSocket
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
D/PMS     (  953): releaseWL(121fbe5c): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = e2 06 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 9f bd 05 7e 0a 14 59 33 44 33 fe b4 7b 48 15 a2 
D/PMS     (  953): acquireWL(99c823a): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5333 1000 null
D/HtcBtWidget_BTWidgetProvider( 5950): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 5950): updateWidget(context) for widget: 
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 54 b8 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = f9 ef 2c 77 85 71 be 4f 86 6d 4c 53 6b fc 32 c8 
I/bt-btm  ( 5915): BTM_SetDiscoverability
I/bt-btm  ( 5915): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5915): disc_mode 0000
I/bt-btm  ( 5915): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5915): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5915): BTM_SetConnectability
I/bt-btm  ( 5915): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5915): disc_mode 0000
D/bt-btm  ( 5915): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 5915): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 5915): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 5915):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 5915): Succeed to create listening socket 
V/BluetoothPbapService( 5915): Accepting socket connection...
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5915): Scan Mode:21
W/System.err(  953): java.lang.Throwable: stack dump
W/System.err(  953): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  953): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  953): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  953): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38a0d2e1:true
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 88 2c 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 88 a6 f2 45 d8 0f 7b a6 41 11 2f 89 f3 71 00 10 
D/BluetoothAdapter( 1217): 579786308: getState(). Returning 12
D/BluetoothAdapter( 1217): 579786308: getState(). Returning 12
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 6d ef 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 6a 0f f4 f7 b3 ed b6 a1 ae d9 55 5c 08 e0 d0 20 
I/QuickSettingBluetooth( 1217): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/wpa_supplicant( 5962): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_953-3\x00
E/WifiStateMachine(  953): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  953): invokeExitMethods: InitialState
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  953): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131144
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  953): deferMessage: msg=131144
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131085
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  953): deferMessage: msg=131085
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131149
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
D/PhoneStatusBar( 1217): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
E/WifiStateMachine(  953):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  953): setSuspendOptimizations: 2 true
E/WifiStateMachine(  953): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131145
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131146
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131101
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  953): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131101
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  953): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147457
E/WifiStateMachine(  953): processMsg: SupplicantStartingState
E/WifiStateMachine(  953):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  953): Supplicant connection established
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = e6 21 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 6d 0c 5d 0b e4 9f e8 d0 3c 8c 0d be b6 89 02 84 
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 5962): set wifi ON
D/BluetoothAdapter( 5333): 370384181: getState(). Returning 12
E/WifiStateMachine(  953): setWifiState: enabled
E/WifiStateMachine(  953): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  953):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 5962): SET_SCREEN_ON:Off
I/wpa_supplicant( 5962): htc_wext_set_keepalive +
I/wpa_supplicant( 5962): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 5962): getPrivFuncNum +	
I/wpa_supplicant( 5962): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5962): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5962): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 5962): get_ip_address source addr = ffffffff
I/wpa_supplicant( 5962): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 5962): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  953): startHal
E/wifi    (  953): getStaticLongField sWifiHalHandle 0x7f8d496300
I/WifiNative-HAL(  953): Could not start hal
E/WifiStateMachine(  953): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
D/WifiStateMachine(  953): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  953): handleScreenStateChanged Exit: false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER MACADDR'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 5962): update_config=1
D/wpa_supplicant( 5962): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  953): Loading config and enabling all networks 
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 5962): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 5962): wpa_supplicant_ctrl_iface_list_networks: return size = 47
I/IntentController( 1217): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 6b 5c 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 04 93 ce 12 05 7d d0 2d 34 d7 4a 17 88 fb bd 22 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/BluetoothInputDevice( 5333): BluetoothInputDevice()
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
,D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 5962): Do not allow key_data field to be exposed
D/BluetoothManagerService(  953): registerStateChangeCallback+
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  953): Registered receivers: 7
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 password'
D/WIFI_ICON( 1217): updateWifiState: WIFI_STATE_CHANGED enabled
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 5962): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 5962): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  953): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/HtcWiFiWidget_WiFiWidgetProvider( 5972): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 5972): updateWidget(context) for widget: 
D/BluetoothPan( 5333): BluetoothPan()
D/BluetoothManagerService(  953): registerStateChangeCallback+
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 5962): device_name='m8qlul_htc_europe'
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  953): Registered receivers: 8
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 5962): manufacturer='HTC'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 5962): model_name='HTC One M8s'
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 01 98 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = bb 23 61 fb b5 c8 e1 ef 30 e8 a9 9d 77 53 f7 5b 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 5962): model_number='HTC One M8s'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 5962): config_methods='physical_display virtual_push_button'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  953): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  953): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  953): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  953): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 5962): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  953): Setting external_sim to 1
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/WifiP2pService(  953): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET external_sim 1'
D/WifiP2pService(  953): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5962): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 5962): external_sim=1
D/BluetoothMap( 5333): Create BluetoothMap proxy object
D/WifiStateMachine(  953): Setting OUI to DA-A1-19
I/WifiNative-HAL(  953): startHal
E/wifi    (  953): getStaticLongField sWifiHalHandle 0x7f8d496360
I/WifiNative-HAL(  953): Could not start hal
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
W/Settings( 5155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 5962): wlan0: Control interface command 'STA_AUTOCONNECT 0'
D/BluetoothManagerService(  953): registerStateChangeCallback+
E/WifiStateMachine(  953): invokeEnterMethods: DriverStartedState
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiStateMachine(  953): Driverstarted State enter
D/BluetoothManagerService(  953): Registered receivers: 9
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  953): DriverStartedState call setCountryCode()
E/WifiStateMachine(  953): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  953): NetworkAgent == null
E/BluetoothMap( 5333): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  953): registerStateChangeCallback+
D/BluetoothSap( 5333): BluetoothSap() call bindService
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  953): Registered receivers: 10
E/WifiStateMachine(  953): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 83 af 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/ContextImpl( 5333): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = a0 3a 66 44 f1 a7 76 3a 83 d2 44 2b 48 91 db 6d 
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  953): setDhcpActive: false
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 5962): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  953): transitionTo: destState=DisconnectedState
E/native  (  953): do suspend false
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/HTCRequest(  953): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/HTCRequest(  953): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 5962): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  953): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/WifiP2pService(  953): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  953): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  953): ENABLE_TRAFFIC_STATS_POLL false Token 0
D/BluetoothPbap( 5333): BluetoothPbap()
D/WifiP2pService(  953): P2pEnablingState
D/WifiMonitor(  953): startMonitoring(p2p0) with mConnected = true
D/BluetoothManagerService(  953): registerStateChangeCallback+
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  953): Registered receivers: 11
D/WifiP2pService(  953): P2pEnablingState{ when=-3ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  953): P2p socket connection successful
D/WifiP2pService(  953): P2pEnabledState
,E/WifiStateMachine(  953): Driverstarted State enter done
E/WifiStateMachine(  953): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  953): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  953): handleMessage: new destination call exit/enter
E/WifiStateMachine(  953): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  953): moveTempStackToStateStack: i=1,j=3
D/WifiP2pService(  953): sending p2p connection changed broadcast
E/WifiStateMachine(  953): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  953): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  953): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  953): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  953): DisconnectedState call setCountryCode()
D/WifiScanningService(  953): SCAN_AVAILABLE : 3
E/WifiStateMachine(  953):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/RttService(  953): SCAN_AVAILABLE : 3
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiScanningService(  953): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  953): startHal
D/RttService(  953): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 5962): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 5962): wlan0: nl80211: sched_scan request
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 4c ec 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = ba d0 e1 6f f2 39 8a b0 7d 3a c0 da bb dc 17 39 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/WifiDisplayController(  953): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WifiDisplayAdapter(  953): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  953):     Client/Owner: Client
D/WifiDisplayAdapter(  953):     GroupId: 
D/WifiDisplayAdapter(  953):     Passphrase: 
D/WifiDisplayAdapter(  953):     SessionId: 0
D/WifiDisplayAdapter(  953):     IP Address: }
D/WifiDisplayController(  953): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayController(  953): mWfdEnabled :false, networkInfo.isConnected() :false
V/AudioService(  953): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  953):     Client/Owner: Client
V/AudioService(  953):     GroupId: 
V/AudioService(  953):     Passphrase: 
V/AudioService(  953):     SessionId: 0
V/AudioService(  953):     IP Address: }
D/HtcEffectManagerBase(  953): onEventChanged id=5 status=false
D/HtcEffectManager(  953): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/BluetoothManagerService(  953): registerStateChangeCallback+
D/HtcEffectManager(  953): convertEffect before=902
D/HtcEffectManager(  953): convertEffect after=902
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  953): Registered receivers: 12
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
I/QuickSettingWifi( 1217): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
D/BluetoothAdapter( 5915): 146746302: getState(). Returning 12
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 5915):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 5915): Accept thread started.
D/BluetoothFtpService( 5915): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 5915): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 5915):  call MAP start service
D/BluetoothHeadset( 5333): BluetoothHeadset()
D/BluetoothManagerService(  953): registerStateChangeCallback+
D/BluetoothManagerService(  953): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
V/BluetoothPbapService( 5915): Pbap Service onBind
D/BluetoothManagerService(  953): Registered receivers: 13
D/BluetoothFtpService( 5915): htc sense version is 6.0
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 5333): LocalBluetoothProfileManager construction complete
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 5915):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 5915): Run Accept thread
E/BluetoothMasService( 5915): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/wpa_supplicant( 5962): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 5962): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 5962): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131144
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131085
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
D/BluetoothMasService( 5915): Add permission for SmsProvider.
E/WifiStateMachine(  953):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131154
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/DockEventReceiver( 5333): finishStartingService: stopping service
E/WifiStateMachine(  953):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/BluetoothInputDevice( 5333): Proxy object connected
E/WifiStateMachine(  953):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
V/BluetoothMasService( 5915): Starting MAS instances
E/WifiStateMachine(  953):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/wifi    (  953): getStaticLongField sWifiHalHandle 0x7f8b1ae520
I/WifiNative-HAL(  953): Could not start hal
E/WifiStateMachine(  953):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
D/HidProfile( 5333): Bluetooth service connected
E/WifiScanningService(  953): could not start HAL
W/WifiHW  (  953): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
E/WifiStateMachine(  953):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=131323
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 5962): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/BluetoothAdapter( 5915): 146746302: getState(). Returning 12
D/wpa_supplicant( 5962): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 5962): persistent_reconnect=1
D/wpa_supplicant( 5962): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5962): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 5962): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  953):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
D/BluetoothAdapter( 5333): 370384181: getState(). Returning 12
E/WifiStateMachine(  953):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState what:131323 0 0
E/WifiStateMachine(  953): setOperatorSSID enter
E/WifiStateMachine(  953): handleMessage: X
,E/WifiStateMachine(  953): handleMessage: E msg.what=131104
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState what:131104 0 0
W/Settings(  953): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/MailMessageReceiver( 5915): reg:com.android.bluetooth.btservice.AdapterApp@2e2c0817 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2c00a404
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 5962): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 5962): CTRL_IFACE: field=AIR_MODE id=0
D/BluetoothPan( 5333): BluetoothPAN Proxy object connected
D/wpa_supplicant( 5962): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  953): handleMessage: X
W/WifiHW  (  953): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  953): handleMessage: E msg.what=131162
E/WifiStateMachine(  953): processMsg: DisconnectedState
I/MailManager( 5915): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2c00a404
V/EmailUtils( 5915): Manager Instance is not NULL
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 5962): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 5962): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 5962): device_name='Android_608e'
,W/WifiHW  (  953): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 5962): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 5962): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 5962): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 5962): P2P: New SSID postfix: -Android_608e
W/WifiHW  (  953): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 5962): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 5962): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/PanProfile( 5333): Bluetooth service connected
W/WifiHW  (  953): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  953):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  953): processMsg: ConnectModeState
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 5962): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5962): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 5962): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5962): config_methods='virtual_push_button physical_display keypad'
,E/WifiStateMachine(  953):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  953): set frequency band 0
I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  953): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 5962): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 5962): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 5962): Single channel concurrency preference: sta
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/WifiNative-HAL(  953): p2pGetDeviceAddress
D/wpa_supplicant( 5962): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 5962): SETBAND: 0
D/wpa_supplicant( 5962): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 5962): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5962): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  953): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  953): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  953): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  953): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5962): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5962): P2P: Add operating class 81
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5962): P2P: Add operating class 115
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5962): P2P: Add operating class 116
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5962): P2P: Add operating class 117
D/wpa_supplicant( 5962): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5962): P2P: Update channel list
D/wpa_supplicant( 5962): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5962): P2P: cli_channels:
D/wpa_supplicant( 5962): p2p0: Updating hw mode
D/wpa_supplicant( 5962): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5962): nl80211: 2402-2482 @ 40 MHz 20 mBm
,D/wpa_supplicant( 5962): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5962): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5962): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5962): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  953): did set frequency band 0
W/WifiHW  (  953): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/WifiNative-HAL(  953): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
D/wpa_supplicant( 5962): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  953): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5962): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5962): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 5962): wlan0: Cancelling sched scan
D/wpa_supplicant( 5962): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 5962): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 5962): wpa_supplicant_scan enter
D/wpa_supplicant( 5962): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 5962): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 5962): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 5962): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  953): done set frequency band 0
,I/ActivityManager(  953): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6042 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/WifiP2pService(  953): DeviceAddress: 92:e7:c4:e6:4c:f8
W/WifiHW  (  953): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 5962): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 5962): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 5962): P2P: Stopping find
D/wpa_supplicant( 5962): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5962): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5962): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 5962): P2P: Stopping find
D/WifiDisplayController(  953): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  953):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  953):  primary type: 10-0050F204-5
D/WifiDisplayController(  953):  secondary type: null
D/WifiDisplayController(  953):  wps: 0
D/WifiDisplayController(  953):  grpcapab: 0
D/WifiDisplayController(  953):  devcapab: 0
D/WifiDisplayController(  953):  status: 3
D/WifiDisplayController(  953):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  953):  WFD CtrlPort: 0
D/WifiDisplayController(  953):  WFD MaxThroughput: 0
D/wpa_supplicant( 5962): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5962): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5962): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  953): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
,D/wpa_supplicant( 5962): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 5962): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  953): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 5962): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 5962): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  953): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 5962): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 5962): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 5962): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5962): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 5962): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5962): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 5962): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  953): sending p2p persistent groups changed broadcast
D/WifiP2pService(  953): InactiveState
,D/BluetoothA2dp( 5333): Proxy object connected
,D/WISPrService( 5333): >>>>>WISPrService start isConnected = false<<<<<
D/A2dpProfile( 5333): Bluetooth service connected
,D/BluetoothAdapter( 5333): 370384181: getState(). Returning 12
,D/BluetoothPbap( 5333): Proxy object connected
,D/PbapServerProfile( 5333): Bluetooth service connected
D/BluetoothHeadset( 5333): Proxy object connected
,D/HeadsetProfile( 5333): Bluetooth service connected
D/WifiService(  953): New client listening to asynchronous messages
E/WifiTrafficPoller(  953): ADD_CLIENT: 8
D/WifiStateMachine(  953): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  953): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=147462
E/WifiStateMachine(  953): processMsg: DisconnectedState
D/WISPrService( 5333): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  953):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=128211  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  953): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  953): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=128212  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  953): handleMessage: X
E/WifiStateMachine(  953): handleMessage: E msg.what=143371
E/WifiStateMachine(  953): processMsg: DisconnectedState
E/WifiStateMachine(  953):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/BluetoothAdapter( 5333): 370384181: getState(). Returning 12
E/WifiStateMachine(  953): processMsg: ConnectModeState
E/WifiStateMachine(  953):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  953): processMsg: DriverStartedState
E/WifiStateMachine(  953):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  953): processMsg: SupplicantStartedState
E/WifiStateMachine(  953):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  953): processMsg: DefaultState
E/WifiStateMachine(  953):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  953): handleMessage: X
D/PMS     (  953): releaseWL(99c823a): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/HtcAdjCursorFactory( 6042): Set CursorWindow size to: 4194304 KB, Tid: 6063
,D/EmailUtils( 5915): ============NULL aList========,
V/EmailUtils( 5915): <-getEmailAccountIdList
V/BluetoothMasService( 5915): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 5915): 146746302: getState(). Returning 12,
V/BluetoothMasService( 5915): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 5915): Manager Instance is not NULL
,D/EmailUtils( 5915): ============NULL aList========
,V/EmailUtils( 5915): <-getEmailAccountIdList
V/BluetoothSapReceiver( 5915): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5915): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5915):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 5915): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 5915): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 5915): BluetoothMns: isEmailEnabled: true
D/AuthorizationBluetoothService( 1894): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
D/bt-btm  ( 5915): BTM_AllocateSCN
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 5915):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5915): BTA_JvCreateRecordByUser
,D/bt-btm  ( 5915): BTM_AllocateSCN
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
,I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 5915):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,I/ActivityManager(  953): Killing 4558:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=4558
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  953): Recipient 4558,
,V/BluetoothSapService( 5915): Sap Service onCreate
,V/BluetoothSapService( 5915): initBinder
,V/BluetoothSapService( 5915): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@11df0eb3,
V/BluetoothSapService( 5915): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@a76cbe9
V/BluetoothSapService( 5915): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 5915): state: 12
D/SapServerProfile( 5333): Bluetooth service connected
V/BluetoothSapService( 5915): Starting SAP server process
,V/BluetoothSapService( 5915): SAP Service startRfcommListenerThread,
V/BluetoothSapService( 5915): Sap Service initRfcommSocket
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5915): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
,I/bt-btm  ( 5915): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 5915):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 5915): Succeed to create listening socket 
V/BluetoothSapService( 5915): Accepting socket connection...
,D/A2dpService( 5915): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@30b1e30f,
D/A2dpSinkService( 5915): getA2dpSinkService(): service is NULL
,D/wpa_supplicant( 5962): EAPOL: disable timer tick
,D/wpa_supplicant( 5962): EAPOL: disable timer tick
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  953): releaseWL(24e6d7a9): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 5860): Test app app.js loaded
I/jxcore-log( 5860): 
,I/chromium( 5860): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  953): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  953): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  953): acquireWL(2235fbf9): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{10024}
,V/AlarmManager(  953): sending alarm PendingIntent{1f58573e: PendingIntentRecord{3b26399f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142475, Int=0
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  953): sending alarm PendingIntent{ff6ed05: PendingIntentRecord{1f38a15a android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146660, Int=0
D/libc    (  953): [NET] android_getaddrinfofornet-, err=8
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  953): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  953): [NET] android_getaddrinfo_proxy+
D/libc    (  953): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  953): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  953): releaseWL(2235fbf9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  953): acquireWL(4cf2aec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(4cf2aec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true,
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  953): handleMessage: X
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
,D/PowerUI ( 1217): closing low battery warning: level=100
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  953): << updateStatus
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1482): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  953): acquireWL(9d15eb5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
,V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=157855, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{ff6ed05: PendingIntentRecord{1f38a15a android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=206672, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{2dfea94a: PendingIntentRecord{263ed0bb android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=207523, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{17fa09d8: PendingIntentRecord{2f17ca66 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=182411, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{19863131: PendingIntentRecord{3e061016 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=184758, Int=0
,D/libc    (  953): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  953): [NET] android_getaddrinfofornet-, err=8,
D/libc    (  953): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  953): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  953): [NET] android_getaddrinfo_proxy+
,D/libc    (  953): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  953): [NET] android_getaddrinfo_proxy-, NODATA,
,D/PMS     (  953): acquireWL(87fbd97): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(3f1eb84): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1894 10024 WorkSource{10024 com.google.android.gms},
D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1894): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1894): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1894): [NET] android_getaddrinfo_proxy+
D/libc    ( 1894): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1894): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  953): releaseWL(9d15eb5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  953): releaseWL(87fbd97): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  953): releaseWL(3f1eb84): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1455): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@b57adff
D/Process (  953): killProcessQuiet, pid=5655
I/ActivityManager(  953): Killing 5655:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5655
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  953): acquireWL(1a643bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(1a643bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  953): >> updateStatus
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): handleMessage: E msg.what=155652
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  953): acquireWL(1290d569): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  953): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): releaseWL(1290d569): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1217): closing low battery warning: level=100
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): runPSCheck
D/WifiController(  953): handleMessage: E msg.what=155652
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): processMsg: DeviceActiveState
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  953): acquireWL(e70bee): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=217856, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{1869271c: PendingIntentRecord{a585f25 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1449681423449, Int=0
D/PMS     (  953): acquireWL(3ac15eab): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  953): sending alarm PendingIntent{103bf8fa: PendingIntentRecord{2f17ca66 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=347094, Int=0
,D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1894): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1894): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1894): [NET] android_getaddrinfo_proxy+
D/libc    ( 1894): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1894): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  953): releaseWL(3ac15eab): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(e70bee): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On,
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  953): acquireWL(126f9908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(126f9908): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  953): plugged=true pluggin=true
,D/UsbnetService(  953): BroadcastReceiver::onReceive+,
,D/UsbnetService(  953): onReceive BATTERY_CHANGED,
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/PMS     (  953): runPSCheck
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): Checking...
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  953): >> updateStatus
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): handleMessage: E msg.what=155652
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: DeviceActiveState
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  953): Explicit concurrent mark sweep GC freed 27943(1460KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.971ms total 213.589ms
,I/ActionCombine( 1894): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1217): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1217): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,W/GLSActivity( 1894): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1894): ,	,at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1894): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1894): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1894): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5357): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5357): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5357): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/RemoteViews( 1217): apply : com.google.android.gms 0 18 5 40,
,I/art     ( 1894): Explicit concurrent mark sweep GC freed 18046(1027KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 998us total 65.227ms,
,W/System  ( 5357): Ignoring header User-Agent because its value was null.,
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5357): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5357): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5357): [NET] android_getaddrinfo_proxy+
D/libc    ( 5357): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5357): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  953): acquireWL(100494aa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(100494aa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  953): BroadcastReceiver::onReceive+,
,D/HtcPowerSaver(  953): updateBatteryInfo
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
,D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
,D/WifiController(  953): processMsg: StaEnabledState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  953): processMsg: DefaultState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  953): << updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): acquireWL(1cbb489b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/BatteryService(  953): n_update end
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): releaseWL(1cbb489b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  953): updateBatteryInfo
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): Checking...
,D/UsbnetService(  953): BroadcastReceiver::onReceive-,
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
,D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: StaEnabledState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  427): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  953): acquireWL(ebf5438): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=397855, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{2e701c11: PendingIntentRecord{2f17ca66 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=626164, Int=0
D/PMS     (  953): acquireWL(346f5176): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1894): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1894): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1894): [NET] android_getaddrinfo_proxy+
D/libc    ( 1894): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1894): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  953): releaseWL(346f5176): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): releaseWL(ebf5438): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/ContactMessageStore( 1482): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1482): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1482): sku_id=118
D/ContactMessageStore( 1482): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1482): start background delete task...
,D/ContactMessageStore( 1482): size: 0 , 0
D/ContactMessageStore( 1482): Background delete complete
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1894): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1894): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1894): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1894): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5357): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5357): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5357): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5357): Ignoring header User-Agent because its value was null.
,D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5357): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5357): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5357): [NET] android_getaddrinfo_proxy+
D/libc    ( 5357): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5357): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1217): reapply : com.google.android.gms 4 40
,D/PMS     (  953): acquireWL(3dcc3b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
,I/BatteryService(  953): n_update end
,D/PMS     (  953): releaseWL(3dcc3b68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953): BroadcastReceiver::onReceive-,
D/WifiController(  953): handleMessage: E msg.what=155652
D/HtcPowerSaver(  953): updateBatteryInfo
D/WifiController(  953): processMsg: DeviceActiveState
D/PMS     (  953): runPSCheck
D/WifiController(  953): processMsg: StaEnabledState
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: X
,D/PowerUI ( 1217): closing low battery warning: level=100
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1894): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1894): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1894): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1894): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5357): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5357): ,	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5357): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5357): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5357): Ignoring header User-Agent because its value was null.
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5357): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5357): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5357): [NET] android_getaddrinfo_proxy+
D/libc    ( 5357): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,I/RemoteViews( 1217): reapply : com.google.android.gms 3 40
D/libc    ( 5357): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  953): acquireWL(16a3b00a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=637856, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{3511307b: PendingIntentRecord{f394e98 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449682094720, Int=0
,D/SmartSyncUtils( 5756): isEpsOn(), nState = 0
,D/PMS     (  953): releaseWL(16a3b00a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/PMS     (  953): acquireWL(12e8f6f1): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5756 1000 null
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 5756): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 5756): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 5756): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 5756): SettingOnTime = 1449727200000, randomSettingOnTime = 1449724188000
D/SmartSyncScreenOnOffTimeReceiver( 5756): SettingOffTime = 1449705600000, randomSettingOffTime = 1449708971000
,D/SmartSyncScreenOnOffTimeReceiver( 5756): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5756): bNightMode = true,
D/SmartSyncScreenOnOffTimeReceiver( 5756): bNightModeTurnOffOnce = false
,D/PMS     (  953): releaseWL(12e8f6f1): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): acquireWL(37d4c2d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
D/UsbnetService(  953): BroadcastReceiver::onReceive+
I/BatteryService(  953): n_update end
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): releaseWL(37d4c2d6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/NotificationService(  953): plugged=true pluggin=true
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/HtcPowerSaver(  953): updateBatteryInfo
D/WifiController(  953): processMsg: StaEnabledState
D/PMS     (  953): runPSCheck
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  953): acquireWL(20785957): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1002},
V/AlarmManager(  953): sending alarm PendingIntent{2ec0bc44: PendingIntentRecord{205112d com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1027877, Int=0
,I/bt-btm  ( 5915): Received oneshot timer event complete
I/bt-btm  ( 5915): btm_ble_timeout
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
,D/PMS     (  953): acquireWL(1d323662): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5915 1002 null
D/PMS     (  953): releaseWL(20785957): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete,
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = db 6d 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = b4 5c a0 bc 90 83 d2 d2 f4 fd 97 f0 05 f8 3f 91 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  953): releaseWL(1d323662): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  953): acquireWL(2cbf33f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(2cbf33f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): runPSCheck
D/HtcPowerSaver(  953): Checking...
I/HtcPowerSaver(  953): >> updateStatus
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  953): User[0] Flushing usage stats to disk
,D/PMS     (  953): acquireWL(302f58b0): PARTIAL_WAKE_LOCK  *alarm* 0x1 953 1000 WorkSource{1000}
,V/AlarmManager(  953): sending alarm PendingIntent{38630511: PendingIntentRecord{29da8676 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806667, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1057855, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{394e9329: PendingIntentRecord{2f17ca66 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1184266, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{120156ae: PendingIntentRecord{b8f1c4f com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449682319945, Int=1800000
,D/PMS     (  953): acquireWL(3aa94fdc): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1894 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1894): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1894): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1894): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1894): [NET] android_getaddrinfo_proxy+,
D/libc    ( 1894): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1894): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  953): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6098 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  953): sending alarm PendingIntent{309438e5: PendingIntentRecord{3e902fba com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1449681895059, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{35cb2e6b: PendingIntentRecord{c56add com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449682043077, Int=0
D/PMS     (  953): releaseWL(3aa94fdc): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(21698dc8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4210 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  953): acquireWL(10018d86): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4210 10024 WorkSource{10024 com.google.android.gms}
D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
D/PMS     (  953): releaseWL(21698dc8): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5756): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  953): releaseWL(302f58b0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 5756): MY_DEBUG = false
,D/PowerUsageService( 5756): repeat time = 1449683220042,
,I/EventLogService( 4210): Aggregate from 1449680519875 (log), 1449680519875 (data),
,I/PowerUsageList:PowerUsageHelper( 5756): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5756): gen(), null == sipper.uidObj, userId = 0,
,D/PMS     (  953): releaseWL(10018d86): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 6121): Error opening trace file: Permission denied (13),
I/dex2oat ( 6121): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6121): dex2oat: override thread count:4
,I/dex2oat ( 6121): dex2oat took 708.180ms (threads: 4)
,I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk,
I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6098): ApplicationMonitor {81e1399}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6098): PnsModel {33e3d4e0}: update(): Update registration caused by: alarm,
,I/PushClient( 6098): PnsConfigModel {3fe12237}: <init>(): Use dm-client for provisioning.
,W/System.err( 6098): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6098): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6098): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6098): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  953): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6128 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6128): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6128 dbg=false s=true
,I/DeviceManagement( 6128): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6128): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6128): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6128): WorkflowService: Starting workflow service
,I/DeviceManagement( 6128): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@81e1399] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6128): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6128): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6128): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6128): SessionStateController: Checking invariants...
,I/DeviceManagement( 6128): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6128): SessionStateController: Checking invariants...
,I/DeviceManagement( 6128): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6128): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@81e1399]
,I/DeviceManagement( 6128): WorkflowService: Stopping workflow service
,D/Process (  953): killProcessQuiet, pid=5426
I/ActivityManager(  953): Killing 5426:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5426
,I/PushClient( 6098): PnsModel {33e3d4e0}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  953): Killing 5283:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  953): killProcessQuiet, pid=5283
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  953): Recipient 5283
,D/PMS     (  953): acquireWL(326d4f37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): releaseWL(326d4f37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  953): BroadcastReceiver::onReceive+
,D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  953): >> updateStatus,
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/WifiController(  953): battery changed pluggedType: 2
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1894): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1894): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1894): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
,W/GLSActivity( 1894): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5357): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5357): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5357): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5357): Ignoring header User-Agent because its value was null.
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5357): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5357): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5357): [NET] android_getaddrinfo_proxy+
D/libc    ( 5357): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5357): [NET] android_getaddrinfo_proxy-, NODATA
,I/RemoteViews( 1217): reapply : com.google.android.gms 5 40
,D/PMS     (  953): acquireWL(1c8cc141): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(1c8cc141): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0,
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  953): BroadcastReceiver::onReceive+,
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PMS     (  953): runPSCheck
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  953): Checking...
,D/UsbnetService(  953): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  953): >> updateStatus
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: StaEnabledState
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  953): processMsg: DefaultState
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  953): acquireWL(41646e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(41646e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo,
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  953): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  953): runPSCheck
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  953): battery changed pluggedType: 2
D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  953): >> updateStatus
,D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  953): << updateStatus,
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1894): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1894): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1894): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1894): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5357): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5357): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5357): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5357): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5357): Ignoring header User-Agent because its value was null.
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5357): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5357): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5357): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5357): [NET] android_getaddrinfo_proxy get netid:0
I/RemoteViews( 1217): reapply : com.google.android.gms 4 40
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5357): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  953): acquireWL(39ab5358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(39ab5358): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  953): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  953): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  953): runPSCheck
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  953): Checking...
D/UsbnetService(  953): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  953): >> updateStatus
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/WifiController(  953): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/WifiController(  953): processMsg: DeviceActiveState
,D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  953): acquireWL(f677cb1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(f677cb1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  953): updateBatteryInfo
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1217): closing low battery warning: level=100
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
D/WifiController(  953): handleMessage: E msg.what=155652
I/HtcPowerSaver(  953): >> updateStatus
D/WifiController(  953): processMsg: DeviceActiveState
D/WifiController(  953): battery changed pluggedType: 2
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  953): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  953): acquireWL(3052b517): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000}
,V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1237856, Int=0
V/AlarmManager(  953): sending alarm PendingIntent{2d2e4d04: PendingIntentRecord{2d4632ed com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1852881, Int=0
,I/ProcessStatsService(  953): Prepared write state in 19ms,
V/AlarmManager(  953): sending alarm PendingIntent{3ab61522: PendingIntentRecord{34438bb3 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1864828, Int=0
,D/PMS     (  953): releaseWL(3052b517): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On,
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/LocationManagerService(  953): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  953): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-34-43.bin
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1894): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1894): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1894): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1894): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1894): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1894): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1894): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1894): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1894): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1894): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5357): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5357): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5357): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5357): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5357): Ignoring header User-Agent because its value was null.
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5357): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5357): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5357): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5357): [NET] android_getaddrinfo_proxy+
D/libc    ( 5357): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5357): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  953): Explicit concurrent mark sweep GC freed 24332(1316KB) AllocSpace objects, 15(1112KB) LOS objects, 33% free, 16MB/24MB, paused 1.735ms total 156.646ms
,I/RemoteViews( 1217): reapply : com.google.android.gms 3 40,
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  953): acquireWL(35aecc82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 953 1000 null,
I/BatteryService(  953): n_update end
D/PMS     (  953): releaseWL(35aecc82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  953): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  953): updateBatteryInfo
D/UsbnetService(  953): onReceive BATTERY_CHANGED
D/NotificationService(  953): plugged=true pluggin=true
D/UsbnetService(  953):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  953): runPSCheck
,D/UsbnetService(  953): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  953): Checking...
I/HtcPowerSaver(  953): >> updateStatus
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
I/HtcPowerSaver(  953): updateStatus (8000,100,-1,false,false,false,-1),
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  953): << updateStatus
D/WifiController(  953): handleMessage: E msg.what=155652
D/WifiController(  953): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  953): processMsg: DeviceActiveState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  953): processMsg: StaEnabledState
D/WifiController(  953): processMsg: DefaultState
D/WifiController(  953): handleMessage: X
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  953): acquireWL(c48df93): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 953 1000 WorkSource{1000},
V/AlarmManager(  953): sending alarm PendingIntent{2419563b: PendingIntentRecord{3b1e158 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1897856, Int=0
,V/AlarmManager(  953): sending alarm PendingIntent{2dd82bd0: PendingIntentRecord{154437c9 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1927889, Int=0
I/bt-btm  ( 5915): Received oneshot timer event complete
I/ActivityManager(  953): Killing 5815:com.htc.calendar/u0a10 (adj 13): empty for 1814s
I/bt-btm  ( 5915): btm_ble_timeout
D/PMS     (  953): acquireWL(5812ece): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5915 1002 null
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
D/Process (  953): killProcessQuiet, pid=5815
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
,I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 3f 15 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 79 c6 7f 5d 7e 13 aa 58 f2 e6 c2 a4 84 8e fb ce 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  953): Recipient 5815,
,D/Process (  953): killProcessQuiet, pid=5791
I/ActivityManager(  953): Killing 5791:com.htc.mobiledata/u0a46 (adj 13): empty for 1815s
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  953): Recipient 5791
,D/Process (  953): killProcessQuiet, pid=5725
,I/ActivityManager(  953): Killing 5725:com.htc.bgp/u0a11 (adj 13): empty for 1815s
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  953): Recipient 5725
,D/Process (  953): killProcessQuiet, pid=5703
I/ActivityManager(  953): Killing 5703:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1821s
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  953): Recipient 5703
,D/Process (  953): killProcessQuiet, pid=5357
I/ActivityManager(  953): Killing 5357:com.android.vending/u0a72 (adj 15): empty for 1827s
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  953): Recipient 5357
,D/Process (  953): killProcessQuiet, pid=5566
I/ActivityManager(  953): Killing 5566:com.android.defcontainer/u0a15 (adj 15): empty for 1840s
,D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  953): Recipient 5566
,D/Process (  953): killProcessQuiet, pid=5950
I/ActivityManager(  953): Killing 5950:com.htc.widget.hmsproc3/u0a34 (adj 13): empty for 1800s
D/Process (  953): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  953): Recipient 5950
,D/PMS     (  953): releaseWL(5812ece): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
D/PMS     (  953): releaseWL(c48df93): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,TIME-OUT KILL (timeout was 1800000ms)
```
