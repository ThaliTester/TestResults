#### Test 50650278654db8c_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  910): acquireWL(21a43609): PARTIAL_WAKE_LOCK  *alarm* 0x1 910 1000 WorkSource{1000}
V/AlarmManager(  910): sending alarm PendingIntent{2f57f00e: PendingIntentRecord{2c69aa2f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450201700263, Int=0
D/PMS     (  910): acquireWL(2a31f83c): PARTIAL_WAKE_LOCK  *backup* 0x1 910 1000 null
W/BackupManagerService(  910): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  910): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  910): releaseWL(2a31f83c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  910): releaseWL(21a43609): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
--------- beginning of main
D/ContactMessageStore( 1456): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1456): MSG_NOTIFY_CS_TO_SYNC <<
,E/cutils-trace( 5914): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5914): ====startRecUseTime====
D/htc.customization.log.level( 5914):  is 
W/CustomizationLogLevel( 5914): Level value is invalid, use default level 2
D/CustomizationManager( 5914):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5914): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5914): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5914): Parsing tag category name = system
I/CustomizationCIDLoader( 5914): Parsing tag category name = application
I/CustomizationCIDLoader( 5914): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5914): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5914): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5914): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5914): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5914): add string-array item, value = 42507
I/CustomizationCIDLoader( 5914): add string-array item, value = 21902
I/CustomizationCIDLoader( 5914): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5914): add string-array item, value = 23420
I/CustomizationCIDLoader( 5914): add string-array item, value = 22299
I/CustomizationCIDLoader( 5914): add string-array item, value = 24002
I/CustomizationCIDLoader( 5914): add string-array item, value = 23210
I/CustomizationCIDLoader( 5914): add string-array item, value = 23205
I/CustomizationCIDLoader( 5914): add string-array item, value = 23806
I/CustomizationCIDLoader( 5914): add string-array item, value = 23430
I/CustomizationCIDLoader( 5914): add string-array item, value = 23408
I/CustomizationCIDLoader( 5914): add string-array item, value = 27205
I/CustomizationCIDLoader( 5914): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5914): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5914):  Read CID file spent 0.071 (s)
D/CustomizationManager( 5914):  All configurations done spent 0.071 (s)
D/PMS     (  910): acquireHCC(2b5129c5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 910 1000 null
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5914 on display 0
D/PMS     (  910): acquireHCC(3fa6ff1a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 910 1000 null
W/asset   (  910): Copying FileAsset 0x55718bb420 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  910): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5932 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  910): Display changed displayId=0
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 5932): Copying FileAsset 0xabe14fc8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1518): [trimMemory] 20
I/WebViewFactory( 5932): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
I/LibraryLoader( 5932): Time to load native libraries: 10 ms (timestamps 6620-6630)
,I/LibraryLoader( 5932): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 5932): Binding Chromium to main looper Looper (main, tid 1) {2cbb5f08},
I/LibraryLoader( 5932): Expected native library version number "",actual native library version number ""
,I/chromium( 5932): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5932): Initializing chromium process, singleProcess=true,
,W/art     ( 5932): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5932): ApplicationContext is null in ApplicationStatus,
,W/chromium( 5932): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5932): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5932): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5932): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5932): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 5932): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5932): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5932): Local Branch: 
I/Adreno-EGL( 5932): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5932): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5932):                  d74aa161a12b9c6fc6332151
,W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@192c27c3:true
D/BluetoothAdapter( 5932): 137377927: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5932): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5932): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5932): CordovaWebView is running on device made by: HTC
W/art     ( 5932): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5932): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  910): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 5932): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  910): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  910): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  910): hiding MENU key
D/StatusBarManagerService(  910): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  910): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  910): hiding MENU key
,D/FindExtension( 5932): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5932): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@21862502, mServedView=org.apache.cordova.engine.SystemWebView{6f08e13 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@35687850
,I/PhoneStatusBar( 1217): setImeWindowStatus(false,false)
,I/InputMethodManagerService(  910): Disable input method client, pid=1518
D/StatusBarManagerService(  910): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 5932): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  910): Displayed com.test.thalitest/.MainActivity: +638ms (total +679ms)
,W/BindingManager( 5932): Cannot call determinedVisibility() - never saw a connection for the pid: 5932
,D/JsMessageQueue( 5932): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5932): JniHelper::setJavaVM(0xaaca88f8), pthread_self() = -1409330776
,D/JX-Cordova( 5932): jxcore cordova android initializing
,W/jxcore-log( 5932): Initializing JXcore engine,
W/jxcore-log( 5932): JXcore engine is ready
,W/jxcore-log( 5932): Starting JXcore engine
,W/jxcore-log( 5932): Platform android,
W/jxcore-log( 5932): 
W/jxcore-log( 5932): Process ARCH arm
W/jxcore-log( 5932): 
,D/PMS     (  910): releaseHCC(2b5129c5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  910): releaseHCC(3fa6ff1a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 5932): JXcore Cordova bridge is ready!,
I/jxcore-log( 5932): 
W/jxcore-log( 5932): JXcore engine is started,
I/chromium( 5932): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5932): Toggling radios to true,
I/jxcore-log( 5932): 
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  910): checking for enable restriction...
D/BluetoothManagerService(  910): checkBTEasState, ret=true
I/BluetoothManagerService(  910): isBluetoothRestricted(): false
D/BluetoothManagerService(  910): enable(): region ID = 6
D/BluetoothManagerService(  910): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  910): MONITOR_LOG
W/Settings:Agent(  910): name: bluetooth_on
W/Settings:Agent(  910): value: 1
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1512
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  910): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  910): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  910): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  910): 
W/Settings:Agent(  910): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  910): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  910): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  910): New client listening to asynchronous messages
E/WifiTrafficPoller(  910): ADD_CLIENT: 7
D/WifiManager( 5932): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  910): setWifiEnabled: true pid=5932, uid=10366
,E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
I/WifiService(  910): isMdmWifiRestricted(): false
,W/Settings:Agent(  910): MONITOR_LOG
W/Settings:Agent(  910): name: wifi_on
W/Settings:Agent(  910): value: 2
,W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
,W/Settings:Agent(  910): Process.myTid(): 1544
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): 
W/System.err(  910): java.lang.Throwable: stack dump
,I/ActivityManager(  910): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5988 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
W/System.err(  910): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  910): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  910): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  910): ,	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
,W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154),
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  910): 	,at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  910): 
W/Settings:Agent(  910): << traceCallingStack(): 16(ms)
,D/WifiManager( 5932): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  910): handleMessage: E msg.what=155656
D/WifiController(  910): processMsg: ApStaDisabledState
E/WifiStateMachine(  910): handleMessage: E msg.what=131145
E/WifiStateMachine(  910): processMsg: InitialState
D/WifiManager( 5932): reconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  910): transitionTo: destState=DeviceActiveState
E/WifiStateMachine(  910):  InitialState CMD_DISCONNECT 0 0
D/WifiController(  910): handleMessage: new destination call exit/enter
E/WifiStateMachine(  910): processMsg: DefaultState
E/WifiStateMachine(  910):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131146
,E/WifiStateMachine(  910): processMsg: InitialState
E/WifiStateMachine(  910):  InitialState CMD_RECONNECT 0 0
E/WifiStateMachine(  910): processMsg: DefaultState
E/WifiStateMachine(  910):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  910): handleMessage: X
,I/jxcore-log( 5932): Radios toggled
I/jxcore-log( 5932): 
,D/WifiController(  910): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/WifiController(  910): invokeExitMethods: ApStaDisabledState
D/WifiController(  910): moveTempStackToStateStack: i=1,j=1
D/WifiController(  910): moveTempStackToStateStack: i=0,j=2
D/WifiController(  910): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
,D/PMS     (  910): acquireWL(518dc46): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 910 1000 null
,D/WifiController(  910): invokeEnterMethods: StaEnabledState
D/WifiController(  910): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  910): handleMessage: E msg.what=131083
E/WifiStateMachine(  910): setting operational mode to 1
E/WifiStateMachine(  910): processMsg: InitialState
D/WifiController(  910): handleMessage: X
E/WifiStateMachine(  910):  InitialState CMD_START_SUPPLICANT 0 0
I/jxcore-log( 5932): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 5932): 
,I/jxcore-log( 5932): Perf Test app loaded loaded,
I/jxcore-log( 5932): 
,I/jxcore-log( 5932): check test folder,
I/jxcore-log( 5932): 
,I/jxcore-log( 5932): found test : ./testFindPeers.js,
I/jxcore-log( 5932): 
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/ResourcesManager( 5988): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
I/jxcore-log( 5932): found test : ./testSendData.js
,I/jxcore-log( 5932): 
,D/AdapterServiceConfig( 5988): Adding HeadsetService,
D/AdapterServiceConfig( 5988): Adding A2dpService
D/AdapterServiceConfig( 5988): Adding HidService
D/AdapterServiceConfig( 5988): Adding HealthService
D/AdapterServiceConfig( 5988): Adding PanService
D/AdapterServiceConfig( 5988): Adding GattService
,I/chromium( 5932): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,W/linker  ( 5988): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  910): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11894d5d:true
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	,at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 5988): make
,I/BluetoothAdapterState( 5988): Entering OffState,
,E/bt_osi_config( 5988): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,D/BluetoothManagerService(  910): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 5988): Address is:90:E7:C4:F6:69:77
,D/BluetoothManagerService(  910): Calling onBluetoothServiceUp callbacks,
D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapter( 3489): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2c325177
D/BluetoothAdapter( 3489): onBluetoothServiceUp done
,D/BluetoothAdapter( 1769): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1d254d12,
D/BluetoothAdapter( 1769): onBluetoothServiceUp done
D/BluetoothAdapter( 5988): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@5127bdd
D/BluetoothAdapter( 5988): onBluetoothServiceUp done
D/BluetoothAdapter(  910): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@24126259
,D/BluetoothAdapter(  910): onBluetoothServiceUp done
D/BluetoothAdapter( 1476): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2f5eeaaa
D/BluetoothAdapter( 1476): onBluetoothServiceUp done
,D/BluetoothAdapter( 2345): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@16b79631
D/BluetoothAdapter( 2345): onBluetoothServiceUp done
D/BluetoothAdapter( 1217): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@77eec7d
,D/BluetoothAdapter( 1217): onBluetoothServiceUp done
D/BluetoothAdapter( 5932): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@393cd364
D/BluetoothAdapter( 5932): onBluetoothServiceUp done
,D/BluetoothAdapter( 1456): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@232fc880
D/BluetoothAdapter( 1456): onBluetoothServiceUp done
D/BluetoothManagerService(  910): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 5988): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 5988): Setting state to 11
,I/BluetoothAdapterState( 5988): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  910): Bluetooth State Change Intent: 10 -> 11
I/IntentController( 1217): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false),
,D/BluetoothBondStateMachine( 5988): make,
,V/BluetoothPbapReceiver( 5988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 5988): ***********state = 11
D/BluetoothAdapterService( 5988): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 5988): checkA2dpState: returning
D/BluetoothAdapterService( 5988): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 5988): checkHfpState: returning
,I/BluetoothBondStateMachine( 5988): StableState(): Entering Off State
D/NGFService( 3489): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,D/Tethering(  910): interfaceAdded wlan0
D/PMS     (  910): releaseWL(518dc46): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,V/Tethering(  910): TetherInterfaceSM: wlan0: enter InitialState
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  910): interfaceAdded p2p0
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  910): p2p0 is not a tetherable iface, ignoring
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6023 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/libc    (  910): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  910): [NET] android_getaddrinfofornet-, SUCCESS
,I/BluetoothAdapterState( 5988): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/Tethering(  910): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  910): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN,
D/PMS     (  910): acquireWL(3b0393c9): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
V/Tethering(  910): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  910): TetherInterfaceSM: wlan0: enter UnavailableState
D/HeadsetService( 5988): Received start request. Starting profile...
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothHeadset( 1456): Proxy object connected
D/BluetoothHeadset(  910): Proxy object connected
D/HeadsetStateMachine( 5988): Version 1.5
D/HeadsetStateMachine( 5988): make
D/Tethering(  910): sendTetherStateChangedBroadcast 0, 0, 0
D/TetherSettings( 4031): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4031): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4031): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4031): Cust_ConnectToPC   : spcsc>false
D/        ( 4031): Cust_ConnectToPC   : IPT>true
D/        ( 4031): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 4031): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4031): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4031): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4031): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  910): releaseWL(3b0393c9): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  910): updateNetworkEnabledLocked()
V/NetworkPolicy(  910): updateNotificationsLocked()
D/PMS     (  910): acquireWL(1ca8a385): PARTIAL_WAKE_LOCK  NetworkStats 0x1 910 1000 null
,D/PMS     (  910): releaseWL(1ca8a385): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/BluetoothAdapter(  910): 327046618: getState(). Returning 11
,D/HeadsetStateMachine( 5988): max_hf_connections = 2
D/BluetoothHeadset( 1456): Proxy object connected
D/BluetoothHeadset( 1456): Proxy object connected
,I/QuickSettingBluetooth( 1217): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/BluetoothHeadset( 1217): Proxy object connected
V/NetworkPolicy(  910): updateNetworkEnabledLocked()
V/NetworkPolicy(  910): updateNotificationsLocked()
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 ,
I/SmartNS_Utility( 4031): setISNotification
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/SmartNS_Utility( 4031): usb_cable_connect = 1
D/SmartNS_Utility( 4031): usb_denied = 0
D/BluetoothPhoneService( 1456): BluetoothHeadset onServiceConnected
I/SmartNS_PSService( 4031): usb notificaiton:true
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 4031): usb_cable_connect = 1
D/SmartNS_Utility( 4031): usb_denied = 0
I/SmartNS_PSService( 4031): usb notificaiton:true
D/HeadsetPhoneState( 5988): listenForPhoneState..for service and signal ,
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
,I/QuickSettingMiniLite( 1217): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@2c6f772
,D/HeadsetDualPhoneStateListener_SLOT1( 5988): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 5988): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 5988): Enter Disconnected: -2, size: 0
,D/HeadsetDualPhoneStateListener_SLOT1( 5988): listen phone state by slot:SLOT1  id:-1,
D/SmartNS_NSReceiver( 4031): Tethered state change:false isNSOpening:false
D/HeadsetDualPhoneStateListener_SLOT2( 5988): listen phone state by slot:SLOT2  id:-100,
D/BluetoothAdapter( 1456): 571626238: getState(). Returning 11
,I/HeadsetStateMachine( 5988): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 5988): BTHF: set_current_device
D/TetherSettings( 4031): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 ,
D/        ( 4031): Cust_ConnectToPC   : Internet_Sharing>true
D/UsbDeviceManager(  910): [USBNET] bCheckSuppFunc: cdc_network
D/        ( 4031): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4031): Cust_ConnectToPC   : spcsc>false
D/UsbDeviceManager(  910): [USBNET] bCheckSuppFunc: cdc_network
D/        ( 4031): Cust_ConnectToPC   : IPT>true
D/        ( 4031): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4031): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4031): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4031): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4031): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterService( 5988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aec16a1
I/SmartNS_Utility( 4031): setISNotification
D/UsbnetService(  910): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/UsbnetService(  910): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/SmartNS_Utility( 4031): usb_cable_connect = 1
D/SmartNS_Utility( 4031): usb_denied = 0
D/A2dpService( 5988): Received start request. Starting profile...
I/SmartNS_PSService( 4031): usb notificaiton:true
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
V/Avrcp   ( 5988): make
D/BluetoothA2dp(  910): Proxy object connected
D/BluetoothAdapter(  910): 327046618: getState(). Returning 11
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
E/RemoteController( 5988): Cannot set synchronization mode on an unregistered RemoteController
,D/A2dpStateMachine( 5988): make
,D/SmartNS_Utility( 4031): usb_cable_connect = 1
D/SmartNS_Utility( 4031): usb_denied = 0
I/RemoteViews( 1217): reapply : com.android.settings 1 36
I/SmartNS_PSService( 4031): usb notificaiton:true
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/HtcBtWidget_BTWidgetProvider( 6023): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 6023): updateWidget(context) for widget: 
D/bt-btif ( 5988): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_NSReceiver( 4031): Tethered state change:false isNSOpening:false
,D/A2dpService( 5988): setA2dpService(): set to: null
D/BluetoothAdapterService( 5988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aec16a1
I/ActivityManager(  910): Killing 5614:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=5614
D/A2dpStateMachine( 5988): Enter Disconnected: -2
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/HidService( 5988): Received start request. Starting profile...
D/BluetoothAdapterService( 5988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aec16a1
I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/HealthService( 5988): Received start request. Starting profile...
I/RemoteViews( 1217): reapply : com.android.settings 1 36
D/BluetoothAdapterService( 5988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aec16a1
D/PanService( 5988): Received start request. Starting profile...
,D/PanService( 5988): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 5988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aec16a1
,D/BtGatt.DebugUtils( 5988): handleDebugAction() action=null,
D/BtGatt.GattService( 5988): Received start request. Starting profile...
D/BtGatt.GattService( 5988): start()
D/BtGatt.AdvertiseManager( 5988): advertise manager created
,D/wpa_supplicant( 6052): wpa_supplicant v2.3-devel-5.0.2,
,D/wpa_supplicant( 6052): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6052): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 6052): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6052): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6052): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6052): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6052): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6052): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6052): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6052): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6052): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6052): update_config=1
D/wpa_supplicant( 6052): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6052): device_name='Android_608e'
D/wpa_supplicant( 6052): manufacturer='HTC'
D/wpa_supplicant( 6052): model_name='HTC_PHONE'
D/wpa_supplicant( 6052): model_number='1234'
D/wpa_supplicant( 6052): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6052): p2p_oper_reg_class=126
D/wpa_supplicant( 6052): p2p_oper_channel=149
D/wpa_supplicant( 6052): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6052): persistent_reconnect=1
D/wpa_supplicant( 6052): key_mgmt_offload=1
,I/wpa_supplicant( 6052): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6052): nl80211: RFKILL status not available
D/wpa_supplicant( 6052): nl80211: Using driver-based roaming
,D/wpa_supplicant( 6052): nl80211: TDLS supported
D/wpa_supplicant( 6052): nl80211: TDLS external setup
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6052): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  910): Recipient 5614
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6052): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
,D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
,D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6052): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6052): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6052): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6052): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6052): nl80211: Subscribe to mgmt frames with non-AP handle 0x55974fcfd0
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=0104
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=040a
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=040b
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=040c
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=040d
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=090a
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=090b
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=090c
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=090d
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=0409506f9a09
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=7f506f9a09
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=0801
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=040e
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=06
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=0a07
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=0a11
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55974fcfd0 match=0a1a
D/wpa_supplicant( 6052): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6052): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6052): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6052): htc_wext_command_init +
E/wpa_supplicant( 6052): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6052): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 1217): 381130289: getState(). Returning 11
I/QuickSettingMiniLite( 1217): updateLiteState:no connect device!
,D/BluetoothAdapterService( 5988): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aec16a1,
,E/WifiStateMachine(  910): setWifiState: enabling,
E/WifiStateMachine(  910): Supplicant start successful
,D/WifiMonitor(  910): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  910): connecting to supplicant
,D/WIFI_ICON( 1217): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,I/IntentController( 1217): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/BluetoothAdapter( 1456): 571626238: getState(). Returning 11,
W/BluetoothHeadset( 1456): Proxy not attached to service
,D/BluetoothHeadset( 1456): java.lang.Throwable,
D/BluetoothHeadset( 1456): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1456): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1456): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1456): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1456): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1456): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1456): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1456): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1456): 	at java.lang.reflect.Method.invoke(Method.java:372)
,D/BluetoothHeadset( 1456): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1456): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6055 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,I/HeadsetPhoneState( 5988): updateServiceState service = 0,roam = 0,
D/HeadsetPhoneState( 5988): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5988): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 5988): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5988): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 5988): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 5988): btu_task pending for preload complete event
E/bt_vendor( 5988): get_bt_soc_type: Failed to get soc type
,I/wpa_supplicant( 6052): wapi_supplicant_init: Init WAI packet p2p0
,D/wpa_supplicant( 6052):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6052):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6052):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
I/QuickSettingWifi( 1217): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6052): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6052): nl80211: Flush PMKIDs
D/wpa_supplicant( 6052): p2p0: State: DISCONNECTED -> INACTIVE
,D/BluetoothMasReceiver( 5988): Bluetooth STATE CHANGED to 11,
,V/BluetoothSapReceiver( 5988): SapReceiver onReceive ,
,V/BluetoothSapReceiver( 5988): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 5988):  Bluetooth Adapter state = 11
,V/BluetoothSapReceiver( 5988): startService = false
,D/AuthorizationBluetoothService( 1858): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
I/qcom-bluetooth( 6077): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,D/wpa_supplicant( 6052): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6052): TDLS: Driver uses external link setup
D/wpa_supplicant( 6052): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6052): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6052): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6052): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6052): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6052): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6052): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6052): Using existing control interface directory.
D/wpa_supplicant( 6052): P2P: Add operating class 81
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
,D/wpa_supplicant( 6052): P2P: Own listen channel: 81:11,
D/wpa_supplicant( 6052): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6052): P2P: initialized
,D/wpa_supplicant( 6052): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6052): P2P: cli_channels:
D/wpa_supplicant( 6052): p2p0: Added interface p2p0
D/wpa_supplicant( 6052): p2p0: State: INACTIVE -> DISCONNECTED
,D/wpa_supplicant( 6052): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6052): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6052): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6052): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6052): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6052): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6052): disable_scan_offload=1
,D/wpa_supplicant( 6052): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6052): update_config=1
D/wpa_supplicant( 6052): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6052): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6052): manufacturer='HTC'
D/wpa_supplicant( 6052): model_name='HTC One M8s'
D/wpa_supplicant( 6052): model_number='HTC One M8s'
D/wpa_supplicant( 6052): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6052): hs20=1
D/wpa_supplicant( 6052): interworking=1
D/wpa_supplicant( 6052): external_sim=1
D/wpa_supplicant( 6052): key_mgmt_offload=1
,I/qcom-bluetooth( 6085): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6086): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6055): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6055): updateWidget(context) for widget: 
,I/ActivityManager(  910): Killing 4561:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=4561
,D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/qcom-bluetooth( 6088): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6089): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,D/wpa_supplicant( 6052): Priority group 338,
D/wpa_supplicant( 6052):    id=0 ssid='NG700'
I/wpa_supplicant( 6052): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6052): nl80211: RFKILL status not available
D/wpa_supplicant( 6052): nl80211: Using driver-based roaming
D/wpa_supplicant( 6052): nl80211: TDLS supported
D/wpa_supplicant( 6052): nl80211: TDLS external setup
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6052): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6052): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
I/qcom-bluetooth( 6090): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Suppor,ted key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6052): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6052): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6052): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6052): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6052): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6052): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6052): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6052): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6052): nl80211: Subscribe to mgmt frames with non-AP handle 0x559751c100
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=0104
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=040a
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=040b
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=040c
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=040d
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=090a
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=090b
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=090c
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=090d
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=0409506f9a09
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=7f506f9a09
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=0801
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=040e
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=06
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=0a07
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=0a11
D/wpa_supplicant( 6052): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x559751c100 match=0a1a
D/wpa_supplicant( 6052): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6052): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6052): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6052): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6052): htc_wext_command_init +
I/wpa_supplicant( 6052): htc_wext_command_init -
I/wpa_supplicant( 6052): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6052): Don't set 00 to countryID.conf
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6052): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6052): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/Tethering(  910): interfaceLinkStateChanged wlan0, false
D/Tethering(  910): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6052): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6052): P2P: Add operating class 81
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6052): P2P: Update channel list
D/wpa_supplicant( 6052): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6052): P2P: cli_channels:
D/wpa_supplicant( 6052): p2p0: Updating hw mode
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6052): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6052): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6052): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
I/qcom-bluetooth( 6091): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/ActivityManager(  910): Recipient 4561
,I/wpa_supplicant( 6052): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 6052):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6052):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6052):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6052): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6052): nl80211: Flush PMKIDs
,D/wpa_supplicant( 6052): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 6052): TDLS: Driver uses external link setup
D/wpa_supplicant( 6052): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6052): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6052): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6052): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6052): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6052): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6052): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6052): Using existing control interface directory.
I/wpa_supplicant( 6052): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6052): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
,D/wpa_supplicant( 6052): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6052): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6052): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 6052): P2P: Add operating class 81
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6052): P2P: Add operating class 115
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6052): P2P: Add operating class 116
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6052): P2P: Add operating class 117
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6052): P2P: Update channel list
D/wpa_supplicant( 6052): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6052): P2P: cli_channels:
D/wpa_supplicant( 6052): p2p0: Updating hw mode
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6052): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
,I/wpa_supplicant( 6052): Auto country group 1: ch36
D/wpa_supplicant( 6052): wlan0: Added interface wlan0
D/wpa_supplicant( 6052): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6052): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6052): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6052): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 6052): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6052): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_910-2\x00
D/wpa_supplicant( 6052): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6052): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
I/qcom-bluetooth( 6094): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
E/WifiStateMachine(  910): transitionTo: destState=SupplicantStartingState
D/wpa_supplicant( 6052): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6052): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6052): nl80211: Regulatory domain change
D/wpa_supplicant( 6052):  * initiator=1
D/wpa_supplicant( 6052):  * type=0
D/wpa_supplicant( 6052):  * alpha2=DE
D/wpa_supplicant( 6052): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6052): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  910): handleMessage: new destination call exit/enter
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6052): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/WifiMonitor(  910): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6052): P2P: Add operating class 81
E/WifiStateMachine(  910): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6052): P2P: Add operating class 115
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6052): P2P: Add operating class 116
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=2): 24 2c
E/WifiStateMachine(  910): invokeExitMethods: InitialState
,D/wpa_supplicant( 6052): P2P: Add operating class 117
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6052): P2P: Update channel list
D/wpa_supplicant( 6052): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6052): P2P: cli_channels:
D/wpa_supplicant( 6052): p2p0: Updating hw mode
,E/WifiStateMachine(  910): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  910): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  910): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131144
E/WifiStateMachine(  910): processMsg: SupplicantStartingState
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6052): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
E/WifiMonitor(  910): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  910): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  910): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  910):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  910): deferMessage: msg=131144
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131085
E/WifiStateMachine(  910): processMsg: SupplicantStartingState
E/WifiStateMachine(  910):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  910): deferMessage: msg=131085
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131149
E/WifiStateMachine(  910): processMsg: SupplicantStartingState
E/WifiStateMachine(  910):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  910): processMsg: DefaultState
E/WifiStateMachine(  910):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  910): setSuspendOptimizations: 2 true
E/WifiStateMachine(  910): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131101
E/WifiStateMachine(  910): processMsg: SupplicantStartingState
E/WifiStateMachine(  910):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  910): processMsg: DefaultState
E/WifiStateMachine(  910):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131101
E/WifiStateMachine(  910): processMsg: SupplicantStartingState
E/WifiStateMachine(  910):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  910): processMsg: DefaultState
E/WifiStateMachine(  910):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  910): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  910): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=147457
E/WifiStateMachine(  910): processMsg: SupplicantStartingState
E/WifiStateMachine(  910):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,E/WifiStateMachine(  910): Supplicant connection established
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6052): set wifi ON
E/WifiStateMachine(  910): setWifiState: enabled
E/WifiStateMachine(  910): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  910):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6052): SET_SCREEN_ON:Off
I/wpa_supplicant( 6052): htc_wext_set_keepalive +
I/wpa_supplicant( 6052): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6052): getPrivFuncNum +	
I/wpa_supplicant( 6052): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6052): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6052): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6052): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6052): htc_wext_set_keepalive gateway addr = 00000000
,I/wpa_supplicant( 6052): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  910): startHal
,I/qcom-bluetooth( 6096): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,E/wifi    (  910): getStaticLongField sWifiHalHandle 0x7f71804300
,I/WifiNative-HAL(  910): Could not start hal
E/WifiStateMachine(  910): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/WifiStateMachine(  910): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  910): handleScreenStateChanged Exit: false
I/IntentController( 1217): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1217): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER MACADDR'
D/HtcWiFiWidget_WiFiWidgetProvider( 6055): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6055): updateWidget(context) for widget: 
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6052): update_config=1
D/wpa_supplicant( 6052): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  910): Loading config and enabling all networks 
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6052): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6052): wpa_supplicant_ctrl_iface_list_networks: return size = 47
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid",
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='priority'
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
,D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6052): Do not allow key_data field to be exposed
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
,D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 phase2'
,D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
,D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6052): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6052): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,E/WifiConfigStore(  910): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe",
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6052): device_name='m8qlul_htc_europe'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6052): manufacturer='HTC'
I/bt-btu  ( 5988): btu_task received preload complete event
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x001f
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6052): model_name='HTC One M8s'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6052): model_number='HTC One M8s'
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x1487
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6052): config_methods='physical_display virtual_push_button'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,D/PMS     (  910): acquireWL(c87e98a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5988 1002 null
E/WifiStateMachine(  910): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  910): handleMessage: new destination call exit/enter
W/Settings( 5694): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiStateMachine(  910): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  910): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  910): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  910): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  910): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  910): invokeEnterMethods: SupplicantStartedState
D/bt-btm  ( 5988): btm_acl_device_down
D/bt-btm  ( 5988): btm_acl_reset_paging
D/WifiP2pService(  910): P2pDisabledState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-btm  ( 5988): btm_acl_set_discing
D/WifiP2pService(  910): DefaultState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6052): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  910): Setting external_sim to 1
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6052): external_sim=1
D/WifiStateMachine(  910): Setting OUI to DA-A1-19
I/WifiNative-HAL(  910): startHal
E/wifi    (  910): getStaticLongField sWifiHalHandle 0x7f71804360
I/WifiNative-HAL(  910): Could not start hal
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6052): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  910): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  910): Driverstarted State enter
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
,E/WifiStateMachine(  910): DriverStartedState call setCountryCode()
E/WifiStateMachine(  910): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  910): NetworkAgent == null
,E/WifiStateMachine(  910): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
E/WifiTrafficPoller(  910): ENABLE_TRAFFIC_STATS_POLL false Token 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
D/WIFI_ICON( 1217): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,I/IntentController( 1217): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,D/WifiDataStallTracker(  910): setDhcpActive: false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6052): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  910): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  910): transitionTo: destState=DisconnectedState
D/StatusBar.NetworkController( 1217): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiMonitor(  910): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/native  (  910): do suspend false
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  910): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/HTCRequest(  910): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6052): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
I/QuickSettingWifi( 1217): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
D/WifiMonitor(  910): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/WifiP2pService(  910): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  910): Driverstarted State enter done
E/WifiStateMachine(  910): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  910): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  910): handleMessage: new destination call exit/enter
E/WifiStateMachine(  910): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  910): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  910): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  910): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  910): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  910): invokeEnterMethods: DisconnectedState
D/WifiScanningService(  910): SCAN_AVAILABLE : 3
E/WifiStateMachine(  910): DisconnectedState call setCountryCode()
D/RttService(  910): SCAN_AVAILABLE : 3
E/WifiStateMachine(  910):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
D/WifiScanningService(  910): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  910): startHal
E/wifi    (  910): getStaticLongField sWifiHalHandle 0x7f6f10c520
D/RttService(  910): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  910): Could not start hal
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6052): wlan0: nl80211: sched_scan request
D/libc    (  910): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,D/libc    (  910): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiScanningService(  910): could not start HAL
,D/WISPrService( 4031): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  910): New client listening to asynchronous messages,
E/WifiTrafficPoller(  910): ADD_CLIENT: 8
,D/WISPrService( 4031): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1217): receive.wifiConnect:false wifiAPname:null elapse:1,
,I/bt-btm  ( 5988): btm_reset_complete
,I/bt-btm  ( 5988): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 5988): Start reading local supported commands
,D/bt-btm  ( 5988): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 5988): BTM reads next extended features page (1)
,D/bt-btm  ( 5988): BTM reads next extended features page (2)
,D/bt-btm  ( 5988): BTM reached last extended features page (2)
D/bt-btm  ( 5988): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 5988): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,D/bt-btm  ( 5988): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 5988): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 5988): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 5988): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 5988): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 5988): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 5988): btm_read_ble_wl_size 
D/bt-btm  ( 5988): btm_read_white_list_size_complete ,
D/bt-btm  ( 5988): btm_get_ble_buffer_size 
,D/bt-btm  ( 5988): btm_read_ble_buf_size_complete 
D/bt-btm  ( 5988): btm_read_ble_local_supported_states 
,D/bt-btm  ( 5988): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 5988): btm_read_ble_local_supported_features 
D/bt-btm  ( 5988): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 5988): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 5988): btm_decode_ext_features_page page: 0
D/bt-btm  ( 5988): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 5988): Local supported SCO packet types: 0x038f
I/bt-btm  ( 5988): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 5988): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 5988): BTM_SetInquiryMode
I/bt-btm  ( 5988): BTM_SetPageScanType
I/bt-btm  ( 5988): BTM_SetInquiryScanType
D/bt-btm  ( 5988): btm_decode_ext_features_page page: 1
W/bt-btm  ( 5988): btm_decode_ext_features_page Secure conn Host support Enabled
,D/bt-btm  ( 5988): btm_decode_ext_features_page page: 2
W/bt-btm  ( 5988): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 5988): BTM_BleLoadLocalKeys
D/bt-btm  ( 5988): BTM_BleLoadLocalKeys
I/bt-btm  ( 5988): BTM_Sec: application registered
E/bt-btm  ( 5988): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf66b4d5 
I/bt-btm  ( 5988): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 5988): SMP_Register state=0
E/bt-btm  ( 5988): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf66b4d5 
I/bt-btm  ( 5988): BTM_Sec: application registered
D/bt-btm  ( 5988): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 5988): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 5988): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 5988): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 5988): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 5988): BTM_RegBusyLevelNotif
D/bt-btm  ( 5988): BTM_BleReadControllerFeatures
I/bt-btm  ( 5988): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 5988): GATT_Register
D/bt-att  ( 5988): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 5988): allocated gatt_if=3
I/bt-att  ( 5988): GATT_StartIf gatt_if=3
D/bt-att  ( 5988): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5988): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 5988): btm_ble_vendor_capability_vsc_cmpl_cback
,D/bt-btm  ( 5988): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 5988): BTM Register For VSEvents is successfully
D/bt-btm  ( 5988): BTM_BleGetVendorCapabilities
I/bt-btif ( 5988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5988): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 5988): bta_dm_set_dev_name: name: HTC One M8s 
E/bt-btif ( 5988): Calling BTA_HhEnable
I/bt-btm  ( 5988): BTA_MceEnable
I/bt-btif ( 5988): BTA_MceEnable
I/bt-btm  ( 5988):  BTM_BleConfigPrivacy
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
,I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 5988): AG evt (hdl 0x0001): State 0, Event 0x0500
E/bt-btif ( 5988): SDP_CreateRecord ok, num_records:3service_mask:0x2140040
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 5988): BTM_AllocateSCN
D/bt-btm  ( 5988): BTM_AllocateSCN
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 5988): BTM_AllocateSCN
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btm  ( 5988): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5988):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5988):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 5988): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 5988): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5988):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5988):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 5988): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/BluetoothAdapterProperties( 5988): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 5988): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
,W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 5988): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 5988): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 5988): A2D_AddRecord uuid: 110a
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
D/bt-btif ( 5988):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 5988): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btm  ( 5988): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5988):                : sec: 0x86, service name [] (up to 21 chars saved)
,I/bt-btm  ( 5988): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5988):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5988):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 5988): GATT_Register
,D/bt-att  ( 5988): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 5988): allocated gatt_if=4
I/bt-att  ( 5988): GATT_StartIf gatt_if=4
D/bt-att  ( 5988): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5988): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 5988): Scan Mode:21
D/BluetoothAdapterProperties( 5988): Discoverable Timeout:120
I/bt-btif ( 5988): BTA_JvEnable
I/bt-btif ( 5988): BTA_JvRegisterL2cCback
I/bt-btm  ( 5988): BTM_ReadConnectability
I/bt-btm  ( 5988): BTM_ReadDiscoverability
I/bt-btm  ( 5988): BTM_SetDiscoverability
I/bt-btm  ( 5988): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
,D/bt-btm  ( 5988): disc_mode 0002
D/bt-btm  ( 5988): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 5988): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5988): BTM_SetConnectability
I/bt-btm  ( 5988): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5988): disc_mode 0002
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 5988): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 5988): BTM_SetDiscoverability
I/bt-btm  ( 5988): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5988): disc_mode 0000
,I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5988): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 5988): BTM_SetConnectability
I/bt-btm  ( 5988): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5988): disc_mode 0000
D/bt-btm  ( 5988): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 5988): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
I/bt-btm  ( 5988): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5988): bta_pan_co_init
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:8
,I/bt-btm  ( 5988): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5988):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5988):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btm  ( 5988): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5988):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5988): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5988):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
,I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 3a 14 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = a0 38 43 3c a2 59 91 b7 0e 78 1a c2 4e 14 89 77 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
,I/bt-btif ( 5988): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 5988): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 5988): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5988): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5988): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 5988): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
,D/BluetoothAdapterState( 5988): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5988): ScanMode =  21
D/BluetoothAdapterProperties( 5988): State =  11
D/BluetoothAdapterProperties( 5988): Setting state to 12
I/BluetoothAdapterState( 5988): Bluetooth adapter state changed: 11-> 12
I/bt-btif ( 5988): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5988): Discoverable Timeout:120
D/BluetoothManagerService(  910): +onBluetoothStateChange prev=11 new=12
,D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 5988): Entering On State
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
,I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = b5 49 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = f4 38 2c 3f aa 4e 12 dd 70 b8 1c ae ea c7 2e 89 
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  910): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  910): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1456): onBluetoothStateChange: up=true
,E/bt_mct  ( 5988): hci lib postload completed
D/BluetoothA2dp(  910): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1217): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1456): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1456): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  910): Bluetooth State Change Intent: 11 -> 12
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 8f 41 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 9b ee 28 46 14 5f 41 86 34 8f 00 72 15 11 eb 33 
D/NGFService( 3489): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3489): Bluetooth Adapter: ON
,I/IntentController( 1217): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothManagerService(  910): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  910): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  910): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapReceiver( 5988): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5988): ***********state = 12
,D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 23 5b 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = f1 ed f7 b6 12 df 97 1a c3 87 71 3a 12 25 25 a0 
,D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 7d 93 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = f3 b2 82 7a f4 83 17 23 93 01 18 c0 b7 0a 53 8f 
,D/PMS     (  910): acquireWL(1d831456): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 4031 1000 null
,W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 67 8d 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 27 3a 82 7a f9 94 9d 1a c6 cd 1d 63 57 1f 3f d6 
,D/bt-btm  ( 5988): btm_ble_rand_enc_complete,
D/PMS     (  910): releaseWL(1d831456): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/PMS     (  910): acquireWL(134729c4): PARTIAL_WAKE_LOCK  StartingDockService 0x1 4031 1000 null
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 63 70 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = b4 cb 9b 81 e4 e2 21 6a 0c 74 9a be 96 b4 45 f6 
V/BluetoothPbapService( 5988): Pbap Service onCreate
V/BluetoothPbapService( 5988): Starting PBAP service
D/BluetoothAdapter( 5988): 1038688771: getState(). Returning 12
D/HtcBtWidget_BTWidgetProvider( 6023): onBTStateChanged() for widget: 
V/BluetoothPbapService( 5988): Handler(): got msg=1
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 6d 95 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = a1 98 c9 b6 ff 7e 5c 66 0a 61 af 4d 5e a6 fc c5 
V/BluetoothPbapService( 5988): Pbap Service startRfcommSocketListener
D/HtcBtWidget_BTWidgetProvider( 6023): updateWidget(context) for widget: 
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): java.lang.Throwable: stack dump
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1341fe2:true
V/BluetoothPbapService( 5988): Pbap Service initSocket
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:454)
D/wpa_supplicant( 6052): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 95 f8 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
,D/wpa_supplicant( 6052): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 6f 1e b9 20 0f 1f 51 da d1 c2 1f a7 cc 4e 28 ac 
D/wpa_supplicant( 6052): wlan0: nl80211: Sched scan started
E/WifiStateMachine(  910): handleMessage: X
D/WifiP2pService(  910): P2pEnablingState
E/WifiStateMachine(  910): handleMessage: E msg.what=131144
E/WifiStateMachine(  910): processMsg: DisconnectedState
D/WifiMonitor(  910): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine(  910):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131085
E/WifiStateMachine(  910): processMsg: DisconnectedState
E/WifiStateMachine(  910):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  910): processMsg: ConnectModeState
E/WifiStateMachine(  910):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  910): processMsg: DriverStartedState
E/WifiStateMachine(  910):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131154
E/WifiStateMachine(  910): processMsg: DisconnectedState
E/WifiStateMachine(  910):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  910): processMsg: ConnectModeState
E/WifiStateMachine(  910):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  910): processMsg: DriverStartedState
E/WifiStateMachine(  910):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  910): processMsg: SupplicantStartedState
E/WifiStateMachine(  910):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine(  910): processMsg: DefaultState
,E/WifiStateMachine(  910):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=131323
E/WifiStateMachine(  910): processMsg: DisconnectedState
E/WifiStateMachine(  910):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  910): processMsg: ConnectModeState
E/WifiStateMachine(  910):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  910): processMsg: DriverStartedState
E/WifiStateMachine(  910):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  910): processMsg: SupplicantStartedState
E/WifiStateMachine(  910):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  910): processMsg: DefaultState
,E/WifiStateMachine(  910):  DefaultState what:131323 0 0
,E/WifiStateMachine(  910): setOperatorSSID enter
E/WifiStateMachine(  910): handleMessage: X
W/BluetoothAdapter( 5988): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine(  910): handleMessage: E msg.what=131104
E/WifiStateMachine(  910): processMsg: DisconnectedState
E/WifiStateMachine(  910):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  910): processMsg: ConnectModeState
E/WifiStateMachine(  910):  ConnectModeState what:131104 0 0
W/Settings(  910): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6052): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6052): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6052): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
I/bt-btif ( 5988): BTA_JvCreateRecordByUser
D/bt-btm  ( 5988): BTA_JvCreateRecordByUser
I/bt-btm  ( 5988): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = 3e e2 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
I/bt-btif ( 5988): Encrypted textcks->adapter_properties_cb
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = ee f3 be ac 96 92 97 12 f4 d4 45 82 9e c4 81 06 
I/bt-btm  ( 5988): BTM_SetDiscoverability
I/bt-btm  ( 5988): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5988): disc_mode 0000
I/bt-btm  ( 5988): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5988): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5988): BTM_SetConnectability
I/bt-btm  ( 5988): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5988): disc_mode 0000
D/bt-btm  ( 5988): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 5988): btm_ble_update_adv_flag old=0x1c
E/WifiStateMachine(  910): handleMessage: X
I/bt-btm  ( 5988): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:10
E/WifiStateMachine(  910): handleMessage: E msg.what=131162
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
E/WifiStateMachine(  910): processMsg: DisconnectedState
I/bt-btif ( 5988): BTA_JvRfcommStartServer
E/WifiStateMachine(  910):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  910): processMsg: ConnectModeState
E/WifiStateMachine(  910):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  910): processMsg: DriverStartedState
D/BluetoothAdapterProperties( 5988): Scan Mode:21
E/WifiStateMachine(  910):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  910): set frequency band 0
I/bt-btm  ( 5988): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 5988):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6052): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6052): SETBAND: 0
D/wpa_supplicant( 6052): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6052): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6052): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  910): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  910): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  910): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  910): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6052): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz ,20 mBm
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
V/BluetoothPbapService( 5988): Succeed to create listening socket 
V/BluetoothPbapService( 5988): Accepting socket connection...
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6052): P2P: Add operating class 81
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6052): P2P: Add operating class 115
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6052): P2P: Add operating class 116
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6052): P2P: Add operating class 117
D/wpa_supplicant( 6052): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6052): P2P: Update channel list
D/wpa_supplicant( 6052): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6052): P2P: cli_channels:
D/wpa_supplicant( 6052): p2p0: Updating hw mode
D/wpa_supplicant( 6052): nl80211: Regulatory information - country=DE
,D/wpa_supplicant( 6052): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/WifiP2pService(  910): P2pEnablingState{ when=-16ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6052): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/WifiP2pService(  910): P2p socket connection successful
D/wpa_supplicant( 6052): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/WifiP2pService(  910): P2pEnabledState
D/wpa_supplicant( 6052): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6052): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6052): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  910): did set frequency band 0
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6052): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  910): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6052): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6052): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6052): wlan0: Cancelling sched scan
D/wpa_supplicant( 6052): nl80211: Sched scan stop sent (ret=0)
D/WifiP2pService(  910): sending p2p connection changed broadcast
D/wpa_supplicant( 6052): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6052): wpa_supplicant_scan enter
D/wpa_supplicant( 6052): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6052): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6052): wlan0: nl80211: Sched scan stopped
D/WifiDisplayController(  910): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/wpa_supplicant( 6052): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  910): done set frequency band 0
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
V/AudioService(  910): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  910):     Client/Owner: Client
V/AudioService(  910):     GroupId: 
V/AudioService(  910):     Passphrase: 
V/AudioService(  910):     SessionId: 0
V/AudioService(  910):     IP Address: }
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
D/bt-smp  ( 5988): smp_encrypt_data
D/HtcEffectManagerBase(  910): onEventChanged id=5 status=false
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = dc fe 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = dc 22 73 a3 b3 b8 3b 4f 3d c0 52 fd 72 3a 8f 71 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
D/HtcEffectManager(  910): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  910): convertEffect before=902
D/HtcEffectManager(  910): convertEffect after=902
D/BluetoothAdapter( 1217): 381130289: getState(). Returning 12
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/WifiStateMachine(  910): Wifi band: 0, ScanBroadCastCounter: 0
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/WifiStateMachine(  910): [M,LHD] enter handleMediaLinkEvent DriverStartedState
D/wpa_supplicant( 6052): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6052): p2p0: Control interface command 'SET persistent_reconnect 1'
E/WifiStateMachine(  910): handleMessage: X
D/wpa_supplicant( 6052): CTRL_IFACE SET 'persistent_reconnect'='1'
D/WifiDisplayController(  910): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/wpa_supplicant( 6052): persistent_reconnect=1
E/WifiStateMachine(  910): handleMessage: E msg.what=147462
D/WifiDisplayController(  910): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 6052): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
E/WifiStateMachine(  910): processMsg: DisconnectedState
D/wpa_supplicant( 6052): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6052): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  910):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=131468  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  910): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  910): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  910): processMsg: ConnectModeState
D/BluetoothAdapter( 1217): 381130289: getState(). Returning 12
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  910):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=131469  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  910): handleMessage: X
E/WifiStateMachine(  910): handleMessage: E msg.what=143371
E/WifiStateMachine(  910): processMsg: DisconnectedState
E/WifiStateMachine(  910):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  910): processMsg: ConnectModeState
E/WifiStateMachine(  910):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  910): processMsg: DriverStartedState
E/WifiStateMachine(  910):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  910): processMsg: SupplicantStartedState
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6052): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6052): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'device_name'='Android_608e'
E/WifiStateMachine(  910):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/wpa_supplicant( 6052): device_name='Android_608e'
E/WifiStateMachine(  910): processMsg: DefaultState
E/WifiStateMachine(  910):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  910): handleMessage: X
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6052): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6052): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6052): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6052): P2P: New SSID postfix: -Android_608e
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6052): GLOBAL_CTRL_IFACE SE,T 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6052): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  910): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6052): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6052): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6052): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6052): config_methods='virtual_push_button physical_display keypad'
D/WifiP2pService(  910): DeviceAddress: 92:e7:c4:e6:4c:f8
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6052): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6052): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6052): Single channel concurrency preference: sta
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = ee 46 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 5f 99 d1 44 c6 c7 ee ce cd 0e 6a cb 33 6e ce 4c 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
D/WifiNative-HAL(  910): p2pGetDeviceAddress
W/WifiHW  (  910): QCOM Debug wifi_send_command "STATUS"
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  910): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
I/QuickSettingBluetooth( 1217): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1217): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 6052): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6052): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6052): P2P: Stopping find
D/wpa_supplicant( 6052): P2P: Clear timeout (state=IDLE)
D/WifiDisplayController(  910): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  910):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  910):  primary type: 10-0050F204-5
D/WifiDisplayController(  910):  secondary type: null
D/WifiDisplayController(  910):  wps: 0
D/WifiDisplayController(  910):  grpcapab: 0
D/WifiDisplayController(  910):  devcapab: 0
D/WifiDisplayController(  910):  status: 3
D/WifiDisplayController(  910):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  910):  WFD CtrlPort: 0
D/WifiDisplayController(  910):  WFD MaxThroughput: 0
D/wpa_supplicant( 6052): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6052): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6052): P2P: Stopping find
D/wpa_supplicant( 6052): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6052): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6052): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  910): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/BluetoothAdapter( 4031): 644009595: getState(). Returning 12
D/wpa_supplicant( 6052): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6052): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  910): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6052): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6052): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  910): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 6052): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6052): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6052): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6052): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6052): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6052): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6052): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  910): sending p2p persistent groups changed broadcast
D/WifiP2pService(  910): InactiveState
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = a3 36 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 24 aa 1b be 76 c2 21 02 f2 00 1a a9 1c cb 72 dd 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
D/BluetoothInputDevice( 4031): BluetoothInputDevice()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 7
D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = ec cd 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 8c c9 05 04 18 4a 50 21 7d c4 a7 b4 02 a2 94 96 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
D/BluetoothPan( 4031): BluetoothPan()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 8
D/BluetoothMap( 4031): Create BluetoothMap proxy object
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/wpa_supplicant( 6052): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 9
D/Tethering(  910): interfaceLinkStateChanged p2p0, false
D/Tethering(  910): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  910): WiFiDisplay: getWifidisplayApEnabled=false
E/BluetoothMap( 4031): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 10
D/BluetoothSap( 4031): BluetoothSap() call bindService
W/ContextImpl( 4031): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/BluetoothPbap( 4031): BluetoothPbap()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 11
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 12
D/BluetoothHeadset( 4031): BluetoothHeadset()
D/BluetoothManagerService(  910): registerStateChangeCallback+
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  910): Registered receivers: 13
,I/art     (  910): Explicit concurrent mark sweep GC freed 28874(1543KB) AllocSpace objects, 4(692KB) LOS objects, 33% free, 16MB/24MB, paused 1.500ms total 146.621ms,
,D/LocalBluetoothProfileManager( 4031): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 4031): finishStartingService: stopping service
D/BluetoothA2dp( 4031): Proxy object connected
V/BluetoothPbapService( 5988): Pbap Service onBind
,D/A2dpProfile( 4031): Bluetooth service connected
,D/BluetoothAdapter( 4031): 644009595: getState(). Returning 12
D/BluetoothInputDevice( 4031): Proxy object connected
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HidProfile( 4031): Bluetooth service connected
,W/BluetoothAdapter( 5988): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapter( 4031): 644009595: getState(). Returning 12
I/bt-btif ( 5988): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:11
,I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btif ( 5988): BTA_JvRfcommStartServer
,I/bt-btm  ( 5988): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 5988):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 5988): Accept thread started.
D/BluetoothHeadset( 4031): Proxy object connected
D/HeadsetProfile( 4031): Bluetooth service connected
D/BluetoothAdapter( 4031): 644009595: getState(). Returning 12
,D/BluetoothPan( 4031): BluetoothPAN Proxy object connected,
,D/PanProfile( 4031): Bluetooth service connected
D/PMS     (  910): releaseWL(134729c4): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothPbap( 4031): Proxy object connected
,D/BluetoothAdapter( 5988): 1038688771: getState(). Returning 12
D/BluetoothFtpService( 5988): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 5988): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 5988):  call MAP start service
D/PbapServerProfile( 4031): Bluetooth service connected
,D/BluetoothFtpService( 5988): htc sense version is 6.0,
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5988): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5988): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:12,
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btif ( 5988): BTA_JvRfcommStartServer
I/bt-btm  ( 5988): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 5988):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 5988): Run Accept thread
E/BluetoothMasService( 5988): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 5988): Add permission for SmsProvider.
,V/BluetoothMasService( 5988): Starting MAS instances
,D/BluetoothAdapter( 5988): 1038688771: getState(). Returning 12
,I/MailMessageReceiver( 5988): reg:com.android.bluetooth.btservice.AdapterApp@211d9498 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@226ec4f1,
,I/MailManager( 5988): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@226ec4f1
V/EmailUtils( 5988): Manager Instance is not NULL
,I/ActivityManager(  910): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6115 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,I/art     (  407): Explicit concurrent mark sweep GC freed 8651(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 270us total 17.621ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 255us total 17.340ms,
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 268us total 17.806ms
,D/HtcAdjCursorFactory( 6115): Set CursorWindow size to: 4194304 KB, Tid: 6134
,D/EmailUtils( 5988): ============NULL aList========
V/EmailUtils( 5988): <-getEmailAccountIdList,
,V/BluetoothMasService( 5988): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 5988): 1038688771: getState(). Returning 12
,V/BluetoothMasService( 5988): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 5988): Manager Instance is not NULL
,D/EmailUtils( 5988): ============NULL aList========
V/EmailUtils( 5988): <-getEmailAccountIdList
V/BluetoothSapReceiver( 5988): SapReceiver onReceive 
V/BluetoothSapReceiver( 5988): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5988):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 5988): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 5988): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 5988): BluetoothMns: isEmailEnabled: true
,D/AuthorizationBluetoothService( 1858): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5988): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5988): BTA_JvCreateRecordByUser
,D/bt-btm  ( 5988): BTM_AllocateSCN
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btif ( 5988): BTA_JvRfcommStartServer
I/bt-btm  ( 5988): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 5988):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,W/BluetoothAdapter( 5988): getBluetoothService() called with no BluetoothManagerCallback,
,I/bt-btif ( 5988): BTA_JvCreateRecordByUser
D/bt-btm  ( 5988): BTM_AllocateSCN
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
,I/bt-btif ( 5988): BTA_JvRfcommStartServer
I/bt-btm  ( 5988): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 5988):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  910): killProcessQuiet, pid=5646
,I/ActivityManager(  910): Killing 5646:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/wpa_supplicant( 6052): EAPOL: disable timer tick
,I/ActivityManager(  910): Recipient 5646,
,V/BluetoothSapService( 5988): Sap Service onCreate,
V/BluetoothSapService( 5988): initBinder
,V/BluetoothSapService( 5988): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@1a36244,
V/BluetoothSapService( 5988): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@44c62
V/BluetoothSapService( 5988): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 5988): state: 12,
D/SapServerProfile( 4031): Bluetooth service connected
,V/BluetoothSapService( 5988): Starting SAP server process,
,D/A2dpService( 5988): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@5965eb0,
,D/A2dpSinkService( 5988): getA2dpSinkService(): service is NULL
,V/BluetoothSapService( 5988): SAP Service startRfcommListenerThread,
,V/BluetoothSapService( 5988): Sap Service initRfcommSocket,
D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5988): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5988): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5988): SDP_CreateRecord ok, num_records:15
,I/bt-btm  ( 5988): Write Extended Inquiry Response to controller
I/bt-btif ( 5988): BTA_JvRfcommStartServer
I/bt-btm  ( 5988): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 5988):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 5988): Succeed to create listening socket 
V/BluetoothSapService( 5988): Accepting socket connection...
,D/wpa_supplicant( 6052): EAPOL: disable timer tick,
,I/jxcore-log( 5932): BLE advertisement not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 5932): 
,D/PMS     (  910): releaseWL(c87e98a): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  910): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  910): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  910): acquireWL(39ea6c9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 910 1000 WorkSource{10024},
V/AlarmManager(  910): sending alarm PendingIntent{2f0359cb: PendingIntentRecord{7cb45a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142870, Int=0,
,V/AlarmManager(  910): sending alarm PendingIntent{8b608c1: PendingIntentRecord{2b8e38e2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=157535, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{158c1843: PendingIntentRecord{22dceec0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146710, Int=0
,D/PMS     (  910): acquireWL(3272b866): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1858 10024 WorkSource{10024 com.google.android.gms},
D/libc    (  910): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  910): [NET] android_getaddrinfofornet-, err=8
D/libc    (  910): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  910): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  910): [NET] android_getaddrinfo_proxy+
D/libc    (  910): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/PMS     (  910): releaseWL(39ea6c9a): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1858): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  910): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    ( 1858): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1858): [NET] android_getaddrinfo_proxy+
D/libc    ( 1858): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1858): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  910): releaseWL(3272b866): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl(  910): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  910): acquireWL(33ebc7a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null,
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/BatteryService(  910): n_update end
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/PMS     (  910): releaseWL(33ebc7a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/NotificationService(  910): plugged=true pluggin=true
D/WifiController(  910): handleMessage: E msg.what=155652
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
D/WifiController(  910): processMsg: DeviceActiveState
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): processMsg: DefaultState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  910): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1456): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1217): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
,D/HtcAppUPService( 1412): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@ad7dde3
I/ActivityManager(  910): Killing 5440:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=5440
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  910): Recipient 5440
,D/PMS     (  910): acquireWL(4631454): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 910 1000 WorkSource{1000},
V/AlarmManager(  910): sending alarm PendingIntent{4d87c7e: PendingIntentRecord{d8f95df android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=164470, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{1b596ffd: PendingIntentRecord{3fe1f4f2 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=207471, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{158c1843: PendingIntentRecord{22dceec0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=217556, Int=0,
V/AlarmManager(  910): sending alarm PendingIntent{31033743: PendingIntentRecord{1a0721c0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185043, Int=0
,D/libc    (  910): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/libc    (  910): [NET] android_getaddrinfofornet-, err=8
D/libc    (  910): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024,
D/libc    (  910): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  910): [NET] android_getaddrinfo_proxy+
D/libc    (  910): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  910): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  910): acquireWL(1bd20ef9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  910): releaseWL(1bd20ef9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  910): releaseWL(4631454): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1217): Weather sync is On
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/UsbnetService(  910): BroadcastReceiver::onReceive+,
D/PMS     (  910): acquireWL(3c9ba1b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/BatteryService(  910): n_update end
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  910): releaseWL(3c9ba1b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/WifiController(  910): handleMessage: E msg.what=155652
,D/NotificationService(  910): plugged=true pluggin=true
D/WifiController(  910): processMsg: DeviceActiveState
D/PMS     (  910): runPSCheck
D/WifiController(  910): processMsg: StaEnabledState
D/HtcPowerSaver(  910): Checking...
D/WifiController(  910): processMsg: DefaultState
I/HtcPowerSaver(  910): >> updateStatus
D/WifiController(  910): handleMessage: X
D/WifiController(  910): battery changed pluggedType: 2
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  910): acquireWL(87304a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4d87c7e: PendingIntentRecord{d8f95df android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=224470, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{d824bbb: PendingIntentRecord{2b8e38e2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=286205, Int=0
,D/PMS     (  910): acquireWL(2231a431): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  910): sending alarm PendingIntent{1e100716: PendingIntentRecord{3fffe897 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450201917668, Int=0
,D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1858): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1858): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1858): [NET] android_getaddrinfo_proxy+
D/libc    ( 1858): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1858): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  910): releaseWL(2231a431): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  910): releaseWL(87304a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On
,W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  910): acquireWL(349e3a84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null,
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(349e3a84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PowerUI ( 1217): closing low battery warning: level=100
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  910): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  910): Checking...
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  910): >> updateStatus
D/WifiController(  910): handleMessage: E msg.what=155652
D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1858): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1858): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1858): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1858): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActionCombine( 1858): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,W/ResourcesManager( 1217): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1217): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1858): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1858): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1858): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/PlayEventLogger( 5368): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5368): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1217): apply : com.google.android.gms 0 13 6 40
,W/System  ( 5368): Ignoring header User-Agent because its value was null.
,D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5368): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5368): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5368): [NET] android_getaddrinfo_proxy+
D/libc    ( 5368): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5368): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  910): acquireWL(ab661c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(ab661c6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  910): plugged=true pluggin=true
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  910): updateBatteryInfo
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/PMS     (  910): runPSCheck
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): Checking...
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/WifiController(  910): handleMessage: E msg.what=155652
D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): battery changed pluggedType: 2
,D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  910): acquireWL(6962587): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(6962587): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  910): plugged=true pluggin=true
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  910): Checking...
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  910): battery changed pluggedType: 2
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): handleMessage: E msg.what=155652
D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  910): acquireWL(1ac74cb4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(1ac74cb4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PowerUI ( 1217): closing low battery warning: level=100
D/PMS     (  910): runPSCheck
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): Checking...
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  910): << updateStatus
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): handleMessage: E msg.what=155652
D/WifiController(  910): processMsg: DeviceActiveState
,D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(2772b0dd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4d87c7e: PendingIntentRecord{d8f95df android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=344470, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{25a6d452: PendingIntentRecord{2b8e38e2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=599448, Int=0
,D/PMS     (  910): acquireWL(26259323): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1858): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1858): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1858): [NET] android_getaddrinfo_proxy+
D/libc    ( 1858): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1858): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  910): releaseWL(26259323): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  910): releaseWL(2772b0dd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1456): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1456): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1456): sku_id=118
D/ContactMessageStore( 1456): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1456): start background delete task...
,D/ContactMessageStore( 1456): size: 0 , 0
,D/ContactMessageStore( 1456): Background delete complete
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1858): Explicit concurrent mark sweep GC freed 19100(1095KB) AllocSpace objects, 3(252KB) LOS objects, 49% free, 4MB/8MB, paused 1.098ms total 71.756ms,
,I/GLSUser ( 1858): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1858): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1858): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1858): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1858): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1858): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1858): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5368): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5368): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5368): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5368): Ignoring header User-Agent because its value was null.
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5368): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5368): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5368): [NET] android_getaddrinfo_proxy+
D/libc    ( 5368): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5368): [NET] android_getaddrinfo_proxy-, NODATA
,I/RemoteViews( 1217): reapply : com.google.android.gms 5 40
,D/PMS     (  910): acquireWL(e268b4d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
,I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(e268b4d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  910): updateBatteryInfo
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  910): Checking...
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  910): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  910): handleMessage: E msg.what=155652
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  910): processMsg: DeviceActiveState
I/HtcPowerSaver(  910): << updateStatus
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(f68f602): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(f68f602): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo,
D/PowerUI ( 1217): closing low battery warning: level=100
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  910): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  910): runPSCheck
,D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  910): Checking...
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): battery changed pluggedType: 2
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/WifiController(  910): handleMessage: E msg.what=155652
,D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(12318b13): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(12318b13): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo,
,D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  910): Checking...
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  910): << updateStatus
D/WifiController(  910): handleMessage: E msg.what=155652
D/NotificationService(  910): plugged=true pluggin=true
D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): processMsg: DefaultState
D/PowerUI ( 1217): closing low battery warning: level=100
D/WifiController(  910): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1858): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1858): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1858): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1858): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1858): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1858): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1858): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1217): reapply : com.google.android.gms 2 40
,E/PlayEventLogger( 5368): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5368): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5368): Ignoring header User-Agent because its value was null.
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5368): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5368): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5368): [NET] android_getaddrinfo_proxy+
D/libc    ( 5368): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5368): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  910): acquireWL(17de1bd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4d87c7e: PendingIntentRecord{d8f95df android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=644470, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{128ee3b2: PendingIntentRecord{3de35f03 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450202588829, Int=0
,D/SmartSyncUtils( 5831): isEpsOn(), nState = 0
,D/PMS     (  910): acquireWL(20148e80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5831 1000 null
,D/PMS     (  910): releaseWL(17de1bd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 5831): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5831): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5831): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5831): SettingOnTime = 1450245600000, randomSettingOnTime = 1450243387000,
D/SmartSyncScreenOnOffTimeReceiver( 5831): SettingOffTime = 1450224000000, randomSettingOffTime = 1450230934000
,D/SmartSyncScreenOnOffTimeReceiver( 5831): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5831): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5831): bNightModeTurnOffOnce = false,
,D/PMS     (  910): releaseWL(20148e80): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  910): acquireWL(232bdcb9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(232bdcb9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  910): Checking...
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): >> updateStatus
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): handleMessage: E msg.what=155652
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(70388fe): PARTIAL_WAKE_LOCK  *alarm* 0x1 910 1000 WorkSource{1002}
,V/AlarmManager(  910): sending alarm PendingIntent{2b2e85f: PendingIntentRecord{17412ac com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1031298, Int=0
I/bt-btm  ( 5988): Received oneshot timer event complete
I/bt-btm  ( 5988): btm_ble_timeout
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
,D/PMS     (  910): acquireWL(19248b75): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5988 1002 null
D/PMS     (  910): releaseWL(70388fe): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
,D/bt-btm  ( 5988): btm_ble_rand_enc_complete,
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = bb 74 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 90 41 38 21 cb 1d 7c a7 05 bd 14 44 f9 c8 58 4c 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  910): releaseWL(19248b75): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  910): acquireWL(288b370a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(288b370a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/WifiController(  910): battery changed pluggedType: 2
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  910): updateBatteryInfo
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PMS     (  910): runPSCheck
D/WifiController(  910): handleMessage: E msg.what=155652
D/HtcPowerSaver(  910): Checking...
D/WifiController(  910): processMsg: DeviceActiveState
I/HtcPowerSaver(  910): >> updateStatus
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  910): acquireWL(9c7ab7b): PARTIAL_WAKE_LOCK  *alarm* 0x1 910 1000 WorkSource{1000},
V/AlarmManager(  910): sending alarm PendingIntent{e5c2d66: PendingIntentRecord{35f898a7 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806707, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{4d87c7e: PendingIntentRecord{d8f95df android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1064471, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{1c65ad98: PendingIntentRecord{2b8e38e2 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1114029, Int=0,
D/PMS     (  910): acquireWL(2dbf69f1): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1858 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1858): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1858): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1858): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1858): [NET] android_getaddrinfo_proxy+
D/libc    ( 1858): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1858): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  910): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6167 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,V/AlarmManager(  910): sending alarm PendingIntent{2e2db9d6: PendingIntentRecord{299b8457 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450202278045, Int=0
V/AlarmManager(  910): sending alarm PendingIntent{bd40b44: PendingIntentRecord{1c3d9d56 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450202536565, Int=0
,D/PMS     (  910): releaseWL(2dbf69f1): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 5831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 5831): MY_DEBUG = false
,D/PMS     (  910): releaseWL(9c7ab7b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/PowerUsageService( 5831): repeat time = 1450203589632
,D/WeatherUtility( 1217): Weather sync is On
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,I/PowerUsageList:PowerUsageHelper( 5831): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5831): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6189): Error opening trace file: Permission denied (13),
I/dex2oat ( 6189): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m,
,I/dex2oat ( 6189): dex2oat: override thread count:4
,I/dex2oat ( 6189): dex2oat took 1.009s (threads: 4),
,I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6167): ApplicationMonitor {348a4352}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6167): PnsModel {5127bdd}: update(): Update registration caused by: alarm,
,I/PushClient( 6167): PnsConfigModel {2e889a38}: <init>(): Use dm-client for provisioning.
,W/System.err( 6167): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
W/System.err( 6167): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6167): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6167): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  910): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6196 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6196): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6196 dbg=false s=true
,I/DeviceManagement( 6196): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6196): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6196): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6196): WorkflowService: Starting workflow service
,I/DeviceManagement( 6196): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2d2b63b4] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6196): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6196): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6196): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6196): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6196): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6196): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6196): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6196): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2d2b63b4]
,I/DeviceManagement( 6196): WorkflowService: Stopping workflow service
,D/Process (  910): killProcessQuiet, pid=5318
,I/ActivityManager(  910): Killing 5318:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  910): Recipient 5318
,I/PushClient( 6167): PnsModel {5127bdd}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  910): Killing 5558:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=5558
,D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  910): Recipient 5558,
,D/PMS     (  910): acquireWL(36064486): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(36064486): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  910): Checking...
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): handleMessage: E msg.what=155652
,D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/WifiController(  910): handleMessage: X
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(2f303147): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(2f303147): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/HtcPowerSaver(  910): Checking...
I/HtcPowerSaver(  910): >> updateStatus
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1217): closing low battery warning: level=100,
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  910): << updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): battery changed pluggedType: 2
,D/WifiController(  910): handleMessage: E msg.what=155652
D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  910): User[0] Flushing usage stats to disk
,D/PMS     (  910): acquireWL(2a72cd74): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(2a72cd74): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  910): updateBatteryInfo
,D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): Checking...
D/WifiController(  910): handleMessage: E msg.what=155652
I/HtcPowerSaver(  910): >> updateStatus
D/WifiController(  910): processMsg: DeviceActiveState
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): battery changed pluggedType: 2,
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  910): << updateStatus
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1858): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1858): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1858): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1858): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/GLSActivity( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1858): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1858): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1858): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1217): reapply : com.google.android.gms 4 40,
E/PlayEventLogger( 5368): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 5368): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5368): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5368): Ignoring header User-Agent because its value was null.
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5368): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5368): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5368): [NET] android_getaddrinfo_proxy+
D/libc    ( 5368): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5368): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  910): acquireWL(122edb36): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
,D/PMS     (  910): releaseWL(122edb36): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1217): closing low battery warning: level=100
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910): BroadcastReceiver::onReceive+
,D/PMS     (  910): runPSCheck
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  910): Checking...
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  910): battery changed pluggedType: 2
,D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  910): handleMessage: E msg.what=155652
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  910): processMsg: DeviceActiveState
I/HtcPowerSaver(  910): << updateStatus
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  910): acquireWL(681fa37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(681fa37): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  910): Checking...,
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  910): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  910): handleMessage: E msg.what=155652
I/HtcPowerSaver(  910): << updateStatus
D/WifiController(  910): processMsg: DeviceActiveState
D/NotificationService(  910): plugged=true pluggin=true
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1217): closing low battery warning: level=100
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true
,I/art     (  910): Explicit concurrent mark sweep GC freed 23125(1224KB) AllocSpace objects, 10(800KB) LOS objects, 33% free, 16MB/24MB, paused 1.782ms total 192.754ms
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1858): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1858): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1858): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1858): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1858): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1858): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1858): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5368): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5368): 	at android.os.Binder.execTransact(Binder.java:454)
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/System  ( 5368): Ignoring header User-Agent because its value was null.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5368): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5368): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5368): [NET] android_getaddrinfo_proxy+
D/libc    ( 5368): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
I/RemoteViews( 1217): reapply : com.google.android.gms 2 40
D/libc    ( 5368): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  910): acquireWL(3dfb7441): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null,
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(3dfb7441): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  910): updateBatteryInfo
,D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  910): plugged=true pluggin=true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  910): runPSCheck
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  910): Checking...
D/UsbnetService(  910): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  910): >> updateStatus
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  910): battery changed pluggedType: 2
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): handleMessage: E msg.what=155652
D/WifiController(  910): processMsg: DeviceActiveState
D/WifiController(  910): processMsg: StaEnabledState
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1217): closing low battery warning: level=100
,D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  910): acquireWL(2cc27de6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/PMS     (  910): releaseWL(2cc27de6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1217): closing low battery warning: level=100
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/WifiController(  910): battery changed pluggedType: 2
D/WifiController(  910): handleMessage: E msg.what=155652
D/HtcPowerSaver(  910): updateBatteryInfo
D/WifiController(  910): processMsg: DeviceActiveState
D/PMS     (  910): runPSCheck
D/WifiController(  910): processMsg: StaEnabledState
D/HtcPowerSaver(  910): Checking...
D/WifiController(  910): processMsg: DefaultState
I/HtcPowerSaver(  910): >> updateStatus
D/WifiController(  910): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  910): acquireWL(26ea15d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 910 1000 null
I/BatteryService(  910): n_update end
D/UsbnetService(  910): BroadcastReceiver::onReceive+
D/PMS     (  910): releaseWL(26ea15d4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  910): onReceive BATTERY_CHANGED
D/UsbnetService(  910):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  910): plugged=true pluggin=true
D/UsbnetService(  910): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  910): updateBatteryInfo
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  910): battery changed pluggedType: 2
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  910): handleMessage: E msg.what=155652
D/PMS     (  910): runPSCheck
D/WifiController(  910): processMsg: DeviceActiveState
D/HtcPowerSaver(  910): Checking...
D/WifiController(  910): processMsg: StaEnabledState
I/HtcPowerSaver(  910): >> updateStatus
D/HeadsetStateMachine( 5988): Disconnected process message: 10, size: 0
D/WifiController(  910): processMsg: DefaultState
D/WifiController(  910): handleMessage: X
I/IntentController( 1217): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1217): closing low battery warning: level=100
D/PowerUI ( 1217): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  910): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  910): << updateStatus
,I/BatteryController( 1217): status:5 level:100 unsupport:false plugged:true,
,I/ProcessStatsService(  910): Prepared write state in 20ms,
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1858): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1858): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1858): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1858): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1858): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1858): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1858): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1858): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196),
W/GLSActivity( 1858): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1858): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5368): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5368): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5368): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5368): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5368): Ignoring header User-Agent because its value was null.
,D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5368): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5368): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5368): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5368): [NET] android_getaddrinfo_proxy+
I/RemoteViews( 1217): reapply : com.google.android.gms 3 40
,D/libc    ( 5368): [NET] android_getaddrinfo_proxy get netid:0
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5368): [NET] android_getaddrinfo_proxy-, NODATA
,I/ProcessStatsService(  910): Pruning old procstats: /data/system/procstats/state-2015-12-15-04-20-42.bin,
,D/PMS     (  910): acquireWL(2c9c2c96): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 910 1000 WorkSource{1000}
,V/AlarmManager(  910): sending alarm PendingIntent{4d87c7e: PendingIntentRecord{d8f95df android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1124470, Int=0
I/bt-btm  ( 5988): Received oneshot timer event complete
V/AlarmManager(  910): sending alarm PendingIntent{2618e017: PendingIntentRecord{35a89c04 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1931307, Int=0
I/bt-btm  ( 5988): btm_ble_timeout
I/bt-btm  ( 5988): btm_gen_resolvable_private_addr
,D/Process (  910): killProcessQuiet, pid=5887
I/ActivityManager(  910): Killing 5887:com.htc.calendar/u0a10 (adj 13): empty for 1817s
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  910): acquireWL(276bd5ed): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5988 1002 null
,D/bt-btm  ( 5988): btm_ble_rand_enc_complete
I/bt-btm  ( 5988): btm_gen_resolve_paddr_low
,D/bt-smp  ( 5988): smp_encrypt_data
W/bt-smp  ( 5988): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5988): Plain text(LSB ~ MSB) = fc d1 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5988): Encrypted text(LSB ~ MSB) = 40 0a 99 be 13 07 e4 be 3c 4e 37 64 1d fd d0 10 
I/bt-btm  ( 5988): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5988): Stopping oneshot timer
D/bt-btm  ( 5988): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  910): Recipient 5887
,D/Process (  910): killProcessQuiet, pid=5863
I/ActivityManager(  910): Killing 5863:com.htc.mobiledata/u0a46 (adj 13): empty for 1817s
,D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  910): Recipient 5863
,D/Process (  910): killProcessQuiet, pid=5801
I/ActivityManager(  910): Killing 5801:com.htc.bgp/u0a11 (adj 13): empty for 1818s
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  910): Recipient 5801
,D/Process (  910): killProcessQuiet, pid=5778
I/ActivityManager(  910): Killing 5778:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1823s
,D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  910): Recipient 5778
,I/ActivityManager(  910): Killing 5368:com.android.vending/u0a72 (adj 13): empty for 1831s
,D/Process (  910): killProcessQuiet, pid=5368
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  910): Recipient 5368
,D/Process (  910): killProcessQuiet, pid=4208
I/ActivityManager(  910): Killing 4208:com.google.android.gms/u0a24 (adj 15): empty for 1833s
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  910): Recipient 4208
,D/Process (  910): killProcessQuiet, pid=5724
,I/ActivityManager(  910): Killing 5724:com.htc.sense.mms/u0a64 (adj 15): empty for 1835s
D/Process (  910): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  910): Recipient 5724
,D/PMS     (  910): releaseWL(2c9c2c96): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1217): Weather sync is On,
W/WeatherTimeKeeper( 1217): [refreshWeatherData] no weather data
,D/PMS     (  910): releaseWL(276bd5ed): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,TIME-OUT KILL (timeout was 1800000ms)
```
