#### Test 513350283842813_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
D/Process (  986): killProcessQuiet, pid=5221
--------- beginning of system
I/ActivityManager(  986): Killing 5221:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  986): Recipient 5221
E/cutils-trace( 6162): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6162): ====startRecUseTime====
D/htc.customization.log.level( 6162):  is 
W/CustomizationLogLevel( 6162): Level value is invalid, use default level 2
D/CustomizationManager( 6162):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6162): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6162): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6162): Parsing tag category name = system
I/CustomizationCIDLoader( 6162): Parsing tag category name = application
I/CustomizationCIDLoader( 6162): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6162): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6162): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6162): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6162): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6162): add string-array item, value = 42507
I/CustomizationCIDLoader( 6162): add string-array item, value = 21902
I/CustomizationCIDLoader( 6162): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6162): add string-array item, value = 23420
I/CustomizationCIDLoader( 6162): add string-array item, value = 22299
I/CustomizationCIDLoader( 6162): add string-array item, value = 24002
I/CustomizationCIDLoader( 6162): add string-array item, value = 23210
I/CustomizationCIDLoader( 6162): add string-array item, value = 23205
I/CustomizationCIDLoader( 6162): add string-array item, value = 23806
I/CustomizationCIDLoader( 6162): add string-array item, value = 23430
I/CustomizationCIDLoader( 6162): add string-array item, value = 23408
I/CustomizationCIDLoader( 6162): add string-array item, value = 27205
I/CustomizationCIDLoader( 6162): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6162): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6162):  Read CID file spent 0.071 (s)
D/CustomizationManager( 6162):  All configurations done spent 0.071 (s)
I/ActivityManager(  986): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6162 on display 0
D/PMS     (  986): acquireHCC(30472aad): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 986 1000 null
D/PMS     (  986): acquireHCC(2c1c11e2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 986 1000 null
W/asset   (  986): Copying FileAsset 0x5574531aa0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  986): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6180 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1327): [EventService]  onDisplayChanged: 0
V/ActivityManager(  986): Display changed displayId=0
D/DotMatrix( 1327): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6180): Copying FileAsset 0xabe94b10 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  986): acquireWL(386d6a2e): PARTIAL_WAKE_LOCK  *alarm* 0x1 986 1000 WorkSource{1000}
D/PMS     (  986): acquireWL(2a8469cf): PARTIAL_WAKE_LOCK  *backup* 0x1 986 1000 null
V/AlarmManager(  986): sending alarm PendingIntent{17b84f5c: PendingIntentRecord{3ed00265 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448443234965, Int=0
D/PMS     (  986): releaseWL(386d6a2e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
W/BackupManagerService(  986): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  986): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  986): releaseWL(2a8469cf): PARTIAL_WAKE_LOCK  *backup* 0x1 null
I/TrimMemoryManager( 1591): [trimMemory] 20
I/WebViewFactory( 6180): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6180): Time to load native libraries: 10 ms (timestamps 5817-5827),
,I/LibraryLoader( 6180): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6180): Binding Chromium to main looper Looper (main, tid 1) {3f57a3f9},
I/LibraryLoader( 6180): Expected native library version number "",actual native library version number ""
,I/chromium( 6180): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6180): Initializing chromium process, singleProcess=true,
,W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6180): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6180): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 6180): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6180): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2),
I/Adreno-EGL( 6180): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6180): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6180): Local Branch: 
I/Adreno-EGL( 6180): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6180): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6180):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_ADAPTER,
D/BluetoothManagerService(  986): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11b0b792:true
W/System.err(  986): java.lang.Throwable: stack dump
W/System.err(  986): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  986): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  986): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  986): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 6180): 459638453: getState() :  mService = null. Returning STATE_OFF,
,W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6180): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 6180): CordovaWebView is running on device made by: HTC
,W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6180): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6180): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
W/HtcSystemUPManager(  986): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,D/StatusBarManagerService(  986): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  986): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  986): hiding MENU key
,D/StatusBarManagerService(  986): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  986): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  986): hiding MENU key
,D/FindExtension( 6180): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6180): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@127fc6ab, mServedView=org.apache.cordova.engine.SystemWebView{2231e108 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@15fd70a1
,I/PhoneStatusBar( 1240): setImeWindowStatus(false,false)
I/InputMethodManagerService(  986): Disable input method client, pid=1591,
D/StatusBarManagerService(  986): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6180): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  986): Displayed com.test.thalitest/.MainActivity: +630ms (total +675ms)
,W/BindingManager( 6180): Cannot call determinedVisibility() - never saw a connection for the pid: 6180,
,D/JsMessageQueue( 6180): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6180): JniHelper::setJavaVM(0xaad288f8), pthread_self() = -1408953680
,D/JX-Cordova( 6180): jxcore cordova android initializing
,W/jxcore-log( 6180): Initializing JXcore engine
W/jxcore-log( 6180): JXcore engine is ready
,W/jxcore-log( 6180): Starting JXcore engine
,W/jxcore-log( 6180): Platform android,
W/jxcore-log( 6180): 
W/jxcore-log( 6180): Process ARCH arm
W/jxcore-log( 6180): 
,D/PMS     (  986): releaseHCC(30472aad): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  986): releaseHCC(2c1c11e2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6180): JXcore Cordova bridge is ready!,
I/jxcore-log( 6180): 
W/jxcore-log( 6180): JXcore engine is started
I/Choreographer( 6180): Skipped 93 frames!  The application may be doing too much work on its main thread.
,D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1542): MSG_NOTIFY_CS_TO_SYNC <<
,I/chromium( 6180): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6180): Toggling radios to true,
I/jxcore-log( 6180): 
,D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  986): checking for enable restriction...
D/BluetoothManagerService(  986): checkBTEasState, ret=true
I/BluetoothManagerService(  986): isBluetoothRestricted(): false
D/BluetoothManagerService(  986): enable(): region ID = 6
D/BluetoothManagerService(  986): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  986): MONITOR_LOG
W/Settings:Agent(  986): name: bluetooth_on
W/Settings:Agent(  986): value: 1
W/Settings:Agent(  986): >> traceCallingStack()
W/Settings:Agent(  986): Process.myPid(): 986
W/Settings:Agent(  986): Process.myTid(): 1641
W/Settings:Agent(  986): Process.myUid(): 1000
W/Settings:Agent(  986): 
W/Settings:Agent(  986): 
W/System.err(  986): java.lang.Throwable: stack dump,
,W/System.err(  986): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  986): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  986): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  986): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  986): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  986): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  986): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  986): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  986): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98),
W/System.err(  986): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  986): 
W/Settings:Agent(  986): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  986): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  986): MESSAGE_ENABLE: mBluetooth = null
,E/WifiTrafficPoller(  986): ADD_CLIENT: 7,
D/WifiService(  986): New client listening to asynchronous messages
D/WifiManager( 6180): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  986): setWifiEnabled: true pid=6180, uid=10366
E/WifiService(  986): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  986): isSprintWifiRestricted(): false
I/WifiService(  986): isMdmWifiRestricted(): false
W/Settings:Agent(  986): MONITOR_LOG
W/Settings:Agent(  986): name: wifi_on
W/Settings:Agent(  986): value: 2
W/Settings:Agent(  986): >> traceCallingStack()
W/Settings:Agent(  986): Process.myPid(): 986
W/Settings:Agent(  986): Process.myTid(): 1619
W/Settings:Agent(  986): Process.myUid(): 1000
W/Settings:Agent(  986): 
W/Settings:Agent(  986): 
W/System.err(  986): java.lang.Throwable: stack dump
,W/System.err(  986): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  986): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  986): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  986): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  986): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  986): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  986): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  986): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  986): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  986): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  986): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  986): 
W/Settings:Agent(  986): << traceCallingStack(): 6(ms)
,I/ActivityManager(  986): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6235 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiController(  986): handleMessage: E msg.what=155656
D/WifiController(  986): processMsg: ApStaDisabledState
D/WifiController(  986): transitionTo: destState=DeviceActiveState
D/WifiController(  986): handleMessage: new destination call exit/enter
,D/WifiManager( 6180): disconnect: Base Package Name=com.test.thalitest, uid=10366
,D/PMS     (  986): acquireWL(219f9e9a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 986 1000 null
E/WifiStateMachine(  986): handleMessage: E msg.what=131145
E/WifiStateMachine(  986): processMsg: InitialState
E/WifiStateMachine(  986):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine(  986): processMsg: DefaultState
E/WifiStateMachine(  986):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  986): handleMessage: X
D/WifiManager( 6180): reconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  986): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  986): handleMessage: E msg.what=131146
D/WifiController(  986): invokeExitMethods: ApStaDisabledState
D/WifiController(  986): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  986): processMsg: InitialState
D/WifiController(  986): moveTempStackToStateStack: i=0,j=2
D/WifiController(  986): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  986): invokeEnterMethods: StaEnabledState
D/WifiController(  986): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  986): setting operational mode to 1
D/WifiController(  986): handleMessage: X
E/WifiStateMachine(  986):  InitialState CMD_RECONNECT 0 0
E/WifiStateMachine(  986): processMsg: DefaultState
E/WifiStateMachine(  986):  DefaultState CMD_RECONNECT 0 0
,E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131083
E/WifiStateMachine(  986): processMsg: InitialState
E/WifiStateMachine(  986):  InitialState CMD_START_SUPPLICANT 0 0
I/jxcore-log( 6180): Radios toggled
I/jxcore-log( 6180): 
I/art     (  453): Explicit concurrent mark sweep GC freed 8668(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 520us total 36.195ms
,I/art     (  453): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 548us total 30.006ms
,W/ResourcesManager( 6235): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
I/art     (  453): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 619us total 33.442ms
,D/AdapterServiceConfig( 6235): Adding HeadsetService
,D/AdapterServiceConfig( 6235): Adding A2dpService
D/AdapterServiceConfig( 6235): Adding HidService
D/AdapterServiceConfig( 6235): Adding HealthService
D/AdapterServiceConfig( 6235): Adding PanService
D/AdapterServiceConfig( 6235): Adding GattService,
,W/linker  ( 6235): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  986): java.lang.Throwable: stack dump
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  986): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@168a62c1:true
W/System.err(  986): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  986): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  986): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  986): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapterState( 6235): make
,I/BluetoothAdapterState( 6235): Entering OffState,
,E/bt_osi_config( 6235): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,D/BluetoothManagerService(  986): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService,
D/BluetoothManagerService(  986): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  986): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 6235): Address is:90:E7:C4:F6:69:77,
,D/BluetoothManagerService(  986): Calling onBluetoothServiceUp callbacks,
D/BluetoothManagerService(  986): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 1240): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4ab7e28
D/BluetoothAdapter( 1240): onBluetoothServiceUp done
,D/BluetoothAdapter( 1562): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@84583f0
D/BluetoothAdapter( 1562): onBluetoothServiceUp done
D/BluetoothAdapter( 1832): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@31b0977b
D/BluetoothAdapter( 1832): onBluetoothServiceUp done
,D/BluetoothAdapter( 3672): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1716ef1c
,D/BluetoothAdapter( 3672): onBluetoothServiceUp done
,D/BluetoothAdapter( 6180): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@29722e51,
,D/BluetoothAdapter( 6180): onBluetoothServiceUp done
,D/BluetoothAdapter( 2405): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@10e05054
D/BluetoothAdapter( 2405): onBluetoothServiceUp done
D/BluetoothAdapter( 1542): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2327b7aa
D/BluetoothAdapter( 1542): onBluetoothServiceUp done
D/BluetoothAdapter(  986): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3b1969fd
,D/BluetoothAdapter(  986): onBluetoothServiceUp done
D/BluetoothAdapter( 6235): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@3e43b14a
D/BluetoothAdapter( 6235): onBluetoothServiceUp done
,D/BluetoothManagerService(  986): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6235): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON,
D/BluetoothAdapterProperties( 6235): Setting state to 11
I/BluetoothAdapterState( 6235): Bluetooth adapter state changed: 10-> 11,
D/BluetoothManagerService(  986): +onBluetoothStateChange prev=10 new=11,
D/Tethering(  986): interfaceAdded wlan0
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothBondStateMachine( 6235): make,
,D/BluetoothManagerService(  986): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  986): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  986): Bluetooth State Change Intent: 10 -> 11
,V/Tethering(  986): TetherInterfaceSM: wlan0: enter InitialState
D/PMS     (  986): releaseWL(219f9e9a): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/BluetoothAdapterService( 6235): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 6235): checkA2dpState: returning
D/BluetoothAdapterService( 6235): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6235): checkHfpState: returning
I/BluetoothBondStateMachine( 6235): StableState(): Entering Off State
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  986): interfaceLinkStateChanged wlan0, false
D/Tethering(  986): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  986): interfaceAdded p2p0
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  986): p2p0 is not a tetherable iface, ignoring
D/Tethering(  986): interfaceLinkStateChanged p2p0, false
D/Tethering(  986): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
V/BluetoothPbapReceiver( 6235): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6235): ***********state = 11
I/IntentController( 1240): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/libc    (  986): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  986): [NET] android_getaddrinfofornet-, SUCCESS
,D/Tethering(  986): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering(  986): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
,D/NGFService( 3672): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
V/Tethering(  986): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  986): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
,D/Tethering(  986): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothHeadset( 1240): Proxy object connected
D/PMS     (  986): acquireWL(2d07e31): PARTIAL_WAKE_LOCK  NetworkStats 0x1 986 1000 null
D/BluetoothHeadset( 1542): Proxy object connected
D/PMS     (  986): releaseWL(2d07e31): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/BluetoothHeadset(  986): Proxy object connected
D/HeadsetService( 6235): Received start request. Starting profile...
D/HeadsetStateMachine( 6235): Version 1.5
D/HeadsetStateMachine( 6235): make
V/NetworkPolicy(  986): updateNetworkEnabledLocked()
V/NetworkPolicy(  986): updateNotificationsLocked()
D/BluetoothPhoneService( 1542): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1542): Proxy object connected
,I/BluetoothAdapterState( 6235): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothHeadset( 1542): Proxy object connected,
D/TetherSettings( 5600): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5600): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5600): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5600): Cust_ConnectToPC   : spcsc>false
,D/        ( 5600): Cust_ConnectToPC   : IPT>true
D/        ( 5600): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5600): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  986): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6274 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,E/SmartNS_Utility( 5600): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5600): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5600): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,D/HeadsetStateMachine( 6235): max_hf_connections = 2
D/BluetoothAdapter(  986): 830126108: getState(). Returning 11,
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
,W/ContextImpl( 5600): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/BluetoothAdapter( 1542): 825667384: getState(). Returning 11,
I/SmartNS_Utility( 5600): setISNotification
,D/UsbnetService(  986): BroadcastReceiver::onReceive+
,D/HeadsetPhoneState( 6235): listenForPhoneState..for service and signal 
,D/SmartNS_Utility( 5600): usb_cable_connect = 1
,D/SmartNS_Utility( 5600): usb_denied = 0
D/HeadsetDualPhoneStateListener_SLOT1( 6235): listen phone state by slot:SLOT1  id:-1
I/SmartNS_PSService( 5600): usb notificaiton:true
,E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetDualPhoneStateListener_SLOT2( 6235): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6235): Enter Disconnected: -2, size: 0
,D/HeadsetDualPhoneStateListener_SLOT1( 6235): listen phone state by slot:SLOT1  id:-1,
D/BluetoothAdapterService( 6235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37dcdf3e
D/HeadsetDualPhoneStateListener_SLOT2( 6235): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6235): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6235): BTHF: set_current_device
I/ActionCombine( 5600): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/A2dpService( 6235): Received start request. Starting profile...
V/Avrcp   ( 6235): make
,D/UsbDeviceManager(  986): [USBNET] bCheckSuppFunc: cdc_network
,D/UsbnetService(  986): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/BluetoothA2dp(  986): Proxy object connected
,D/BluetoothAdapter(  986): 830126108: getState(). Returning 11
,D/SmartNS_Utility( 5600): usb_cable_connect = 1
D/SmartNS_Utility( 5600): usb_denied = 0
I/SmartNS_PSService( 5600): usb notificaiton:true
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
E/RemoteController( 6235): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 6235): make
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/bt-btif ( 6235): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/SmartNS_NSReceiver( 5600): Tethered state change:false isNSOpening:false
D/TetherSettings( 5600): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5600): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5600): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5600): Cust_ConnectToPC   : spcsc>false
D/A2dpService( 6235): setA2dpService(): set to: null
D/        ( 5600): Cust_ConnectToPC   : IPT>true
D/        ( 5600): Cust_ConnectToPC   : Singel_USB>false
D/BluetoothAdapterService( 6235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37dcdf3e
W/Settings( 5600): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5600): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5600): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5600): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/A2dpStateMachine( 6235): Enter Disconnected: -2
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5600): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5600): setISNotification
,D/SmartNS_Utility( 5600): usb_cable_connect = 1
,D/SmartNS_Utility( 5600): usb_denied = 0
I/SmartNS_PSService( 5600): usb notificaiton:true
,E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
,I/QuickSettingMiniLite( 1240): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@38651741
,D/HidService( 6235): Received start request. Starting profile...
,D/BluetoothAdapterService( 6235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37dcdf3e
D/SmartNS_Utility( 5600): usb_cable_connect = 1
D/SmartNS_Utility( 5600): usb_denied = 0
I/SmartNS_PSService( 5600): usb notificaiton:true
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/HtcBtWidget_BTWidgetProvider( 6274): onBTStateChanged() for widget: 
D/HealthService( 6235): Received start request. Starting profile...
D/HtcBtWidget_BTWidgetProvider( 6274): updateWidget(context) for widget: 
E/WifiStateMachine(  986): setWifiState: enabling
E/WifiStateMachine(  986): Supplicant start successful
D/WifiMonitor(  986): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  986): connecting to supplicant
,D/wpa_supplicant( 6272): wpa_supplicant v2.3-devel-5.0.2
D/SmartNS_NSReceiver( 5600): Tethered state change:false isNSOpening:false
D/BluetoothAdapterService( 6235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37dcdf3e
I/QuickSettingBluetooth( 1240): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
I/IntentController( 1240): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/PanService( 6235): Received start request. Starting profile...
I/RemoteViews( 1240): reapply : com.android.settings 2 36
,D/wpa_supplicant( 6272): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6272): random: Trying to read entropy from /dev/random
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/PanService( 6235): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 6235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37dcdf3e
I/RemoteViews( 1240): reapply : com.android.settings 1 36
D/wpa_supplicant( 6272): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6272): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6272): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6272): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6272): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6272): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6272): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6272): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6272): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6272): update_config=1
D/wpa_supplicant( 6272): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6272): device_name='Android_608e'
D/wpa_supplicant( 6272): manufacturer='HTC'
D/wpa_supplicant( 6272): model_name='HTC_PHONE'
D/wpa_supplicant( 6272): model_number='1234'
D/wpa_supplicant( 6272): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6272): p2p_oper_reg_class=126
D/wpa_supplicant( 6272): p2p_oper_channel=149
D/wpa_supplicant( 6272): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6272): persistent_reconnect=1
D/wpa_supplicant( 6272): key_mgmt_offload=1
I/RemoteViews( 1240): reapply : com.android.settings 0 36
D/BtGatt.DebugUtils( 6235): handleDebugAction() action=null
I/wpa_supplicant( 6272): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6272): nl80211: RFKILL status not available
D/BtGatt.GattService( 6235): Received start request. Starting profile...
D/BtGatt.GattService( 6235): start()
D/wpa_supplicant( 6272): nl80211: Using driver-based roaming
D/wpa_supplicant( 6272): nl80211: TDLS supported
D/wpa_supplicant( 6272): nl80211: TDLS external setup
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:5
D/WIFI_ICON( 1240): updateWifiState: WIFI_STATE_CHANGED disabled
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:2
D/StatusBar.NetworkController( 1240): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6272): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl8,0211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/BtGatt.AdvertiseManager( 6235): advertise manager created
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
I/ActivityManager(  986): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6302 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  986): Killing 5867:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6272): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6272): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6272): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6272): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6272): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b94adfd0
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=0104
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=040a
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=040b
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=040c
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=040d
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=090a
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=090b
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=090c
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=090d
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=0409506f9a09
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=7f506f9a09
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=0801
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=040e
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=06
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=0a07
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=0a11
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94adfd0 match=0a1a
D/wpa_supplicant( 6272): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  986): interfaceLinkStateChanged p2p0, false
D/Tethering(  986): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6272): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6272): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6272): htc_wext_command_init +
E/wpa_supplicant( 6272): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6272): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  986): interfaceLinkStateChanged p2p0, false
D/Tethering(  986): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/Process (  986): killProcessQuiet, pid=5867
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/RemoteViews( 1240): reapply : com.android.settings 1 36
,I/QuickSettingWifi( 1240): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
I/ActivityManager(  986): Recipient 5867
D/BluetoothAdapter( 1240): 818114704: getState(). Returning 11
I/QuickSettingMiniLite( 1240): updateLiteState:no connect device!
,D/BluetoothAdapterService( 6235): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37dcdf3e
,D/BluetoothAdapter( 1542): 825667384: getState(). Returning 11,
W/BluetoothHeadset( 1542): Proxy not attached to service
,I/HeadsetPhoneState( 6235): updateServiceState service = 0,roam = 0,
D/HeadsetPhoneState( 6235): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 6235): Disconnected process message: 11, size: 0
,D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 6235): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6235): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 6235): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/BluetoothHeadset( 1542): java.lang.Throwable
D/BluetoothHeadset( 1542): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1542): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1542): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1542): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1542): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/BluetoothHeadset( 1542): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1542): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1542): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1542): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1542): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1542): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/bt-btu  ( 6235): btu_task pending for preload complete event
,E/bt_vendor( 6235): get_bt_soc_type: Failed to get soc type
,D/BluetoothMasReceiver( 6235): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 6235): SapReceiver onReceive ,
,V/BluetoothSapReceiver( 6235): action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothSapReceiver( 6235):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6235): startService = false
,D/AuthorizationBluetoothService( 1933): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/qcom-bluetooth( 6328): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,D/HtcWiFiWidget_WiFiWidgetProvider( 6302): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 6302): updateWidget(context) for widget: 
,I/wpa_supplicant( 6272): wapi_supplicant_init: Init WAI packet p2p0,
D/wpa_supplicant( 6272):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6272):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6272):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): p2p0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 6272): nl80211: Flush PMKIDs
D/wpa_supplicant( 6272): p2p0: State: DISCONNECTED -> INACTIVE
,I/ActivityManager(  986): Killing 4753:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  986): killProcessQuiet, pid=4753
,D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/qcom-bluetooth( 6334): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6335): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 6272): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6272): TDLS: Driver uses external link setup
D/wpa_supplicant( 6272): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6272): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6272): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6272): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6272): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6272): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6272): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6272): Using existing control interface directory.
I/qcom-bluetooth( 6337): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/wpa_supplicant( 6272): P2P: Add operating class 81
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6272): P2P: Own listen channel: 81:6
D/wpa_supplicant( 6272): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6272): P2P: initialized
D/wpa_supplicant( 6272): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6272): P2P: cli_channels:
D/wpa_supplicant( 6272): p2p0: Added interface p2p0
D/wpa_supplicant( 6272): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6272): nl80211: Set p2p0 operstate 0->0 (DORMANT)
,D/wpa_supplicant( 6272): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6272): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6272): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6272): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
,I/qcom-bluetooth( 6338): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/wpa_supplicant( 6272): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6272): disable_scan_offload=1
D/wpa_supplicant( 6272): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6272): update_config=1
D/wpa_supplicant( 6272): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6272): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6272): manufacturer='HTC'
D/wpa_supplicant( 6272): model_name='HTC One M8s'
D/wpa_supplicant( 6272): model_number='HTC One M8s'
D/wpa_supplicant( 6272): config_methods='physical_display virtual_push_button'
,D/wpa_supplicant( 6272): hs20=1
D/wpa_supplicant( 6272): interworking=1
D/wpa_supplicant( 6272): external_sim=1
D/wpa_supplicant( 6272): key_mgmt_offload=1
,I/qcom-bluetooth( 6339): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6340): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,D/wpa_supplicant( 6272): Priority group 176,
D/wpa_supplicant( 6272):    id=0 ssid='NG700'
I/wpa_supplicant( 6272): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6272): nl80211: RFKILL status not available
D/wpa_supplicant( 6272): nl80211: Using driver-based roaming
D/wpa_supplicant( 6272): nl80211: TDLS supported
D/wpa_supplicant( 6272): nl80211: TDLS external setup
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6272): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6272): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl8021,1: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads, 0x0
I/ActivityManager(  986): Recipient 4753
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6272): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6272): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6272): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6272): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6272): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6272): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6272): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6272): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6272): nl80211: Subscribe to mgmt frames with non-AP handle 0x55b94cd100
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=0104
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=040a
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=040b
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=040c
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=040d
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=090a
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=090b
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=090c
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=090d
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=0409506f9a09
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=7f506f9a09
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=0801
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=040e
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=06
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=0a07
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=0a11
D/wpa_supplicant( 6272): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55b94cd100 match=0a1a
D/wpa_supplicant( 6272): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6272): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6272): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6272): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6272): htc_wext_command_init +
I/wpa_supplicant( 6272): htc_wext_command_init -
I/wpa_supplicant( 6272): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6272): Don't set 00 to countryID.conf
D/Tethering(  986): interfaceLinkStateChanged wlan0, false
D/Tethering(  986): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6272): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6272): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6272): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6272): P2P: Add operating class 81
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6272): P2P: Update channel list
D/wpa_supplicant( 6272): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6272): P2P: cli_channels:
D/wpa_supplicant( 6272): p2p0: Updating hw mode
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6272): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6272): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6272): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
,I/wpa_supplicant( 6272): wapi_supplicant_init: Init WAI packet wlan0,
D/wpa_supplicant( 6272):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6272):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6272):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6272): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6272): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6272): nl80211: Flush PMKIDs
,D/wpa_supplicant( 6272): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 6272): TDLS: Driver uses external link setup
D/wpa_supplicant( 6272): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6272): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6272): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6272): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6272): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6272): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6272): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6272): Using existing control interface directory.
,I/wpa_supplicant( 6272): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6272): Initial scan channel cmd: COUNTRY DE
,I/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6272): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6272): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6272): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6272): P2P: Add operating class 81
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6272): P2P: Add operating class 115
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6272): P2P: Add operating class 116
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6272): P2P: Add operating class 117
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6272): P2P: Update channel list
D/wpa_supplicant( 6272): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6272): P2P: cli_channels:
D/wpa_supplicant( 6272): p2p0: Updating hw mode
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6272): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6272): Auto country group 1: ch36
D/wpa_supplicant( 6272): wlan0: Added interface wlan0
D/wpa_supplicant( 6272): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6272): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6272): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 6272): random: Got 20/20 bytes from /dev/random
I/qcom-bluetooth( 6343): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,D/wpa_supplicant( 6272): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2),
D/wpa_supplicant( 6272): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_986-2\x00
D/wpa_supplicant( 6272): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
E/WifiStateMachine(  986): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  986): handleMessage: new destination call exit/enter
E/WifiStateMachine(  986): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  986): invokeExitMethods: InitialState
E/WifiStateMachine(  986): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  986): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  986): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131144
E/WifiStateMachine(  986): processMsg: SupplicantStartingState
E/WifiStateMachine(  986):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  986): deferMessage: msg=131144
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131085
E/WifiStateMachine(  986): processMsg: SupplicantStartingState
E/WifiStateMachine(  986):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  986): deferMessage: msg=131085
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131149
E/WifiStateMachine(  986): processMsg: SupplicantStartingState
E/WifiStateMachine(  986):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  986): processMsg: DefaultState
E/WifiStateMachine(  986):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  986): setSuspendOptimizations: 2 true
E/WifiStateMachine(  986): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131101
E/WifiStateMachine(  986): processMsg: SupplicantStartingState
,E/WifiStateMachine(  986):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  986): processMsg: DefaultState
E/WifiStateMachine(  986):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  986): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  986): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=147457
E/WifiStateMachine(  986): processMsg: SupplicantStartingState
D/wpa_supplicant( 6272): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6272): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6272): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
E/WifiStateMachine(  986):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
D/wpa_supplicant( 6272): nl80211: Regulatory domain change
D/wpa_supplicant( 6272):  * initiator=1
D/wpa_supplicant( 6272):  * type=0
E/WifiStateMachine(  986): Supplicant connection established
D/wpa_supplicant( 6272):  * alpha2=DE
D/wpa_supplicant( 6272): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6272): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/WifiMonitor(  986): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6272): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6272): P2P: Add operating class 81
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6272): P2P: Add operating class 115
E/WifiMonitor(  986): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6272): P2P: Add operating class 116
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6272): P2P: Add operating class 117
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6272): P2P: Update channel list
D/wpa_supplicant( 6272): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6272): P2P: cli_channels:
D/wpa_supplicant( 6272): p2p0: Updating hw mode
E/WifiMonitor(  986): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  986): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6272): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6272): set wifi ON
E/WifiStateMachine(  986): setWifiState: enabled
E/WifiStateMachine(  986): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  986):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 62,72): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6272): SET_SCREEN_ON:Off
I/wpa_supplicant( 6272): htc_wext_set_keepalive +
I/wpa_supplicant( 6272): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6272): getPrivFuncNum +	
I/wpa_supplicant( 6272): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6272): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6272): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6272): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6272): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6272): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  986): startHal
,I/qcom-bluetooth( 6344): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,E/wifi    (  986): getStaticLongField sWifiHalHandle 0x7f8d1e1300
,I/WifiNative-HAL(  986): Could not start hal
E/WifiStateMachine(  986): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  986): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  986):     Client/Owner: Client
D/WifiDisplayAdapter(  986):     GroupId: 
D/WifiDisplayAdapter(  986):     Passphrase: 
D/WifiDisplayAdapter(  986):     SessionId: 0
D/WifiDisplayAdapter(  986):     IP Address: }
D/WifiStateMachine(  986): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  986): handleScreenStateChanged Exit: false
,I/IntentController( 1240): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WIFI_ICON( 1240): updateWifiState: WIFI_STATE_CHANGED enabled
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/StatusBar.NetworkController( 1240): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER MACADDR'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6272): update_config=1
D/wpa_supplicant( 6272): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  986): Loading config and enabling all networks 
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6272): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6272): wpa_supplicant_ctrl_iface_list_networks: return size = 47
D/HtcWiFiWidget_WiFiWidgetProvider( 6302): onWiFiStateChanged() for widget: 
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
,D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/HtcWiFiWidget_WiFiWidgetProvider( 6302): updateWidget(context) for widget: 
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
,D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
,D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6272): Do not allow key_data field to be exposed
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='group'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
,D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
,D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6272): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6272): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,E/WifiConfigStore(  986): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
,D/wpa_supplicant( 6272): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6272): device_name='m8qlul_htc_europe'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6272): manufacturer='HTC'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6272): model_name='HTC One M8s'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6272): model_number='HTC One M8s'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6272): config_methods='physical_display virtual_push_button'
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,E/WifiStateMachine(  986): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  986): handleMessage: new destination call exit/enter
E/WifiStateMachine(  986): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  986): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  986): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  986): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  986): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  986): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6272): wlan0: Setting scan interval: 15 sec
,W/Settings( 5947): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  986): Setting external_sim to 1
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/WifiP2pService(  986): P2pDisabledState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  986): DefaultState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6272): external_sim=1
,D/WifiStateMachine(  986): Setting OUI to DA-A1-19
I/WifiNative-HAL(  986): startHal
E/wifi    (  986): getStaticLongField sWifiHalHandle 0x7f8d1e1360
I/WifiNative-HAL(  986): Could not start hal
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6272): wlan0: Control interface command 'STA_AUTOCONNECT 0'
,E/WifiStateMachine(  986): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  986): Driverstarted State enter
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
,E/WifiStateMachine(  986): DriverStartedState call setCountryCode()
E/WifiStateMachine(  986): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  986): NetworkAgent == null
,E/WifiStateMachine(  986): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
E/WifiTrafficPoller(  986): ENABLE_TRAFFIC_STATS_POLL false Token 0
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
,W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,D/WifiDataStallTracker(  986): setDhcpActive: false
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6272): wlan0: Control interface command 'STATUS'
I/IntentController( 1240): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiMonitor(  986): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  986): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  986): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  986): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  986): transitionTo: destState=DisconnectedState
E/native  (  986): do suspend false
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
,D/HTCRequest(  986): WifiMonitor:handleSupplicantStateChange(): SSID
D/WIFI_ICON( 1240): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/WifiMonitor(  986): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
,I/bt-btu  ( 6235): btu_task received preload complete event
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6272): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x001f
D/WifiP2pService(  986): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/libc    (  986): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
,D/StatusBar.NetworkController( 1240): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/QuickSettingWifi( 1240): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
E/WifiStateMachine(  986): Driverstarted State enter done
E/WifiStateMachine(  986): moveDeferredMessageAtFrontOfQueue; what=131085
D/libc    (  986): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  986): moveDeferredMessageAtFrontOfQueue; what=131144
,E/WifiStateMachine(  986): handleMessage: new destination call exit/enter
E/WifiStateMachine(  986): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  986): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  986): moveTempStackToStateStack: i=0,j=4
D/WifiP2pService(  986): P2pEnablingState
E/WifiStateMachine(  986): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  986): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  986): invokeEnterMethods: DisconnectedState
D/PMS     (  986): acquireWL(3f79759e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6235 1002 null
E/WifiStateMachine(  986): DisconnectedState call setCountryCode()
E/WifiStateMachine(  986):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiScanningService(  986): SCAN_AVAILABLE : 3
D/RttService(  986): SCAN_AVAILABLE : 3
D/wpa_supplicant( 6272): wlan0: Control interface command 'SET pno 1'
D/RttService(  986): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6272): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6272): wlan0: nl80211: sched_scan request
D/WifiMonitor(  986): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService(  986): DefaultState got{ when=-3ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  986): startHal
,D/bt-btm  ( 6235): btm_acl_device_down
,D/bt-btm  ( 6235): btm_acl_reset_paging
D/bt-btm  ( 6235): btm_acl_set_discing
,D/WifiP2pService(  986): P2pEnablingState{ when=-10ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  986): P2p socket connection successful
D/WifiP2pService(  986): P2pEnabledState
D/WifiP2pService(  986): sending p2p connection changed broadcast
,D/WISPrService( 5600): >>>>>WISPrService start isConnected = false<<<<<
,D/WifiDisplayController(  986): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayAdapter(  986): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  986):     Client/Owner: Client
D/WifiDisplayAdapter(  986):     GroupId: 
D/WifiDisplayAdapter(  986):     Passphrase: 
D/WifiDisplayAdapter(  986):     SessionId: 0
D/WifiDisplayAdapter(  986):     IP Address: }
V/AudioService(  986): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  986):     Client/Owner: Client
V/AudioService(  986):     GroupId: 
V/AudioService(  986):     Passphrase: 
V/AudioService(  986):     SessionId: 0
V/AudioService(  986):     IP Address: }
D/HtcEffectManagerBase(  986): onEventChanged id=5 status=false
D/HtcEffectManager(  986): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  986): convertEffect before=902
D/HtcEffectManager(  986): convertEffect after=902
,D/WifiDisplayController(  986): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayController(  986): mWfdEnabled :false, networkInfo.isConnected() :false
,D/WifiService(  986): New client listening to asynchronous messages
,E/WifiTrafficPoller(  986): ADD_CLIENT: 8
,D/WISPrService( 5600): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/QuickSettingWifi( 1240): receive.wifiConnect:false wifiAPname:null elapse:1
,I/bt-btm  ( 6235): btm_reset_complete,
I/bt-btm  ( 6235): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 6235): Start reading local supported commands
,D/bt-btm  ( 6235): btm_read_local_supported_cmds_complete status (0x00)
,D/bt-btm  ( 6235): BTM reads next extended features page (1)
,D/bt-btm  ( 6235): BTM reads next extended features page (2)
,D/bt-btm  ( 6235): BTM reached last extended features page (2)
,D/bt-btm  ( 6235): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,D/bt-btm  ( 6235): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
,D/bt-btm  ( 6235): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
,I/bt-btm  ( 6235): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 6235): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
,I/bt-btm  ( 6235): btm_vendor_capability_vsc_cmpl_cback: status=0
D/bt-btm  ( 6235): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01,
D/bt-btm  ( 6235): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6235): btm_read_ble_wl_size 
D/bt-btm  ( 6235): btm_read_white_list_size_complete 
D/bt-btm  ( 6235): btm_get_ble_buffer_size 
D/bt-btm  ( 6235): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6235): btm_read_ble_local_supported_states 
,D/bt-btm  ( 6235): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 6235): btm_read_ble_local_supported_features 
D/bt-btm  ( 6235): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 6235): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6235): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6235): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6235): Local supported SCO packet types: 0x038f
,I/bt-btm  ( 6235): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6235): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6235): BTM_SetInquiryMode
I/bt-btm  ( 6235): BTM_SetPageScanType
I/bt-btm  ( 6235): BTM_SetInquiryScanType
,D/bt-btm  ( 6235): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6235): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6235): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6235): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6235): BTM_BleLoadLocalKeys
D/bt-btm  ( 6235): BTM_BleLoadLocalKeys
I/bt-btm  ( 6235): BTM_Sec: application registered
E/bt-btm  ( 6235): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf72a4d5 
,I/bt-btm  ( 6235): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6235): SMP_Register state=0
E/bt-btm  ( 6235): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf72a4d5 
I/bt-btm  ( 6235): BTM_Sec: application registered
D/bt-btm  ( 6235): BTM_SetDefaultLinkSuperTout
,I/bt-btm  ( 6235): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6235): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6235): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6235): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6235): BTM_RegBusyLevelNotif
D/bt-btm  ( 6235): BTM_BleReadControllerFeatures
I/bt-btm  ( 6235): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6235): GATT_Register
D/bt-att  ( 6235): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6235): allocated gatt_if=3
I/bt-att  ( 6235): GATT_StartIf gatt_if=3
D/bt-att  ( 6235): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6235): gatt_find_the_connected_bda found=0 found_idx=16
D/bt-btm  ( 6235): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 6235): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6235): BTM Register For VSEvents is successfully
D/bt-btm  ( 6235): BTM_BleGetVendorCapabilities
I/bt-btif ( 6235): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6235): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6235): bta_dm_set_dev_name: name: HTC One M8s 
E/bt-btif ( 6235): Calling BTA_HhEnable
I/bt-btif ( 6235): BTA_MceEnable
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btm  ( 6235):  BTM_BleConfigPrivacy
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
E/bt-btif ( 6235): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-btif ( 6235): AG evt (hdl 0x0001): State 0, Event 0x0500
I/bt-btif ( 6235): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6235): BTM_AllocateSCN
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
,D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6235): BTM_AllocateSCN
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btm  ( 6235): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6235):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6235):                : sec: 0x1086, service name [] (up to 21 chars saved),
D/bt-btif ( 6235): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6235): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6235):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/BluetoothAdapterProperties( 6235): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 6235): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6235):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6235): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6235): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:5
D/WifiP2pService(  986): DeviceAddress: 92:e7:c4:e6:4c:f8
I/bt-avp  ( 6235): AVRC_AddRecord uuid: 110c
D/WifiDisplayController(  986): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  986):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  986):  primary type: 10-0050F204-5
D/WifiDisplayController(  986):  secondary type: null
D/WifiDisplayController(  986):  wps: 0
D/WifiDisplayController(  986):  grpcapab: 0
D/WifiDisplayController(  986):  devcapab: 0
D/WifiDisplayController(  986):  status: 3
D/WifiDisplayController(  986):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  986):  WFD CtrlPort: 0
D/WifiDisplayController(  986):  WFD MaxThroughput: 0
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6235): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
D/bt-btif ( 6235):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6235): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btm  ( 6235): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6235):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6235):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_,id 6, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6235):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6235): GATT_Register
D/bt-att  ( 6235): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6235): allocated gatt_if=4
I/bt-att  ( 6235): GATT_StartIf gatt_if=4
D/bt-att  ( 6235): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6235): gatt_find_the_connected_bda found=0 found_idx=16
D/wpa_supplicant( 6272): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6272): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6272): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6272): wlan0: nl80211: Sched scan started
D/Tethering(  986): interfaceLinkStateChanged p2p0, false
D/Tethering(  986): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  986): WiFiDisplay: getWifidisplayApEnabled=false
E/wifi    (  986): getStaticLongField sWifiHalHandle 0x7f8af4b520
I/WifiNative-HAL(  986): Could not start hal
E/WifiScanningService(  986): could not start HAL
W/WifiHW  (  986): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
E/WifiStateMachine(  986): handleMessage: X
D/wpa_supplicant( 6272): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6272): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'persistent_reconnect'='1'
E/WifiStateMachine(  986): handleMessage: E msg.what=131144
D/wpa_supplicant( 6272): persistent_reconnect=1
E/WifiStateMachine(  986): processMsg: DisconnectedState
D/wpa_supplicant( 6272): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiP2pService(  986): sending p2p persistent groups changed broadcast
D/wpa_supplicant( 6272): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6272): P2P: Set Operating channel: reg_class 126 channel 149
D/WifiP2pService(  986): InactiveState
E/WifiStateMachine(  986):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131085
E/WifiStateMachine(  986): processMsg: DisconnectedState
E/WifiStateMachine(  986):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  986): processMsg: ConnectModeState
E/WifiStateMachine(  986):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  986): processMsg: DriverStartedState
E/WifiStateMachine(  986):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131154
E/WifiStateMachine(  986): processMsg: DisconnectedState
E/WifiStateMachine(  986):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  986): processMsg: ConnectModeState
E/WifiStateMachine(  986):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  986): processMsg: DriverStartedState
E/WifiStateMachine(  986):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  986): processMsg: SupplicantStartedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  986):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  986): processMsg: DefaultState
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6272): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6272): p2p0: Control interface command 'SET device_name Android_,608e'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6272): device_name='Android_608e'
E/WifiStateMachine(  986):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131323
E/WifiStateMachine(  986): processMsg: DisconnectedState
D/BluetoothAdapterProperties( 6235): Scan Mode:21
D/BluetoothAdapterProperties( 6235): Discoverable Timeout:120
I/bt-btif ( 6235): BTA_JvEnable
I/bt-btif ( 6235): BTA_JvRegisterL2cCback
I/bt-btm  ( 6235): BTM_ReadConnectability
I/bt-btm  ( 6235): BTM_ReadDiscoverability
I/bt-btm  ( 6235): BTM_SetDiscoverability
I/bt-btm  ( 6235): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6235): disc_mode 0002
D/bt-btm  ( 6235): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6235): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6235): BTM_SetConnectability
I/bt-btm  ( 6235): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6235): disc_mode 0002
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6235): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6235): BTM_SetDiscoverability
I/bt-btm  ( 6235): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6235): disc_mode 0000
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6235): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6235): BTM_SetConnectability
I/bt-btm  ( 6235): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6235): disc_mode 0000
D/bt-btm  ( 6235): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6235): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
I/bt-btm  ( 6235): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/WifiStateMachine(  986):  DisconnectedState what:131323 0 0
I/bt-btif ( 6235): bta_pan_co_init
E/WifiStateMachine(  986): processMsg: ConnectModeState
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6235): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6235):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6235):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btm  ( 6235): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6235):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6235): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6235):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
E/WifiStateMachine(  986):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  986): processMsg: DriverStartedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6272): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6272): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6272): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6272): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  986):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  986): processMsg: SupplicantStartedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
E/WifiStateMachine(  986):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  986): processMsg: DefaultState
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6272): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6272): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  986):  DefaultState what:131323 0 0
E/WifiStateMachine(  986): setOperatorSSID enter
W/WifiHW  (  986): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  986): handleMessage: X
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6272): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6272): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6272): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6272): config_methods='virtual_push_button physical_display keypad'
E/WifiStateMachine(  986): handleMessage: E msg.what=131104
E/WifiStateMachine(  986): processMsg: DisconnectedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6272): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6272): [p2p command] (P2P_SET conc_pref sta)
E/WifiStateMachine(  986):  DisconnectedState what:131104 0 0
D/wpa_supplicant( 6272): Single channel concurrency preference: sta
E/WifiStateMachine(  986): processMsg: ConnectModeState
D/WifiNative-HAL(  986): p2pGetDeviceAddress
W/WifiHW  (  986): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = fe bb 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = bf 5d 4d 1e 9c b7 85 38 5f 7b 4a 46 68 ae 89 c0 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:9
D/WifiNative-HAL(  986): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
E/WifiStateMachine(  986):  ConnectModeState what:131104 0 0
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): HAL bt_hal_cbacks->adapter_state_changed_cb
W/Settings(  986): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt-btif ( 6235): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/bt-btif ( 6235): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6235): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6235): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6235): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/wpa_supplicant( 6272): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6272): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6272): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=131162
E/WifiStateMachine(  986): processMsg: DisconnectedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "P2P_FLUSH"
E/WifiStateMachine(  986):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  986): processMsg: ConnectModeState
D/wpa_supplicant( 6272): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6272): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6272): P2P: Stopping find
D/wpa_supplicant( 6272): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6272): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6272): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6272): P2P: Stopping find
D/wpa_supplicant( 6272): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6272): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6272): wpa_driver_set_ap_wps_p2p_ie: Entry
E/WifiStateMachine(  986):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  986): processMsg: DriverStartedState
W/WifiHW  (  986): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6272): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6272): [p2p command] (P2P_SERVICE_FLUSH)
E/WifiStateMachine(  986):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  986): set frequency band 0
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6272): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6272): SETBAND: 0
D/wpa_supplicant( 6272): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6272): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6272): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/BluetoothAdapterState( 6235): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6235): ScanMode =  21
D/BluetoothAdapterProperties( 6235): State =  11
D/BluetoothAdapterProperties( 6235): Setting state to 12
I/BluetoothAdapterState( 6235): Bluetooth adapter state changed: 11-> 12
D/WifiMonitor(  986): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  986): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  986): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  986): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6272): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/WifiStateMachine(  986): Wifi band: 0, ScanBroadCastCounter: 0
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6272): P2P: Add operating class 81
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6272): P2P: Add operating class 115
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6272): P2P: Add operating class 116
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6272): P2P: Add operating class 117
D/wpa_supplicant( 6272): P2P: Channels - hexdump(len=2): 28 30
E/bt_mct  ( 6235): hci lib postload completed
D/wpa_supplicant( 6272): P2P: Update channel list
D/wpa_supplicant( 6272): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6272): P2P: cli_channels:
D/wpa_supplicant( 6272): p2p0: Updating hw mode
D/BluetoothManagerService(  986): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  986): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  986): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  986): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/wpa_supplicant( 6272): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6272): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6272): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6272): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/BluetoothHeadset( 1542): onBluetoothStateChange: up=true
D/wpa_supplicant( 6272): nl80211: Added 802.11b mode based on 802.11g information
I/bt-btif ( 6235): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset(  986): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 6235): Discoverable Timeout:120
D/BluetoothA2dp(  986): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1542): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6235): Entering On State
W/WifiHW  (  986): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/BluetoothHeadset( 1240): onBluetoothStateChange: up=true
D/wpa_supplicant( 6272): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6272): wpa_supplicant_ctrl_iface_list_networks: return size = 34
D/BluetoothHeadset( 1542): onBluetoothStateChange: up=true
W/WifiHW  (  986): QCOM Debug wifi_send_command "SAVE_CONFIG"
E/WifiStateMachine(  986): did set frequency band 0
D/wpa_supplicant( 6272): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6272): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 62 0f 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 6b e9 f0 07 15 83 19 63 84 25 35 72 ab 14 2a 6b 
D/wpa_supplicant( 6272): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6272): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6272): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6272): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6272): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6272): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  986): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6272): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6272): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6272): wlan0: Cancelling sched scan
D/wpa_supplicant( 6272): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6272): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6272): wpa_supplicant_scan enter
D/wpa_supplicant( 6272): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6272): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6272): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6272): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  986): done set frequency band 0
D/BluetoothManagerService(  986): Bluetooth State Change Intent: 11 -> 12
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 23 de 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 3d ea 71 5f fe 72 80 dc d0 5f 13 39 2a 37 d5 1c 
I/IntentController( 1240): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3672): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3672): Bluetooth Adapter: ON
D/BluetoothManagerService(  986): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  986): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  986): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapReceiver( 6235): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6235): ***********state = 12
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
D/PMS     (  986): acquireWL(286a5895): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5600 1000 null
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 68 47 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 53 dd 96 fd e5 97 93 e1 6a b9 23 e2 3b 24 8d f2 
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 89 ea 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = b0 a0 1c ac c9 47 7d 53 5b c0 97 65 0d b0 2e 51 
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 0b c3 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 2c dc 09 28 41 2d 60 23 c7 e6 18 cb 10 f3 11 76 
D/WifiStateMachine(  986): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=147462
E/WifiStateMachine(  986): processMsg: DisconnectedState
E/WifiStateMachine(  986):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129633  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  986): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  986): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  986): processMsg: ConnectModeState
E/WifiStateMachine(  986):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129634  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  986): handleMessage: X
E/WifiStateMachine(  986): handleMessage: E msg.what=143371
E/WifiStateMachine(  986): processMsg: DisconnectedState
E/WifiStateMachine(  986):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  986): processMsg: ConnectModeState
E/WifiStateMachine(  986):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  986): processMsg: DriverStartedState
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 67 dd 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/ContextImpl( 5600): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 5a ee b3 ab 40 90 2d 61 e1 56 35 2a bc 96 3d 7d 
V/BluetoothPbapService( 6235): Pbap Service onCreate
E/WifiStateMachine(  986):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
V/BluetoothPbapService( 6235): Starting PBAP service
E/WifiStateMachine(  986): processMsg: SupplicantStartedState
E/WifiStateMachine(  986):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  986): processMsg: DefaultState
E/WifiStateMachine(  986):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
D/BluetoothAdapter( 6235): 396598328: getState(). Returning 12
E/WifiStateMachine(  986): handleMessage: X
V/BluetoothPbapService( 6235): Handler(): got msg=1
V/BluetoothPbapService( 6235): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6235): Pbap Service initSocket
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 48 54 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 35 55 09 89 e3 90 e3 64 ca 5b ce 5e 10 bc 61 da 
D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6235): getBluetoothService() called with no BluetoothManagerCallback
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = aa 28 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 70 38 6a b1 34 1e 00 0d bc 10 45 b0 ed 59 30 4a 
I/bt-btm  ( 6235): BTM_SetDiscoverability
I/bt-btm  ( 6235): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6235): disc_mode 0000
I/bt-btm  ( 6235): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6235): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6235): BTM_SetConnectability
I/bt-btm  ( 6235): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6235): disc_mode 0000
D/bt-btm  ( 6235): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6235): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6235): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6235): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): BTA_JvRfcommStartServer
I/bt-btm  ( 6235): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6235):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6235): Succeed to create listening socket 
V/BluetoothPbapService( 6235): Accepting socket connection...
I/bt-btif ( 6235): HAL bt_hal_cbacks->adapter_properties_cb
D/PMS     (  986): releaseWL(286a5895): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6274): onBTStateChanged() for widget: 
D/BluetoothAdapterProperties( 6235): Scan Mode:21
D/HtcBtWidget_BTWidgetProvider( 6274): updateWidget(context) for widget: 
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = be ad 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = cd 07 27 6a 96 ec 90 5a f5 d0 30 67 9c 63 e4 77 
D/PMS     (  986): acquireWL(190e0d9b): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5600 1000 null
,W/System.err(  986): java.lang.Throwable: stack dump
W/System.err(  986): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  986): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  986): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  986): 	at android.os.Binder.execTransact(Binder.java:454)
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 6a 23 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_ADAPTER
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 23 d3 d0 45 6f f7 19 08 b2 b7 45 92 be 80 e3 8d 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  986): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14a09a76:true
D/BluetoothAdapter( 1240): 818114704: getState(). Returning 12
D/BluetoothAdapter( 1240): 818114704: getState(). Returning 12
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = c8 60 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 2c 81 5d c7 7e 29 81 3c 47 dd 81 78 73 74 64 0b 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 5600): 1939475: getState(). Returning 12
I/QuickSettingBluetooth( 1240): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1240): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothInputDevice( 5600): BluetoothInputDevice()
D/BluetoothManagerService(  986): registerStateChangeCallback+
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 7
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 46 3c 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = e1 e9 60 32 8e c7 c6 7b ba 12 c3 ba 0b f5 02 97 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
D/BluetoothPan( 5600): BluetoothPan()
D/BluetoothManagerService(  986): registerStateChangeCallback+
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 8
D/BluetoothMap( 5600): Create BluetoothMap proxy object
D/BluetoothManagerService(  986): registerStateChangeCallback+
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 9
D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 79 a6 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 47 f8 a4 89 f1 9e 2d 3d f1 92 4d 36 ea 29 2c 6b 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
E/BluetoothMap( 5600): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  986): registerStateChangeCallback+
D/BluetoothSap( 5600): BluetoothSap() call bindService
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 10
W/ContextImpl( 5600): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
D/BluetoothPbap( 5600): BluetoothPbap()
,D/BluetoothManagerService(  986): registerStateChangeCallback+
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 11
,D/BluetoothManagerService(  986): registerStateChangeCallback+
,D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 12
,D/BluetoothHeadset( 5600): BluetoothHeadset(),
D/BluetoothManagerService(  986): registerStateChangeCallback+
D/BluetoothManagerService(  986): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  986): Registered receivers: 13
,D/LocalBluetoothProfileManager( 5600): LocalBluetoothProfileManager construction complete,
,D/DockEventReceiver( 5600): finishStartingService: stopping service
D/BluetoothA2dp( 5600): Proxy object connected
D/A2dpProfile( 5600): Bluetooth service connected
V/BluetoothPbapService( 6235): Pbap Service onBind
D/BluetoothAdapter( 5600): 1939475: getState(). Returning 12
,D/BluetoothHeadset( 5600): Proxy object connected
,D/HeadsetProfile( 5600): Bluetooth service connected
D/BluetoothAdapter( 5600): 1939475: getState(). Returning 12
,D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothInputDevice( 5600): Proxy object connected
W/BluetoothAdapter( 6235): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6235): BTA_JvCreateRecordByUser
D/HidProfile( 5600): Bluetooth service connected
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): BTA_JvRfcommStartServer
I/bt-btm  ( 6235): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6235):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6235): Accept thread started.
D/BluetoothAdapter( 5600): 1939475: getState(). Returning 12
,D/PMS     (  986): releaseWL(190e0d9b): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothPan( 5600): BluetoothPAN Proxy object connected
D/BluetoothAdapter( 6235): 396598328: getState(). Returning 12
,D/BluetoothFtpService( 6235): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 6235): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6235):  call MAP start service
,D/PanProfile( 5600): Bluetooth service connected
D/BluetoothPbap( 5600): Proxy object connected
,D/PbapServerProfile( 5600): Bluetooth service connected
D/BluetoothFtpService( 6235): htc sense version is 6.0
,D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6235): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6235): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:12
,I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): BTA_JvRfcommStartServer
I/bt-btm  ( 6235): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6235):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6235): Run Accept thread
E/BluetoothMasService( 6235): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 6235): Add permission for SmsProvider.
,V/BluetoothMasService( 6235): Starting MAS instances
,D/BluetoothAdapter( 6235): 396598328: getState(). Returning 12
,I/MailMessageReceiver( 6235): reg:com.android.bluetooth.btservice.AdapterApp@f80e449 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@38e5a14e
,I/MailManager( 6235): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@38e5a14e
,V/EmailUtils( 6235): Manager Instance is not NULL
,I/ActivityManager(  986): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6364 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/art     (  986): Explicit concurrent mark sweep GC freed 26672(1372KB) AllocSpace objects, 2(316KB) LOS objects, 33% free, 16MB/24MB, paused 1.655ms total 148.591ms
,D/HtcAdjCursorFactory( 6364): Set CursorWindow size to: 4194304 KB, Tid: 6383
,D/wpa_supplicant( 6272): EAPOL: disable timer tick
,D/EmailUtils( 6235): ============NULL aList========
V/EmailUtils( 6235): <-getEmailAccountIdList
V/BluetoothMasService( 6235): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 6235): 396598328: getState(). Returning 12
,V/BluetoothMasService( 6235): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 6235): Manager Instance is not NULL
,D/EmailUtils( 6235): ============NULL aList========
,V/EmailUtils( 6235): <-getEmailAccountIdList
V/BluetoothSapReceiver( 6235): SapReceiver onReceive 
V/BluetoothSapReceiver( 6235): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6235):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6235): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothMasService( 6235): handleMessage: mIsEmailEnabledtrue
D/AuthorizationBluetoothService( 1933): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BtMns   ( 6235): BluetoothMns: isEmailEnabled: true
,D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6235): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6235): BTA_JvCreateRecordByUser
D/bt-btm  ( 6235): BTM_AllocateSCN,
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): BTA_JvRfcommStartServer
I/bt-btm  ( 6235): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6235):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6235): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6235): BTA_JvCreateRecordByUser
D/bt-btm  ( 6235): BTM_AllocateSCN
D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): BTA_JvRfcommStartServer
,I/bt-btm  ( 6235): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6235):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
I/ActivityManager(  986): Killing 4389:com.google.android.gms/u0a24 (adj 15): empty #17
D/Process (  986): killProcessQuiet, pid=4389
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,I/ActivityManager(  986): Recipient 4389,
,V/BluetoothSapService( 6235): Sap Service onCreate
V/BluetoothSapService( 6235): initBinder
V/BluetoothSapService( 6235): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@6ea7c05
V/BluetoothSapService( 6235): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@3dcdf68b
V/BluetoothSapService( 6235): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6235): state: 12
D/SapServerProfile( 5600): Bluetooth service connected
V/BluetoothSapService( 6235): Starting SAP server process
,D/A2dpService( 6235): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@2d9bd381
,D/A2dpSinkService( 6235): getA2dpSinkService(): service is NULL
V/BluetoothSapService( 6235): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6235): Sap Service initRfcommSocket
D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6235): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6235): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6235): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6235): Write Extended Inquiry Response to controller
I/bt-btif ( 6235): BTA_JvRfcommStartServer
I/bt-btm  ( 6235): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6235):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6235): Succeed to create listening socket 
,V/BluetoothSapService( 6235): Accepting socket connection...
,D/wpa_supplicant( 6272): EAPOL: disable timer tick
,D/BluetoothManagerService(  986): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/jxcore-log( 6180): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6180): 
I/jxcore-log( 6180): my name is : HTC-HTC One M8s_PT3233
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): attempting to connect to test coordinator,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): check test folder
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): found test : ./testFindPeers.js,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): found test : ./testReConnect.js,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): found test : ./testSendData.js,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): Test app app.js loaded,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/chromium( 6180): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/PMS     (  986): releaseWL(3f79759e): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/BluetoothAdapter( 6180): 459638453: getState(). Returning 12
I/jxcore-log( 6180): BLE supported!!
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  986): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  986): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/libc    (  986): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  986): acquireWL(352a8029): PARTIAL_WAKE_LOCK  *alarm* 0x1 986 1000 WorkSource{1000}
D/libc    (  986): [NET] android_getaddrinfofornet-, err=8
V/AlarmManager(  986): sending alarm PendingIntent{2d14f537: PendingIntentRecord{342d5aa4 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146761, Int=0
D/libc    (  986): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=150691, Int=0
D/libc    (  986): [NET] android_getaddrinfofornet-, pass to proxy
V/AlarmManager(  986): sending alarm PendingIntent{1edb3fae: PendingIntentRecord{1f55514f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143863, Int=0
D/libc    (  986): [NET] android_getaddrinfo_proxy+
V/AlarmManager(  986): sending alarm PendingIntent{833e0dc: PendingIntentRecord{2ed9db4a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=161671, Int=0
D/libc    (  986): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    (  986): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  986): acquireWL(12c1f5e5): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1933 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1933): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1933): [NET] android_getaddrinfo_proxy+
D/libc    ( 1933): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/PMS     (  986): releaseWL(352a8029): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1933): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  986): releaseWL(12c1f5e5): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1240): Weather sync is On,
I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): ,
W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
,W/ContextImpl(  986): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6180): ,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(299fa8ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null,
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(299fa8ba): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  986): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  986): plugged=true pluggin=true
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/PowerUI ( 1240): closing low battery warning: level=100
,I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  986): >> updateStatus
D/UsbnetService(  986): BroadcastReceiver::onReceive-
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/TelephonyReceiver( 1542): switchBindHtcMsgCursor: null,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/HtcUPManager( 1240): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1515): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@ae867e3
,D/Process (  986): killProcessQuiet, pid=5899
I/ActivityManager(  986): Killing 5899:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/HtcUPManager( 1240): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
,I/ActivityManager(  986): Recipient 5899
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(183fb36b): PARTIAL_WAKE_LOCK  *alarm* 0x1 986 1000 WorkSource{1000}
V/AlarmManager(  986): sending alarm PendingIntent{2b8c2ec8: PendingIntentRecord{37a10b61 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=207488, Int=0
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=210690, Int=0
V/AlarmManager(  986): sending alarm PendingIntent{2d14f537: PendingIntentRecord{342d5aa4 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=221679, Int=0
,V/AlarmManager(  986): sending alarm PendingIntent{2f0f9686: PendingIntentRecord{3b241b47 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=187013, Int=0
,D/libc    (  986): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  986): [NET] android_getaddrinfofornet-, err=8
D/libc    (  986): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  986): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  986): [NET] android_getaddrinfo_proxy+
D/libc    (  986): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    (  986): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  986): acquireWL(e996f74): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1933 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  986): releaseWL(e996f74): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1240): Weather sync is On
W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
D/PMS     (  986): releaseWL(183fb36b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(1f01fc9d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  986): releaseWL(1f01fc9d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/WifiController(  986): battery changed pluggedType: 2
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PowerUI ( 1240): closing low battery warning: level=100
D/WifiController(  986): handleMessage: E msg.what=155652
,D/PMS     (  986): runPSCheck
D/WifiController(  986): processMsg: DeviceActiveState
D/HtcPowerSaver(  986): Checking...
D/WifiController(  986): processMsg: StaEnabledState
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): processMsg: DefaultState
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): handleMessage: X
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(d3e9512): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 986 1000 WorkSource{1000}
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=270691, Int=0
V/AlarmManager(  986): sending alarm PendingIntent{12fd24e3: PendingIntentRecord{2ed9db4a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=294117, Int=0
D/PMS     (  986): acquireWL(386c599): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1933 10024 WorkSource{10024 com.google.android.gms}
V/AlarmManager(  986): sending alarm PendingIntent{3decf05e: PendingIntentRecord{15d32c3f com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448443452308, Int=0
,D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1933): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,D/libc    ( 1933): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1933): [NET] android_getaddrinfo_proxy+
D/libc    ( 1933): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1933): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  986): releaseWL(386c599): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1240): Weather sync is On
W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data,
D/PMS     (  986): releaseWL(d3e9512): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(1a1f390c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null,
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(1a1f390c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/NotificationService(  986): plugged=true pluggin=true,
,D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PMS     (  986): runPSCheck
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): handleMessage: E msg.what=155652
,D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: DeviceActiveState
D/PowerUI ( 1240): closing low battery warning: level=100
D/WifiController(  986): processMsg: StaEnabledState
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): processMsg: DefaultState
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  986): handleMessage: X
I/HtcPowerSaver(  986): << updateStatus
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3,
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1933): Explicit concurrent mark sweep GC freed 15971(891KB) AllocSpace objects, 0(0B) LOS objects, 49% free, 4MB/8MB, paused 1.080ms total 71.570ms
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1240): reapply : com.google.android.gms 4 40
W/GLSActivity( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1933): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1933): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1933): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5624): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889),
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5624): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5624): Ignoring header User-Agent because its value was null.,
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5624): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5624): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5624): [NET] android_getaddrinfo_proxy+
D/libc    ( 5624): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5624): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): ,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  986): acquireWL(3ce42d0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  986): n_update end
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  986): releaseWL(3ce42d0e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PowerUI ( 1240): closing low battery warning: level=100
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  986): Checking...
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): handleMessage: E msg.what=155652
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): ,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,W/Atfwd_Sendcmd(  468): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  986): acquireWL(19b5a32f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
,I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(19b5a32f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1240): closing low battery warning: level=100
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): BroadcastReceiver::onReceive+
,D/WifiController(  986): battery changed pluggedType: 2
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PMS     (  986): runPSCheck
D/WifiController(  986): handleMessage: E msg.what=155652
D/HtcPowerSaver(  986): Checking...
D/WifiController(  986): processMsg: DeviceActiveState
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
,D/WifiController(  986): handleMessage: X
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(2f68fd3c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
,D/PMS     (  986): releaseWL(2f68fd3c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PowerUI ( 1240): closing low battery warning: level=100
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  986): battery changed pluggedType: 2
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PMS     (  986): runPSCheck
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): handleMessage: E msg.what=155652
D/HtcPowerSaver(  986): Checking...
D/WifiController(  986): processMsg: DeviceActiveState
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  986): acquireWL(5444ac5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 986 1000 WorkSource{1000},
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=390690, Int=0
V/AlarmManager(  986): sending alarm PendingIntent{263a0c1a: PendingIntentRecord{2ed9db4a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=607828, Int=0
D/PMS     (  986): acquireWL(2c83434b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1933 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1933): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1933): [NET] android_getaddrinfo_proxy+
D/libc    ( 1933): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1933): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  986): releaseWL(2c83434b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  986): releaseWL(5444ac5): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1240): Weather sync is On
W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/ContactMessageStore( 1542): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1542): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1542): sku_id=118,
D/ContactMessageStore( 1542): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1542): start background delete task...,
,D/ContactMessageStore( 1542): size: 0 , 0
,D/ContactMessageStore( 1542): Background delete complete
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): ,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1933): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1933): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1933): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5624): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5624): 	at android.os.Binder.execTransact(Binder.java:454)
I/RemoteViews( 1240): reapply : com.google.android.gms 3 40
W/System  ( 5624): Ignoring header User-Agent because its value was null.
,D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5624): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5624): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5624): [NET] android_getaddrinfo_proxy+
D/libc    ( 5624): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5624): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(25a66f35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
,I/BatteryService(  986): n_update end
,D/PMS     (  986): releaseWL(25a66f35): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1240): closing low battery warning: level=100
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/NotificationService(  986): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  986): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  986): >> updateStatus
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(35bdafca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
D/UsbnetService(  986): BroadcastReceiver::onReceive+
I/BatteryService(  986): n_update end
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PMS     (  986): releaseWL(35bdafca): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  986): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1240): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  986): updateBatteryInfo
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  986): Checking...
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(2d8f953b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
,D/PMS     (  986): releaseWL(2d8f953b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  986): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1240): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  986): plugged=true pluggin=true
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/PMS     (  986): runPSCheck
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  986): >> updateStatus
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
D/WifiController(  986): battery changed pluggedType: 2
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(c3cb458): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 986 1000 WorkSource{1000},
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=630690, Int=0
V/AlarmManager(  986): sending alarm PendingIntent{25ae996a: PendingIntentRecord{1011ce5b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806767, Int=0
,V/AlarmManager(  986): sending alarm PendingIntent{2ceefe96: PendingIntentRecord{7973b com.android.vending startService}}, i=null, t=0, cnt=1, w=1448443766342, Int=0
,D/Finsky  ( 5624): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  986): sending alarm PendingIntent{31584a17: PendingIntentRecord{df4be04 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448443948357, Int=1800000
,I/ActivityManager(  986): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6409 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  986): sending alarm PendingIntent{e146e22: PendingIntentRecord{88d70b3 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448443977709, Int=0
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  986): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=6426 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  986): sending alarm PendingIntent{20e4650f: PendingIntentRecord{10a3c99c com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
V/AlarmManager(  986): sending alarm PendingIntent{7d28fa5: PendingIntentRecord{2865e39f com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448444071671, Int=0
,I/ActivityManager(  986): Start proc com.google.android.gms for broadcast com.google.android.gms/.checkin.EventLogService$Receiver: pid=6443 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,D/WeatherUtility( 1240): Weather sync is On,
W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
,W/ResourcesManager( 6443): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6443): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 6443): VM with version 2.1.0 has multidex support,
I/MultiDex( 6443): install,
I/MultiDex( 6443): VM has multidex support, MultiDex support library is disabled.
,W/Finsky  ( 5624): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ImageRamCache( 6426): create image Cache, size: 31457280.
,I/ImageRamCache( 6426): [resize] ImageRamCache resized to: 30Mb.
I/ImageRamCache( 6426): create image Cache, size: 31457280.
,I/FeedSettings( 6426): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 6426): GroupBudget 0.500000 0.380000
I/FeedSettings( 6426): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 6426): changeLocale(): en_GB
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/Prism.AllAppsOptionsMa_( 6426): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 6426): loadGridSize() with Alternative
V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/cutils-trace( 6480): Error opening trace file: Permission denied (13)
I/dex2oat ( 6480): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6480): dex2oat: override thread count:4
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 6426): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4
D/libc    ( 6426): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6426): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
,D/libc    ( 6426): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6426): [NET] android_getaddrinfo_proxy+
D/libc    ( 6426): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6426): [NET] android_getaddrinfo_proxy-, NODATA
,E/[CSBICLIENT][v12][BiLogUploadService]( 6426): Exception on getConfig()
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6443): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,W/Finsky  ( 5624): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ActivityThread( 6443): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6443): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18652661: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6443): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  986): acquireWL(230e5239): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 6443 10024 WorkSource{10024 com.google.android.gms},
,W/ContextImpl( 6080): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,D/PMS     (  986): releaseWL(c3cb458): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/GCM     ( 1933): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/PowerUsageList:PowerUsageHelper( 6080): MY_DEBUG = false,
D/PMS     (  986): acquireWL(1a5b262c): PARTIAL_WAKE_LOCK  Event Log Service 0x1 6443 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  986): releaseWL(230e5239): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageService( 6080): repeat time = 1448444972200
,D/AuthorizationBluetoothService( 1933): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 6443): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  986): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6501 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a,
,I/PackageManager(  986):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6443, uid=10024, userID:0,
,W/ResourcesManager( 6501): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6501): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PowerUsageList:PowerUsageHelper( 6080): PowerProfile::POWER_SCREEN_FULL = 154.8,
,I/MultiDex( 6501): VM with version 2.1.0 has multidex support
,I/MultiDex( 6501): install
I/MultiDex( 6501): VM has multidex support, MultiDex support library is disabled.
D/PowerUsageList:BatterySipperExt( 6080): gen(), null == sipper.uidObj, userId = 0
D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 94
D/AccFlag ( 1542): sku_id=118
,D/PowerUsageList:BatterySipperExt( 6080): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6080): gen(), null == sipper.uidObj, userId = 0
,V/JNIHelp ( 6501): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/PowerUsageService( 6080): calcPower(), no data,
,W/ActivityThread( 6501): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6501): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dcdf68b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6501): Installed default security provider GmsCore_OpenSSL
,I/art     (  986): Explicit concurrent mark sweep GC freed 21167(1045KB) AllocSpace objects, 5(780KB) LOS objects, 33% free, 16MB/24MB, paused 1.974ms total 165.968ms
,D/LocationInitializer( 6443): Restart initialization of location
,D/GCM     ( 1933): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,D/AuthorizationBluetoothService( 1933): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.,
,V/GmsCoreStatsServiceLauncher( 6443): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/EventLogService( 6443): Aggregate from 1448442148164 (log), 1448442148164 (data),
D/WearableService( 6501): callingUid 10024, callindPid: 6501
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 91
,D/AccFlag ( 1542): sku_id=118
,I/PackageManager(  986):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=6443, uid=10024, userID:0
,E/MDM     ( 1832): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1832): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/LocationInitializer( 6443): Restart initialization of location,
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 94,
D/AccFlag ( 1542): sku_id=118
,D/TelephUtils( 1542): QUERY for  <hidden uri>  [ com.google.android.gms ] tid: 92,
D/AccFlag ( 1542): sku_id=118
,I/dex2oat ( 6480): dex2oat took 811.694ms (threads: 4),
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
,I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6409): ApplicationMonitor {c1338bb}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6409): PnsModel {3e43b14a}: update(): Update registration caused by: alarm
,D/PMS     (  986): releaseWL(1a5b262c): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,I/PushClient( 6409): PnsConfigModel {2f6c7d69}: <init>(): Use dm-client for provisioning.
,W/System.err( 6409): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6409): SLF4J: Defaulting to no-operation (NOP) logger implementation,
W/System.err( 6409): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6409): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 ,
,I/ActivityManager(  986): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6537 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5624): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5624): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5624): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U],
,D/Finsky  ( 5624): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2),
,D/DeviceConnectionService( 1832): client connected with version: 7571000,
,D/Process (  986): killProcessQuiet, pid=5694,
I/ActivityManager(  986): Killing 5694:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  986): Recipient 5694
,I/DeviceManagement( 6537): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6537 dbg=false s=true
,I/DeviceManagement( 6537): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6537): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6537): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6537): WorkflowService: Starting workflow service
,I/DeviceManagement( 6537): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3e43b14a] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6537): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6537): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6537): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6537): SessionStateController: Checking invariants...,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/DeviceManagement( 6537): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6537): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6537): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6537): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3e43b14a],
,I/DeviceManagement( 6537): WorkflowService: Stopping workflow service,
,D/Process (  986): killProcessQuiet, pid=5550
I/ActivityManager(  986): Killing 5550:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6409): PnsModel {3e43b14a}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  986): Recipient 5550,
,D/Process (  986): killProcessQuiet, pid=5813,
I/ActivityManager(  986): Killing 5813:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  986): Recipient 5813,
,W/SQLiteConnectionPool( 6426): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,D/Process (  986): killProcessQuiet, pid=5975,
I/ActivityManager(  986): Killing 5975:com.htc.sense.mms/u0a64 (adj 15): empty #17
,D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  986): Recipient 5975
,D/Process (  986): killProcessQuiet, pid=6028
I/ActivityManager(  986): Killing 6028:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  986): Recipient 6028
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
I/RemoteViews( 1240): reapply : com.google.android.gms 2 40
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/GLSActivity( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1933): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1933): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1933): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5624): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 5624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5624): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5624): Ignoring header User-Agent because its value was null.
,D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5624): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5624): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5624): [NET] android_getaddrinfo_proxy+
D/libc    ( 5624): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5624): [NET] android_getaddrinfo_proxy-, NODATA
,E/SQLiteLog( 1933): (283) recovered 34 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(166c39c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 986 1000 WorkSource{10072}
V/AlarmManager(  986): sending alarm PendingIntent{31f39566: PendingIntentRecord{3ac0c1cd com.android.vending startService}}, i=null, t=0, cnt=1, w=1448444087040, Int=0
,D/PMS     (  986): releaseWL(166c39c1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5624): [582] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5624): [1] 5.onFinished: Installation state replication succeeded.,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(2f1fe0a7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 986 1000 WorkSource{1000}
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=990691, Int=0,
V/AlarmManager(  986): sending alarm PendingIntent{2f2fb954: PendingIntentRecord{cc1b0fd com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448444123392, Int=0
,D/SmartSyncUtils( 6080): isEpsOn(), nState = 0
,D/PMS     (  986): acquireWL(1313a1f2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6080 1000 null
D/PMS     (  986): releaseWL(2f1fe0a7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1240): Weather sync is On
,W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6080): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6080): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 6080): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 6080): SettingOnTime = 1448517600000, randomSettingOnTime = 1448514474000
D/SmartSyncScreenOnOffTimeReceiver( 6080): SettingOffTime = 1448496000000, randomSettingOffTime = 1448498689000
,D/SmartSyncScreenOnOffTimeReceiver( 6080): bDayMode = false,
D/SmartSyncScreenOnOffTimeReceiver( 6080): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6080): bNightModeTurnOffOnce = false
,D/PMS     (  986): releaseWL(1313a1f2): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(ddfe043): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null,
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(ddfe043): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/WifiController(  986): battery changed pluggedType: 2
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PMS     (  986): runPSCheck
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1240): closing low battery warning: level=100,
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(157916c0): PARTIAL_WAKE_LOCK  *alarm* 0x1 986 1000 WorkSource{1002}
I/bt-btm  ( 6235): Received oneshot timer event complete
V/AlarmManager(  986): sending alarm PendingIntent{21fd5ff9: PendingIntentRecord{1fb5eb3e com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1029483, Int=0
I/bt-btm  ( 6235): btm_ble_timeout
D/PMS     (  986): releaseWL(157916c0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
,D/PMS     (  986): acquireWL(1e163d9f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6235 1002 null,
,D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = 37 75 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 7c b6 c2 ff 74 95 6b 6b b2 0a 19 82 70 be ec 59 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  986): releaseWL(1e163d9f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(1e38deec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null,
I/BatteryService(  986): n_update end
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/PMS     (  986): releaseWL(1e38deec): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  986): onReceive BATTERY_CHANGED
,D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): handleMessage: E msg.what=155652
D/PowerUI ( 1240): closing low battery warning: level=100
D/WifiController(  986): processMsg: DeviceActiveState
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): processMsg: StaEnabledState
D/HtcPowerSaver(  986): updateBatteryInfo
D/WifiController(  986): processMsg: DefaultState
D/PMS     (  986): runPSCheck
,D/WifiController(  986): handleMessage: X
D/HtcPowerSaver(  986): Checking...
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  986): >> updateStatus
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(8ab02b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
D/UsbnetService(  986): BroadcastReceiver::onReceive+
I/BatteryService(  986): n_update end
D/UsbnetService(  986): onReceive BATTERY_CHANGED
,D/PMS     (  986): releaseWL(8ab02b5): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/NotificationService(  986): plugged=true pluggin=true
D/PMS     (  986): runPSCheck
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  986): Checking...
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  986): >> updateStatus
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1240): closing low battery warning: level=100
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): handleMessage: E msg.what=155652
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  986): processMsg: DeviceActiveState
,I/HtcPowerSaver(  986): << updateStatus
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  986): acquireWL(18a17d4a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 986 1000 WorkSource{1000}
,V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1050691, Int=0
V/AlarmManager(  986): sending alarm PendingIntent{222b14bb: PendingIntentRecord{2ed9db4a com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1137453, Int=0
D/PMS     (  986): acquireWL(304afdd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1933 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1933): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1933): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1933): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1933): [NET] android_getaddrinfo_proxy+
D/libc    ( 1933): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1933): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  986): releaseWL(304afdd8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1240): Weather sync is On
,D/PMS     (  986): releaseWL(18a17d4a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(16561531): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
,I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(16561531): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  986): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  986): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  986): >> updateStatus
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  986): battery changed pluggedType: 2
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
,D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1240): closing low battery warning: level=100
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/UsageStatsService(  986): User[0] Flushing usage stats to disk,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(12022416): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(12022416): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PowerUI ( 1240): closing low battery warning: level=100
D/WifiController(  986): handleMessage: E msg.what=155652
,D/HtcPowerSaver(  986): Checking...
D/WifiController(  986): processMsg: DeviceActiveState
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): processMsg: StaEnabledState
,D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
,D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1933): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1933): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1933): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5624): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5624): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1240): reapply : com.google.android.gms 2 40,
,W/System  ( 5624): Ignoring header User-Agent because its value was null.
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5624): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5624): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5624): [NET] android_getaddrinfo_proxy+
D/libc    ( 5624): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5624): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(2ae58d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(2ae58d08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  986): updateBatteryInfo
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1240): closing low battery warning: level=100
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/PMS     (  986): runPSCheck
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): handleMessage: E msg.what=155652
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): battery changed pluggedType: 2
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  986): processMsg: StaEnabledState
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(10e5aca1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(10e5aca1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  986): updateBatteryInfo
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  986): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1240): closing low battery warning: level=100
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  986): runPSCheck
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  986): >> updateStatus
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/WifiController(  986): battery changed pluggedType: 2
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1933): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1933): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1933): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5624): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5624): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5624): Ignoring header User-Agent because its value was null.
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
I/RemoteViews( 1240): reapply : com.google.android.gms 3 40
D/libc    ( 5624): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5624): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5624): [NET] android_getaddrinfo_proxy+
D/libc    ( 5624): [NET] android_getaddrinfo_proxy get netid:0
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5624): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(3c198c9b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
,D/PMS     (  986): releaseWL(3c198c9b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1240): closing low battery warning: level=100
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  986): runPSCheck
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  986): Checking...
D/WifiController(  986): handleMessage: E msg.what=155652
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): battery changed pluggedType: 2
D/WifiController(  986): processMsg: StaEnabledState
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  986): acquireWL(3a9a4838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  986): n_update end
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  986): releaseWL(3a9a4838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/PowerUI ( 1240): closing low battery warning: level=100
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/WifiController(  986): battery changed pluggedType: 2
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): updateBatteryInfo
D/UsbnetService(  986): BroadcastReceiver::onReceive-
D/PMS     (  986): runPSCheck
D/WifiController(  986): handleMessage: E msg.what=155652
D/HtcPowerSaver(  986): Checking...
D/WifiController(  986): processMsg: DeviceActiveState
I/HtcPowerSaver(  986): >> updateStatus
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
,I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  986): << updateStatus
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(10056576): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 986 1000 null
I/BatteryService(  986): n_update end
D/PMS     (  986): releaseWL(10056576): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  986): updateBatteryInfo
,D/UsbnetService(  986): BroadcastReceiver::onReceive+
D/NotificationService(  986): plugged=true pluggin=true
D/UsbnetService(  986): onReceive BATTERY_CHANGED
D/PMS     (  986): runPSCheck
D/UsbnetService(  986):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  986): Checking...
D/UsbnetService(  986): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  986): >> updateStatus
D/HeadsetStateMachine( 6235): Disconnected process message: 10, size: 0
D/WifiController(  986): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  986): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  986): << updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  986): handleMessage: E msg.what=155652
D/WifiController(  986): processMsg: DeviceActiveState
D/WifiController(  986): processMsg: StaEnabledState
D/WifiController(  986): processMsg: DefaultState
D/WifiController(  986): handleMessage: X
I/IntentController( 1240): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1240): closing low battery warning: level=100,
,D/PowerUI ( 1240): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1240): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/ProcessStatsService(  986): Prepared write state in 24ms,
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1933): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1933): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1933): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1933): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1933): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1933): Explicit concurrent mark sweep GC freed 28036(1616KB) AllocSpace objects, 11(924KB) LOS objects, 49% free, 4MB/8MB, paused 1.162ms total 58.462ms,
,W/GLSActivity( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1933): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1933): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1933): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1933): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5624): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5624): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5624): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5624): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/System  ( 5624): Ignoring header User-Agent because its value was null.
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix,
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5624): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5624): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5624): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5624): [NET] android_getaddrinfo_proxy+
I/RemoteViews( 1240): reapply : com.google.android.gms 4 40
D/libc    ( 5624): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  400): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  400): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  400): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  400): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5624): [NET] android_getaddrinfo_proxy-, NODATA
,I/ProcessStatsService(  986): Pruning old procstats: /data/system/procstats/state-2015-11-24-13-57-38.bin,
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
,D/PMS     (  986): acquireWL(204c2f68): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 986 1000 WorkSource{1000}
V/AlarmManager(  986): sending alarm PendingIntent{21a237ff: PendingIntentRecord{d5bb9cc android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1170690, Int=0
,I/bt-btm  ( 6235): Received oneshot timer event complete
,V/AlarmManager(  986): sending alarm PendingIntent{9520f81: PendingIntentRecord{37701826 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1929496, Int=0
I/bt-btm  ( 6235): btm_ble_timeout
I/ActivityManager(  986): Killing 6302:com.htc.widget.hmsproc2/u0a40 (adj 13): empty for 1800s
I/bt-btm  ( 6235): btm_gen_resolvable_private_addr
D/PMS     (  986): acquireWL(157a0c67): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6235 1002 null
D/Process (  986): killProcessQuiet, pid=6302
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/bt-btm  ( 6235): btm_ble_rand_enc_complete
I/bt-btm  ( 6235): btm_gen_resolve_paddr_low
D/bt-smp  ( 6235): smp_encrypt_data
W/bt-smp  ( 6235): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6235): Plain text(LSB ~ MSB) = a3 77 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6235): Encrypted text(LSB ~ MSB) = 19 92 8a 5d a1 a9 7c e6 56 2d 28 4e 82 cf 2a 4c 
I/bt-btm  ( 6235): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6235): Stopping oneshot timer
D/bt-btm  ( 6235): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  986): Recipient 6302
,D/Process (  986): killProcessQuiet, pid=6135
I/ActivityManager(  986): Killing 6135:com.htc.calendar/u0a10 (adj 13): empty for 1814s
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 ,
,I/ActivityManager(  986): Recipient 6135
,D/Process (  986): killProcessQuiet, pid=6111
I/ActivityManager(  986): Killing 6111:com.htc.mobiledata/u0a46 (adj 15): empty for 1815s
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  986): Recipient 6111
,D/Process (  986): killProcessQuiet, pid=6050
I/ActivityManager(  986): Killing 6050:com.htc.bgp/u0a11 (adj 15): empty for 1815s
,D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  986): Recipient 6050
,D/Process (  986): killProcessQuiet, pid=6364
I/ActivityManager(  986): Killing 6364:com.htc.android.mail:sync/u0a62 (adj 13): empty for 1800s
,D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  986): Recipient 6364
,D/Process (  986): killProcessQuiet, pid=6274
I/ActivityManager(  986): Killing 6274:com.htc.widget.hmsproc3/u0a34 (adj 13): empty for 1800s
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  986): Recipient 6274
,D/Process (  986): killProcessQuiet, pid=5600
I/ActivityManager(  986): Killing 5600:com.android.settings/1000 (adj 13): empty for 1800s
,D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  986): Recipient 5600
D/WifiService(  986): Client connection lost with reason: 4
,D/PMS     (  986): releaseWL(157a0c67): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,V/BluetoothSapService( 6235): onUnbind
,D/WeatherUtility( 1240): Weather sync is On
W/WeatherTimeKeeper( 1240): [refreshWeatherData] no weather data
,D/PMS     (  986): releaseWL(204c2f68): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6180): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 6582): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6582): ====startRecUseTime====
D/htc.customization.log.level( 6582):  is 
W/CustomizationLogLevel( 6582): Level value is invalid, use default level 2
I/jxcore-log( 6180): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6180): 
D/CustomizationManager( 6582):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6582): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6582): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6582): Parsing tag category name = system
I/CustomizationCIDLoader( 6582): Parsing tag category name = application
I/CustomizationCIDLoader( 6582): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6582): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6582): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6582): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6582): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6582): add string-array item, value = 42507
I/CustomizationCIDLoader( 6582): add string-array item, value = 21902
I/CustomizationCIDLoader( 6582): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6582): add string-array item, value = 23420
I/CustomizationCIDLoader( 6582): add string-array item, value = 22299
I/CustomizationCIDLoader( 6582): add string-array item, value = 24002
I/CustomizationCIDLoader( 6582): add string-array item, value = 23210
I/CustomizationCIDLoader( 6582): add string-array item, value = 23205
I/CustomizationCIDLoader( 6582): add string-array item, value = 23806
I/CustomizationCIDLoader( 6582): add string-array item, value = 23430
I/CustomizationCIDLoader( 6582): add string-array item, value = 23408
I/CustomizationCIDLoader( 6582): add string-array item, value = 27205
I/CustomizationCIDLoader( 6582): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6582): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6582):  Read CID file spent 0.096 (s)
D/CustomizationManager( 6582):  All configurations done spent 0.096 (s)
D/PackageManager(  986): deletePackageAsUser: pkg=com.test.thalitest, pid=6582, uid=2000 userid=0
I/ActivityManager(  986): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  986): killProcessQuiet, pid=6180
I/ActivityManager(  986): Killing 6180:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  986): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  986): Skipping PackageSetting{2396e5a1 com.example.hello/10373} due to missing metadata
I/ActivityManager(  986): Recipient 6180
E/InputEventReceiver( 1383): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{2ddd978e uid 10366 pid 6180} (c)'
I/WindowState(  986): WIN DEATH: Window{3c522942 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  986): Client connection lost with reason: 4
I/ActivityManager(  986):   Force finishing activity ActivityRecord{c32a973 u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  986): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  986):   Force finishing activity ActivityRecord{c32a973 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  986): Duplicate finish request for ActivityRecord{c32a973 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  986): Spurious death for ProcessRecord{1368da14 6180:com.test.thalitest/u0a366}, curProc for 6180: null
D/DotMatrix( 1327): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1327): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  986): acquireWL(5b590b2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1832 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1832): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  986): Cannot find grip_rejection_width, use default value instead
D/PMS     (  986): releaseWL(5b590b2): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1711): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
I/InputMethodManagerService(  986): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/Prism.ItemManager( 6426): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 6426): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1711): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1678): Cleaning up data for package: com.test.thalitest
W/ResourcesManager(  986): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/PhoneApp( 1542): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1515): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/art     ( 1591): Explicit concurrent mark sweep GC freed 6732(379KB) AllocSpace objects, 9(644KB) LOS objects, 34% free, 29MB/45MB, paused 1.035ms total 110.202ms
D/Prism.PackageStateRece_( 1591): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1591): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1591): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1515): handle notify Blinkfeed plugin client changed
I/Launcher( 1591): Deferring update until onResume
D/Launcher( 1591): waitUntilResume // bindAppsRemoved
I/ActivityManager(  986): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6604 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/AccTypeManager( 1711): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 1711): Unsupported attribute readOnly
I/art     (  986): Explicit concurrent mark sweep GC freed 36789(2MB) AllocSpace objects, 13(728KB) LOS objects, 33% free, 16MB/25MB, paused 1.437ms total 211.195ms
I/art     (  986): WaitForGcToComplete blocked for 190.083ms for cause Explicit
W/PackageManager(  986): Unable to load service info ResolveInfo{abe1c2 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  986): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  986): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  986): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  986): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  986): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  986): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  986): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  986): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  986): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  986): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  986): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  986): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  986): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  986): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  986): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  986): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/JobSchedulerService(  986): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  986): Explicit concurrent mark sweep GC freed 8876(560KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 3.300ms total 185.884ms
W/asset   (  986): Copying FileAsset 0x5574551860 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/TaskPersister(  986): removeObsoleteFile: deleting file=8_task.xml
D/StatusBarManagerService(  986): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  986): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  986): hiding MENU key
D/StatusBarManagerService(  986): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  986): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  986): hiding MENU key
D/FindExtension( 1591): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1591): Defer allocateBuffers to drawing time
W/ContextImpl( 6604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
W/InputMethodManagerService(  986): Got RemoteException sending setActive(false) notification to pid 6180 uid 10366
D/StatusBarManagerService(  986): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1240): setImeWindowStatus(false,false)
I/ActivityManager(  986): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6630): -onCreate()
V/Settings:HtcSettingsApplication( 6630): [6630/6630] onCreate()
E/SQLiteLog( 1933): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1933): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/gcm_registrar.db, handle: 0x5573e739d0
E/AndroidRuntime( 1933): FATAL EXCEPTION: main
E/AndroidRuntime( 1933): Process: com.google.process.gapps, PID: 1933
E/AndroidRuntime( 1933): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1933): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2726)
E/AndroidRuntime( 1933): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1933): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1449)
E/AndroidRuntime( 1933): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1933): 	at android.os.Looper.loop(Looper.java:155)
E/AndroidRuntime( 1933): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
E/AndroidRuntime( 1933): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1933): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1933): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/AndroidRuntime( 1933): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/AndroidRuntime( 1933): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1933): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1933): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 1933): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1933): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1933): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 1933): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1933): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1933): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1933): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2712)
E/AndroidRuntime( 1933): 	... 9 more
E/ActivityManager(  986): App crashed! Process: com.google.process.gapps
D/Process ( 1933): killProcess, pid=1933
D/Process ( 1933): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  986): Can't write: system_app_crash
E/DropBoxManagerService(  986): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  986): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  986): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  986): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  986): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  986): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  986): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  986): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  986): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  986): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  986): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  986): 	... 5 more
D/Settings:HtcWirelessFeatureFlags( 6630): id/is att sku: 118/false
E/Settings:HtcWrapHeaderInfo( 6630): no such activity!
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6630): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6630): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 6630): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]support         :false
I/ActivityManager(  986): Recipient 1933
I/ActivityManager(  986): Process com.google.process.gapps (pid 1933) has died
W/ActivityManager(  986): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
W/ActivityManager(  986): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 11000ms
W/ActivityManager(  986): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
E/Settings:HtcVoWifiWidgetEnabler( 6630): isSupportVoWifi: null
I/ActivityManager(  986): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6630): Failed to find provider info for com.htc.vowifi
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6630): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6630): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 6630): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6630): [supportHomeButton]support         :false
I/ActivityManager(  986): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6630): isSupportVoWifi: null
E/ActivityThread( 6630): Failed to find provider info for com.htc.vowifi
I/art     ( 1832): Explicit concurrent mark sweep GC freed 16660(930KB) AllocSpace objects, 6(120KB) LOS objects, 46% free, 4MB/8MB, paused 1.381ms total 78.129ms
E/DataBuffer( 1832): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c233adc)
E/DataBuffer( 1832): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@291747e5)
I/Prism.ItemManager( 6426): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 6426): loadItems() com.htc.launcher.pageview.WidgetManager@1b32a597 +
I/Prism.WidgetManager( 6426): onLoadItems() +
I/Prism.ItemManager( 1591): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1591): loadItems() com.htc.launcher.pageview.WidgetManager@3342b53e +
I/Prism.WidgetManager( 1591): onLoadItems() +
W/ResourcesManager( 1591): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1591): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6426): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.

```
