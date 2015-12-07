#### Test 519863404492c11_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  958): killProcessQuiet, pid=5280
--------- beginning of system
I/ActivityManager(  958): Killing 5280:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  958): Recipient 5280
D/PMS     (  958): acquireWL(8d8665e): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{1000}
V/AlarmManager(  958): sending alarm PendingIntent{3e086a3f: PendingIntentRecord{25ae9f0c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1449470957747, Int=0
D/PMS     (  958): acquireWL(f179055): PARTIAL_WAKE_LOCK  *backup* 0x1 958 1000 null
D/PMS     (  958): releaseWL(8d8665e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  958): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  958): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  958): releaseWL(f179055): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,E/cutils-trace( 6141): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6141): ====startRecUseTime====
D/htc.customization.log.level( 6141):  is 
W/CustomizationLogLevel( 6141): Level value is invalid, use default level 2
D/CustomizationManager( 6141):  Read ACC file spent 0.049 (s)
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6141): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6141): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6141): Parsing tag category name = system
I/CustomizationCIDLoader( 6141): Parsing tag category name = application
I/CustomizationCIDLoader( 6141): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6141): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6141): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6141): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6141): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6141): add string-array item, value = 42507
I/CustomizationCIDLoader( 6141): add string-array item, value = 21902
I/CustomizationCIDLoader( 6141): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6141): add string-array item, value = 23420
I/CustomizationCIDLoader( 6141): add string-array item, value = 22299
I/CustomizationCIDLoader( 6141): add string-array item, value = 24002
I/CustomizationCIDLoader( 6141): add string-array item, value = 23210
I/CustomizationCIDLoader( 6141): add string-array item, value = 23205
I/CustomizationCIDLoader( 6141): add string-array item, value = 23806
I/CustomizationCIDLoader( 6141): add string-array item, value = 23430
I/CustomizationCIDLoader( 6141): add string-array item, value = 23408
I/CustomizationCIDLoader( 6141): add string-array item, value = 27205
I/CustomizationCIDLoader( 6141): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6141): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6141):  Read CID file spent 0.106 (s)
D/CustomizationManager( 6141):  All configurations done spent 0.106 (s)
I/ActivityManager(  958): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6141 on display 0
D/PMS     (  958): acquireHCC(11c08a6a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 958 1000 null
D/PMS     (  958): acquireHCC(31236b5b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 958 1000 null
W/asset   (  958): Copying FileAsset 0x557f490ee0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  958): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6159 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1303): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1303): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  958): Display changed displayId=0
W/asset   ( 6159): Copying FileAsset 0xac39c828 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1526): [trimMemory] 20
I/WebViewFactory( 6159): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6159): Time to load native libraries: 13 ms (timestamps 6730-6743)
,I/LibraryLoader( 6159): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6159): Binding Chromium to main looper Looper (main, tid 1) {16544515}
,I/LibraryLoader( 6159): Expected native library version number "",actual native library version number ""
,I/chromium( 6159): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6159): Initializing chromium process, singleProcess=true
,W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6159): ApplicationContext is null in ApplicationStatus
,W/chromium( 6159): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 6159): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6159): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6159): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6159): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6159): Local Branch: 
I/Adreno-EGL( 6159): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6159): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6159):                  d74aa161a12b9c6fc6332151
,W/System.err(  958): java.lang.Throwable: stack dump
,W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d4f7610:true
D/BluetoothAdapter( 6159): 79764881: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6159): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6159): CordovaWebView is running on device made by: HTC
,W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6159): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/HtcSystemUPManager(  958): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
D/StatusBarManagerService(  958): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
D/FindExtension( 6159): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6159): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@211585e7, mServedView=org.apache.cordova.engine.SystemWebView{1ca09594 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@226af83d
,I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/InputMethodManagerService(  958): Disable input method client, pid=1526
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6159): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  958): Displayed com.test.thalitest/.MainActivity: +626ms (total +670ms)
,W/BindingManager( 6159): Cannot call determinedVisibility() - never saw a connection for the pid: 6159,
,D/JsMessageQueue( 6159): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6159): JniHelper::setJavaVM(0xab2308f8), pthread_self() = -1403571200,
D/JX-Cordova( 6159): jxcore cordova android initializing
,W/jxcore-log( 6159): Initializing JXcore engine,
W/jxcore-log( 6159): JXcore engine is ready
,W/jxcore-log( 6159): Starting JXcore engine,
,W/jxcore-log( 6159): Platform android
W/jxcore-log( 6159): 
W/jxcore-log( 6159): Process ARCH arm
W/jxcore-log( 6159): ,
,D/PMS     (  958): releaseHCC(11c08a6a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  958): releaseHCC(31236b5b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6159): JXcore Cordova bridge is ready!,
I/jxcore-log( 6159): 
W/jxcore-log( 6159): JXcore engine is started
,I/chromium( 6159): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6159): Toggling radios to true,
I/jxcore-log( 6159): 
,D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  958): checking for enable restriction...
D/BluetoothManagerService(  958): checkBTEasState, ret=true
I/BluetoothManagerService(  958): isBluetoothRestricted(): false
D/BluetoothManagerService(  958): enable(): region ID = 6
D/BluetoothManagerService(  958): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  958): MONITOR_LOG
W/Settings:Agent(  958): name: bluetooth_on
,W/Settings:Agent(  958): value: 1
W/Settings:Agent(  958): >> traceCallingStack()
W/Settings:Agent(  958): Process.myPid(): 958
W/Settings:Agent(  958): Process.myTid(): 1714
W/Settings:Agent(  958): Process.myUid(): 1000
W/Settings:Agent(  958): 
W/Settings:Agent(  958): 
W/System.err(  958): java.lang.Throwable: stack dump
,W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  958): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  958): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  958): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  958): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  958): 
W/Settings:Agent(  958): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  958): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  958): MESSAGE_ENABLE: mBluetooth = null,
,E/WifiTrafficPoller(  958): ADD_CLIENT: 7
D/WifiService(  958): New client listening to asynchronous messages
D/WifiManager( 6159): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  958): setWifiEnabled: true pid=6159, uid=10366
W/Settings:Agent(  958): MONITOR_LOG
E/WifiService(  958): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  958): name: wifi_on
I/WifiService(  958): isSprintWifiRestricted(): false
W/Settings:Agent(  958): value: 2
I/WifiService(  958): isMdmWifiRestricted(): false
W/Settings:Agent(  958): >> traceCallingStack()
W/Settings:Agent(  958): Process.myPid(): 958
W/Settings:Agent(  958): Process.myTid(): 1718
W/Settings:Agent(  958): Process.myUid(): 1000
W/Settings:Agent(  958): 
W/Settings:Agent(  958): 
W/System.err(  958): java.lang.Throwable: stack dump
,W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
I/ActivityManager(  958): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6214 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
W/System.err(  958): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  958): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  958): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  958): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  958): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  958): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  958): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  958): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  958): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
,W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  958): 
W/Settings:Agent(  958): << traceCallingStack(): 13(ms)
,D/WifiController(  958): handleMessage: E msg.what=155656
D/WifiController(  958): processMsg: ApStaDisabledState
D/WifiManager( 6159): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/PMS     (  958): acquireWL(68e4817): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 958 1000 null
D/WifiController(  958): transitionTo: destState=DeviceActiveState
D/WifiController(  958): handleMessage: new destination call exit/enter
D/WifiController(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  958): invokeExitMethods: ApStaDisabledState
D/WifiController(  958): moveTempStackToStateStack: i=1,j=1
D/WifiController(  958): moveTempStackToStateStack: i=0,j=2
D/WifiController(  958): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  958): invokeEnterMethods: StaEnabledState
D/WifiController(  958): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  958): setting operational mode to 1
E/WifiStateMachine(  958): handleMessage: E msg.what=131083
E/WifiStateMachine(  958): processMsg: InitialState
D/WifiController(  958): handleMessage: X
E/WifiStateMachine(  958):  InitialState CMD_START_SUPPLICANT 0 0
D/WifiManager( 6159): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 6159): Radios toggled
I/jxcore-log( 6159): 
I/art     (  431): Explicit concurrent mark sweep GC freed 8677(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 427us total 40.775ms
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 314us total 23.729ms
,I/art     (  431): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 328us total 21.787ms
W/ResourcesManager( 6214): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 6214): Adding HeadsetService,
D/AdapterServiceConfig( 6214): Adding A2dpService
,D/AdapterServiceConfig( 6214): Adding HidService
,D/AdapterServiceConfig( 6214): Adding HealthService,
D/AdapterServiceConfig( 6214): Adding PanService
D/AdapterServiceConfig( 6214): Adding GattService
,W/linker  ( 6214): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  958): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER,
,D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39c90422:true
,W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 6214): make,
,I/BluetoothAdapterState( 6214): Entering OffState,
,E/bt_osi_config( 6214): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,D/BluetoothManagerService(  958): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  958): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  958): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6214): Address is:90:E7:C4:F6:69:77
,D/BluetoothManagerService(  958): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  958): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 1215): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3916c67f
D/BluetoothAdapter( 1215): onBluetoothServiceUp done
D/BluetoothAdapter( 3723): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@111732e8
D/BluetoothAdapter( 3723): onBluetoothServiceUp done
,D/BluetoothAdapter( 1821): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1864dbb7
D/BluetoothAdapter( 1821): onBluetoothServiceUp done
D/BluetoothAdapter( 2346): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@5047359
D/BluetoothAdapter( 2346): onBluetoothServiceUp done
D/BluetoothAdapter(  958): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1a97406e
D/BluetoothAdapter(  958): onBluetoothServiceUp done
,D/BluetoothAdapter( 1488): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2fea87ef
D/BluetoothAdapter( 1488): onBluetoothServiceUp done
D/BluetoothAdapter( 6214): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@c61f4f6
,D/BluetoothAdapter( 6214): onBluetoothServiceUp done
D/BluetoothAdapter( 1468): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@9cfa5d7
D/BluetoothAdapter( 1468): onBluetoothServiceUp done
,D/BluetoothAdapter( 6159): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@126f954d
D/BluetoothAdapter( 6159): onBluetoothServiceUp done
D/BluetoothManagerService(  958): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6214): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6214): Setting state to 11
I/BluetoothAdapterState( 6214): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  958): +onBluetoothStateChange prev=10 new=11
,D/BluetoothManagerService(  958): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  958): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  958): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 6214): make
,I/IntentController( 1215): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothAdapterService( 6214): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 6214): checkA2dpState: returning
,I/BluetoothBondStateMachine( 6214): StableState(): Entering Off State
D/BluetoothAdapterService( 6214): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6214): checkHfpState: returning
,V/BluetoothPbapReceiver( 6214): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6214): ***********state = 11
D/NGFService( 3723): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED,
,I/BluetoothAdapterState( 6214): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothHeadset( 1468): Proxy object connected
D/BluetoothHeadset( 1215): Proxy object connected,
D/BluetoothHeadset(  958): Proxy object connected
D/HeadsetService( 6214): Received start request. Starting profile...
,D/HeadsetStateMachine( 6214): Version 1.5
D/HeadsetStateMachine( 6214): make
,D/BluetoothAdapter(  958): 595351092: getState(). Returning 11,
,D/BluetoothHeadset( 1468): Proxy object connected
,D/PMS     (  958): releaseWL(68e4817): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4,
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  958): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6250 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/BluetoothPhoneService( 1468): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset( 1468): Proxy object connected
,D/Tethering(  958): interfaceAdded wlan0
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,D/HeadsetStateMachine( 6214): max_hf_connections = 2
V/Tethering(  958): TetherInterfaceSM: wlan0: enter InitialState
D/Tethering(  958): interfaceLinkStateChanged wlan0, false
,D/Tethering(  958): interfaceStatusChanged wlan0, false
D/PMS     (  958): acquireWL(e554291): PARTIAL_WAKE_LOCK  NetworkStats 0x1 958 1000 null
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  958): interfaceAdded p2p0
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  958): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  958): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  958): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  958): TetherInterfaceSM: wlan0: enter UnavailableState
D/Tethering(  958): p2p0 is not a tetherable iface, ignoring
D/Tethering(  958): interfaceLinkStateChanged p2p0, false
D/Tethering(  958): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  958): sendTetherStateChangedBroadcast 0, 0, 0
,D/PMS     (  958): releaseWL(e554291): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
V/NetworkPolicy(  958): updateNotificationsLocked()
D/PMS     (  958): acquireWL(21bbb5f6): PARTIAL_WAKE_LOCK  NetworkStats 0x1 958 1000 null
D/PMS     (  958): releaseWL(21bbb5f6): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  958): updateNetworkEnabledLocked()
V/NetworkPolicy(  958): updateNotificationsLocked()
,D/TetherSettings( 5658): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5658): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5658): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5658): Cust_ConnectToPC   : spcsc>false
D/        ( 5658): Cust_ConnectToPC   : IPT>true
D/        ( 5658): Cust_ConnectToPC   : Singel_USB>false
D/BluetoothAdapter( 1468): 601387437: getState(). Returning 11
,W/Settings( 5658): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/SmartNS_Utility( 5658): hasRemovableStorageSlot: true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/SmartNS_Utility( 5658): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5658): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetPhoneState( 6214): listenForPhoneState..for service and signal 
,D/HeadsetDualPhoneStateListener_SLOT1( 6214): listen phone state by slot:SLOT1  id:-1,
,D/HeadsetDualPhoneStateListener_SLOT2( 6214): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6214): Enter Disconnected: -2, size: 0
,W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5658): setISNotification
,D/BluetoothAdapterService( 6214): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@322c002a
,D/HeadsetDualPhoneStateListener_SLOT1( 6214): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6214): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6214): setCurrentDevice, the latest mCurrentDevice is:null
,D/UsbDeviceManager(  958): [USBNET] bCheckSuppFunc: cdc_network
D/bt-btif ( 6214): BTHF: set_current_device
D/UsbDeviceManager(  958): [USBNET] bCheckSuppFunc: cdc_network
,D/UsbnetService(  958): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/UsbnetService(  958): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/BluetoothA2dp(  958): Proxy object connected
D/A2dpService( 6214): Received start request. Starting profile...
V/Avrcp   ( 6214): make
D/BluetoothAdapter(  958): 595351092: getState(). Returning 11
,D/SmartNS_Utility( 5658): usb_cable_connect = 1,
D/SmartNS_Utility( 5658): usb_denied = 0
,I/SmartNS_PSService( 5658): usb notificaiton:true,
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,E/RemoteController( 6214): Cannot set synchronization mode on an unregistered RemoteController
,D/A2dpStateMachine( 6214): make
,D/bt-btif ( 6214): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,I/QuickSettingMiniLite( 1215): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@467664c
,D/A2dpService( 6214): setA2dpService(): set to: null
D/BluetoothAdapterService( 6214): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@322c002a
D/A2dpStateMachine( 6214): Enter Disconnected: -2
,I/ActionCombine( 5658): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
D/HtcBtWidget_BTWidgetProvider( 6250): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 6250): updateWidget(context) for widget: 
,I/QuickSettingBluetooth( 1215): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON,
D/HidService( 6214): Received start request. Starting profile...
D/BluetoothAdapterService( 6214): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@322c002a
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
D/HealthService( 6214): Received start request. Starting profile...
,D/SmartNS_Utility( 5658): usb_cable_connect = 1
D/SmartNS_Utility( 5658): usb_denied = 0
I/SmartNS_PSService( 5658): usb notificaiton:true
E/WifiStateMachine(  958): setWifiState: enabling,
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  958): Supplicant start successful
D/WifiMonitor(  958): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  958): connecting to supplicant
E/WifiHW  (  958): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
I/IntentController( 1215): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/BluetoothAdapterService( 6214): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@322c002a
,I/RemoteViews( 1215): reapply : com.android.settings 2 36
D/WIFI_ICON( 1215): updateWifiState: WIFI_STATE_CHANGED disabled
D/PanService( 6214): Received start request. Starting profile...
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/SmartNS_NSReceiver( 5658): Tethered state change:false isNSOpening:false
,D/PanService( 6214): HTC_CUSTOMIZATION_MHS_ENABLE = false,
D/BluetoothAdapterService( 6214): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@322c002a
D/TetherSettings( 5658): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5658): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5658): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5658): Cust_ConnectToPC   : spcsc>false
D/        ( 5658): Cust_ConnectToPC   : IPT>true
D/        ( 5658): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5658): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5658): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5658): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5658): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/BtGatt.DebugUtils( 6214): handleDebugAction() action=null
,D/BtGatt.GattService( 6214): Received start request. Starting profile...
D/BtGatt.GattService( 6214): start()
D/BtGatt.AdvertiseManager( 6214): advertise manager created
,I/RemoteViews( 1215): reapply : com.android.settings 1 36
I/SmartNS_Utility( 5658): setISNotification
D/SmartNS_Utility( 5658): usb_cable_connect = 1
D/SmartNS_Utility( 5658): usb_denied = 0
I/SmartNS_PSService( 5658): usb notificaiton:true
,E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterService( 6214): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@322c002a
D/wpa_supplicant( 6278): wpa_supplicant v2.3-devel-5.0.2
,D/wpa_supplicant( 6278): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6278): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 6278): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6278): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6278): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6278): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6278): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6278): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6278): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
,D/wpa_supplicant( 6278): ctrl_interface='/data/misc/wifi/sockets',
D/wpa_supplicant( 6278): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6278): update_config=1
,D/wpa_supplicant( 6278): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6278): device_name='Android_608e'
D/wpa_supplicant( 6278): manufacturer='HTC'
D/wpa_supplicant( 6278): model_name='HTC_PHONE'
D/wpa_supplicant( 6278): model_number='1234'
D/wpa_supplicant( 6278): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6278): p2p_oper_reg_class=126
D/wpa_supplicant( 6278): p2p_oper_channel=149,
D/wpa_supplicant( 6278): p2p_ssid_postfix='-Android_608e'
,D/wpa_supplicant( 6278): persistent_reconnect=1,
D/wpa_supplicant( 6278): key_mgmt_offload=1
D/BluetoothAdapter( 1468): 601387437: getState(). Returning 11
W/BluetoothHeadset( 1468): Proxy not attached to service
D/SmartNS_Utility( 5658): usb_cable_connect = 1
I/wpa_supplicant( 6278): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6278): nl80211: RFKILL status not available
D/wpa_supplicant( 6278): nl80211: Using driver-based roaming
D/wpa_supplicant( 6278): nl80211: TDLS supported
D/wpa_supplicant( 6278): nl80211: TDLS external setup
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:4
,D/wpa_supplicant( 6278): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6278): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
,D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
,D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/SmartNS_Utility( 5658): usb_denied = 0
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6278): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6278): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6278): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6278): nl80211: Set mode ifindex 30 iftype 2 (STATION)
I/SmartNS_PSService( 5658): usb notificaiton:true
D/wpa_supplicant( 6278): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a180bfd0
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=0104
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=040a
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=040b
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=040c
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=040d
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=090a
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=090b
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=090c
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=090d
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=0409506f9a09
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=7f506f9a09
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=0801
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=040e
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=06
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=0a07
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 match=0a11
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a180bfd0 mat,ch=0a1a
D/BluetoothHeadset( 1468): java.lang.Throwable
D/BluetoothHeadset( 1468): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1468): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1468): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1468): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1468): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1468): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1468): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1468): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1468): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1468): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1468): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/wpa_supplicant( 6278): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  958): interfaceLinkStateChanged p2p0, false
D/Tethering(  958): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6278): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6278): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6278): htc_wext_command_init +
E/wpa_supplicant( 6278): htc_wext_command_init: ifname=p2p0, ignore
D/Tethering(  958): interfaceLinkStateChanged p2p0, false
D/Tethering(  958): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6278): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/SmartNS_NSReceiver( 5658): Tethered state change:false isNSOpening:false
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/HeadsetPhoneState( 6214): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 6214): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 6214): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6214): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6214): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 6214): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 6214): btu_task pending for preload complete event
I/QuickSettingWifi( 1215): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
I/RemoteViews( 1215): reapply : com.android.settings 0 36
E/bt_vendor( 6214): get_bt_soc_type: Failed to get soc type
I/ActivityManager(  958): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6285 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
I/ActivityManager(  958): Killing 5899:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5899
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
D/BluetoothAdapter( 1215): 771936165: getState(). Returning 11
I/QuickSettingMiniLite( 1215): updateLiteState:no connect device!
I/qcom-bluetooth( 6299): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,I/qcom-bluetooth( 6313): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
I/qcom-bluetooth( 6314): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 6316): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/ActivityManager(  958): Recipient 5899
,I/qcom-bluetooth( 6317): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 6318): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6319): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/RemoteViews( 1215): reapply : com.android.settings 1 36
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/BluetoothMasReceiver( 6214): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 6214): SapReceiver onReceive ,
V/BluetoothSapReceiver( 6214): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6214):  Bluetooth Adapter state = 11,
V/BluetoothSapReceiver( 6214): startService = false
,I/wpa_supplicant( 6278): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 6278):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6278):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6278):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6278): nl80211: Flush PMKIDs
D/wpa_supplicant( 6278): p2p0: State: DISCONNECTED -> INACTIVE
D/AuthorizationBluetoothService( 1882): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 6285): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6285): updateWidget(context) for widget: 
,D/Process (  958): killProcessQuiet, pid=5921
I/ActivityManager(  958): Killing 5921:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/wpa_supplicant( 6278): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6278): TDLS: Driver uses external link setup
D/wpa_supplicant( 6278): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6278): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6278): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6278): nl80211: Skip set_supp_port(unauthorized) while not associated
,D/wpa_supplicant( 6278): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6278): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6278): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6278): Using existing control interface directory.
D/wpa_supplicant( 6278): P2P: Add operating class 81
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6278): P2P: Own listen channel: 81:1
D/wpa_supplicant( 6278): P2P: Configured operating channel: 126:149
D/wpa_supplicant( 6278): P2P: initialized
D/wpa_supplicant( 6278): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6278): P2P: cli_channels:
D/wpa_supplicant( 6278): p2p0: Added interface p2p0
D/wpa_supplicant( 6278): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6278): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6278): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 6278): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6278): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6278): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 6278): ctrl_interface='/data/misc/wifi/sockets'
,D/wpa_supplicant( 6278): disable_scan_offload=1
D/wpa_supplicant( 6278): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6278): update_config=1
D/wpa_supplicant( 6278): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6278): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6278): manufacturer='HTC'
D/wpa_supplicant( 6278): model_name='HTC One M8s'
D/wpa_supplicant( 6278): model_number='HTC One M8s'
,D/wpa_supplicant( 6278): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6278): hs20=1
D/wpa_supplicant( 6278): interworking=1
D/wpa_supplicant( 6278): external_sim=1
D/wpa_supplicant( 6278): key_mgmt_offload=1
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/wpa_supplicant( 6278): Priority group 239,
D/wpa_supplicant( 6278):    id=0 ssid='NG700'
I/wpa_supplicant( 6278): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6278): nl80211: RFKILL status not available
D/wpa_supplicant( 6278): nl80211: Using driver-based roaming
D/wpa_supplicant( 6278): nl80211: TDLS supported
D/wpa_supplicant( 6278): nl80211: TDLS external setup
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6278): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6278): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  958): Recipient 5921
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
,D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
,D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6278): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
,D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
,D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6278): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6278): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6278): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6278): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6278): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6278): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6278): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6278): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a182b100
,D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=0104
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=040a
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=040b
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=040c
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=040d
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=090a
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=090b
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=090c
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=090d
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=0409506f9a09
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=7f506f9a09
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=0801
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=040e
,D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=06
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=0a07
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=0a11
D/wpa_supplicant( 6278): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a182b100 match=0a1a
D/wpa_supplicant( 6278): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6278): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6278): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6278): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6278): htc_wext_command_init +
I/wpa_supplicant( 6278): htc_wext_command_init -
I/wpa_supplicant( 6278): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6278): Don't set 00 to countryID.conf
,D/Tethering(  958): interfaceLinkStateChanged wlan0, false
D/Tethering(  958): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6278): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6278): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6278): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 6278): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6278): P2P: Add operating class 81
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6278): P2P: Update channel list
D/wpa_supplicant( 6278): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6278): P2P: cli_channels:
D/wpa_supplicant( 6278): p2p0: Updating hw mode
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6278): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
,D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6278): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 6278): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6278): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
,I/qcom-bluetooth( 6322): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,I/qcom-bluetooth( 6323): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 6214): btu_task received preload complete event
,W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/PMS     (  958): acquireWL(66f510b): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6214 1002 null,
D/bt-btm  ( 6214): btm_acl_device_down
D/bt-btm  ( 6214): btm_acl_reset_paging
D/bt-btm  ( 6214): btm_acl_set_discing
,I/wpa_supplicant( 6278): wapi_supplicant_init: Init WAI packet wlan0,
D/wpa_supplicant( 6278):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6278):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6278):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6278): wlan0: RSN: flushing PMKID list in the driver,
D/wpa_supplicant( 6278): nl80211: Flush PMKIDs
,I/bt-btm  ( 6214): btm_reset_complete,
I/bt-btm  ( 6214): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 6214): Start reading local supported commands,
,D/bt-btm  ( 6214): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 6214): BTM reads next extended features page (1),
,D/bt-btm  ( 6214): BTM reads next extended features page (2)
,D/bt-btm  ( 6214): BTM reached last extended features page (2)
D/bt-btm  ( 6214): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,D/bt-btm  ( 6214): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,D/bt-btm  ( 6214): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 6214): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 6214): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 6214): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 6214): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 6214): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 6214): btm_read_ble_wl_size 
D/bt-btm  ( 6214): btm_read_white_list_size_complete 
D/bt-btm  ( 6214): btm_get_ble_buffer_size 
,D/wpa_supplicant( 6278): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6278): TDLS: Driver uses external link setup
D/wpa_supplicant( 6278): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6278): EAPOL: SUPP_PAE entering state DISCONNECTED
,D/wpa_supplicant( 6278): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6278): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6278): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6278): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6278): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6278): Using existing control interface directory.
,D/bt-btm  ( 6214): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6214): btm_read_ble_local_supported_states 
,D/bt-btm  ( 6214): btm_read_ble_local_supported_states_complete 
,D/bt-btm  ( 6214): btm_read_ble_local_supported_features 
,D/bt-btm  ( 6214): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 6214): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6214): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6214): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6214): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6214): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6214): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6214): BTM_SetInquiryMode
I/wpa_supplicant( 6278): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6278): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6278): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6278): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6278): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
,D/wpa_supplicant( 6278): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6278): P2P: Add operating class 81
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6278): P2P: Add operating class 115
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6278): P2P: Add operating class 116
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6278): P2P: Add operating class 117
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6278): P2P: Update channel list
D/wpa_supplicant( 6278): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6278): P2P: cli_channels:
D/wpa_supplicant( 6278): p2p0: Updating hw mode
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6278): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
I/bt-btm  ( 6214): BTM_SetPageScanType
I/bt-btm  ( 6214): BTM_SetInquiryScanType
,D/bt-btm  ( 6214): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6214): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6214): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6214): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6214): BTM_BleLoadLocalKeys
D/bt-btm  ( 6214): BTM_BleLoadLocalKeys
I/bt-btm  ( 6214): BTM_Sec: application registered
,E/bt-btm  ( 6214): BTM_SecRegister:p_cb_info->p_le_callback == 0xdfb004d5 
I/bt-btm  ( 6214): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6214): SMP_Register state=0
E/bt-btm  ( 6214): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdfb004d5 
I/bt-btm  ( 6214): BTM_Sec: application registered
D/bt-btm  ( 6214): BTM_SetDefaultLinkSuperTout
,I/bt-btm  ( 6214): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6214): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6214): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6214): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6214): BTM_RegBusyLevelNotif
D/bt-btm  ( 6214): BTM_BleReadControllerFeatures
I/bt-btm  ( 6214): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6214): GATT_Register
D/bt-att  ( 6214): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 6214): allocated gatt_if=3
I/bt-att  ( 6214): GATT_StartIf gatt_if=3
D/bt-att  ( 6214): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6214): gatt_find_the_connected_bda found=0 found_idx=16
I/wpa_supplicant( 6278): Auto country group 1: ch36
,D/wpa_supplicant( 6278): wlan0: Added interface wlan0
D/wpa_supplicant( 6278): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6278): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6278): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 6278): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 6278): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6278): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6278): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6278): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6278): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
,D/wpa_supplicant( 6278): nl80211: Regulatory domain change
D/wpa_supplicant( 6278):  * initiator=1
D/wpa_supplicant( 6278):  * type=0
D/wpa_supplicant( 6278):  * alpha2=DE
D/wpa_supplicant( 6278): wlan0: Event CHANNEL_LIST_CHANGED (30) received
,I/wpa_supplicant( 6278): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=DE
,D/wpa_supplicant( 6278): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
,D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6278): P2P: Add operating class 81
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6278): P2P: Add operating class 115
,D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6278): P2P: Add operating class 116
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6278): P2P: Add operating class 117
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6278): P2P: Update channel list
D/wpa_supplicant( 6278): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6278): P2P: cli_channels:
D/wpa_supplicant( 6278): p2p0: Updating hw mode
,D/wpa_supplicant( 6278): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6278): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm
,D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/bt-btm  ( 6214): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 6214): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
,I/bt-btm  ( 6214): BTM Register For VSEvents is successfully
D/bt-btm  ( 6214): BTM_BleGetVendorCapabilities
I/bt-btif ( 6214): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6214): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6214): bta_dm_set_dev_name: name: HTC One M8s 
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btm  ( 6214):  BTM_BleConfigPrivacy
,I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): Calling BTA_HhEnable
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
E/bt-btif ( 6214): btm_gen_resolvable_p
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
,I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btif ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
,D/bt-btif ( 6214): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6214): BTM_AllocateSCN
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6214): BTM_AllocateSCN
,I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btm  ( 6214): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6214):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6214):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6214): AG evt (hdl 0x0002): State 0, Event 0x0500
,I/bt-btm  ( 6214): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6214):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6214):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6214): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x2090, service name [] (up to 21 chars saved),
I/bt-btm  ( 6214): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
,I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): btif_storage_get_adapter_property psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6214):                : sec: 0x80, servi service_] (up to 21 chars saved)
E/bt-btif ( 6214): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 
,I/bt-btm  ( 6214): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btif ( 6214): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6214): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x2090, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6214): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 6214): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6214): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
D/bt-btif ( 6214):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
,D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6214): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btm  ( 6214): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6214):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6214):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6214):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6214): GATT_Register
D/bt-att  ( 6214): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6214): allocated gatt_if=4
I/bt-att  ( 6214): GATT_StartIf gatt_if=4
D/bt-att  ( 6214): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6214): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 6214): Address is:90:E7:C4:F6:69:77
D/BluetoothAdapterProperties( 6214): Scan Mode:21
D/BluetoothAdapterProperties( 6214): Discoverable Timeout:120
I/bt-btif ( 6214): BTA_JvEnable
I/bt-btif ( 6214): BTA_JvRegisterL2cCback
I/bt-btm  ( 6214): BTM_ReadConnectability
I/bt-btm  ( 6214): BTM_ReadDiscoverability
,I/bt-btm  ( 6214): BTM_SetDiscoverability
I/bt-btm  ( 6214): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6214): disc_mode 0002
D/bt-btm  ( 6214): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6214): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6214): BTM_SetConnectability
I/bt-btm  ( 6214): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6214): disc_mode 0002
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6214): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6214): BTM_SetDiscoverability
I/bt-btm  ( 6214): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6214): disc_mode 0000
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6214): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6214): BTM_SetConnectability
I/bt-btm  ( 6214): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6214): disc_mode 0000
D/bt-btm  ( 6214): btm_ble_update_adv_flag new=0x1c
,D/bt-btm  ( 6214): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
I/bt-btm  ( 6214): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6214): bta_pan_co_init
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6214): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6214):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6214):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btm  ( 6214): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6214):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6214): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6214):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 0e 4b 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = f7 6e bd 73 c9 53 d1 c6 f0 e9 0b 9c c3 69 4a e6 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
,D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btif ( 6214): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 6214): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6214): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6214): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6214): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6214): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 6214): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6214): ScanMode =  21
D/BluetoothAdapterProperties( 6214): State =  11
I/bt-btif ( 6214): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6214): Setting state to 12
I/BluetoothAdapterState( 6214): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 6214): Discoverable Timeout:120
D/BluetoothManagerService(  958): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  958): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  958): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 6214): Entering On State
D/BluetoothManagerService(  958): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1215): onBluetoothStateChange: up=true
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 8a 91 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 0c e8 95 88 6f 0b 5a cd a3 0a ab 32 8b 9b 4d b3 
D/BluetoothHeadset( 1468): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1468): onBluetoothStateChange: up=true
D/BluetoothA2dp(  958): onBluetoothStateChange: up=true
D/BluetoothHeadset(  958): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1468): onBluetoothStateChange: up=true
E/bt_mct  ( 6214): hci lib postload completed
D/BluetoothManagerService(  958): Bluetooth State Change Intent: 11 -> 12
I/IntentController( 1215): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 58 33 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = f3 b0 b1 b1 bb ac 14 22 30 67 15 fc 50 cb f6 22 
D/BluetoothManagerService(  958): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  958): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/NGFService( 3723): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  958): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapReceiver( 6214): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,D/NGFService( 3723): Bluetooth Adapter: ON
V/BluetoothPbapReceiver( 6214): ***********state = 12
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = bc 42 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = eb 9c bc a1 b9 3f 6c 15 7c d8 f3 1b 6a 7b fe 6c 
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = ad 96 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = f7 06 2c ae a4 b8 65 28 99 09 fe 5c f2 3a 9d a8 
D/PMS     (  958): acquireWL(59b88a6): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5658 1000 null
,W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothPbapService( 6214): Pbap Service onCreate
,V/BluetoothPbapService( 6214): Starting PBAP service
D/BluetoothAdapter( 6214): 685673412: getState(). Returning 12
V/BluetoothPbapService( 6214): Handler(): got msg=1
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 3d 6c 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 3d f6 f8 d3 1b 78 2f 87 8a f1 b8 02 48 43 77 d3 
V/BluetoothPbapService( 6214): Pbap Service startRfcommSocketListener
D/PMS     (  958): releaseWL(59b88a6): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null,
,V/BluetoothPbapService( 6214): Pbap Service initSocket
D/PMS     (  958): acquireWL(35e6fe94): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5658 1000 null
D/HtcBtWidget_BTWidgetProvider( 6250): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6250): updateWidget(context) for widget: 
,D/bt-btm  ( 6214): btm_ble_rand_enc_complete
,I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 73 5b 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 84 1f 59 36 fc 92 80 16 f5 48 48 ec 66 c8 a0 14 
D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 5a 16 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = cb b5 b6 a7 8b 93 f8 f0 69 96 20 88 5a 76 7e 8d 
,W/System.err(  958): java.lang.Throwable: stack dump
W/System.err(  958): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  958): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  958): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  958): 	at android.os.Binder.execTransact(Binder.java:454)
W/BluetoothAdapter( 6214): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  958): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@348ed683:true
,I/bt-btm  ( 6214): BTM_SetDiscoverability
I/bt-btm  ( 6214): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6214): disc_mode 0000
I/bt-btm  ( 6214): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6214): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6214): BTM_SetConnectability
I/bt-btm  ( 6214): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6214): disc_mode 0000
D/bt-btm  ( 6214): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6214): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6214): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 27 33 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 18 2f cc b0 45 80 46 c6 67 db 8e 5e 52 b0 3a 3c 
I/bt-btif ( 6214): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btif ( 6214): BTA_JvRfcommStartServer
,I/bt-btm  ( 6214): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6214):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6214): Succeed to create listening socket 
V/BluetoothPbapService( 6214): Accepting socket connection...
I/bt-btif ( 6214): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6214): Scan Mode:21
,D/BluetoothAdapter( 1215): 771936165: getState(). Returning 12
,D/BluetoothAdapter( 1215): 771936165: getState(). Returning 12
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 8d 6d 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = e3 33 ff d3 21 e0 7a f7 81 84 86 18 23 b4 84 ce 
,I/QuickSettingBluetooth( 1215): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1215): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/bt-btm  ( 6214): btm_ble_rand_enc_complete
,I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 9c 35 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 83 ca f8 ec b7 58 bd 69 75 1c 3f 21 ca 38 5d b5 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 5658): 317680301: getState(). Returning 12
,D/BluetoothInputDevice( 5658): BluetoothInputDevice()
,D/BluetoothManagerService(  958): registerStateChangeCallback+
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  958): Registered receivers: 7
,D/BluetoothPan( 5658): BluetoothPan()
,D/BluetoothManagerService(  958): registerStateChangeCallback+
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  958): Registered receivers: 8
,D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 46 d6 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 6e 5e 30 37 a6 fa 53 d1 68 e9 0b fe 0b 7d f7 48 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
,D/BluetoothMap( 5658): Create BluetoothMap proxy object
D/BluetoothManagerService(  958): registerStateChangeCallback+
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  958): Registered receivers: 9
,E/BluetoothMap( 5658): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  958): registerStateChangeCallback+
D/BluetoothSap( 5658): BluetoothSap() call bindService
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  958): Registered receivers: 10
W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5658): BluetoothPbap()
D/BluetoothManagerService(  958): registerStateChangeCallback+,
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  958): Registered receivers: 11
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 79 86 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = a7 43 bf 3a 60 be 01 be 42 58 60 31 9f 40 38 56 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
,D/BluetoothManagerService(  958): registerStateChangeCallback+,
D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  958): Registered receivers: 12
,D/BluetoothHeadset( 5658): BluetoothHeadset()
D/BluetoothManagerService(  958): registerStateChangeCallback+
,D/BluetoothManagerService(  958): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  958): Registered receivers: 13,
D/LocalBluetoothProfileManager( 5658): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5658): finishStartingService: stopping service
D/bt-btm  ( 6214): btm_ble_rand_enc_complete
D/BluetoothA2dp( 5658): Proxy object connected
I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 05 6d 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = ee a1 d2 cc 6a cd be ed b8 49 53 5c a6 56 7e 4a 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
D/A2dpProfile( 5658): Bluetooth service connected
,V/BluetoothPbapService( 6214): Pbap Service onBind
D/BluetoothAdapter( 5658): 317680301: getState(). Returning 12
,D/BluetoothHeadset( 5658): Proxy object connected
D/HeadsetProfile( 5658): Bluetooth service connected
D/BluetoothAdapter( 5658): 317680301: getState(). Returning 12
,D/BluetoothInputDevice( 5658): Proxy object connected
,D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HidProfile( 5658): Bluetooth service connected
,D/BluetoothAdapter( 5658): 317680301: getState(). Returning 12
,D/PMS     (  958): releaseWL(35e6fe94): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 6214): 685673412: getState(). Returning 12
W/BluetoothAdapter( 6214): getBluetoothService() called with no BluetoothManagerCallback,
,D/BluetoothFtpService( 6214): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothPan( 5658): BluetoothPAN Proxy object connected
D/BluetoothMasReceiver( 6214): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6214):  call MAP start service
,I/bt-btif ( 6214): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:11
,I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btif ( 6214): BTA_JvRfcommStartServer
I/bt-btm  ( 6214): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 6214):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6214): Accept thread started.
D/PanProfile( 5658): Bluetooth service connected
D/BluetoothPbap( 5658): Proxy object connected
,D/PbapServerProfile( 5658): Bluetooth service connected
D/BluetoothFtpService( 6214): htc sense version is 6.0
D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6214): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6214): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
,I/bt-btif ( 6214): BTA_JvRfcommStartServer
I/bt-btm  ( 6214): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6214):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6214): Run Accept thread
,E/BluetoothMasService( 6214): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 6214): Add permission for SmsProvider.
,V/BluetoothMasService( 6214): Starting MAS instances
,D/BluetoothAdapter( 6214): 685673412: getState(). Returning 12
,I/MailMessageReceiver( 6214): reg:com.android.bluetooth.btservice.AdapterApp@6404265 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@3cb53b3a
,I/MailManager( 6214): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@3cb53b3a
V/EmailUtils( 6214): Manager Instance is not NULL
,I/ActivityManager(  958): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6339 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/wpa_supplicant( 6278): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP]),
D/Tethering(  958): interfaceLinkStateChanged p2p0, false
D/Tethering(  958): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  958): WiFiDisplay: getWifidisplayApEnabled=false
,D/HtcAdjCursorFactory( 6339): Set CursorWindow size to: 4194304 KB, Tid: 6358,
,D/EmailUtils( 6214): ============NULL aList========,
V/EmailUtils( 6214): <-getEmailAccountIdList
V/BluetoothMasService( 6214): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 6214): 685673412: getState(). Returning 12
V/BluetoothMasService( 6214): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 6214): Manager Instance is not NULL
D/EmailUtils( 6214): ============NULL aList========
V/EmailUtils( 6214): <-getEmailAccountIdList
V/BluetoothSapReceiver( 6214): SapReceiver onReceive 
V/BluetoothSapReceiver( 6214): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6214):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6214): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6214): handleMessage: mIsEmailEnabledtrue
D/AuthorizationBluetoothService( 1882): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BtMns   ( 6214): BluetoothMns: isEmailEnabled: true
D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6214): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6214): BTA_JvCreateRecordByUser,
D/bt-btm  ( 6214): BTM_AllocateSCN
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btif ( 6214): BTA_JvRfcommStartServer
I/bt-btm  ( 6214): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6214):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6214): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6214): BTA_JvCreateRecordByUser
,D/bt-btm  ( 6214): BTM_AllocateSCN
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btif ( 6214): BTA_JvRfcommStartServer
I/bt-btm  ( 6214): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6214):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  958): killProcessQuiet, pid=4804
,I/ActivityManager(  958): Killing 4804:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/wpa_supplicant( 6278): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_958-3\x00
,E/WifiStateMachine(  958): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
,E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  958): invokeExitMethods: InitialState
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  958): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131144
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  958): deferMessage: msg=131144
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131085
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  958): deferMessage: msg=131085
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131149
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
,E/WifiStateMachine(  958): processMsg: DefaultState
,E/WifiStateMachine(  958):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  958): setSuspendOptimizations: 2 true
E/WifiStateMachine(  958): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131145
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131146
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131101
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
,E/WifiStateMachine(  958):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  958): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  958): handleMessage: X
,E/WifiStateMachine(  958): handleMessage: E msg.what=131101
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  958): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147457
E/WifiStateMachine(  958): processMsg: SupplicantStartingState
E/WifiStateMachine(  958):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,E/WifiStateMachine(  958): Supplicant connection established
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6278): set wifi ON
E/WifiStateMachine(  958): setWifiState: enabled
,E/WifiStateMachine(  958): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  958):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6278): SET_SCREEN_ON:Off
,I/wpa_supplicant( 6278): htc_wext_set_keepalive +
D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
I/wpa_supplicant( 6278): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6278): getPrivFuncNum +,	
I/wpa_supplicant( 6278): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6278): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6278): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6278): get_ip_address source addr = ffffffff
,I/wpa_supplicant( 6278): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6278): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  958): startHal
E/wifi    (  958): getStaticLongField sWifiHalHandle 0x7f779a7300
I/WifiNative-HAL(  958): Could not start hal
,E/WifiStateMachine(  958): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  958): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  958): handleScreenStateChanged Exit: false
,I/ActivityManager(  958): Recipient 4804,
,V/BluetoothSapService( 6214): Sap Service onCreate,
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/WIFI_ICON( 1215): updateWifiState: WIFI_STATE_CHANGED enabled
,D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER MACADDR'
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
V/BluetoothSapService( 6214): initBinder
,V/BluetoothSapService( 6214): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@15f79fe1
I/IntentController( 1215): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET update_config 1'
,D/wpa_supplicant( 6278): CTRL_IFACE SET 'update_config'='1'
,V/BluetoothSapService( 6214): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@3afc03c7
D/wpa_supplicant( 6278): update_config=1
D/wpa_supplicant( 6278): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/WifiConfigStore(  958): Loading config and enabling all networks 
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6278): wlan0: Control interface command 'LIST_NETWORKS',
D/wpa_supplicant( 6278): wpa_supplicant_ctrl_iface_list_networks: return size = 47
,V/BluetoothSapService( 6214): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapService( 6214): state: 12
D/SapServerProfile( 5658): Bluetooth service connected
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
,D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
V/BluetoothSapService( 6214): Starting SAP server process
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 psk'
,D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6278): Do not allow key_data field to be exposed
D/HtcWiFiWidget_WiFiWidgetProvider( 6285): onWiFiStateChanged() for widget: 
V/BluetoothSapService( 6214): SAP Service startRfcommListenerThread
D/HtcWiFiWidget_WiFiWidgetProvider( 6285): updateWidget(context) for widget: 
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
V/BluetoothSapService( 6214): Sap Service initRfcommSocket
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
,D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='group'
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/BluetoothAdapter( 6214): getBluetoothService() called with no BluetoothManagerCallback
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
,D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
,D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert',
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
I/bt-btif ( 6214): BTA_JvCreateRecordByUser
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='identity'
D/bt-sdp  ( 6214): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6214): Write Extended Inquiry Response to controller
I/bt-btif ( 6214): BTA_JvRfcommStartServer
I/bt-btm  ( 6214): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
I/bt-btm  ( 6214):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
V/BluetoothSapService( 6214): Succeed to create listening socket 
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
V/BluetoothSapService( 6214): Accepting socket connection...
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6278): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6278): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,E/WifiConfigStore(  958): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe",
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6278): device_name='m8qlul_htc_europe'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6278): manufacturer='HTC'
I/QuickSettingWifi( 1215): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6278): model_name='HTC One M8s'
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6278): model_number='HTC One M8s'
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6278): config_methods='physical_display virtual_push_button'
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,E/WifiStateMachine(  958): transitionTo: destState=DriverStartedState
,E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  958): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  958): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  958): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6278): wlan0: Setting scan interval: 15 sec
,D/WifiNative-HAL(  958): Setting external_sim to 1
D/WifiP2pService(  958): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/WifiP2pService(  958): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6278): external_sim=1
W/Settings( 5482): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  958): Setting OUI to DA-A1-19
I/WifiNative-HAL(  958): startHal
E/wifi    (  958): getStaticLongField sWifiHalHandle 0x7f779a7360
I/WifiNative-HAL(  958): Could not start hal
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6278): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  958): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  958): Driverstarted State enter
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
,D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  958): DriverStartedState call setCountryCode()
E/WifiStateMachine(  958): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  958): NetworkAgent == null
,E/WifiStateMachine(  958): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
I/IntentController( 1215): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1215): updateWifiState: NETWORK_STATE_CHANGED disconnected
E/WifiTrafficPoller(  958): ENABLE_TRAFFIC_STATS_POLL false Token 0
D/StatusBar.NetworkController( 1215): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  958): setDhcpActive: false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
,D/wpa_supplicant( 6278): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  958): transitionTo: destState=DisconnectedState
D/WifiP2pService(  958): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/native  (  958): do suspend false
D/HTCRequest(  958): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/HTCRequest(  958): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
,W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6278): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  958): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, SUCCESS
D/A2dpService( 6214): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@116d591d
,E/WifiStateMachine(  958): Driverstarted State enter done
E/WifiStateMachine(  958): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  958): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  958): handleMessage: new destination call exit/enter
D/WifiP2pService(  958): P2pEnablingState
D/WifiMonitor(  958): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine(  958): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  958): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  958): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  958): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  958): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  958): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  958): DisconnectedState call setCountryCode()
D/A2dpSinkService( 6214): getA2dpSinkService(): service is NULL
E/WifiStateMachine(  958):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 6278): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6278): wlan0: nl80211: sched_scan request
,D/WifiScanningService(  958): SCAN_AVAILABLE : 3
D/RttService(  958): SCAN_AVAILABLE : 3
D/WifiScanningService(  958): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  958): startHal
D/RttService(  958): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  958): P2pEnablingState{ when=-4ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  958): P2p socket connection successful
D/WifiP2pService(  958): P2pEnabledState
D/WifiP2pService(  958): sending p2p connection changed broadcast
,D/WifiDisplayController(  958): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayAdapter(  958): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  958):     Client/Owner: Client
D/WifiDisplayAdapter(  958):     GroupId: 
D/WifiDisplayAdapter(  958):     Passphrase: 
D/WifiDisplayAdapter(  958):     SessionId: 0
D/WifiDisplayAdapter(  958):     IP Address: }
V/AudioService(  958): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  958):     Client/Owner: Client
V/AudioService(  958):     GroupId: 
V/AudioService(  958):     Passphrase: 
V/AudioService(  958):     SessionId: 0
V/AudioService(  958):     IP Address: }
D/HtcEffectManagerBase(  958): onEventChanged id=5 status=false
D/HtcEffectManager(  958): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  958): convertEffect before=902
D/HtcEffectManager(  958): convertEffect after=902
,D/WifiDisplayController(  958): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayController(  958): mWfdEnabled :false, networkInfo.isConnected() :false
,D/wpa_supplicant( 6278): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
,D/wpa_supplicant( 6278): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6278): wlan0: nl80211: Sched scan started
E/wifi    (  958): getStaticLongField sWifiHalHandle 0x7f754b7520
I/WifiNative-HAL(  958): Could not start hal
E/WifiScanningService(  958): could not start HAL
E/WifiStateMachine(  958): handleMessage: X
W/WifiHW  (  958): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
E/WifiStateMachine(  958): handleMessage: E msg.what=131144,
E/WifiStateMachine(  958): processMsg: DisconnectedState
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6278): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6278): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6278): persistent_reconnect=1
,D/wpa_supplicant( 6278): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6278): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6278): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  958):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131085
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_START_DRIVER 0 0
,E/WifiStateMachine(  958): processMsg: DriverStartedState
W/WifiHW  (  958): QCOM Debug wifi_send_command "SET device_name Android_608e"
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
E/WifiStateMachine(  958):  DriverStartedState CMD_START_DRIVER 0 0
D/wpa_supplicant( 6278): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6278): p2p0: Control interface command 'SET device_name Android_608e'
E/WifiStateMachine(  958): handleMessage: X
D/wpa_supplicant( 6278): CTRL_IFACE SET 'device_name'='Android_608e'
E/WifiStateMachine(  958): handleMessage: E msg.what=131154
D/wpa_supplicant( 6278): device_name='Android_608e'
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
W/WifiHW  (  958): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
E/WifiStateMachine(  958):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6278): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6278): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
E/WifiStateMachine(  958):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
D/wpa_supplicant( 6278): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
D/wpa_supplicant( 6278): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6278): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  958):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
D/WifiP2pService(  958): DeviceAddress: 92:e7:c4:e6:4c:f8
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131323
E/WifiStateMachine(  958): processMsg: DisconnectedState
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6278): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6278): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  958):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState what:131323 0 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  958): processMsg: DriverStartedState
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6278): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
,D/wpa_supplicant( 6278): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6278): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6278): config_methods='virtual_push_button physical_display keypad'
E/WifiStateMachine(  958):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  958): processMsg: DefaultState
D/WifiDisplayController(  958): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  958):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  958):  primary type: 10-0050F204-5
D/WifiDisplayController(  958):  secondary type: null
D/WifiDisplayController(  958):  wps: 0
D/WifiDisplayController(  958):  grpcapab: 0
D/WifiDisplayController(  958):  devcapab: 0
D/WifiDisplayController(  958):  status: 3
D/WifiDisplayController(  958):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  958):  WFD CtrlPort: 0
D/WifiDisplayController(  958):  WFD MaxThroughput: 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6278): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6278): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6278): Single channel concurrency preference: sta
,E/WifiStateMachine(  958):  DefaultState what:131323 0 0
E/WifiStateMachine(  958): setOperatorSSID enter
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131104
E/WifiStateMachine(  958): processMsg: DisconnectedState
D/WifiNative-HAL(  958): p2pGetDeviceAddress
W/WifiHW  (  958): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
E/WifiStateMachine(  958):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState what:131104 0 0
W/Settings(  958): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  958): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6278): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6278): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6278): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=131162
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  958): processMsg: DriverStartedState
W/WifiHW  (  958): QCOM Debug wifi_send_command "P2P_FLUSH"
E/WifiStateMachine(  958):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/wpa_supplicant( 6278): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6278): [p2p command] (P2P_FLUSH)
E/WifiStateMachine(  958): set frequency band 0
D/wpa_supplicant( 6278): P2P: Stopping find
,D/wpa_supplicant( 6278): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6278): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6278): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  958): sending p2p persistent groups changed broadcast
D/wpa_supplicant( 6278): P2P: Stopping find
D/wpa_supplicant( 6278): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6278): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6278): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiP2pService(  958): InactiveState
I/QuickSettingWifi( 1215): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6278): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6278): SETBAND: 0
D/wpa_supplicant( 6278): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6278): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6278): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  958): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  958): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  958): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  958): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6278): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6278): P2P: Add operating class 81
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6278): P2P: Add operating class 115
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6278): P2P: Add operating class 116
,D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6278): P2P: Add operating class 117
D/wpa_supplicant( 6278): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6278): P2P: Update channel list
D/wpa_supplicant( 6278): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6278): P2P: cli_channels:
D/wpa_supplicant( 6278): p2p0: Updating hw mode
D/wpa_supplicant( 6278): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6278): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6278): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6278): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6278): nl80211: Added 802.11b mode based on 802.11g information
,E/WifiStateMachine(  958): did set frequency band 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6278): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6278): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6278): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  958): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6278): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6278): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  958): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
,D/wpa_supplicant( 6278): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6278): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6278): wlan0: Cancelling sched scan
D/wpa_supplicant( 6278): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6278): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6278): wpa_supplicant_scan enter
D/wpa_supplicant( 6278): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6278): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6278): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6278): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  958): done set frequency band 0
W/WifiHW  (  958): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 6278): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6278): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6278): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6278): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6278): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6278): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
,D/wpa_supplicant( 6278): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WISPrService( 5658): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiService(  958): New client listening to asynchronous messages
,E/WifiTrafficPoller(  958): ADD_CLIENT: 8
,D/WISPrService( 5658): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  958): Wifi band: 0, ScanBroadCastCounter: 0,
D/WifiStateMachine(  958): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=147462
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=130905  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  958): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  958): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=130906  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  958): handleMessage: X
E/WifiStateMachine(  958): handleMessage: E msg.what=143371
E/WifiStateMachine(  958): processMsg: DisconnectedState
E/WifiStateMachine(  958):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  958): processMsg: ConnectModeState
E/WifiStateMachine(  958):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  958): processMsg: DriverStartedState
E/WifiStateMachine(  958):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  958): processMsg: SupplicantStartedState
E/WifiStateMachine(  958):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  958): processMsg: DefaultState
E/WifiStateMachine(  958):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  958): handleMessage: X
,D/wpa_supplicant( 6278): EAPOL: disable timer tick
,D/wpa_supplicant( 6278): EAPOL: disable timer tick,
,D/BluetoothManagerService(  958): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6159): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6159): 
I/jxcore-log( 6159): my name is : HTC-HTC One M8s_PT1266
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): attempting to connect to test coordinator,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): check test folder
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): found test : ./testFindPeers.js,
I/jxcore-log( 6159): 
,I/art     (  958): Explicit concurrent mark sweep GC freed 26952(1406KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.953ms total 160.010ms
,I/jxcore-log( 6159): found test : ./testReConnect.js,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): found test : ./testSendData.js
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): Test app app.js loaded
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
I/chromium( 6159): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): releaseWL(66f510b): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/BluetoothAdapter( 6159): 79764881: getState(). Returning 12
,I/jxcore-log( 6159): BLE supported!!
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  958): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  958): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  958): acquireWL(3852adb): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{10024}
V/AlarmManager(  958): sending alarm PendingIntent{13242978: PendingIntentRecord{18b024b1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=131125, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{35d86851: PendingIntentRecord{1c9348b6 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144114, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{5d649b5: PendingIntentRecord{3db0b84a android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=147448, Int=0
D/PMS     (  958): acquireWL(3da199b7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/PMS     (  958): releaseWL(3852adb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1882): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1882): [NET] android_getaddrinfo_proxy+
D/libc    ( 1882): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  958): [NET] android_getaddrinfofornet-, err=8
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  958): [NET] android_getaddrinfo_proxy+
D/libc    (  958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1882): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  958): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  958): releaseWL(3da199b7): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,W/ContextImpl(  958): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(152e6524): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null,
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(152e6524): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/PMS     (  958): runPSCheck
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): Checking...
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/TelephonyReceiver( 1468): switchBindHtcMsgCursor: null
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1215): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
D/HtcAppUPService( 1414): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@1cac403e
,I/ActivityManager(  958): Killing 5953:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  958): killProcessQuiet, pid=5953
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5953
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(56a388d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PMS     (  958): releaseWL(56a388d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  958): updateBatteryInfo
D/WifiController(  958): processMsg: DeviceActiveState
D/PMS     (  958): runPSCheck
D/WifiController(  958): processMsg: StaEnabledState
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: DefaultState
I/HtcPowerSaver(  958): >> updateStatus
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
D/WifiController(  958): handleMessage: X
D/WifiController(  958): battery changed pluggedType: 2
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  958): acquireWL(35833a42): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000},
V/AlarmManager(  958): sending alarm PendingIntent{c01e192: PendingIntentRecord{3873b763 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=167737, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{5d649b5: PendingIntentRecord{3db0b84a android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=207469, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{15ac1a53: PendingIntentRecord{197eaf90 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=208477, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{dced089: PendingIntentRecord{378eb88e com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186574, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{2fd408af: PendingIntentRecord{18b024b1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=234848, Int=0
,D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4,
D/libc    (  958): [NET] android_getaddrinfofornet-, err=8
D/libc    (  958): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/PMS     (  958): acquireWL(1e4734bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  958): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  958): [NET] android_getaddrinfo_proxy+
D/libc    (  958): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    (  958): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  958): releaseWL(1e4734bc): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  958): acquireWL(1bcaec45): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1882): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1882): [NET] android_getaddrinfo_proxy+
D/libc    ( 1882): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1882): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  958): releaseWL(1bcaec45): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(35833a42): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(2bc1cf9a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  958): n_update end
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  958): releaseWL(2bc1cf9a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  958): runPSCheck
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  958): processMsg: DefaultState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  958): handleMessage: X
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
,D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  958): << updateStatus
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5682): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5682): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1215): reapply : com.google.android.gms 6 40
,W/System  ( 5682): Ignoring header User-Agent because its value was null.,
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5682): [NET] android_getaddrinfofornet-, err=8,
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5682): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5682): [NET] android_getaddrinfo_proxy+
D/libc    ( 5682): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5682): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(271f44ec): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000}
,V/AlarmManager(  958): sending alarm PendingIntent{c01e192: PendingIntentRecord{3873b763 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=287736, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{247d534a: PendingIntentRecord{2df932bb com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1449471175148, Int=0,
,V/AlarmManager(  958): sending alarm PendingIntent{3831c3d8: PendingIntentRecord{18b024b1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=409642, Int=0
,D/PMS     (  958): acquireWL(27ec6331): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1882 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1882): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1882): [NET] android_getaddrinfo_proxy+
D/libc    ( 1882): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1882): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  958): releaseWL(27ec6331): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  958): releaseWL(271f44ec): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(2ec55a16): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  958): n_update end
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  958): releaseWL(2ec55a16): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  958): updateBatteryInfo
W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
D/PowerUI ( 1215): closing low battery warning: level=100
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PMS     (  958): runPSCheck
D/HtcPowerSaver(  958): Checking...
I/HtcPowerSaver(  958): >> updateStatus
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  958): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  958): << updateStatus
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  958): plugged=true pluggin=true
,D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: E msg.what=155652
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(e7e3f97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(e7e3f97): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PMS     (  958): runPSCheck
D/WifiController(  958): handleMessage: E msg.what=155652
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: DeviceActiveState
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: StaEnabledState
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/Atfwd_Sendcmd(  466): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(28eb4584): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(28eb4584): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PMS     (  958): runPSCheck
D/WifiController(  958): handleMessage: E msg.what=155652
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: DeviceActiveState
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/ContactMessageStore( 1468): MSG_CHECK_DELETION >>,
,D/ContactMessageStore( 1468): mDeleteTask = null, bDeleting = false,
D/AccFlag ( 1468): sku_id=118,
D/ContactMessageStore( 1468): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1468): start background delete task...
,D/ContactMessageStore( 1468): size: 0 , 0
,D/ContactMessageStore( 1468): Background delete complete
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(2373016d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
,I/BatteryService(  958): n_update end
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  958): releaseWL(2373016d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  958): updateBatteryInfo
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  958): plugged=true pluggin=true
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  958): runPSCheck
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  958): Checking...
,I/HtcPowerSaver(  958): >> updateStatus
D/PowerUI ( 1215): closing low battery warning: level=100
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/UsbnetService(  958): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  958): << updateStatus
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): handleMessage: E msg.what=155652
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: DefaultState,
D/WifiController(  958): handleMessage: X
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5682): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5682): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5682): Ignoring header User-Agent because its value was null.
,D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5682): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5682): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5682): [NET] android_getaddrinfo_proxy+
D/libc    ( 5682): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5682): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1215): reapply : com.google.android.gms 5 40
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  958): acquireWL(8d83c87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  958): n_update end
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PMS     (  958): releaseWL(8d83c87): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  958): plugged=true pluggin=true
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/PMS     (  958): runPSCheck
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): Checking...
D/UsbnetService(  958): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): handleMessage: E msg.what=155652
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  958): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  958): processMsg: StaEnabledState
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  958): processMsg: DefaultState
I/HtcPowerSaver(  958): << updateStatus
D/WifiController(  958): handleMessage: X
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(3ded17b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
,I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(3ded17b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  958): plugged=true pluggin=true
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/WifiController(  958): battery changed pluggedType: 2
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  958): updateBatteryInfo
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  958): runPSCheck
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  958): Checking...
D/UsbnetService(  958): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  958): >> updateStatus
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): handleMessage: E msg.what=155652
D/WifiController(  958): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(24641fdd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(24641fdd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
,D/WifiController(  958): handleMessage: E msg.what=155652
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: DeviceActiveState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  958): updateBatteryInfo
,D/PMS     (  958): runPSCheck
D/HtcPowerSaver(  958): Checking...
I/HtcPowerSaver(  958): >> updateStatus
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  958): acquireWL(2451752): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(2451752): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  958): runPSCheck
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DeviceActiveState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  958): processMsg: StaEnabledState
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  958): processMsg: DefaultState
I/HtcPowerSaver(  958): << updateStatus
D/WifiController(  958): handleMessage: X
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(1ff21a23): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000},
V/AlarmManager(  958): sending alarm PendingIntent{c01e192: PendingIntentRecord{3873b763 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=467736, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{1c186c9f: PendingIntentRecord{978e1ec android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=807450, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{381dfb20: PendingIntentRecord{18b024b1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=759176, Int=0
,I/ActivityManager(  958): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6387 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  958): sending alarm PendingIntent{2207dcd9: PendingIntentRecord{b79569e com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1449471540829, Int=0
,I/ActivityManager(  958): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=6406 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  958): sending alarm PendingIntent{3742357f: PendingIntentRecord{12b7a94c com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
,V/AlarmManager(  958): sending alarm PendingIntent{2a906d95: PendingIntentRecord{15eddfc9 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449471794750, Int=0
,D/PMS     (  958): acquireWL(37203eaa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1882 10024 WorkSource{10024 com.google.android.gms},
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1882): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1882): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1882): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1882): [NET] android_getaddrinfo_proxy+
W/ContextImpl( 6057): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/libc    ( 1882): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  958): releaseWL(37203eaa): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1882): [NET] android_getaddrinfo_proxy-, NODATA
,D/WeatherUtility( 1215): Weather sync is On,
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/PMS     (  958): releaseWL(1ff21a23): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6057): MY_DEBUG = false
,D/PowerUsageService( 6057): repeat time = 1449472694873,
,I/ImageRamCache( 6406): create image Cache, size: 31457280.,
I/ImageRamCache( 6406): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 6406): create image Cache, size: 31457280.
,I/FeedSettings( 6406): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 6406): GroupBudget 0.500000 0.380000
I/FeedSettings( 6406): GroupBudget 60 45 15
,I/PowerUsageList:PowerUsageHelper( 6057): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/Prism.ExternalStringMa_( 6406): changeLocale(): en_GB
,D/PowerUsageList:BatterySipperExt( 6057): gen(), null == sipper.uidObj, userId = 0
,I/Prism.AllAppsOptionsMa_( 6406): loadSortType() with Custom,
,I/Prism.AllAppsOptionsMa_( 6406): loadGridSize() with Alternative
,E/cutils-trace( 6436): Error opening trace file: Permission denied (13),
I/dex2oat ( 6436): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6436): dex2oat: override thread count:4
,D/libc    ( 6406): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4,
,D/libc    ( 6406): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 6406): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    ( 6406): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6406): [NET] android_getaddrinfo_proxy+
D/libc    ( 6406): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 6406): [NET] android_getaddrinfo_proxy-, NODATA
,E/[CSBICLIENT][v12][BiLogUploadService]( 6406): Exception on getConfig()
,D/Process (  958): killProcessQuiet, pid=5751
I/ActivityManager(  958): Killing 5751:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5751
,I/dex2oat ( 6436): dex2oat took 672.937ms (threads: 4),
,I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
,I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6387): ApplicationMonitor {a9c70f7}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6387): PnsModel {c61f4f6}: update(): Update registration caused by: alarm,
,I/PushClient( 6387): PnsConfigModel {34119d85}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6387): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6387): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6387): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6387): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  958): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6447 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6447): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6447 dbg=false s=true,
,I/DeviceManagement( 6447): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6447): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6447): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6447): WorkflowService: Starting workflow service
,I/DeviceManagement( 6447): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4c11d91] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6447): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6447): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6447): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6447): SessionStateController: Checking invariants...
,I/DeviceManagement( 6447): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 6447): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6447): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6447): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4c11d91],
,I/DeviceManagement( 6447): WorkflowService: Stopping workflow service
,D/Process (  958): killProcessQuiet, pid=5609
I/ActivityManager(  958): Killing 5609:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5609
,I/PushClient( 6387): PnsModel {c61f4f6}: update(): The registration record has not expired yet. No need to update.
,D/Process (  958): killProcessQuiet, pid=5865
I/ActivityManager(  958): Killing 5865:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  958): Recipient 5865
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/SQLiteConnectionPool( 6406): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5682): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5682): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
W/System  ( 5682): Ignoring header User-Agent because its value was null.
,D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5682): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5682): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5682): [NET] android_getaddrinfo_proxy+
D/libc    ( 5682): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5682): [NET] android_getaddrinfo_proxy-, NODATA
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): ,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(9c8db57): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000}
V/AlarmManager(  958): sending alarm PendingIntent{c01e192: PendingIntentRecord{3873b763 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1007736, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{19a41644: PendingIntentRecord{263e632d com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1449471846516, Int=0
,D/SmartSyncUtils( 6057): isEpsOn(), nState = 0
,D/WeatherUtility( 1215): Weather sync is On
,W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
D/PMS     (  958): releaseWL(9c8db57): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/PMS     (  958): acquireWL(2c962062): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6057 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 6057): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6057): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6057): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6057): SettingOnTime = 1449554400000, randomSettingOnTime = 1449554049000
D/SmartSyncScreenOnOffTimeReceiver( 6057): SettingOffTime = 1449532800000, randomSettingOffTime = 1449533073000
D/SmartSyncScreenOnOffTimeReceiver( 6057): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6057): bNightMode = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6057): bNightModeTurnOffOnce = false
D/PMS     (  958): releaseWL(2c962062): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,D/PMS     (  958): acquireWL(2795d5f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null,
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(2795d5f3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  958): BroadcastReceiver::onReceive+,
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/NotificationService(  958): plugged=true pluggin=true
,D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  958): runPSCheck
,D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: StaEnabledState
D/PowerUI ( 1215): closing low battery warning: level=100
D/WifiController(  958): processMsg: DefaultState
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  958): handleMessage: X
I/HtcPowerSaver(  958): << updateStatus
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(2eee52b0): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{1002}
,I/bt-btm  ( 6214): Received oneshot timer event complete
V/AlarmManager(  958): sending alarm PendingIntent{3ccb0529: PendingIntentRecord{24b9e0ae com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1030209, Int=0
I/bt-btm  ( 6214): btm_ble_timeout
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
D/PMS     (  958): releaseWL(2eee52b0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
,D/PMS     (  958): acquireWL(3a2dde4f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6214 1002 null
,D/bt-btm  ( 6214): btm_ble_rand_enc_complete,
I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = bf cd 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = a2 92 1e b6 ad 4c b5 bf ff f9 7a 0f 13 b3 c7 dc 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  958): releaseWL(3a2dde4f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  958): acquireWL(3f5de9dc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  958): n_update end
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  958): releaseWL(3f5de9dc): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1215): closing low battery warning: level=100
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PMS     (  958): runPSCheck
D/WifiController(  958): handleMessage: E msg.what=155652
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: DeviceActiveState
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: StaEnabledState
I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  958): processMsg: DefaultState
I/HtcPowerSaver(  958): << updateStatus
D/WifiController(  958): handleMessage: X
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(1465cae5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(1465cae5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  958): runPSCheck
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PowerUI ( 1215): closing low battery warning: level=100
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  958): << updateStatus
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/UsageStatsService(  958): User[0] Flushing usage stats to disk
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): ,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5682): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5682): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5682): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1215): reapply : com.google.android.gms 3 40
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5682): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5682): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5682): [NET] android_getaddrinfo_proxy+
D/libc    ( 5682): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5682): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(268f93f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null,
,I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  958): n_update end
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PMS     (  958): releaseWL(268f93f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PowerUI ( 1215): closing low battery warning: level=98
D/WifiController(  958): handleMessage: E msg.what=155652
D/PMS     (  958): runPSCheck
D/WifiController(  958): processMsg: DeviceActiveState
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: StaEnabledState
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: X
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetPhoneState( 6214): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
I/HtcPowerSaver(  958): updateStatus (8000,98,-1,false,false,false,-1)
D/HeadsetStateMachine( 6214): Disconnected process message: 11, size: 0
I/HtcPowerSaver(  958): << updateStatus
D/DotMatrix( 1303): [EventService] reorderNotification, total:1
W/ContextImpl( 6057): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/TetherSettings( 5658): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5658): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5658): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5658): Cust_ConnectToPC   : spcsc>false
D/        ( 5658): Cust_ConnectToPC   : IPT>true
D/        ( 5658): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5658): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5658): Index of the first 1 = -1
I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5658): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5658): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5658): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5658): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1215): status:2 level:98 unsupport:false plugged:true
,D/SmartNS_Utility( 5658): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5658): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(2eb83755): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null,
,I/BatteryService(  958): n_update end
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PMS     (  958): releaseWL(2eb83755): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
,D/PMS     (  958): runPSCheck
D/WifiController(  958): handleMessage: E msg.what=155652
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: DeviceActiveState
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: DefaultState
,I/HtcPowerSaver(  958): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  958): handleMessage: X
I/HtcPowerSaver(  958): << updateStatus
D/PowerUI ( 1215): closing low battery warning: level=98
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
,I/BatteryController( 1215): status:2 level:98 unsupport:false plugged:true,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(2609a56a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(2609a56a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PMS     (  958): runPSCheck
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): handleMessage: E msg.what=155652
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DeviceActiveState
D/PowerUI ( 1215): closing low battery warning: level=98
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
,D/WifiController(  958): handleMessage: X
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
,D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  958): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1215): status:2 level:98 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5682): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5682): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5682): Ignoring header User-Agent because its value was null.
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5682): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5682): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5682): [NET] android_getaddrinfo_proxy+
D/libc    ( 5682): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5682): [NET] android_getaddrinfo_proxy-, NODATA
D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
I/RemoteViews( 1215): reapply : com.google.android.gms 7 40
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(224b863c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  958): n_update end
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/PMS     (  958): releaseWL(224b863c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): closing low battery warning: level=99
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): updateBatteryInfo
D/WifiController(  958): handleMessage: E msg.what=155652
D/PMS     (  958): runPSCheck
D/WifiController(  958): processMsg: DeviceActiveState
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: StaEnabledState,
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/HtcPowerSaver(  958): updateStatus (8000,99,-1,false,false,false,-1),
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1215): status:2 level:99 unsupport:false plugged:true,
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/PMS     (  958): acquireWL(2b769fc5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService(  958): n_update end
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  958): releaseWL(2b769fc5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/PowerUI ( 1215): closing low battery warning: level=99
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  958): battery changed pluggedType: 2
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  958): updateBatteryInfo
D/WifiController(  958): handleMessage: E msg.what=155652
D/PMS     (  958): runPSCheck
D/WifiController(  958): processMsg: DeviceActiveState
D/HtcPowerSaver(  958): Checking...
D/WifiController(  958): processMsg: StaEnabledState
I/HtcPowerSaver(  958): >> updateStatus
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
,I/HtcPowerSaver(  958): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,I/BatteryController( 1215): status:2 level:99 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(3d8e3d1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
D/PMS     (  958): releaseWL(3d8e3d1a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1303): [EventService] reorderNotification, total:0
D/PowerUI ( 1215): closing low battery warning: level=100
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  958): updateBatteryInfo
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  958): plugged=true pluggin=true
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6214): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6214): Disconnected process message: 11, size: 0
,D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/WifiController(  958): handleMessage: E msg.what=155652
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/PMS     (  958): runPSCheck
D/WifiController(  958): handleMessage: X
D/HtcPowerSaver(  958): Checking...
I/HtcPowerSaver(  958): >> updateStatus
,W/ContextImpl( 6057): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,I/HtcPowerSaver(  958): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  958): << updateStatus
,D/TetherSettings( 5658): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5658): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5658): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5658): Cust_ConnectToPC   : spcsc>false
D/        ( 5658): Cust_ConnectToPC   : IPT>true
D/        ( 5658): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5658): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
D/SmartNS_NSReceiver( 5658): Index of the first 1 = -1
,W/ContextImpl( 5658): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5658): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5658): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5658): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5658): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/ProcessStatsService(  958): Prepared write state in 7ms
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1882): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1882): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1882): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1882): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1882): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1882): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1882): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1882): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1882): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1882): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1303): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5682): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5682): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5682): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5682): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5682): Ignoring header User-Agent because its value was null.
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5682): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5682): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5682): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5682): [NET] android_getaddrinfo_proxy+
I/RemoteViews( 1215): reapply : com.google.android.gms 2 40
,D/libc    ( 5682): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  396): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  396): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  396): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  396): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5682): [NET] android_getaddrinfo_proxy-, NODATA
,I/ProcessStatsService(  958): Pruning old procstats: /data/system/procstats/state-2015-12-06-10-45-10.bin
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6159): 
,D/PMS     (  958): acquireWL(170020ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 958 1000 WorkSource{1000}
V/AlarmManager(  958): sending alarm PendingIntent{c01e192: PendingIntentRecord{3873b763 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1067737, Int=0
,V/AlarmManager(  958): sending alarm PendingIntent{3b47b23b: PendingIntentRecord{2a770d58 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1930218, Int=0
,D/Process (  958): killProcessQuiet, pid=6113
I/ActivityManager(  958): Killing 6113:com.htc.calendar/u0a10 (adj 13): empty for 1815s
,I/bt-btm  ( 6214): Received oneshot timer event complete
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/bt-btm  ( 6214): btm_ble_timeout
I/bt-btm  ( 6214): btm_gen_resolvable_private_addr
,I/ActivityManager(  958): Recipient 6113
,D/Process (  958): killProcessQuiet, pid=6089
I/ActivityManager(  958): Killing 6089:com.htc.mobiledata/u0a46 (adj 13): empty for 1815s
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/art     (  958): Explicit concurrent mark sweep GC freed 29516(1590KB) AllocSpace objects, 16(1128KB) LOS objects, 33% free, 16MB/24MB, paused 1.612ms total 175.262ms,
D/PMS     (  958): acquireWL(4d1aeb1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6214 1002 null
,D/bt-btm  ( 6214): btm_ble_rand_enc_complete
I/bt-btm  ( 6214): btm_gen_resolve_paddr_low
D/bt-smp  ( 6214): smp_encrypt_data
W/bt-smp  ( 6214): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6214): Plain text(LSB ~ MSB) = 37 b7 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6214): Encrypted text(LSB ~ MSB) = 9b f7 06 40 df 0f e0 00 6e f8 84 80 12 53 80 9d 
I/bt-btm  ( 6214): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6214): Stopping oneshot timer
D/bt-btm  ( 6214): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  958): Recipient 6089,
,D/Process (  958): killProcessQuiet, pid=6027
,I/ActivityManager(  958): Killing 6027:com.htc.bgp/u0a11 (adj 13): empty for 1816s
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 6027
,D/Process (  958): killProcessQuiet, pid=6004
I/ActivityManager(  958): Killing 6004:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1821s
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 6004
,D/Process (  958): killProcessQuiet, pid=5682
I/ActivityManager(  958): Killing 5682:com.android.vending/u0a72 (adj 15): empty for 1829s
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 5682
,D/Process (  958): killProcessQuiet, pid=4442
I/ActivityManager(  958): Killing 4442:com.google.android.gms/u0a24 (adj 15): empty for 1831s
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  958): Recipient 4442
,D/Process (  958): killProcessQuiet, pid=6250,
I/ActivityManager(  958): Killing 6250:com.htc.widget.hmsproc3/u0a34 (adj 13): empty for 1800s
,D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  958): Recipient 6250
,D/PMS     (  958): releaseWL(4d1aeb1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/PMS     (  958): releaseWL(170020ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1215): Weather sync is On
W/WeatherTimeKeeper( 1215): [refreshWeatherData] no weather data
,I/jxcore-log( 6159): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6159): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 6492): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6492): ====startRecUseTime====
D/htc.customization.log.level( 6492):  is 
W/CustomizationLogLevel( 6492): Level value is invalid, use default level 2
D/CustomizationManager( 6492):  Read ACC file spent 0.033 (s)
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6492): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6492): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6492): Parsing tag category name = system
I/CustomizationCIDLoader( 6492): Parsing tag category name = application
I/CustomizationCIDLoader( 6492): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6492): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6492): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6492): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6492): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6492): add string-array item, value = 42507
I/CustomizationCIDLoader( 6492): add string-array item, value = 21902
I/CustomizationCIDLoader( 6492): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6492): add string-array item, value = 23420
I/CustomizationCIDLoader( 6492): add string-array item, value = 22299
I/CustomizationCIDLoader( 6492): add string-array item, value = 24002
I/CustomizationCIDLoader( 6492): add string-array item, value = 23210
I/CustomizationCIDLoader( 6492): add string-array item, value = 23205
I/CustomizationCIDLoader( 6492): add string-array item, value = 23806
I/CustomizationCIDLoader( 6492): add string-array item, value = 23430
I/CustomizationCIDLoader( 6492): add string-array item, value = 23408
I/CustomizationCIDLoader( 6492): add string-array item, value = 27205
I/CustomizationCIDLoader( 6492): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6492): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6492):  Read CID file spent 0.068 (s)
D/CustomizationManager( 6492):  All configurations done spent 0.068 (s)
D/PackageManager(  958): deletePackageAsUser: pkg=com.test.thalitest, pid=6492, uid=2000 userid=0
I/ActivityManager(  958): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  958): Killing 6159:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  958): killProcessQuiet, pid=6159
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  958): Skipping PackageSetting{29a6ce94 com.example.hello/10373} due to missing metadata
I/ActivityManager(  958): Recipient 6159
E/InputEventReceiver( 1353): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{1ec1b33b uid 10366 pid 6159} (c)'
I/WindowState(  958): WIN DEATH: Window{1b07f41f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  958): Client connection lost with reason: 4
I/ActivityManager(  958):   Force finishing activity ActivityRecord{1a2c9ff8 u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  958): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  958):   Force finishing activity ActivityRecord{1a2c9ff8 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  958): Duplicate finish request for ActivityRecord{1a2c9ff8 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  958): Spurious death for ProcessRecord{3e677f96 6159:com.test.thalitest/u0a366}, curProc for 6159: null
D/DotMatrix( 1303): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1303): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1303): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/SystemReader(  958): Cannot find grip_rejection_width, use default value instead
D/PMS     (  958): acquireWL(142184ed): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1821 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1821): Ignoring removeGeofence because network location is disabled.
D/PMS     (  958): releaseWL(142184ed): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
I/InputMethodManagerService(  958): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/AccTypeManager( 1687): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/Prism.ItemManager( 6406): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 6406): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1687): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PhoneApp( 1468): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/art     ( 1526): Explicit concurrent mark sweep GC freed 6266(360KB) AllocSpace objects, 9(644KB) LOS objects, 34% free, 29MB/45MB, paused 904us total 88.899ms
I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1644): Cleaning up data for package: com.test.thalitest
I/Launcher( 1526): Deferring update until onResume
D/Launcher( 1526): waitUntilResume // bindAppsRemoved
D/Prism.PackageStateRece_( 1526): action: android.intent.action.PACKAGE_REMOVED
W/ResourcesManager(  958): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/[PluginManager]RegisterService( 1414): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/ActivityManager(  958): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6513 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/[PluginManager]RegisterService( 1414): handle notify Blinkfeed plugin client changed
D/AccTypeManager( 1687): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 1687): Unsupported attribute readOnly
I/art     (  958): Explicit concurrent mark sweep GC freed 15918(1348KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.529ms total 203.100ms
I/art     (  958): WaitForGcToComplete blocked for 178.092ms for cause Explicit
D/StatusBarManagerService(  958): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
D/StatusBarManagerService(  958): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  958): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  958): hiding MENU key
W/ContextImpl( 6513): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/FindExtension( 1526): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1526): Defer allocateBuffers to drawing time
W/InputMethodManagerService(  958): Got RemoteException sending setActive(false) notification to pid 6159 uid 10366
D/StatusBarManagerService(  958): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  958): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6537 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
I/ActivityManager(  958): Killing 6339:com.htc.android.mail:sync/u0a62 (adj 15): empty for 1807s
D/Process (  958): killProcessQuiet, pid=6339
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/PackageManager(  958): Unable to load service info ResolveInfo{2e0f43d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  958): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  958): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  958): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  958): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  958): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  958): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  958): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  958): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  958): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  958): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  958): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  958): Explicit concurrent mark sweep GC freed 7370(408KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 4.190ms total 213.830ms
W/asset   (  958): Copying FileAsset 0x557f8b96e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  958): Recipient 6339
D/TaskPersister(  958): removeObsoleteFile: deleting file=8_task.xml
I/PhoneStatusBar( 1215): setImeWindowStatus(false,false)
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=6537, uid=10072, userID:0
W/global  ( 6537): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6537): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/global  ( 6537): [apache-http] Connection GC has been deprecated!
W/global  ( 6537): [apache-http] Connection GC has been deprecated!
D/Finsky  ( 6537): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  958): acquireWL(25e18da7): PARTIAL_WAKE_LOCK  *alarm* 0x1 958 1000 WorkSource{10024}
V/AlarmManager(  958): sending alarm PendingIntent{105c6254: PendingIntentRecord{3e43a5fd com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449472102774, Int=1800000
V/AlarmManager(  958): sending alarm PendingIntent{3e0ef2f2: PendingIntentRecord{18b024b1 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1661595, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{138f5d43: PendingIntentRecord{27474fc0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1854671, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{2229a4f9: PendingIntentRecord{d954c3e com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1866630, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{1c186c9f: PendingIntentRecord{978e1ec android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1682584, Int=0
V/AlarmManager(  958): sending alarm PendingIntent{3eff0ee3: PendingIntentRecord{2fb4b0e0 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825652, Int=1800000
V/AlarmManager(  958): sending alarm PendingIntent{3bc08a9f: PendingIntentRecord{15eddfc9 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1449472694873, Int=0
I/ActivityManager(  958): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6578 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/Settings( 6537): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6537): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6537): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6537): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6537): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6537): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 6537): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6537): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6537): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6537): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6537): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 6537): Process: com.android.vending, PID: 6537
E/AndroidRuntime( 6537): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6537): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6537): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6537): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 6537): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 6537): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 6537): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6537): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6537): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6537): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  958):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=6537, uid=10072, userID:0
E/ActivityManager(  958): App crashed! Process: com.android.vending
D/Process ( 6537): killProcess, pid=6537
E/SQLiteDatabase( 6537): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6537): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6537): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6537): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 6537): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 6537): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6537): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6537): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6537): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6537): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6537): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6537): crash in the same process: AsyncTask #1
E/AndroidRuntime_2_crash( 6537): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 6537): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 6537): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 6537): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 6537): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 6537): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 6537): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 6537): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 6537): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime_2_crash( 6537): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime_2_crash( 6537): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime_2_crash( 6537): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime_2_crash( 6537): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime_2_crash( 6537): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/AndroidRuntime_2_crash( 6537): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/AndroidRuntime_2_crash( 6537): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/AndroidRuntime_2_crash( 6537): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/AndroidRuntime_2_crash( 6537): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/AndroidRuntime_2_crash( 6537): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/AndroidRuntime_2_crash( 6537): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 6537): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 6537): 	... 4 more
D/Process (  958): killProcessQuiet, pid=6285
I/ActivityManager(  958): Killing 6285:com.htc.widget.hmsproc2/u0a40 (adj 15): empty for 1807s
D/Process (  958): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActiveServices.realStartServiceLocked:1458 
D/Process ( 6537): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.finsky.FinskyApp$CrashHandler.uncaughtException:316 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
I/ActivityManager(  958): Recipient 6537
I/ActivityManager(  958): Recipient 6285
I/ActivityManager(  958): Process com.android.vending (pid 6537) has died
I/TrimMemoryManager( 1526): [trimMemory] 5
D/HtcUPManager( 1215): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 5
W/ResourcesManager( 6578): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6578): VM with version 2.1.0 has multidex support
I/MultiDex( 6578): install
I/MultiDex( 6578): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6578): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/PMS     (  958): acquireWL(21e5fca2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 958 1000 null
I/BatteryService(  958): n_update end
I/IntentController( 1215): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  958): releaseWL(21e5fca2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6214): Disconnected process message: 10, size: 0
D/UsbnetService(  958): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  958): updateBatteryInfo
D/UsbnetService(  958): onReceive BATTERY_CHANGED
D/PowerUI ( 1215): closing low battery warning: level=100
D/UsbnetService(  958):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  958): plugged=true pluggin=true
D/UsbnetService(  958): BroadcastReceiver::onReceive-
D/PMS     (  958): runPSCheck
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  958): Checking...
D/DotMatrix( 1303): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  958): >> updateStatus
D/DotMatrix( 1303): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  958): battery changed pluggedType: 2
D/WifiController(  958): handleMessage: E msg.what=155652
D/PowerUI ( 1215): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  958): processMsg: DeviceActiveState
D/WifiController(  958): processMsg: StaEnabledState
D/WifiController(  958): processMsg: DefaultState
D/WifiController(  958): handleMessage: X
E/SQLiteLog( 1882): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1882): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x557f1032a0
E/AndroidRuntime( 1882): FATAL EXCEPTION: main
E/AndroidRuntime( 1882): Process: com.google.process.gapps, PID: 1882
E/AndroidRuntime( 1882): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1882): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1882): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1882): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1882): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1882): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1882): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1882): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1882): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1882): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1882): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1882): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1882): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1882): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1882): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1882): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1882): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1882): 	... 9 more
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
D/Process ( 1882): killProcess, pid=1882
D/Process ( 1882): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
W/ActivityThread( 6578): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6578): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@162bd106: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6578): Installed default security provider GmsCore_OpenSSL
I/BatteryController( 1215): status:5 level:100 unsupport:false plugged:true
I/ActivityManager(  958): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=6607 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ResourcesManager( 6607): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6607): VM with version 2.1.0 has multidex support
I/MultiDex( 6607): install
I/MultiDex( 6607): VM has multidex support, MultiDex support library is disabled.
D/Process (  958): killProcessQuiet, pid=1882
D/HtcAmsUtil(  958): isDyingProcess: deadTime=1938773 createTime=27383
D/Process (  958): com.android.server.am.ActivityManagerService.appDiedLocked:5099 com.android.server.am.ActivityManagerService.appDiedLocked:5073 com.android.server.am.ActivityManagerService.getContentProviderImpl:9814 
D/HtcAmsUtil(  958): isDyingProcess: dying proc=1882:14
I/ActivityManager(  958): Provider proc ProcessRecord{37bf99fb 1882:com.google.process.gapps/u0a24} is dying
I/ActivityManager(  958): Existing provider com.google.android.gsf/.gservices.GservicesProvider is crashing; detaching ProcessRecord{2867598f 6607:com.google.android.gms/u0a24}
I/ActivityManager(  958): Recipient 1882
I/ActivityThread( 6578): Removing dead content provider:android.content.ContentProviderProxy@3afc03c7
I/ActivityManager(  958): Process com.google.process.gapps (pid 1882) has died
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
W/ActivityManager(  958): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
I/ActivityManager(  958): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6630 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
W/ActivityManager(  958): Spurious death for ProcessRecord{37bf99fb 0:com.google.process.gapps/u0a24}, curProc for 1882: null
I/Prism.ItemManager( 6406): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 6406): loadItems() com.htc.launcher.pageview.WidgetManager@33306a82 +
I/Prism.WidgetManager( 6406): onLoadItems() +
I/Prism.ItemManager( 1526): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1526): loadItems() com.htc.launcher.pageview.WidgetManager@15c5f4cc +
I/Prism.WidgetManager( 1526): onLoadItems() +
W/ResourcesManager( 1526): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 6406): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/GservicesProvider( 6630): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 6630): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 6630): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6630): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6630): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/SQLiteDatabase( 6630): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/SQLiteDatabase( 6630): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/SQLiteDatabase( 6630): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/SQLiteDatabase( 6630): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/SQLiteDatabase( 6630): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/SQLiteDatabase( 6630): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/SQLiteDatabase( 6630): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/SQLiteDatabase( 6630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/SQLiteDatabase( 6630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6630): 	at android.os.Looper.loop(Looper.java:155)
E/SQLiteDatabase( 6630): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/SQLiteDatabase( 6630): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6630): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/SQLiteDatabase( 6630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6630): FATAL EXCEPTION: main
E/AndroidRuntime( 6630): Process: com.google.process.gapps, PID: 6630
E/AndroidRuntime( 6630): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6630): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5424)
E/AndroidRuntime( 6630): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4992)
E/AndroidRuntime( 6630): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4927)
E/AndroidRuntime( 6630): 	at android.app.ActivityThread.access$1500(ActivityThread.java:144)
E/AndroidRuntime( 6630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1424)
E/AndroidRuntime( 6630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6630): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 6630): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 6630): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6630): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 6630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 6630): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AndroidRuntime( 6630): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AndroidRuntime( 6630): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6630): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6630): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
E/AndroidRuntime( 6630): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
E/AndroidRuntime( 6630): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1702)
E/AndroidRuntime( 6630): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1665)
E/AndroidRuntime( 6630): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5421)
E/AndroidRuntime( 6630): 	... 11 more
E/DropBoxManagerService(  958): Can't write: system_app_crash
E/DropBoxManagerService(  958): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  958): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  958): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  958): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  958): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  958): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  958): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  958): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  958): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  958): 	... 5 more
E/ActivityManager(  958): App crashed! Process: com.google.process.gapps
D/Process ( 6630): killProcess, pid=6630
D/Process ( 6630): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  958): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6652 uid=10072 gids={50072, 9997, 3003, 1028, 1015} abi=arm64-v8a
V/AlarmManager(  958): sending alarm PendingIntent{1609ffab: PendingIntentRecord{2c6d0302 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449472771557, Int=0
W/ResourcesManager( 1526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  958): Recipient 6630
I/ActivityManager(  958): Process com.google.process.gapps (pid 6630) has died
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{347aa873 u0 com.google.android.gms/.playlog.service.PlayLogBrokerService}
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{a7fa519 u0 com.google.android.gms/.gcm.GcmService}
W/ActivityManager(  958): Service crashed 2 times, stopping: ServiceRecord{a4b1fa2 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
W/ResourcesManager( 6406): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  430): Explicit concurrent mark sweep GC freed 8672(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 340us total 49.020ms
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 173us total 33.203ms
I/art     (  430): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 142us total 15.337ms

```
