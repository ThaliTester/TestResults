#### Test 51790364a0f6051_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  966): acquireWL(121e3302): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=114600, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{1ff28413: PendingIntentRecord{38323650 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448520608140, Int=0
D/PMS     (  966): acquireWL(bcdb049): PARTIAL_WAKE_LOCK  *backup* 0x1 966 1000 null
,W/BackupManagerService(  966): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  966): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  966): releaseWL(bcdb049): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  966): releaseWL(121e3302): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
E/cutils-trace( 6014): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6014): ====startRecUseTime====
D/htc.customization.log.level( 6014):  is 
W/CustomizationLogLevel( 6014): Level value is invalid, use default level 2
D/CustomizationManager( 6014):  Read ACC file spent 0.042 (s)
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6014): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6014): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6014): Parsing tag category name = system
I/CustomizationCIDLoader( 6014): Parsing tag category name = application
I/CustomizationCIDLoader( 6014): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6014): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6014): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6014): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6014): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6014): add string-array item, value = 42507
I/CustomizationCIDLoader( 6014): add string-array item, value = 21902
I/CustomizationCIDLoader( 6014): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6014): add string-array item, value = 23420
I/CustomizationCIDLoader( 6014): add string-array item, value = 22299
I/CustomizationCIDLoader( 6014): add string-array item, value = 24002
I/CustomizationCIDLoader( 6014): add string-array item, value = 23210
I/CustomizationCIDLoader( 6014): add string-array item, value = 23205
I/CustomizationCIDLoader( 6014): add string-array item, value = 23806
I/CustomizationCIDLoader( 6014): add string-array item, value = 23430
I/CustomizationCIDLoader( 6014): add string-array item, value = 23408
I/CustomizationCIDLoader( 6014): add string-array item, value = 27205
I/CustomizationCIDLoader( 6014): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6014): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6014):  Read CID file spent 0.088 (s)
D/CustomizationManager( 6014):  All configurations done spent 0.089 (s)
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6014 on display 0
D/PMS     (  966): acquireHCC(13c07d4e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 966 1000 null
D/PMS     (  966): acquireHCC(7774e6f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 966 1000 null
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6032 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  966): Display changed displayId=0
D/DotMatrix( 1301): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1301): [EventService] mbHDMIConnect: false, mCoverOn:false
I/TrimMemoryManager( 1512): [trimMemory] 20
I/WebViewFactory( 6032): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 6032): Time to load native libraries: 10 ms (timestamps 3482-3492),
I/LibraryLoader( 6032): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6032): Binding Chromium to main looper Looper (main, tid 1) {ec42319}
,I/LibraryLoader( 6032): Expected native library version number "",actual native library version number ""
,I/chromium( 6032): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6032): Initializing chromium process, singleProcess=true
,W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6032): ApplicationContext is null in ApplicationStatus
,W/chromium( 6032): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 6032): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6032): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6032): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6032): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6032): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6032): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6032): Local Branch: 
I/Adreno-EGL( 6032): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6032): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6032):                  d74aa161a12b9c6fc6332151
,W/System.err(  966): java.lang.Throwable: stack dump
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27682a14:true
,D/BluetoothAdapter( 6032): 78402700: getState() :  mService = null. Returning STATE_OFF
,I/art     (  966): Explicit concurrent mark sweep GC freed 30796(1706KB) AllocSpace objects, 4(920KB) LOS objects, 33% free, 16MB/24MB, paused 1.397ms total 131.867ms,
,W/ActivityManager(  966): Activity pause timeout for ActivityRecord{208c677c u0 com.test.thalitest/.MainActivity t8},
W/HtcSystemUPManager(  966): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6032): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6032): CordovaWebView is running on device made by: HTC
,W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 6032): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6032): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
D/StatusBarManagerService(  966): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
,D/FindExtension( 6032): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6032): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@13914cb, mServedView=org.apache.cordova.engine.SystemWebView{9a5e4a8 VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@293dbbc1
,I/InputMethodManagerService(  966): Disable input method client, pid=1512
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0,
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 6032): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +774ms (total +816ms)
,W/BindingManager( 6032): Cannot call determinedVisibility() - never saw a connection for the pid: 6032,
,D/JsMessageQueue( 6032): Set native->JS mode to OnlineEventsBridgeMode,
,D/Process (  966): killProcessQuiet, pid=5196
,I/ActivityManager(  966): Killing 5196:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/jxcore_app_log( 6032): JniHelper::setJavaVM(0xab0e18f8), pthread_self() = -1405010976,
D/JX-Cordova( 6032): jxcore cordova android initializing
,I/ActivityManager(  966): Recipient 5196
,W/jxcore-log( 6032): Initializing JXcore engine,
W/jxcore-log( 6032): JXcore engine is ready
,W/jxcore-log( 6032): Starting JXcore engine
,D/PMS     (  966): releaseHCC(13c07d4e): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  966): releaseHCC(7774e6f): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 6032): Platform android,
W/jxcore-log( 6032): 
W/jxcore-log( 6032): Process ARCH arm
W/jxcore-log( 6032): 
,I/jxcore-log( 6032): JXcore Cordova bridge is ready!,
I/jxcore-log( 6032): 
W/jxcore-log( 6032): JXcore engine is started
,I/Choreographer( 6032): Skipped 94 frames!  The application may be doing too much work on its main thread.,
I/chromium( 6032): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6032): Toggling radios to true
I/jxcore-log( 6032): 
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  966): checking for enable restriction...
D/BluetoothManagerService(  966): checkBTEasState, ret=true
I/BluetoothManagerService(  966): isBluetoothRestricted(): false
D/BluetoothManagerService(  966): enable(): region ID = 6
D/BluetoothManagerService(  966): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  966): MONITOR_LOG
W/Settings:Agent(  966): name: bluetooth_on
,W/Settings:Agent(  966): value: 1
W/Settings:Agent(  966): >> traceCallingStack()
W/Settings:Agent(  966): Process.myPid(): 966
W/Settings:Agent(  966): Process.myTid(): 1483
W/Settings:Agent(  966): Process.myUid(): 1000
,W/Settings:Agent(  966): 
W/Settings:Agent(  966): 
W/System.err(  966): java.lang.Throwable: stack dump
,W/System.err(  966): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  966): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  966): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  966): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  966): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  966): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  966): 
W/Settings:Agent(  966): << traceCallingStack(): 7(ms)
,D/BluetoothManagerService(  966): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  966): MESSAGE_ENABLE: mBluetooth = null
I/DropBoxManagerService(  966): Usage (1281) > Quota (1280)
,D/WifiManager( 6032): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  966): New client listening to asynchronous messages
,E/WifiTrafficPoller(  966): ADD_CLIENT: 7
D/WifiService(  966): setWifiEnabled: true pid=6032, uid=10366
,E/WifiService(  966): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  966): isSprintWifiRestricted(): false
,I/WifiService(  966): isMdmWifiRestricted(): false
W/Settings:Agent(  966): MONITOR_LOG
W/Settings:Agent(  966): name: wifi_on
,W/Settings:Agent(  966): value: 2
W/Settings:Agent(  966): >> traceCallingStack()
W/Settings:Agent(  966): Process.myPid(): 966
W/Settings:Agent(  966): Process.myTid(): 1157
W/Settings:Agent(  966): Process.myUid(): 1000
W/Settings:Agent(  966): 
W/Settings:Agent(  966): 
W/System.err(  966): java.lang.Throwable: stack dump
,I/ActivityManager(  966): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6086 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  966): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  966): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  966): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  966): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  966): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  966): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  966): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  966): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  966): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  966): 
W/Settings:Agent(  966): << traceCallingStack(): 13(ms)
,D/WifiManager( 6032): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  966): handleMessage: E msg.what=155656
,D/WifiController(  966): processMsg: ApStaDisabledState
D/WifiController(  966): transitionTo: destState=DeviceActiveState
D/WifiController(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): handleMessage: E msg.what=131145
D/WifiManager( 6032): reconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  966): processMsg: InitialState
,D/WifiController(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/PMS     (  966): acquireWL(1a05d1c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 966 1000 null
D/WifiController(  966): invokeExitMethods: ApStaDisabledState
D/WifiController(  966): moveTempStackToStateStack: i=1,j=1
D/WifiController(  966): moveTempStackToStateStack: i=0,j=2
D/WifiController(  966): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  966): invokeEnterMethods: StaEnabledState
,D/WifiController(  966): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  966): setting operational mode to 1
D/WifiController(  966): handleMessage: X
E/WifiStateMachine(  966):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131083
E/WifiStateMachine(  966): processMsg: InitialState
E/WifiStateMachine(  966):  InitialState CMD_START_SUPPLICANT 0 0
I/jxcore-log( 6032): Radios toggled
I/jxcore-log( 6032): 
,W/ResourcesManager( 6086): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 6086): Adding HeadsetService,
D/AdapterServiceConfig( 6086): Adding A2dpService
D/AdapterServiceConfig( 6086): Adding HidService
D/AdapterServiceConfig( 6086): Adding HealthService
D/AdapterServiceConfig( 6086): Adding PanService
D/AdapterServiceConfig( 6086): Adding GattService
,W/linker  ( 6086): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  966): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11017186:true
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55),
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapterState( 6086): make
,I/BluetoothAdapterState( 6086): Entering OffState
,E/bt_osi_config( 6086): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,D/BluetoothAdapterProperties( 6086): Address is:90:E7:C4:F6:69:77
,D/BluetoothManagerService(  966): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  966): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  966): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  966): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapter( 1215): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2cacb1e0
D/BluetoothAdapter( 1215): onBluetoothServiceUp done
D/BluetoothAdapter(  966): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2bf32012
D/BluetoothAdapter(  966): onBluetoothServiceUp done
,D/BluetoothAdapter( 1457): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1665fc6d
D/BluetoothAdapter( 1457): onBluetoothServiceUp done
D/BluetoothAdapter( 1813): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@12172538
,D/BluetoothAdapter( 1813): onBluetoothServiceUp done
D/BluetoothAdapter( 6086): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1fefbea
D/BluetoothAdapter( 6086): onBluetoothServiceUp done
,D/BluetoothAdapter( 1474): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@16673390
D/BluetoothAdapter( 1474): onBluetoothServiceUp done
D/BluetoothAdapter( 6032): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@262707d7
D/BluetoothAdapter( 6032): onBluetoothServiceUp done
,D/BluetoothAdapter( 3513): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1b33f8bc
D/BluetoothAdapter( 3513): onBluetoothServiceUp done
,D/BluetoothAdapter( 2397): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@37fb19cf
D/BluetoothAdapter( 2397): onBluetoothServiceUp done
D/BluetoothManagerService(  966): Broadcasting onBluetoothServiceUp() done
D/BluetoothAdapterState( 6086): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6086): Setting state to 11
I/BluetoothAdapterState( 6086): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  966): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  966): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  966): Bluetooth State Change Intent: 10 -> 11
I/IntentController( 1215): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 6086): make
V/BluetoothPbapReceiver( 6086): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 6086): ***********state = 11
,D/BluetoothAdapterService( 6086): checkA2dpState: isA2dpSinkEnabled = false
I/BluetoothBondStateMachine( 6086): StableState(): Entering Off State
E/BluetoothAdapterService( 6086): checkA2dpState: returning
D/BluetoothAdapterService( 6086): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6086): checkHfpState: returning
,D/NGFService( 3513): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothAdapterState( 6086): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothHeadset(  966): Proxy object connected
D/HeadsetService( 6086): Received start request. Starting profile...
D/BluetoothHeadset( 1215): Proxy object connected
D/BluetoothHeadset( 1457): Proxy object connected
,D/HeadsetStateMachine( 6086): Version 1.5
D/HeadsetStateMachine( 6086): make
,D/PMS     (  966): releaseWL(1a05d1c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/BluetoothHeadset( 1457): Proxy object connected
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
,D/BluetoothAdapter(  966): 1001733368: getState(). Returning 11
D/Tethering(  966): interfaceAdded wlan0
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  966): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6122 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a,
,V/Tethering(  966): TetherInterfaceSM: wlan0: enter InitialState
D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothHeadset( 1457): Proxy object connected
D/Tethering(  966): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  966): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  966): TetherInterfaceSM: wlan0: exit InitialState
,V/Tethering(  966): TetherInterfaceSM: wlan0: enter UnavailableState
D/PMS     (  966): acquireWL(145b280e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  966): interfaceAdded p2p0
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false,
D/Tethering(  966): p2p0 is not a tetherable iface, ignoring
D/Tethering(  966): interfaceLinkStateChanged p2p0, false
D/Tethering(  966): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  966): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothPhoneService( 1457): BluetoothHeadset onServiceConnected
D/HeadsetStateMachine( 6086): max_hf_connections = 2
D/PMS     (  966): releaseWL(145b280e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
V/NetworkPolicy(  966): updateNotificationsLocked()
D/PMS     (  966): acquireWL(1da5b71a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/QuickSettingMiniLite( 1215): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@16fa2c99
D/PMS     (  966): releaseWL(1da5b71a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/TetherSettings( 5503): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
D/        ( 5503): Cust_ConnectToPC   : Internet_Sharing>true
V/NetworkPolicy(  966): updateNotificationsLocked()
D/        ( 5503): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5503): Cust_ConnectToPC   : spcsc>false
D/        ( 5503): Cust_ConnectToPC   : IPT>true
D/        ( 5503): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5503): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BluetoothAdapter( 1457): 881078579: getState(). Returning 11
,E/SmartNS_Utility( 5503): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5503): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5503): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,D/HeadsetPhoneState( 6086): listenForPhoneState..for service and signal 
,I/QuickSettingBluetooth( 1215): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/HeadsetDualPhoneStateListener_SLOT1( 6086): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6086): listen phone state by slot:SLOT2  id:-100,
W/ContextImpl( 5503): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/HeadsetStateMachine( 6086): Enter Disconnected: -2, size: 0
,I/SmartNS_Utility( 5503): setISNotification
D/UsbDeviceManager(  966): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  966): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  966): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/SmartNS_Utility( 5503): usb_cable_connect = 1
,D/HeadsetDualPhoneStateListener_SLOT1( 6086): listen phone state by slot:SLOT1  id:-1
D/SmartNS_Utility( 5503): usb_denied = 0
D/BluetoothAdapterService( 6086): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a8abfde
I/SmartNS_PSService( 5503): usb notificaiton:true
D/HeadsetDualPhoneStateListener_SLOT2( 6086): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6086): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6086): BTHF: set_current_device
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothA2dp(  966): Proxy object connected
D/A2dpService( 6086): Received start request. Starting profile...
,V/Avrcp   ( 6086): make
D/BluetoothAdapter(  966): 1001733368: getState(). Returning 11
,I/ActionCombine( 5503): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/HtcBtWidget_BTWidgetProvider( 6122): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6122): updateWidget(context) for widget: 
,D/SmartNS_Utility( 5503): usb_cable_connect = 1
E/RemoteController( 6086): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 6086): make
D/SmartNS_Utility( 5503): usb_denied = 0
I/SmartNS_PSService( 5503): usb notificaiton:true
,E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/bt-btif ( 6086): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/RemoteViews( 1215): reapply : com.android.settings 1 36
,D/A2dpService( 6086): setA2dpService(): set to: null
D/BluetoothAdapterService( 6086): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a8abfde
D/A2dpStateMachine( 6086): Enter Disconnected: -2
,D/SmartNS_NSReceiver( 5503): Tethered state change:false isNSOpening:false
,D/TetherSettings( 5503): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5503): Cust_ConnectToPC   : Internet_Sharing>true
W/ContextImpl( 5503): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5503): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5503): Cust_ConnectToPC   : spcsc>false
D/        ( 5503): Cust_ConnectToPC   : IPT>true
D/        ( 5503): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5503): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5503): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5503): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5503): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,I/SmartNS_Utility( 5503): setISNotification
,D/SmartNS_Utility( 5503): usb_cable_connect = 1
D/SmartNS_Utility( 5503): usb_denied = 0
I/SmartNS_PSService( 5503): usb notificaiton:true
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_Utility( 5503): usb_cable_connect = 1
,D/SmartNS_Utility( 5503): usb_denied = 0
I/SmartNS_PSService( 5503): usb notificaiton:true
D/HidService( 6086): Received start request. Starting profile...
D/BluetoothAdapterService( 6086): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a8abfde
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
E/WifiStateMachine(  966): setWifiState: enabling
E/WifiStateMachine(  966): Supplicant start successful
D/WifiMonitor(  966): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  966): connecting to supplicant
D/HealthService( 6086): Received start request. Starting profile...
E/WifiHW  (  966): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
D/SmartNS_NSReceiver( 5503): Tethered state change:false isNSOpening:false
I/IntentController( 1215): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothAdapterService( 6086): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a8abfde
I/RemoteViews( 1215): reapply : com.android.settings 1 36
,D/PanService( 6086): Received start request. Starting profile...
D/WIFI_ICON( 1215): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/RemoteViews( 1215): reapply : com.android.settings 1 36
,D/PanService( 6086): HTC_CUSTOMIZATION_MHS_ENABLE = false
,D/BluetoothAdapterService( 6086): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a8abfde
I/ActivityManager(  966): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6153 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/Process (  966): killProcessQuiet, pid=5771
I/ActivityManager(  966): Killing 5771:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/BtGatt.DebugUtils( 6086): handleDebugAction() action=null
D/BtGatt.GattService( 6086): Received start request. Starting profile...
D/BtGatt.GattService( 6086): start()
D/BtGatt.AdvertiseManager( 6086): advertise manager created
D/BluetoothAdapter( 1215): 484523868: getState(). Returning 11
I/QuickSettingMiniLite( 1215): updateLiteState:no connect device!
,D/wpa_supplicant( 6149): wpa_supplicant v2.3-devel-5.0.2
,D/wpa_supplicant( 6149): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/wpa_supplicant( 6149): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 6149): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6149): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6149): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6149): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6149): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6149): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6149): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
,D/wpa_supplicant( 6149): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6149): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6149): update_config=1
D/wpa_supplicant( 6149): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6149): device_name='Android_608e'
D/wpa_supplicant( 6149): manufacturer='HTC'
D/wpa_supplicant( 6149): model_name='HTC_PHONE'
D/wpa_supplicant( 6149): model_number='1234'
D/wpa_supplicant( 6149): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6149): p2p_oper_reg_class=126
D/wpa_supplicant( 6149): p2p_oper_channel=149
,D/wpa_supplicant( 6149): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6149): persistent_reconnect=1
D/wpa_supplicant( 6149): key_mgmt_offload=1
,I/wpa_supplicant( 6149): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6149): nl80211: RFKILL status not available
D/wpa_supplicant( 6149): nl80211: Using driver-based roaming
D/wpa_supplicant( 6149): nl80211: TDLS supported
D/wpa_supplicant( 6149): nl80211: TDLS external setup
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6149): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6149): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6149): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6149): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6149): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6149): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a4f1cfd0
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=0104
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=040a
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=040b
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=040c
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=040d
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=090a
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=090b
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=090c
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=090d
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=0409506f9a09
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=7f506f9a09
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=0801
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=040e
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=06
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=0a07
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=0a11
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f1cfd0 match=0a1a
D/wpa_supplicant( 6149): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6149): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6149): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6149): htc_wext_command_init +
E/wpa_supplicant( 6149): htc_wext_command_init: ifname=p2p0, ignore
D/Tethering(  966): interfaceLinkStateChanged p2p0, false
D/Tethering(  966): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6149): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  966): interfaceLinkStateChanged p2p0, false
D/Tethering(  966): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingWifi( 1215): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
,I/ActivityManager(  966): Recipient 5771
,D/BluetoothAdapterService( 6086): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a8abfde
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1215): reapply : com.android.settings 3 36,
,D/BluetoothAdapter( 1457): 881078579: getState(). Returning 11
W/BluetoothHeadset( 1457): Proxy not attached to service
,D/BluetoothHeadset( 1457): java.lang.Throwable,
D/BluetoothHeadset( 1457): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1457): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1457): ,	,at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1457): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1457): 	at android.os.Handler.dispatchMessage(Handler.java:102),
D/BluetoothHeadset( 1457): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1457): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1457): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1457): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1457): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1457): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/HeadsetPhoneState( 6086): updateServiceState service = 0,roam = 0
,D/HeadsetPhoneState( 6086): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 6086): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 6086): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6086): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 6086): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bt-btu  ( 6086): btu_task pending for preload complete event
,E/bt_vendor( 6086): get_bt_soc_type: Failed to get soc type
,D/BluetoothMasReceiver( 6086): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 6086): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6086): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6086):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6086): startService = false
,D/AuthorizationBluetoothService( 1884): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/qcom-bluetooth( 6179): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,I/wpa_supplicant( 6149): wapi_supplicant_init: Init WAI packet p2p0,
D/wpa_supplicant( 6149):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6149):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6149):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6149): nl80211: Flush PMKIDs
D/wpa_supplicant( 6149): p2p0: State: DISCONNECTED -> INACTIVE
,D/HtcWiFiWidget_WiFiWidgetProvider( 6153): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6153): updateWidget(context) for widget: 
,D/Process (  966): killProcessQuiet, pid=5794
I/ActivityManager(  966): Killing 5794:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/qcom-bluetooth( 6185): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6186): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 6188): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6189): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
I/qcom-bluetooth( 6190): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/wpa_supplicant( 6149): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6149): TDLS: Driver uses external link setup
D/wpa_supplicant( 6149): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
I/qcom-bluetooth( 6191): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/wpa_supplicant( 6149): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 6149): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6149): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6149): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6149): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6149): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6149): Using existing control interface directory.
D/wpa_supplicant( 6149): P2P: Add operating class 81
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6149): P2P: Own listen channel: 81:6
D/wpa_supplicant( 6149): P2P: Configured operating channel: 126:149
D/wpa_supplicant( 6149): P2P: initialized
D/wpa_supplicant( 6149): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6149): P2P: cli_channels:
D/wpa_supplicant( 6149): p2p0: Added interface p2p0
D/wpa_supplicant( 6149): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6149): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6149): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6149): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6149): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6149): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6149): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6149): disable_scan_offload=1
D/wpa_supplicant( 6149): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6149): update_config=1
D/wpa_supplicant( 6149): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6149): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6149): manufacturer='HTC'
D/wpa_supplicant( 6149): model_name='HTC One M8s'
D/wpa_supplicant( 6149): model_number='HTC One M8s'
D/wpa_supplicant( 6149): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6149): hs20=1
D/wpa_supplicant( 6149): interworking=1
D/wpa_supplicant( 6149): external_sim=1
D/wpa_supplicant( 6149): key_mgmt_offload=1
,I/ActivityManager(  966): Recipient 5794
,D/wpa_supplicant( 6149): Priority group 187,
D/wpa_supplicant( 6149):    id=0 ssid='NG700'
I/wpa_supplicant( 6149): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6149): nl80211: RFKILL status not available
D/wpa_supplicant( 6149): nl80211: Using driver-based roaming
D/wpa_supplicant( 6149): nl80211: TDLS supported
D/wpa_supplicant( 6149): nl80211: TDLS external setup
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6149): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6149): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0,
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6149): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6149): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6149): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6149): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6149): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6149): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6149): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6149): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6149): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a4f3c100
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=0104
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=040a
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=040b
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=040c
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=040d
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=090a
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=090b
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=090c
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=090d
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=0409506f9a09
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=7f506f9a09
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=0801
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=040e
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=06
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=0a07
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=0a11
D/wpa_supplicant( 6149): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a4f3c100 match=0a1a
D/wpa_supplicant( 6149): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6149): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6149): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6149): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6149): htc_wext_command_init +
I/wpa_supplicant( 6149): htc_wext_command_init -
I/wpa_supplicant( 6149): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6149): Don't set 00 to countryID.conf
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6149): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6149): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/Tethering(  966): interfaceLinkStateChanged wlan0, false
D/Tethering(  966): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6149): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6149): P2P: Add operating class 81
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6149): P2P: Update channel list
D/wpa_supplicant( 6149): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6149): P2P: cli_channels:
D/wpa_supplicant( 6149): p2p0: Updating hw mode
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6149): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6149): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6149): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
,I/wpa_supplicant( 6149): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 6149):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
,D/wpa_supplicant( 6149):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6149):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6149): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6149): nl80211: Flush PMKIDs
,D/wpa_supplicant( 6149): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 6149): TDLS: Driver uses external link setup
D/wpa_supplicant( 6149): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6149): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6149): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6149): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6149): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6149): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6149): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6149): Using existing control interface directory.
,I/wpa_supplicant( 6149): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6149): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6149): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6149): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6149): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6149): P2P: Add operating class 81
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6149): P2P: Add operating class 115
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6149): P2P: Add operating class 116
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6149): P2P: Add operating class 117
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6149): P2P: Update channel list
D/wpa_supplicant( 6149): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6149): P2P: cli_channels:
D/wpa_supplicant( 6149): p2p0: Updating hw mode
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6149): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6149): Auto country group 1: ch36
D/wpa_supplicant( 6149): wlan0: Added interface wlan0
D/wpa_supplicant( 6149): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6149): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6149): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6149): random: Got 20/20 bytes from /dev/random
,I/qcom-bluetooth( 6194): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,D/wpa_supplicant( 6149): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6149): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6149): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6149): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6149): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6149): nl80211: Regulatory domain change
D/wpa_supplicant( 6149):  * initiator=1
D/wpa_supplicant( 6149):  * type=0
D/wpa_supplicant( 6149):  * alpha2=DE
D/wpa_supplicant( 6149): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6149): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6149): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6149): P2P: Add operating class 81
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6149): P2P: Add operating class 115
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6149): P2P: Add operating class 116
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6149): P2P: Add operating class 117
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6149): P2P: Update channel list
D/wpa_supplicant( 6149): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6149): P2P: cli_channels:
D/wpa_supplicant( 6149): p2p0: Updating hw mode
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6149): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
,I/qcom-bluetooth( 6195): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 6086): btu_task received preload complete event,
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/PMS     (  966): acquireWL(3574551f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6086 1002 null
,D/bt-btm  ( 6086): btm_acl_device_down
D/bt-btm  ( 6086): btm_acl_reset_paging
D/bt-btm  ( 6086): btm_acl_set_discing
,I/bt-btm  ( 6086): btm_reset_complete,
I/bt-btm  ( 6086): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 6086): Start reading local supported commands,
,D/bt-btm  ( 6086): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 6086): BTM reads next extended features page (1)
,D/bt-btm  ( 6086): BTM reads next extended features page (2)
,D/bt-btm  ( 6086): BTM reached last extended features page (2)
D/bt-btm  ( 6086): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f,
,D/bt-btm  ( 6086): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,D/bt-btm  ( 6086): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
,I/bt-btm  ( 6086): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 6086): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11,
I/bt-btm  ( 6086): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 6086): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01,
,D/bt-btm  ( 6086): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00,
D/bt-btm  ( 6086): btm_read_ble_wl_size 
,D/bt-btm  ( 6086): btm_read_white_list_size_complete 
D/bt-btm  ( 6086): btm_get_ble_buffer_size 
,D/bt-btm  ( 6086): btm_read_ble_buf_size_complete 
,D/bt-btm  ( 6086): btm_read_ble_local_supported_states 
,D/bt-btm  ( 6086): btm_read_ble_local_supported_states_complete 
,D/bt-btm  ( 6086): btm_read_ble_local_supported_features 
,D/bt-btm  ( 6086): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 6086): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6086): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6086): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6086): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6086): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6086): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6086): BTM_SetInquiryMode
I/bt-btm  ( 6086): BTM_SetPageScanType
I/bt-btm  ( 6086): BTM_SetInquiryScanType
D/bt-btm  ( 6086): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6086): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6086): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6086): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6086): BTM_BleLoadLocalKeys
D/bt-btm  ( 6086): BTM_BleLoadLocalKeys
I/bt-btm  ( 6086): BTM_Sec: application registered
E/bt-btm  ( 6086): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf3cb4d5 
I/bt-btm  ( 6086): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6086): SMP_Register state=0
E/bt-btm  ( 6086): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf3cb4d5 
I/bt-btm  ( 6086): BTM_Sec: application registered
D/bt-btm  ( 6086): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6086): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6086): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6086): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007),
D/bt-btm  ( 6086): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6086): BTM_RegBusyLevelNotif
D/bt-btm  ( 6086): BTM_BleReadControllerFeatures
I/bt-btm  ( 6086): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6086): GATT_Register
D/bt-att  ( 6086): UUID=[0x87878787878787878787878787878787],
I/bt-att  ( 6086): allocated gatt_if=3
I/bt-att  ( 6086): GATT_StartIf gatt_if=3
D/bt-att  ( 6086): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 6086): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 6086): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 6086): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6086): BTM Register For VSEvents is successfully
D/bt-btm  ( 6086): BTM_BleGetVendorCapabilities
,I/bt-btif ( 6086): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6086): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 6086): Calling BTA_HhEnable
,D/bt-btm  ( 6086): bta_dm_set_dev_name: name: HTC One M8s 
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btm  ( 6086):  BTM_BleConfigPrivacy
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 6086): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6086): BTM_AllocateSCN
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6086): BTM_AllocateSCN
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btm  ( 6086): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6086):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6086):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6086): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6086): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6086):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6086):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6086): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6086): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 6086): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6086): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
D/bt-btif ( 6086):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6086): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): BTA_MceEnable
I/bt-btm  ( 6086): BTM_SEC_REG[8]: id ,32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6086):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6086):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6086):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6086): GATT_Register
D/bt-att  ( 6086): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6086): allocated gatt_if=4
I/bt-att  ( 6086): GATT_StartIf gatt_if=4
D/bt-att  ( 6086): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6086): gatt_find_the_connected_bda found=0 found_idx=16
E/bt-btif ( 6086): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 6086): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6086): Address is:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 6086): Scan Mode:21
D/BluetoothAdapterProperties( 6086): Discoverable Timeout:120
I/bt-btif ( 6086): BTA_JvEnable
I/bt-btif ( 6086): BTA_JvRegisterL2cCback
I/bt-btm  ( 6086): BTM_ReadConnectability
I/bt-btm  ( 6086): BTM_ReadDiscoverability
I/bt-btm  ( 6086): BTM_SetDiscoverability
I/bt-btm  ( 6086): btm_ble_set_discoverability mode=0x0 combined_mode=0x2,
D/bt-btm  ( 6086): disc_mode 0002
D/bt-btm  ( 6086): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): evt_type=0x0 p-cb->evt_type=0x3 
,I/bt-btm  ( 6086): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6086): BTM_SetConnectability
I/bt-btm  ( 6086): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6086): disc_mode 0002
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
,I/bt-btm  ( 6086): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6086): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6086): BTM_SetDiscoverability
I/bt-btm  ( 6086): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 6086): disc_mode 0000
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6086): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6086): BTM_SetConnectability
I/bt-btm  ( 6086): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6086): disc_mode 0000
,D/bt-btm  ( 6086): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6086): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
I/bt-btm  ( 6086): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6086): bta_pan_co_init
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6086): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6086):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6086):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btm  ( 6086): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6086):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6086): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6086):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 87 d2 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = af 92 eb 46 1a 83 57 b5 6e cc 62 18 f5 45 4a 88 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 6086): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6086): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6086): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6086): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6086): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 6086): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6086): ScanMode =  21
D/BluetoothAdapterProperties( 6086): State =  11
D/BluetoothAdapterProperties( 6086): Setting state to 12
I/BluetoothAdapterState( 6086): Bluetooth adapter state changed: 11-> 12
I/bt-btif ( 6086): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6086): Discoverable Timeout:120
D/BluetoothManagerService(  966): +onBluetoothStateChange prev=11 new=12
I/BluetoothAdapterState( 6086): Entering On State
D/BluetoothManagerService(  966): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  966): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp(  966): onBluetoothStateChange: up=true
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = e1 28 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = c3 ef bb af e2 e2 c8 2e f8 f3 bb 72 86 f3 ac fd 
D/BluetoothHeadset( 1215): onBluetoothStateChange: up=true
E/bt_mct  ( 6086): hci lib postload completed
D/BluetoothHeadset( 1457): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1457): onBluetoothSta,teChange: up=true
D/BluetoothHeadset(  966): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1457): onBluetoothStateChange: up=true
D/BluetoothManagerService(  966): Bluetooth State Change Intent: 11 -> 12
I/IntentController( 1215): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
D/NGFService( 3513): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3513): Bluetooth Adapter: ON
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
,W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 73 86 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 6c 76 d2 1e 46 91 b6 26 14 9c f8 40 35 2c 6b a2 
,D/BluetoothManagerService(  966): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,V/BluetoothPbapReceiver( 6086): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6086): ***********state = 12
,D/BluetoothManagerService(  966): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  966): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
,D/PMS     (  966): acquireWL(30ea1aca): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5503 1000 null
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
W/ContextImpl( 5503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = c5 64 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = cd 45 4e 29 2d ef a7 7e e7 ee ea 44 d7 67 af f9 
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 61 d1 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 34 f9 09 7b 34 24 19 eb e6 34 66 68 1d 6b 2f 3c 
,V/BluetoothPbapService( 6086): Pbap Service onCreate
V/BluetoothPbapService( 6086): Starting PBAP service
D/BluetoothAdapter( 6086): 175097816: getState(). Returning 12
V/BluetoothPbapService( 6086): Handler(): got msg=1
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
V/BluetoothPbapService( 6086): Pbap Service startRfcommSocketListener
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 77 66 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 80 1d 73 31 ff 3d 82 68 8c 26 80 e8 7a 27 16 5d 
,V/BluetoothPbapService( 6086): Pbap Service initSocket
D/PMS     (  966): releaseWL(30ea1aca): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6122): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 6122): updateWidget(context) for widget: 
,D/PMS     (  966): acquireWL(3fd29758): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5503 1000 null
,D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = fb 30 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = c5 00 7b 6f d1 e7 07 6d 3e 31 2e 4d 67 47 29 a0 
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/wpa_supplicant( 6149): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
,D/Tethering(  966): interfaceLinkStateChanged p2p0, false
D/Tethering(  966): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  966): WiFiDisplay: getWifidisplayApEnabled=false
,W/System.err(  966): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1405c917:true
W/BluetoothAdapter( 6086): getBluetoothService() called with no BluetoothManagerCallback
W/System.err(  966): 	at java.lang.Thread.dumpStack(Thread.java:490)
,W/System.err(  966): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  966): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
,I/bt-btm  ( 6086): BTM_SetDiscoverability
I/bt-btm  ( 6086): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6086): disc_mode 0000
I/bt-btm  ( 6086): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6086): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6086): BTM_SetConnectability
I/bt-btm  ( 6086): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6086): disc_mode 0000
D/bt-btm  ( 6086): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6086): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6086): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6086): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 6086): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): BTA_JvRfcommStartServer
I/bt-btm  ( 6086): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6086):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6086): Succeed to create listening socket 
V/BluetoothPbapService( 6086): Accepting socket connection...
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data,
,W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = e8 46 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = eb bf a1 aa b0 fe 06 f2 ae ed 28 04 e1 10 ca 6e 
D/BluetoothAdapterProperties( 6086): Scan Mode:21
,D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 6e 85 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 12 fb d5 7e 43 5c 03 2f 8c 92 4f 96 5d b8 a1 23 
D/BluetoothAdapter( 1215): 484523868: getState(). Returning 12
,D/BluetoothAdapter( 1215): 484523868: getState(). Returning 12
,D/bt-btm  ( 6086): btm_ble_rand_enc_complete
,I/bt-btm  ( 6086): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 45 29 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 27 b3 49 ee ae 04 c7 49 16 3d f4 76 e9 30 af 78 
,I/QuickSettingBluetooth( 1215): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1215): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothAdapter( 5503): 10288662: getState(). Returning 12
,D/BluetoothInputDevice( 5503): BluetoothInputDevice()
,D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 7
,D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = eb 3a 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 2f 29 40 7a 55 46 6c e7 55 98 e6 29 82 47 5b 3e 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
D/BluetoothPan( 5503): BluetoothPan()
,D/BluetoothManagerService(  966): registerStateChangeCallback+
,D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 8
,D/BluetoothMap( 5503): Create BluetoothMap proxy object
,D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 9
,E/BluetoothMap( 5503): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 10
D/BluetoothSap( 5503): BluetoothSap() call bindService
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = cc eb 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 46 45 c5 9d af 45 45 14 8c 0b 73 65 a1 72 39 bf 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
W/ContextImpl( 5503): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5503): BluetoothPbap()
D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  966): Registered receivers: 11
,D/BluetoothManagerService(  966): registerStateChangeCallback+,
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 6f 4a 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 2d cf 89 77 c9 08 56 77 67 0d 45 98 7f 35 bb 23 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  966): Registered receivers: 12
,D/BluetoothHeadset( 5503): BluetoothHeadset()
,D/BluetoothManagerService(  966): registerStateChangeCallback+
D/BluetoothManagerService(  966): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  966): Registered receivers: 13
,D/LocalBluetoothProfileManager( 5503): LocalBluetoothProfileManager construction complete,
D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 97 bf 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = b9 b1 24 21 23 fe fe df fe 65 b7 0f d6 8e 48 28 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
,D/DockEventReceiver( 5503): finishStartingService: stopping service
D/BluetoothA2dp( 5503): Proxy object connected
,D/A2dpProfile( 5503): Bluetooth service connected
D/BluetoothAdapter( 5503): 10288662: getState(). Returning 12
,D/BluetoothHeadset( 5503): Proxy object connected,
V/BluetoothPbapService( 6086): Pbap Service onBind
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HeadsetProfile( 5503): Bluetooth service connected
D/BluetoothAdapter( 5503): 10288662: getState(). Returning 12
W/BluetoothAdapter( 6086): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6086): BTA_JvCreateRecordByUser
D/BluetoothInputDevice( 5503): Proxy object connected
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
,I/bt-btif ( 6086): BTA_JvRfcommStartServer
I/bt-btm  ( 6086): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6086):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6086): Accept thread started.
D/HidProfile( 5503): Bluetooth service connected
,D/BluetoothAdapter( 5503): 10288662: getState(). Returning 12
,D/PMS     (  966): releaseWL(3fd29758): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothPan( 5503): BluetoothPAN Proxy object connected
D/PanProfile( 5503): Bluetooth service connected
D/BluetoothPbap( 5503): Proxy object connected
D/PbapServerProfile( 5503): Bluetooth service connected
,D/BluetoothAdapter( 6086): 175097816: getState(). Returning 12
D/BluetoothFtpService( 6086): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 6086): Bluetooth STATE CHANGED to 12
,D/BluetoothMasReceiver( 6086):  call MAP start service
,D/BluetoothFtpService( 6086): htc sense version is 6.0
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6086): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6086): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): BTA_JvRfcommStartServer
I/bt-btm  ( 6086): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6086):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6086): Run Accept thread
,E/BluetoothMasService( 6086): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 6086): Add permission for SmsProvider.
,V/BluetoothMasService( 6086): Starting MAS instances
D/BluetoothAdapter( 6086): 175097816: getState(). Returning 12
,I/MailMessageReceiver( 6086): reg:com.android.bluetooth.btservice.AdapterApp@14ad7b69 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@5adb9ee
,I/MailManager( 6086): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@5adb9ee
V/EmailUtils( 6086): Manager Instance is not NULL
,I/ActivityManager(  966): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6212 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/wpa_supplicant( 6149): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_966-3\x00
E/WifiStateMachine(  966): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  966): invokeExitMethods: InitialState
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  966): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131144
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  966): deferMessage: msg=131144
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131085
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  966): deferMessage: msg=131085
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131149
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  966): setSuspendOptimizations: 2 true
E/WifiStateMachine(  966): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131146
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131101
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  966): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131101
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  966): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=147457
E/WifiStateMachine(  966): processMsg: SupplicantStartingState
E/WifiStateMachine(  966):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  966): Supplicant connection established
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6149): set wifi ON
,E/WifiStateMachine(  966): setWifiState: enabled
E/WifiStateMachine(  966): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  966):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6149): SET_SCREEN_ON:Off
I/wpa_supplicant( 6149): htc_wext_set_keepalive +
I/wpa_supplicant( 6149): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6149): getPrivFuncNum +	
I/wpa_supplicant( 6149): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6149): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6149): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6149): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6149): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6149): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  966): startHal
,E/wifi    (  966): getStaticLongField sWifiHalHandle 0x7f6ef34300
I/WifiNative-HAL(  966): Could not start hal
,E/WifiStateMachine(  966): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  966): backgroundScan enabled=true startBackgroundScanIfNeeded:false
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
E/WifiStateMachine(  966): handleScreenStateChanged Exit: false
I/IntentController( 1215): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER MACADDR'
D/HtcWiFiWidget_WiFiWidgetProvider( 6153): onWiFiStateChanged() for widget: 
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/WIFI_ICON( 1215): updateWifiState: WIFI_STATE_CHANGED enabled
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET update_config 1'
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 6149): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6149): update_config=1
D/wpa_supplicant( 6149): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  966): Loading config and enabling all networks 
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6149): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6149): wpa_supplicant_ctrl_iface_list_networks: return size = 47
D/HtcWiFiWidget_WiFiWidgetProvider( 6153): updateWidget(context) for widget: 
,W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6149): Do not allow key_data field to be exposed
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplic,ant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6149): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6149): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  966): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6149): device_name='m8qlul_htc_europe'
,W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6149): manufacturer='HTC'
,W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6149): model_name='HTC One M8s'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
,D/wpa_supplicant( 6149): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6149): model_number='HTC One M8s'
,W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6149): config_methods='physical_display virtual_push_button'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  966): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  966): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  966): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6149): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  966): Setting external_sim to 1
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6149): external_sim=1
W/Settings( 5326): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiP2pService(  966): P2pDisabledState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  966): DefaultState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  966): Setting OUI to DA-A1-19
I/WifiNative-HAL(  966): startHal
E/wifi    (  966): getStaticLongField sWifiHalHandle 0x7f6ef34360
I/WifiNative-HAL(  966): Could not start hal
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
,D/wpa_supplicant( 6149): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  966): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  966): Driverstarted State enter
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  966): DriverStartedState call setCountryCode()
E/WifiStateMachine(  966): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
D/HtcAdjCursorFactory( 6212): Set CursorWindow size to: 4194304 KB, Tid: 6231
E/WifiStateMachine(  966): NetworkAgent == null
E/WifiStateMachine(  966): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
E/WifiTrafficPoller(  966): ENABLE_TRAFFIC_STATS_POLL false Token 0
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
,D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  966): setDhcpActive: false
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6149): wlan0: Control interface command 'STATUS'
,D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  966): transitionTo: destState=DisconnectedState
D/WifiP2pService(  966): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/native  (  966): do suspend false
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/HTCRequest(  966): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  966): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6149): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  966): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,E/WifiStateMachine(  966): Driverstarted State enter done
E/WifiStateMachine(  966): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  966): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  966): handleMessage: new destination call exit/enter
E/WifiStateMachine(  966): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  966): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  966): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  966): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  966): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  966): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  966): DisconnectedState call setCountryCode()
D/WifiScanningService(  966): SCAN_AVAILABLE : 3
D/RttService(  966): SCAN_AVAILABLE : 3
E/WifiStateMachine(  966):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/libc    (  966): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiScanningService(  966): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  966): startHal
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/RttService(  966): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6149): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6149): wlan0: nl80211: sched_scan request
,I/QuickSettingWifi( 1215): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
,D/WISPrService( 5503): >>>>>WISPrService start isConnected = false<<<<<,
,D/WifiService(  966): New client listening to asynchronous messages
,E/WifiTrafficPoller(  966): ADD_CLIENT: 8
,D/EmailUtils( 6086): ============NULL aList========
V/EmailUtils( 6086): <-getEmailAccountIdList
D/WISPrService( 5503): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothMasService( 6086): onCreate: mIsEmailEnabled: true
D/wpa_supplicant( 6149): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6149): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6149): wlan0: nl80211: Sched scan started
D/WifiP2pService(  966): P2pEnablingState,
E/wifi    (  966): getStaticLongField sWifiHalHandle 0x7f6cc9e520
I/WifiNative-HAL(  966): Could not start hal
E/WifiScanningService(  966): could not start HAL
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131144
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131085
E/WifiStateMachine(  966): processMsg: DisconnectedState
,D/WifiP2pService(  966): P2pEnablingState{ when=-3ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  966):  DisconnectedState CMD_START_DRIVER 0 0
D/WifiP2pService(  966): P2p socket connection successful
E/WifiStateMachine(  966): processMsg: ConnectModeState
,D/WifiP2pService(  966): P2pEnabledState
,D/WifiMonitor(  966): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  966): sending p2p connection changed broadcast
E/WifiStateMachine(  966):  ConnectModeState CMD_START_DRIVER 0 0
D/WifiDisplayController(  966): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
E/WifiStateMachine(  966): processMsg: DriverStartedState
D/WifiDisplayAdapter(  966): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  966):     Client/Owner: Client
D/WifiDisplayAdapter(  966):     GroupId: 
D/WifiDisplayAdapter(  966):     Passphrase: 
D/WifiDisplayAdapter(  966):     SessionId: 0
D/WifiDisplayAdapter(  966):     IP Address: }
E/WifiStateMachine(  966):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131154
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
D/BluetoothAdapter( 6086): 175097816: getState(). Returning 12
E/WifiStateMachine(  966):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
V/BluetoothMasService( 6086): parseIntent 1: mIsEmailEnabled: true
E/WifiStateMachine(  966): processMsg: DefaultState
V/EmailUtils( 6086): Manager Instance is not NULL
E/WifiStateMachine(  966):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131323
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState what:131323 0 0
E/WifiStateMachine(  966): setOperatorSSID enter
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131104
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState what:131104 0 0
W/Settings(  966): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6149): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6149): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6149): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=131162
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  966): set frequency band 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6149): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6149):, SETBAND: 0
D/wpa_supplicant( 6149): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6149): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6149): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6149): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6149): P2P: Add operating class 81
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6149): P2P: Add operating class 115
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6149): P2P: Add operating class 116
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6149): P2P: Add operating class 117
D/wpa_supplicant( 6149): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6149): P2P: Update channel list
D/wpa_supplicant( 6149): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6149): P2P: cli_channels:
D/wpa_supplicant( 6149): p2p0: Updating hw mode
D/WifiDisplayController(  966): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/wpa_supplicant( 6149): nl80211: Regulatory information - country=DE
D/WifiDisplayController(  966): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 6149): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6149): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6149): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6149): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  966): did set frequency band 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6149): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  966): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/WifiMonitor(  966): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  966): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6149): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6149): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6149): wlan0: Cancelling sched scan
E/WifiMonitor(  966): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  966): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6149): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6149): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6149): wpa_supplicant_scan enter
D/wpa_supplicant( 6149): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6149): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6149): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6149): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  966): done set frequency band 0
W/WifiHW  (  966): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6149): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6149): p2p0: Contr,ol interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6149): persistent_reconnect=1
D/wpa_supplicant( 6149): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6149): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6149): P2P: Set Operating channel: reg_class 126 channel 149
V/AudioService(  966): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  966):     Client/Owner: Client
V/AudioService(  966):     GroupId: 
V/AudioService(  966):     Passphrase: 
V/AudioService(  966):     SessionId: 0
V/AudioService(  966):     IP Address: }
D/HtcEffectManagerBase(  966): onEventChanged id=5 status=false
D/HtcEffectManager(  966): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  966): convertEffect before=902
D/HtcEffectManager(  966): convertEffect after=902
W/WifiHW  (  966): QCOM Debug wifi_send_command "SET device_name Android_608e"
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6149): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6149): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6149): device_name='Android_608e'
W/WifiHW  (  966): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6149): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6149): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/EmailUtils( 6086): ============NULL aList========
D/wpa_supplicant( 6149): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
V/EmailUtils( 6086): <-getEmailAccountIdList
D/WifiP2pService(  966): DeviceAddress: 92:e7:c4:e6:4c:f8
D/wpa_supplicant( 6149): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6149): P2P: New SSID postfix: -Android_608e
W/WifiHW  (  966): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
V/BluetoothSapReceiver( 6086): SapReceiver onReceive 
V/BluetoothSapReceiver( 6086): action = android.bluetooth.adapter.action.STATE_CHANGED
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6149): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6149): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'device_type'='10-0050F204-5'
V/BluetoothSapReceiver( 6086):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6086): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
W/WifiHW  (  966): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6149): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6149): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6149): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6149): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  966): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6149): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/WifiDisplayController(  966): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  966):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  966):  primary type: 10-0050F204-5
D/WifiDisplayController(  966):  secondary type: null
D/WifiDisplayController(  966):  wps: 0
D/WifiDisplayController(  966):  grpcapab: 0
D/WifiDisplayController(  966):  devcapab: 0
D/WifiDisplayController(  966):  status: 3
D/WifiDisplayController(  966):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  966):  WFD CtrlPort: 0
D/WifiDisplayController(  966):  WFD MaxThroughput: 0
I/wpa_supplicant( 6149): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6149): Single channel concurrency preference: sta
D/WifiNative-HAL(  966): p2pGetDeviceAddress
W/WifiHW  (  966): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  966): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
W/WifiHW  (  966): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 6149): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6149): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6149): P2P: Stopping find
D/wpa_supplicant( 6149): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6149): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6149): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6149): P2P: Stopping find
D/wpa_supplicant( 6149): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6149): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6149): wpa_driver_set_ap_wps_p2p_ie: Entry
V/BluetoothMasService( 6086): handleMessage: mIsEmailEnabledtrue
W/WifiHW  (  966): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6149): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6149): [p2p command] (P2P_SERVICE_FLUSH)
V/BtMns   ( 6086): BluetoothMns: isEmailEnabled: true
W/WifiHW  (  966): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6149): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6149): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  966): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 6149): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6149): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/AuthorizationBluetoothService( 1884): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6086): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6086): BTA_JvCreateRecordByUser
D/bt-btm  ( 6086): BTM_AllocateSCN
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): BTA_JvRfcommStartServer
I/bt-btm  ( 6086): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6086):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6086): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6086): BTA_JvCreateRecordByUser
D/bt-btm  ( 6086): BTM_AllocateSCN
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): BTA_JvRfcommStartServer
I/bt-btm  ( 6086): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6086):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:14
I/ActivityManager(  966): Killing 4730:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  966): killProcessQuiet, pid=4730
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
D/wpa_supplicant( 6149): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6149): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6149): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6149): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6149): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  966): sending p2p persistent groups changed broadcast
D/WifiStateMachine(  966): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiStateMachine(  966): Wifi band: 0, ScanBroadCastCounter: 0
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=147462
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=127613  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  966): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  966): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=127613  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  966): handleMessage: X
E/WifiStateMachine(  966): handleMessage: E msg.what=143371
E/WifiStateMachine(  966): processMsg: DisconnectedState
E/WifiStateMachine(  966):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  966): processMsg: ConnectModeState
E/WifiStateMachine(  966):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  966): processMsg: DriverStartedState
E/WifiStateMachine(  966):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  966): processMsg: SupplicantStartedState
E/WifiStateMachine(  966):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  966): processMsg: DefaultState
E/WifiStateMachine(  966):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  966): handleMessage: X
,I/ActivityManager(  966): Recipient 4730
,D/WifiP2pService(  966): InactiveState
,V/BluetoothSapService( 6086): Sap Service onCreate,
V/BluetoothSapService( 6086): initBinder
V/BluetoothSapService( 6086): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@8996525
V/BluetoothSapService( 6086): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@2d08d4ab
,V/BluetoothSapService( 6086): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6086): state: 12
D/SapServerProfile( 5503): Bluetooth service connected
,V/BluetoothSapService( 6086): Starting SAP server process
,V/BluetoothSapService( 6086): SAP Service startRfcommListenerThread,
,V/BluetoothSapService( 6086): Sap Service initRfcommSocket
D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6086): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6086): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6086): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6086): Write Extended Inquiry Response to controller
I/bt-btif ( 6086): BTA_JvRfcommStartServer
I/bt-btm  ( 6086): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
,I/bt-btm  ( 6086):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6086): Succeed to create listening socket 
V/BluetoothSapService( 6086): Accepting socket connection...
,D/A2dpService( 6086): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@6a02ea1,
D/A2dpSinkService( 6086): getA2dpSinkService(): service is NULL
,D/wpa_supplicant( 6149): EAPOL: disable timer tick,
,D/wpa_supplicant( 6149): EAPOL: disable timer tick,
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6032): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): my name is : HTC-HTC One M8s_PT2956
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): attempting to connect to test coordinator,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): check test folder,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): found test : ./testFindPeers.js,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): found test : ./testReConnect.js,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): found test : ./testSendData.js,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): Test app app.js loaded,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/chromium( 6032): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,D/PMS     (  966): releaseWL(3574551f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,D/BluetoothAdapter( 6032): 78402700: getState(). Returning 12,
,I/jxcore-log( 6032): BLE supported!!
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,D/GpsLocationProvider(  966): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  966): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  966): acquireWL(a7375ef): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{10024},
V/AlarmManager(  966): sending alarm PendingIntent{6f238fc: PendingIntentRecord{38bb43ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=133234, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{11673b85: PendingIntentRecord{2af50dda com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141101, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{1c8d1a8d: PendingIntentRecord{3c397442 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145260, Int=0
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  966): acquireWL(52b820b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  966): [NET] android_getaddrinfofornet-, err=8
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/PMS     (  966): releaseWL(a7375ef): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  966): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  966): [NET] android_getaddrinfo_proxy+
D/libc    (  966): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    (  966): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  966): releaseWL(52b820b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(14a7e8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(14a7e8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  966): updateBatteryInfo
D/NotificationService(  966): plugged=true pluggin=true
D/PMS     (  966): runPSCheck
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): Checking...
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  966): >> updateStatus
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  966): << updateStatus
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6032): 
,D/TelephonyReceiver( 1457): switchBindHtcMsgCursor: null,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
D/HtcAppUPService( 1422): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@12ec1238
,D/Process (  966): killProcessQuiet, pid=5826
I/ActivityManager(  966): Killing 5826:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5826
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(3fe50b01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  966): releaseWL(3fe50b01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/PMS     (  966): runPSCheck
D/WifiController(  966): handleMessage: E msg.what=155652
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: DeviceActiveState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: StaEnabledState
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(1a62da6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
,V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=174600, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{1c8d1a8d: PendingIntentRecord{3c397442 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=205287, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{a0e33e7: PendingIntentRecord{2786ab94 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=206300, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{2516563d: PendingIntentRecord{8f77e32 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185447, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{6802783: PendingIntentRecord{38bb43ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=241210, Int=0
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  966): [NET] android_getaddrinfofornet-, err=8
D/libc    (  966): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  966): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  966): [NET] android_getaddrinfo_proxy+
D/libc    (  966): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    (  966): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  966): acquireWL(22eced00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): releaseWL(22eced00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(1d171939): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/WeatherUtility( 1215): Weather sync is On
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  966): releaseWL(1a62da6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  966): releaseWL(1d171939): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  966): Explicit concurrent mark sweep GC freed 28769(1496KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.863ms total 199.380ms
,I/art     ( 1884): Explicit concurrent mark sweep GC freed 17094(959KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 1.210ms total 96.714ms,
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1215): reapply : com.google.android.gms 2 40,
W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5527): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5527): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5527): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5527): Ignoring header User-Agent because its value was null.,
,D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5527): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5527): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5527): [NET] android_getaddrinfo_proxy+
D/libc    ( 5527): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5527): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(2409f773): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
,V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=294600, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{1793c2a9: PendingIntentRecord{6ef902e com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448520825674, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{238297cf: PendingIntentRecord{38bb43ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=433112, Int=0
D/PMS     (  966): acquireWL(21f5e55c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  966): releaseWL(2409f773): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  966): releaseWL(21f5e55c): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): acquireWL(22bce065): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  966): n_update end
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): releaseWL(22bce065): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,W/Atfwd_Sendcmd(  421): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/ContactMessageStore( 1457): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1457): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1457): sku_id=118,
,D/ContactMessageStore( 1457): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1457): start background delete task...
,D/ContactMessageStore( 1457): size: 0 , 0,
D/ContactMessageStore( 1457): Background delete complete
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(9e8813a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(9e8813a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
,D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
,D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5527): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5527): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5527): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5527): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
,D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5527): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5527): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5527): [NET] android_getaddrinfo_proxy+
D/libc    ( 5527): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5527): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  966): acquireWL(34ab5d8c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  966): n_update end
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): releaseWL(34ab5d8c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): handleMessage: E msg.what=155652
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(9bfacd5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(9bfacd5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DeviceActiveState
,D/HtcPowerSaver(  966): updateBatteryInfo
D/WifiController(  966): processMsg: StaEnabledState
D/PMS     (  966): runPSCheck
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: X
D/PowerUI ( 1215): closing low battery warning: level=100
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(f03acea): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=474599, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{34ab9cdb: PendingIntentRecord{233eb378 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=805273, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{2a3c1bdb: PendingIntentRecord{38bb43ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=816832, Int=0
,I/ActivityManager(  966): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6261 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  966): sending alarm PendingIntent{3276c678: PendingIntentRecord{25db4151 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448521356387, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{1e7adb6: PendingIntentRecord{40603a5 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448521446591, Int=0
,D/PMS     (  966): acquireWL(37569ab7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  966): releaseWL(37569ab7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
I/art     (  407): Explicit concurrent mark sweep GC freed 8662(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 328us total 39.539ms
,D/PMS     (  966): releaseWL(f03acea): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PowerUsageList:PowerUsageHelper( 5930): MY_DEBUG = false
,D/PowerUsageService( 5930): repeat time = 1448522346676
I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 314us total 21.263ms
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 367us total 20.885ms
,I/PowerUsageList:PowerUsageHelper( 5930): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5930): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 5930): gen(), null == sipper.uidObj, userId = 0,
,D/PowerUsageList:BatterySipperExt( 5930): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6285): Error opening trace file: Permission denied (13),
I/dex2oat ( 6285): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6285): dex2oat: override thread count:4
,D/PowerUsageService( 5930): calcPower(), no data
,I/dex2oat ( 6285): dex2oat took 677.066ms (threads: 4),
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6261): ApplicationMonitor {b4ebedb}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6261): PnsModel {1fefbea}: update(): Update registration caused by: alarm
,I/PushClient( 6261): PnsConfigModel {2d070489}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6261): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6261): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6261): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6261): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  966): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6292 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6292): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6292 dbg=false s=true
,I/DeviceManagement( 6292): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6292): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6292): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6292): WorkflowService: Starting workflow service
,I/DeviceManagement( 6292): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1fefbea] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6292): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6292): ModelRegistry: Loading model meta data from resources...,
,I/DeviceManagement( 6292): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6292): SessionStateController: Checking invariants...
,I/DeviceManagement( 6292): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6292): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6292): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6292): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1fefbea],
,I/DeviceManagement( 6292): WorkflowService: Stopping workflow service
,I/ActivityManager(  966): Killing 5597:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  966): killProcessQuiet, pid=5597
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5597
,I/PushClient( 6261): PnsModel {1fefbea}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  966): killProcessQuiet, pid=5452,
I/ActivityManager(  966): Killing 5452:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  966): Recipient 5452
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): ,	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5527): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): 	,at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5527): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5527): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5527): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5527): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5527): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5527): [NET] android_getaddrinfo_proxy+
D/libc    ( 5527): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5527): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(1e93e84a): PARTIAL_WAKE_LOCK  *alarm* 0x1 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{8fca3bb: PendingIntentRecord{2b16e0d8 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448521496843, Int=0
,D/SmartSyncUtils( 5930): isEpsOn(), nState = 0
,D/PMS     (  966): releaseWL(1e93e84a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  966): acquireWL(104fbc31): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5930 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5930): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 5930): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 5930): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 5930): SettingOnTime = 1448604000000, randomSettingOnTime = 1448602378000
,D/SmartSyncScreenOnOffTimeReceiver( 5930): SettingOffTime = 1448582400000, randomSettingOffTime = 1448588046000
,D/SmartSyncScreenOnOffTimeReceiver( 5930): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5930): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5930): bNightModeTurnOffOnce = false
,D/PMS     (  966): releaseWL(104fbc31): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(3c303f16): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null,
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(3c303f16): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
,D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
,D/UsbnetService(  966): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: DeviceActiveState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  966): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): << updateStatus
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(34c7c097): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000},
,V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1014600, Int=0
I/bt-btm  ( 6086): Received oneshot timer event complete
,V/AlarmManager(  966): sending alarm PendingIntent{21853284: PendingIntentRecord{3132ea6d com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1027142, Int=0
,I/bt-btm  ( 6086): btm_ble_timeout,
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
D/PMS     (  966): acquireWL(336936a2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6086 1002 null
,D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = 28 7b 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 01 3e b0 9d 28 5c ba 9f f2 ff 8e ef 27 55 fd de 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  966): releaseWL(34c7c097): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): releaseWL(336936a2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(15bdcf33): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(15bdcf33): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  966): updateBatteryInfo
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): runPSCheck
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/UsageStatsService(  966): User[0] Flushing usage stats to disk
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5527): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5527): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
E/PlayEventLogger( 5527): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5527): Ignoring header User-Agent because its value was null.,
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
,D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5527): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
,D/libc    ( 5527): [NET] android_getaddrinfofornet-, pass to proxy
,W/ResourcesManager( 1301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/libc    ( 5527): [NET] android_getaddrinfo_proxy+
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/libc    ( 5527): [NET] android_getaddrinfo_proxy get netid:0
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
W/ResourcesManager( 1301): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5527): [NET] android_getaddrinfo_proxy-, NODATA
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(2a7048dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(2a7048dd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  966): updateBatteryInfo
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
,D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): Checking...
,D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  966): >> updateStatus
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
,D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(3ff08c52): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(3ff08c52): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  966): updateBatteryInfo
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
,D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
D/WifiController(  966): processMsg: DeviceActiveState
D/HtcPowerSaver(  966): Checking...
D/WifiController(  966): processMsg: StaEnabledState
I/HtcPowerSaver(  966): >> updateStatus
,D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  966): acquireWL(1d98eb23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  966): n_update end
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  966): releaseWL(1d98eb23): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
,D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): handleMessage: X
D/PMS     (  966): runPSCheck
D/HtcPowerSaver(  966): Checking...
I/HtcPowerSaver(  966): >> updateStatus
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
,W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5527): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5527): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5527): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5527): Ignoring header User-Agent because its value was null.
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5527): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5527): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5527): [NET] android_getaddrinfo_proxy+
D/libc    ( 5527): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
I/RemoteViews( 1215): reapply : com.google.android.gms 4 40
D/libc    ( 5527): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(37ba234d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(37ba234d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/PMS     (  966): runPSCheck
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  966): Checking...
D/UsbnetService(  966): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DeviceActiveState
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(b90ae02): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(b90ae02): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
,D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): battery changed pluggedType: 2
D/WifiController(  966): processMsg: StaEnabledState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: X
I/HtcPowerSaver(  966): << updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(3c24a950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
,I/BatteryService(  966): n_update end
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/PMS     (  966): releaseWL(3c24a950): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  966): plugged=true pluggin=true
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  966): updateBatteryInfo
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  966): runPSCheck
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): Checking...
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): handleMessage: E msg.what=155652
D/WifiController(  966): processMsg: DeviceActiveState
D/WifiController(  966): processMsg: StaEnabledState
D/WifiController(  966): processMsg: DefaultState
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  966): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(b12a749): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1074600, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{34ab9cdb: PendingIntentRecord{233eb378 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1681254, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{1435100f: PendingIntentRecord{16989c android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1824383, Int=1800000
,V/AlarmManager(  966): sending alarm PendingIntent{115fa84e: PendingIntentRecord{5569d6f com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448522103480, Int=1800000
V/AlarmManager(  966): sending alarm PendingIntent{1cb30a7c: PendingIntentRecord{38bb43ed com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1728617, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{1d556f05: PendingIntentRecord{2811fb5a com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1851835, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{bd9a18b: PendingIntentRecord{17645268 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1865503, Int=0
,V/AlarmManager(  966): sending alarm PendingIntent{2b42f681: PendingIntentRecord{40603a5 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448522346676, Int=0
,D/PMS     (  966): acquireWL(3b647326): PARTIAL_WAKE_LOCK  NetworkStats 0x1 966 1000 null
,I/ProcessStatsService(  966): Prepared write state in 22ms
,I/ProcessStatsService(  966): Prepared write state in 5ms
,D/PMS     (  966): releaseWL(3b647326): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  966): updateNetworkEnabledLocked()
V/NetworkPolicy(  966): updateNotificationsLocked()
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  966): acquireWL(1a3ecb67): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4232 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(232779bd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1884 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  966): acquireWL(24149bb2): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4232 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1884): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1884): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1884): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1884): [NET] android_getaddrinfo_proxy+
D/libc    ( 1884): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  393): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/PMS     (  966): releaseWL(1a3ecb67): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1884): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  966): releaseWL(232779bd): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/LocationManagerService(  966): getAllProviders()=[passive, gps, network]
,D/PMS     (  966): releaseWL(b12a749): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 5930): MY_DEBUG = false
,D/PowerUsageService( 5930): repeat time = 1448523251041,
,I/EventLogService( 4232): Aggregate from 1448520303420 (log), 1448520303420 (data)
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  966): releaseWL(24149bb2): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,I/ProcessStatsService(  966): Pruning old procstats: /data/system/procstats/state-2015-11-25-11-41-24.bin
,I/PowerUsageList:PowerUsageHelper( 5930): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5930): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5930): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 5930): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageService( 5930): calcPower(), no data,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1884): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1884): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1884): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1884): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1884): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1884): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1884): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1884): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1884): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1884): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5527): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5527): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5527): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5527): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5527): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5527): Ignoring header User-Agent because its value was null.
D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/DotMatrix( 1301): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    ( 5527): [NET] android_getaddrinfofornet-, err=8
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    ( 5527): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5527): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5527): [NET] android_getaddrinfo_proxy+
D/libc    ( 5527): [NET] android_getaddrinfo_proxy get netid:0
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
D/libc    (  393): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  393): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  393): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  393): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5527): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(eb3db12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 966 1000 null
I/BatteryService(  966): n_update end
D/PMS     (  966): releaseWL(eb3db12): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  966): BroadcastReceiver::onReceive+
D/NotificationService(  966): plugged=true pluggin=true
D/UsbnetService(  966): onReceive BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
D/UsbnetService(  966):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  966): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  966): updateBatteryInfo
D/WifiController(  966): handleMessage: E msg.what=155652
D/PMS     (  966): runPSCheck
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  966): Checking...
,D/WifiController(  966): processMsg: DeviceActiveState
I/HtcPowerSaver(  966): >> updateStatus
D/WifiController(  966): processMsg: StaEnabledState
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  966): processMsg: DefaultState
I/HtcPowerSaver(  966): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  966): handleMessage: X
,I/HtcPowerSaver(  966): << updateStatus
D/HeadsetStateMachine( 6086): Disconnected process message: 10, size: 0
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1301): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6032): 
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
,D/PMS     (  966): acquireWL(113ff2e3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 966 1000 WorkSource{1000}
,V/AlarmManager(  966): sending alarm PendingIntent{5422056: PendingIntentRecord{3b8628d7 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1914600, Int=0
V/AlarmManager(  966): sending alarm PendingIntent{12cdc4e0: PendingIntentRecord{18d94399 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1927154, Int=0
,I/bt-btm  ( 6086): Received oneshot timer event complete
I/ActivityManager(  966): Killing 5987:com.htc.calendar/u0a10 (adj 13): empty for 1814s
I/bt-btm  ( 6086): btm_ble_timeout
D/PMS     (  966): acquireWL(2870965e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6086 1002 null
I/bt-btm  ( 6086): btm_gen_resolvable_private_addr
D/Process (  966): killProcessQuiet, pid=5987
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/bt-btm  ( 6086): btm_ble_rand_enc_complete
I/bt-btm  ( 6086): btm_gen_resolve_paddr_low
D/bt-smp  ( 6086): smp_encrypt_data
W/bt-smp  ( 6086): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 6086): Plain text(LSB ~ MSB) = d9 18 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6086): Encrypted text(LSB ~ MSB) = 93 0c ab d8 70 ef 0b ca ff 61 42 0e 60 f3 0f 47 
I/bt-btm  ( 6086): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6086): Stopping oneshot timer
D/bt-btm  ( 6086): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  966): Recipient 5987
,D/Process (  966): killProcessQuiet, pid=5962
I/ActivityManager(  966): Killing 5962:com.htc.mobiledata/u0a46 (adj 13): empty for 1815s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  966): Recipient 5962
,D/Process (  966): killProcessQuiet, pid=5899
I/ActivityManager(  966): Killing 5899:com.htc.bgp/u0a11 (adj 13): empty for 1815s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  966): Recipient 5899
,D/Process (  966): killProcessQuiet, pid=5876
I/ActivityManager(  966): Killing 5876:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1821s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  966): Recipient 5876
,D/Process (  966): killProcessQuiet, pid=5527
I/ActivityManager(  966): Killing 5527:com.android.vending/u0a72 (adj 15): empty for 1828s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  966): Recipient 5527
,I/ActivityManager(  966): Killing 5737:com.android.defcontainer/u0a15 (adj 15): empty for 1840s
,D/Process (  966): killProcessQuiet, pid=5737
,D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  966): Recipient 5737
,D/Process (  966): killProcessQuiet, pid=6122
I/ActivityManager(  966): Killing 6122:com.htc.widget.hmsproc3/u0a34 (adj 13): empty for 1800s
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  966): Recipient 6122
,D/PMS     (  966): releaseWL(113ff2e3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,D/PMS     (  966): releaseWL(2870965e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6032): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 6032): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6032): 
E/cutils-trace( 6340): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6340): ====startRecUseTime====
D/htc.customization.log.level( 6340):  is 
W/CustomizationLogLevel( 6340): Level value is invalid, use default level 2
D/CustomizationManager( 6340):  Read ACC file spent 0.056 (s)
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6340): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6340): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6340): Parsing tag category name = system
I/CustomizationCIDLoader( 6340): Parsing tag category name = application
I/CustomizationCIDLoader( 6340): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6340): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6340): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6340): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6340): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6340): add string-array item, value = 42507
I/CustomizationCIDLoader( 6340): add string-array item, value = 21902
I/CustomizationCIDLoader( 6340): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6340): add string-array item, value = 23420
I/CustomizationCIDLoader( 6340): add string-array item, value = 22299
I/CustomizationCIDLoader( 6340): add string-array item, value = 24002
I/CustomizationCIDLoader( 6340): add string-array item, value = 23210
I/CustomizationCIDLoader( 6340): add string-array item, value = 23205
I/CustomizationCIDLoader( 6340): add string-array item, value = 23806
I/CustomizationCIDLoader( 6340): add string-array item, value = 23430
I/CustomizationCIDLoader( 6340): add string-array item, value = 23408
I/CustomizationCIDLoader( 6340): add string-array item, value = 27205
I/CustomizationCIDLoader( 6340): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6340): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6340):  Read CID file spent 0.114 (s)
D/CustomizationManager( 6340):  All configurations done spent 0.114 (s)
D/PackageManager(  966): deletePackageAsUser: pkg=com.test.thalitest, pid=6340, uid=2000 userid=0
I/ActivityManager(  966): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  966): killProcessQuiet, pid=6032
I/ActivityManager(  966): Killing 6032:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  966): Skipping PackageSetting{1ae0b0c1 com.example.hello/10373} due to missing metadata
I/ActivityManager(  966): Recipient 6032
I/WindowState(  966): WIN DEATH: Window{3c1b87f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  966): Client connection lost with reason: 4
E/InputEventReceiver( 1349): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{165cb04f uid 10366 pid 6032} (c)'
E/libprocessgroup(  966): failed to kill 1 processes for processgroup 6032
I/ActivityManager(  966):   Force finishing activity ActivityRecord{208c677c u0 com.test.thalitest/.MainActivity t8}
W/ActivityManager(  966): Spurious death for ProcessRecord{3074da3f 6032:com.test.thalitest/u0a366}, curProc for 6032: null
I/ActivityManager(  966): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1301): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1301): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  966): acquireWL(7fa4f0c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1813 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1813): Ignoring removeGeofence because network location is disabled.
D/PMS     (  966): releaseWL(7fa4f0c): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1673): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
W/SystemReader(  966): Cannot find grip_rejection_width, use default value instead
D/AccTypeManager( 1673): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/InputMethodManagerService(  966): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1457): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/art     ( 1512): Explicit concurrent mark sweep GC freed 4878(271KB) AllocSpace objects, 8(624KB) LOS objects, 34% free, 29MB/45MB, paused 1.627ms total 100.444ms
I/Prism.ItemManager( 1512): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1512): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1673): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1512): Deferring update until onResume
W/ResourcesManager(  966): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/Launcher( 1512): waitUntilResume // bindAppsRemoved
E/ExternalAccountType( 1673): Unsupported attribute readOnly
I/art     (  966): Explicit concurrent mark sweep GC freed 41781(2MB) AllocSpace objects, 21(2MB) LOS objects, 33% free, 16MB/25MB, paused 1.715ms total 222.781ms
I/art     (  966): WaitForGcToComplete blocked for 216.291ms for cause Explicit
W/PackageManager(  966): Unable to load service info ResolveInfo{4735f9c com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  966): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  966): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  966): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  966): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  966): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  966): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  966): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  966): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  966): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  966): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  966): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  966): Explicit concurrent mark sweep GC freed 8820(595KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 3.725ms total 211.674ms
I/art     (  966): WaitForGcToComplete blocked for 402.485ms for cause Explicit
I/art     (  966): Explicit concurrent mark sweep GC freed 1824(96KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.221ms total 209.096ms
D/TaskPersister(  966): removeObsoleteFile: deleting file=8_task.xml
D/VoicemailCleanupService( 1634): Cleaning up data for package: com.test.thalitest
D/Prism.PackageStateRece_( 1512): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1422): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  966): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/[PluginManager]RegisterService( 1422): handle notify Blinkfeed plugin client changed
D/StatusBarManagerService(  966): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
W/ContextImpl( 6361): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  966): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  966): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  966): hiding MENU key
D/FindExtension( 1512): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1512): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  966): Got RemoteException sending setActive(false) notification to pid 6032 uid 10366
D/StatusBarManagerService(  966): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
E/SQLiteDatabase( 6361): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6361): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 6361): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 6361): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6361): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6361): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6361): Process: com.android.keychain, PID: 6361
E/AndroidRuntime( 6361): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6361): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6361): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6361): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6361): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 6361): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 6361): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6361): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  966): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6388 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
E/ActivityManager(  966): App crashed! Process: com.android.keychain
D/ErrorReport(  966): HtcErrorReportManager Begin---add error logs to dropbox
W/System.err(  966): java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
W/System.err(  966): 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
W/System.err(  966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  966): 	at android.os.Looper.loop(Looper.java:155)
W/System.err(  966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.Posix.open(Native Method)
W/System.err(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  966): 	... 12 more
W/System.err(  966): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:69)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:304)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  966): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.Posix.open(Native Method)
W/System.err(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  966): 	... 14 more
W/System.err(  966): java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
W/System.err(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:154)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:121)
W/System.err(  966): 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:93)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:305)
W/System.err(  966): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:257)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12578)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12242)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12214)
W/System.err(  966): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1391)
W/System.err(  966): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2567)
W/System.err(  966): 	at android.os.Binder.execTransact(Binder.java:454)
W/System.err(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err(  966): 	at libcore.io.Posix.open(Native Method)
W/System.err(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err(  966): 	... 14 more
E/ErrorReport(  966): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  966): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1448522422383.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/ErrorReport(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/ErrorReport(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/ErrorReport(  966): 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:455)
E/ErrorReport(  966): 	at java.lang.Thread.run(Thread.java:818)
E/ErrorReport(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  966): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/ErrorReport(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/ErrorReport(  966): 	... 4 more
D/Process ( 6361): killProcess, pid=6361
D/Process ( 6361): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6388, uid=10072, userID:0
W/global  ( 6388): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6388): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 6388): [apache-http] Connection GC has been deprecated!
I/ActivityManager(  966): Recipient 6361
I/ActivityManager(  966): Process com.android.keychain (pid 6361) has died
W/ActivityManager(  966): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/global  ( 6388): [apache-http] Connection GC has been deprecated!
E/RollingFileStream( 6388): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
D/Finsky  ( 6388): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager(  966): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6428 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 6388): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6388): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6388): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 6388): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6388): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6388): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 6388): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 6388): Process: com.android.vending, PID: 6388
E/AndroidRuntime( 6388): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 6388): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 6388): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 6388): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 6388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 6388): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 6388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 6388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 6388): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 6388): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime( 6388): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime( 6388): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime( 6388): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime( 6388): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime( 6388): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 6388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 6388): 	... 4 more
E/SQLiteDatabase( 6388): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 6388): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6388): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6388): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime_2_crash( 6388): crash in the same process: libraries-thread
E/AndroidRuntime_2_crash( 6388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 6388): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime_2_crash( 6388): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime_2_crash( 6388): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime_2_crash( 6388): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime_2_crash( 6388): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime_2_crash( 6388): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime_2_crash( 6388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  966): App crashed! Process: com.android.vending
I/ActivityManager(  966): Killing 6153:com.htc.widget.hmsproc2/u0a40 (adj 15): empty for 1809s
D/Process (  966): killProcessQuiet, pid=6153
E/DropBoxManagerService(  966): Can't write: system_app_crash
E/DropBoxManagerService(  966): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  966): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  966): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  966): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  966): 	... 5 more
D/Process (  966): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
I/PackageManager(  966):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6388, uid=10072, userID:0
E/SQLiteDatabase( 6388): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/SQLiteDatabase( 6388): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/SQLiteDatabase( 6388): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6388): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6388): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 6388): crash in the same process: AsyncTask #3
E/AndroidRuntime_3_crash( 6388): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 6388): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 6388): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 6388): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 6388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 6388): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 6388): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 6388): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 6388): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_3_crash( 6388): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_3_crash( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_3_crash( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_3_crash( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_3_crash( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_3_crash( 6388): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_3_crash( 6388): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_3_crash( 6388): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_3_crash( 6388): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:61)
E/AndroidRuntime_3_crash( 6388): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:33)
E/AndroidRuntime_3_crash( 6388): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 6388): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 6388): 	... 4 more
I/ActivityManager(  966): Recipient 6153
D/Process ( 6388): killProcess, pid=6388
D/Process ( 6388): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
W/ResourcesManager( 6428): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6428): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6428): VM with version 2.1.0 has multidex support
I/MultiDex( 6428): install
I/MultiDex( 6428): VM has multidex support, MultiDex support library is disabled.
I/Prism.ItemManager( 1512): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1512): loadItems() com.htc.launcher.pageview.WidgetManager@21c042eb +
I/Prism.WidgetManager( 1512): onLoadItems() +
V/JNIHelp ( 6428): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ResourcesManager( 1512): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  966): Recipient 6388
I/ActivityManager(  966): Process com.android.vending (pid 6388) has died
I/TrimMemoryManager( 1512): [trimMemory] 5
D/HtcUPManager( 1215): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 5
D/ChimeraCfgMgr( 4232): Loading module com.google.android.gms.kids from APK com.google.android.gms
W/ActivityThread( 6428): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6428): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d08d4ab: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6428): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 6428): Failed to open lock file
W/NativeLibraryUtils( 6428): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6428): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6428): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6428): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6428): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6428): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6428): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6428): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6428): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6428): 	... 3 more
E/SQLiteLog( 1884): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1884): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x557a0c2110
E/AndroidRuntime( 1884): FATAL EXCEPTION: main
E/AndroidRuntime( 1884): Process: com.google.process.gapps, PID: 1884
E/AndroidRuntime( 1884): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1884): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1884): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1884): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1884): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1884): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1884): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1884): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1884): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1884): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1884): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1884): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1884): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1884): 	... 9 more
E/ActivityManager(  966): App crashed! Process: com.google.process.gapps
D/Process ( 1884): killProcess, pid=1884
D/Process ( 1884): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  966): Can't write: system_app_crash
E/DropBoxManagerService(  966): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  966): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  966): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  966): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  966): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  966): 	... 5 more
W/ResourcesManager( 1512): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  966): Recipient 1884
I/ActivityThread( 6428): Removing dead content provider:android.content.ContentProviderProxy@6a02ea1
I/ActivityManager(  966): Process com.google.process.gapps (pid 1884) has died
W/ActivityManager(  966): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  966): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
W/ActivityManager(  966): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
I/ActivityManager(  966): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6461 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/asset   ( 1512): Copying FileAsset 0x557a5e5be0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.

```
