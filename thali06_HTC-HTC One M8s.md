#### Test 50650278e3ff7c2_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  971): acquireWL(1444d3b4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117562, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{b072bdd: PendingIntentRecord{2b593352 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450100346893, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{260a0623: PendingIntentRecord{22357720 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=119386, Int=0
D/PMS     (  971): acquireWL(1dcfa8d9): PARTIAL_WAKE_LOCK  *backup* 0x1 971 1000 null
W/BackupManagerService(  971): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  971): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  971): acquireWL(27b3329e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(1dcfa8d9): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  971): releaseWL(1444d3b4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  971): acquireWL(4ece17f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(27b3329e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(4ece17f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(908f995): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  971): Killing 5129:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  971): killProcessQuiet, pid=5129
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/PMS     (  971): releaseWL(908f995): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(331bdaaa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
I/ActivityManager(  971): Recipient 5129
D/PMS     (  971): releaseWL(331bdaaa): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(8f8169b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(3f670a38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(8f8169b): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
I/VacuumService( 1865): Vacuum at: now=1450100347311 tag=VacuumService
D/PMS     (  971): releaseWL(3f670a38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(38b4f776): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(38b4f776): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): acquireWL(23b78177): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  971): releaseWL(23b78177): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 5981): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5981): ====startRecUseTime====
D/htc.customization.log.level( 5981):  is 
W/CustomizationLogLevel( 5981): Level value is invalid, use default level 2
D/CustomizationManager( 5981):  Read ACC file spent 0.034 (s)
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5981): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5981): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5981): Parsing tag category name = system
I/CustomizationCIDLoader( 5981): Parsing tag category name = application
I/CustomizationCIDLoader( 5981): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5981): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5981): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5981): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5981): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5981): add string-array item, value = 42507
I/CustomizationCIDLoader( 5981): add string-array item, value = 21902
I/CustomizationCIDLoader( 5981): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5981): add string-array item, value = 23420
I/CustomizationCIDLoader( 5981): add string-array item, value = 22299
I/CustomizationCIDLoader( 5981): add string-array item, value = 24002
I/CustomizationCIDLoader( 5981): add string-array item, value = 23210
I/CustomizationCIDLoader( 5981): add string-array item, value = 23205
I/CustomizationCIDLoader( 5981): add string-array item, value = 23806
I/CustomizationCIDLoader( 5981): add string-array item, value = 23430
I/CustomizationCIDLoader( 5981): add string-array item, value = 23408
I/CustomizationCIDLoader( 5981): add string-array item, value = 27205
I/CustomizationCIDLoader( 5981): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5981): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5981):  Read CID file spent 0.070 (s)
D/CustomizationManager( 5981):  All configurations done spent 0.071 (s)
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5981 on display 0
D/PMS     (  971): acquireHCC(379e91e4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 971 1000 null
D/PMS     (  971): acquireHCC(394fc64d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 971 1000 null
W/asset   (  971): Copying FileAsset 0x556d12ffb0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  971): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5999 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
V/ActivityManager(  971): Display changed displayId=0
W/asset   ( 5999): Copying FileAsset 0xac364938 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1529): [trimMemory] 20
I/WebViewFactory( 5999): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5999): Time to load native libraries: 9 ms (timestamps 5955-5964),
,I/LibraryLoader( 5999): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 5999): Binding Chromium to main looper Looper (main, tid 1) {26d3f91b},
I/LibraryLoader( 5999): Expected native library version number "",actual native library version number ""
,I/chromium( 5999): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5999): Initializing chromium process, singleProcess=true,
,W/art     ( 5999): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5999): ApplicationContext is null in ApplicationStatus
,W/chromium( 5999): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5999): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5999): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5999): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5999): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5999): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5999): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5999): Local Branch: 
I/Adreno-EGL( 5999): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5999): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5999):                  d74aa161a12b9c6fc6332151
,W/System.err(  971): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@772981:true
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): ,	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapter( 5999): 61803511: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5999): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5999): onDetachedFromWindow called when already detached. Ignoring,
D/SystemWebViewEngine( 5999): CordovaWebView is running on device made by: HTC
W/art     ( 5999): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5999): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  971): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/chromium( 5999): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  971): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
D/StatusBarManagerService(  971): hiding MENU key
D/StatusBarManagerService(  971): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  971): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  971): hiding MENU key
,D/FindExtension( 5999): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5999): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2ed54b3d, mServedView=org.apache.cordova.engine.SystemWebView{1bebcf32 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@2f34a483,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/InputMethodManagerService(  971): Disable input method client, pid=1529
D/StatusBarManagerService(  971): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 5999): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  971): Displayed com.test.thalitest/.MainActivity: +620ms (total +666ms)
,W/BindingManager( 5999): Cannot call determinedVisibility() - never saw a connection for the pid: 5999,
,D/JsMessageQueue( 5999): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5999): JniHelper::setJavaVM(0xab1f88f8), pthread_self() = -1403986088
D/JX-Cordova( 5999): jxcore cordova android initializing
,D/ContactMessageStore( 1475): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1475): MSG_NOTIFY_CS_TO_SYNC <<
,W/jxcore-log( 5999): Initializing JXcore engine
W/jxcore-log( 5999): JXcore engine is ready
,W/jxcore-log( 5999): Starting JXcore engine,
,W/jxcore-log( 5999): Platform android,
W/jxcore-log( 5999): 
W/jxcore-log( 5999): Process ARCH arm
W/jxcore-log( 5999): 
,D/PMS     (  971): releaseHCC(379e91e4): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  971): releaseHCC(394fc64d): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 5999): JXcore Cordova bridge is ready!
I/jxcore-log( 5999): 
W/jxcore-log( 5999): JXcore engine is started
,I/Choreographer( 5999): Skipped 97 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 5999): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5999): Toggling radios to true,
I/jxcore-log( 5999): 
,D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  971): checking for enable restriction...
D/BluetoothManagerService(  971): checkBTEasState, ret=true
I/BluetoothManagerService(  971): isBluetoothRestricted(): false
D/BluetoothManagerService(  971): enable(): region ID = 6
D/BluetoothManagerService(  971): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  971): MONITOR_LOG
W/Settings:Agent(  971): name: bluetooth_on
W/Settings:Agent(  971): value: 1
W/Settings:Agent(  971): >> traceCallingStack()
W/Settings:Agent(  971): Process.myPid(): 971
W/Settings:Agent(  971): Process.myTid(): 1698
W/Settings:Agent(  971): Process.myUid(): 1000
,W/Settings:Agent(  971): 
W/Settings:Agent(  971): 
W/System.err(  971): java.lang.Throwable: stack dump
,W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  971): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  971): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  971): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  971): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  971): 
W/Settings:Agent(  971): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  971): Message: MESSAGE_ENABLE,
D/BluetoothManagerService(  971): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  971): New client listening to asynchronous messages
D/WifiManager( 5999): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  971): setWifiEnabled: true pid=5999, uid=10366
E/WifiService(  971): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  971): isSprintWifiRestricted(): false
,E/WifiTrafficPoller(  971): ADD_CLIENT: 8
I/WifiService(  971): isMdmWifiRestricted(): false
W/Settings:Agent(  971): MONITOR_LOG
W/Settings:Agent(  971): name: wifi_on
W/Settings:Agent(  971): value: 2
W/Settings:Agent(  971): >> traceCallingStack()
W/Settings:Agent(  971): Process.myPid(): 971
W/Settings:Agent(  971): Process.myTid(): 1010
W/Settings:Agent(  971): Process.myUid(): 1000
W/Settings:Agent(  971): 
W/Settings:Agent(  971): 
W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  971): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  971): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  971): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  971): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  971): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  971): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  971): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  971): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  971): 
W/Settings:Agent(  971): << traceCallingStack(): 3(ms)
,I/ActivityManager(  971): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6053 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
D/WifiController(  971): handleMessage: E msg.what=155656
D/WifiManager( 5999): disconnect: Base Package Name=com.test.thalitest, uid=10366
,D/PMS     (  971): acquireWL(1973d129): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 971 1000 null
D/WifiController(  971): processMsg: ApStaDisabledState
D/WifiController(  971): transitionTo: destState=DeviceActiveState
D/WifiController(  971): handleMessage: new destination call exit/enter
E/WifiStateMachine(  971): handleMessage: E msg.what=131145
E/WifiStateMachine(  971): processMsg: InitialState
D/WifiController(  971): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiManager( 5999): reconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  971): invokeExitMethods: ApStaDisabledState
D/WifiController(  971): moveTempStackToStateStack: i=1,j=1
D/WifiController(  971): moveTempStackToStateStack: i=0,j=2
D/WifiController(  971): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  971): invokeEnterMethods: StaEnabledState
D/WifiController(  971): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  971): setting operational mode to 1
D/WifiController(  971): handleMessage: X
E/WifiStateMachine(  971):  InitialState CMD_DISCONNECT 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131146
E/WifiStateMachine(  971): processMsg: InitialState
I/jxcore-log( 5999): Radios toggled
I/jxcore-log( 5999): 
E/WifiStateMachine(  971):  InitialState CMD_RECONNECT 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131083
E/WifiStateMachine(  971): processMsg: InitialState
D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine(  971):  InitialState CMD_START_SUPPLICANT 0 0
I/jxcore-log( 5999): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 5999): 
I/jxcore-log( 5999): Perf Test app loaded loaded
I/jxcore-log( 5999): 
I/jxcore-log( 5999): check test folder
I/jxcore-log( 5999): 
I/jxcore-log( 5999): found test : ./testFindPeers.js
I/jxcore-log( 5999): 
,I/art     (  410): Explicit concurrent mark sweep GC freed 8680(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 529us total 48.453ms,
,I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 302us total 22.528ms
,I/jxcore-log( 5999): found test : ./testSendData.js
I/jxcore-log( 5999): 
,I/art     (  410): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 336us total 17.062ms
,W/ResourcesManager( 6053): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/chromium( 5999): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AdapterServiceConfig( 6053): Adding HeadsetService
D/AdapterServiceConfig( 6053): Adding A2dpService
D/AdapterServiceConfig( 6053): Adding HidService
D/AdapterServiceConfig( 6053): Adding HealthService
D/AdapterServiceConfig( 6053): Adding PanService
D/AdapterServiceConfig( 6053): Adding GattService
,W/linker  ( 6053): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/System.err(  971): java.lang.Throwable: stack dump
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@148625dc:true
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 6053): make
,I/BluetoothAdapterState( 6053): Entering OffState
,E/bt_osi_config( 6053): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,D/BluetoothAdapterProperties( 6053): Address is:90:E7:C4:F6:69:77,
D/BluetoothManagerService(  971): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  971): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  971): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  971): Calling onBluetoothServiceUp callbacks,
,D/BluetoothManagerService(  971): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 1222): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2cc8369b
D/BluetoothAdapter( 1222): onBluetoothServiceUp done
D/BluetoothAdapter(  971): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2b3dc3c8
,D/BluetoothAdapter(  971): onBluetoothServiceUp done
D/BluetoothAdapter( 1794): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@20867e24
D/BluetoothAdapter( 1794): onBluetoothServiceUp done
D/BluetoothAdapter( 1475): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@e06bea9
D/BluetoothAdapter( 1475): onBluetoothServiceUp done
,D/BluetoothAdapter( 1494): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@7f09085
D/BluetoothAdapter( 1494): onBluetoothServiceUp done
,D/BluetoothAdapter( 6053): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1f378a64
D/BluetoothAdapter( 6053): onBluetoothServiceUp done
D/BluetoothAdapter( 3528): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@15476ea6
D/BluetoothAdapter( 3528): onBluetoothServiceUp done
,D/BluetoothAdapter( 2360): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2fea0207
D/BluetoothAdapter( 2360): onBluetoothServiceUp done
D/BluetoothAdapter( 5999): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3c01c426
D/BluetoothAdapter( 5999): onBluetoothServiceUp done
D/BluetoothManagerService(  971): Broadcasting onBluetoothServiceUp() done
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 2,
D/Tethering(  971): interfaceAdded wlan0
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterState( 6053): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6053): Setting state to 11
,I/BluetoothAdapterState( 6053): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  971): +onBluetoothStateChange prev=10 new=11
D/PMS     (  971): releaseWL(1973d129): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/BluetoothManagerService(  971): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  971): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  971): Bluetooth State Change Intent: 10 -> 11
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/libc    (  971): [NET] android_getaddrinfofornet-, SUCCESS
V/BluetoothPbapReceiver( 6053): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6053): ***********state = 11
D/BluetoothBondStateMachine( 6053): make
V/Tethering(  971): TetherInterfaceSM: wlan0: enter InitialState
D/Tethering(  971): interfaceLinkStateChanged wlan0, false
D/Tethering(  971): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  971): interfaceAdded p2p0
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  971): p2p0 is not a tetherable iface, ignoring
I/BluetoothBondStateMachine( 6053): StableState(): Entering Off State
D/BluetoothAdapterService( 6053): checkA2dpState: isA2dpSinkEnabled = false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
E/BluetoothAdapterService( 6053): checkA2dpState: returning
D/BluetoothAdapterService( 6053): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6053): checkHfpState: returning
,D/Tethering(  971): interfaceLinkStateChanged p2p0, false
D/Tethering(  971): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  971): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  971): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  971): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  971): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,D/NGFService( 3528): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,D/PMS     (  971): acquireWL(109fa53f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 971 1000 null
,D/Tethering(  971): sendTetherStateChangedBroadcast 0, 0, 0
D/UsbnetService(  971): BroadcastReceiver::onReceive+
,D/BluetoothHeadset( 1475): Proxy object connected,
,V/NetworkPolicy(  971): updateNetworkEnabledLocked()
,V/NetworkPolicy(  971): updateNotificationsLocked()
D/BluetoothHeadset( 1222): Proxy object connected
D/PMS     (  971): releaseWL(109fa53f): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/HeadsetService( 6053): Received start request. Starting profile...
D/HeadsetStateMachine( 6053): Version 1.5
D/PMS     (  971): acquireWL(1501416a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 971 1000 null
,D/HeadsetStateMachine( 6053): make
,D/PMS     (  971): releaseWL(1501416a): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  971): updateNetworkEnabledLocked()
V/NetworkPolicy(  971): updateNotificationsLocked()
,I/BluetoothAdapterState( 6053): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 6053): max_hf_connections = 2
,D/BluetoothHeadset( 1475): Proxy object connected
,D/UsbDeviceManager(  971): [USBNET] bCheckSuppFunc: cdc_network,
D/UsbnetService(  971): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  971): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  971): BroadcastReceiver::onReceive-,
D/BluetoothHeadset(  971): Proxy object connected
,D/TetherSettings( 5390): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5390): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5390): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5390): Cust_ConnectToPC   : spcsc>false
D/        ( 5390): Cust_ConnectToPC   : IPT>true
D/        ( 5390): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5390): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/HeadsetPhoneState( 6053): listenForPhoneState..for service and signal 
E/SmartNS_Utility( 5390): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5390): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5390): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,D/BluetoothHeadset( 1475): Proxy object connected
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  971): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6090 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/HeadsetDualPhoneStateListener_SLOT1( 6053): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6053): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6053): Enter Disconnected: -2, size: 0
,D/BluetoothPhoneService( 1475): BluetoothHeadset onServiceConnected
,D/HeadsetDualPhoneStateListener_SLOT1( 6053): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6053): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6053): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6053): BTHF: set_current_device
,W/ContextImpl( 5390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24097ab8
I/SmartNS_Utility( 5390): setISNotification
,D/A2dpService( 6053): Received start request. Starting profile...
,V/Avrcp   ( 6053): make
D/BluetoothAdapter(  971): 800243521: getState(). Returning 11
,D/BluetoothA2dp(  971): Proxy object connected
,D/BluetoothAdapter(  971): 800243521: getState(). Returning 11
,E/WifiStateMachine(  971): setWifiState: enabling
E/WifiStateMachine(  971): Supplicant start successful
D/WifiMonitor(  971): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  971): connecting to supplicant
,I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/BluetoothAdapter( 1475): 474215375: getState(). Returning 11,
,E/RemoteController( 6053): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 6053): make
,D/bt-btif ( 6053): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/A2dpService( 6053): setA2dpService(): set to: null
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24097ab8,
D/A2dpStateMachine( 6053): Enter Disconnected: -2
,D/SmartNS_Utility( 5390): usb_cable_connect = 1
,D/SmartNS_Utility( 5390): usb_denied = 0,
,I/SmartNS_PSService( 5390): usb notificaiton:true
,E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 6087): wpa_supplicant v2.3-devel-5.0.2
,D/wpa_supplicant( 6087): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6087): random: Trying to read entropy from /dev/random,
D/HidService( 6053): Received start request. Starting profile...
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24097ab8
D/wpa_supplicant( 6087): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6087): Global control interface '@android:wpa_wlan0'
,D/wpa_supplicant( 6087): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6087): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6087): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6087): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6087): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
I/ActionCombine( 5390): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/HealthService( 6053): Received start request. Starting profile...
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24097ab8
,D/wpa_supplicant( 6087): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6087): driver_param='use_multi_chan_concurrent=1',
,D/wpa_supplicant( 6087): update_config=1
D/wpa_supplicant( 6087): uuid=12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6087): device_name='Android_608e'
D/wpa_supplicant( 6087): manufacturer='HTC'
D/wpa_supplicant( 6087): model_name='HTC_PHONE'
D/wpa_supplicant( 6087): model_number='1234'
D/wpa_supplicant( 6087): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6087): p2p_oper_reg_class=126
D/wpa_supplicant( 6087): p2p_oper_channel=149
D/wpa_supplicant( 6087): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6087): persistent_reconnect=1
D/wpa_supplicant( 6087): key_mgmt_offload=1
I/wpa_supplicant( 6087): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6087): nl80211: RFKILL status not available
D/wpa_supplicant( 6087): nl80211: Using driver-based roaming
D/wpa_supplicant( 6087): nl80211: TDLS supported
D/wpa_supplicant( 6087): nl80211: TDLS external setup
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:6,
D/wpa_supplicant( 6087): nl80211: Supports Probe Response offload in AP mode
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  971): Killing 5676:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/PanService( 6053): Received start request. Starting profile...
,D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
I/QuickSettingMiniLite( 1222): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@28c4aa38
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6087): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6087): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6087): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6087): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6087): nl80211: Subscribe to mgmt frames with non-AP handle 0x558246dfd0
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=0104
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=040a
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=040b
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=040c
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=040d
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=090a
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=090b
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=090c
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=090d
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=0409506f9a09
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=7f506f9a09
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=0801
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=040e
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=06
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=0a07
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=0a11
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558246dfd0 match=0a1a
D/wpa_supplicant( 6087): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  971): interfaceLinkStateChanged p2p0, false
D/Tethering(  971): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6087): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6087): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6087): htc_wext_command_init +
E/wpa_supplicant( 6087): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6087): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  971): interfaceLinkStateChanged p2p0, false
D/Tethering(  971): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/PanService( 6053): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/HtcBtWidget_BTWidgetProvider( 6090): onBTStateChanged() for widget: 
D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24097ab8
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/HtcBtWidget_BTWidgetProvider( 6090): updateWidget(context) for widget: 
D/SmartNS_Utility( 5390): usb_cable_connect = 1
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_Utility( 5390): usb_denied = 0
I/SmartNS_PSService( 5390): usb notificaiton:true
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/Process (  971): killProcessQuiet, pid=5676
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/BtGatt.DebugUtils( 6053): handleDebugAction() action=null
D/BtGatt.GattService( 6053): Received start request. Starting profile...
D/BtGatt.GattService( 6053): start()
D/BtGatt.AdvertiseManager( 6053): advertise manager created
I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
,D/BluetoothAdapter( 1222): 319860267: getState(). Returning 11
I/QuickSettingMiniLite( 1222): updateLiteState:no connect device!
I/ActivityManager(  971): Recipient 5676
,D/SmartNS_NSReceiver( 5390): Tethered state change:false isNSOpening:false
,D/BluetoothAdapterService( 6053): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24097ab8
,D/TetherSettings( 5390): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 5390): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5390): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5390): Cust_ConnectToPC   : spcsc>false
D/        ( 5390): Cust_ConnectToPC   : IPT>true
D/        ( 5390): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5390): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5390): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5390): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
I/RemoteViews( 1222): reapply : com.android.settings 1 36,
D/SmartNS_NSReceiver( 5390): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5390): setISNotification
,D/SmartNS_Utility( 5390): usb_cable_connect = 1
,D/SmartNS_Utility( 5390): usb_denied = 0
,I/SmartNS_PSService( 5390): usb notificaiton:true
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/SmartNS_Utility( 5390): usb_cable_connect = 1
,D/SmartNS_Utility( 5390): usb_denied = 0
,I/SmartNS_PSService( 5390): usb notificaiton:true
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
,I/HeadsetPhoneState( 6053): updateServiceState service = 0,roam = 0,
D/HeadsetPhoneState( 6053): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0,
D/HeadsetStateMachine( 6053): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 6053): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6053): Disconnected process message: 11, size: 0
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 2 36
,D/SmartNS_NSReceiver( 5390): Tethered state change:false isNSOpening:false
,I/wpa_supplicant( 6087): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 6087):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6087):  Initialization: WAPI: Initializing WAPI Supplicant
,E/wpa_supplicant( 6087):  Initialization: WAPI:set Staues=1 ,
D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6087): nl80211: Flush PMKIDs
D/wpa_supplicant( 6087): p2p0: State: DISCONNECTED -> INACTIVE
D/BluetoothAdapter( 1475): 474215375: getState(). Returning 11
,W/BluetoothHeadset( 1475): Proxy not attached to service
E/bt_vendor( 6053): get_bt_soc_type: Failed to get soc type
I/bt-btu  ( 6053): btu_task pending for preload complete event
D/BluetoothHeadset( 1475): java.lang.Throwable
D/BluetoothHeadset( 1475): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1475): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1475): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1475): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1475): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1475): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1475): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1475): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1475): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1475): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/ActivityManager(  971): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6124 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,I/qcom-bluetooth( 6136): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/BluetoothMasReceiver( 6053): Bluetooth STATE CHANGED to 11
,I/RemoteViews( 1222): reapply : com.android.settings 7 36
,D/wpa_supplicant( 6087): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 6087): TDLS: Driver uses external link setup
D/wpa_supplicant( 6087): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,V/BluetoothSapReceiver( 6053): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6053): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6053):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6053): startService = false
,D/AuthorizationBluetoothService( 1865): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/wpa_supplicant( 6087): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6087): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6087): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6087): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6087): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6087): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6087): Using existing control interface directory.
,D/wpa_supplicant( 6087): P2P: Add operating class 81
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6087): P2P: Own listen channel: 81:6
D/wpa_supplicant( 6087): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6087): P2P: initialized
D/wpa_supplicant( 6087): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
,D/wpa_supplicant( 6087): P2P: cli_channels:
D/wpa_supplicant( 6087): p2p0: Added interface p2p0
D/wpa_supplicant( 6087): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6087): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6087): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6087): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6087): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6087): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6087): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6087): disable_scan_offload=1
D/wpa_supplicant( 6087): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6087): update_config=1
D/wpa_supplicant( 6087): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6087): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6087): manufacturer='HTC'
D/wpa_supplicant( 6087): model_name='HTC One M8s'
D/wpa_supplicant( 6087): model_number='HTC One M8s'
D/wpa_supplicant( 6087): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6087): hs20=1
,D/wpa_supplicant( 6087): interworking=1
D/wpa_supplicant( 6087): external_sim=1
D/wpa_supplicant( 6087): key_mgmt_offload=1
,I/qcom-bluetooth( 6151): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6152): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,D/wpa_supplicant( 6087): Priority group 303,
D/wpa_supplicant( 6087):    id=0 ssid='NG700'
I/wpa_supplicant( 6087): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6087): nl80211: RFKILL status not available
D/wpa_supplicant( 6087): nl80211: Using driver-based roaming
D/wpa_supplicant( 6087): nl80211: TDLS supported
D/wpa_supplicant( 6087): nl80211: TDLS external setup,
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6087): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6087): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Su,pported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
I/ActivityManager(  971): Killing 4621:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6087): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant(, 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6087): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6087): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6087): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6087): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6087): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6087): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6087): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6087): nl80211: Subscribe to mgmt frames with non-AP handle 0x558248d100
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=0104
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=040a
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=040b
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=040c
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=040d
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=090a
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=090b
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=090c
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=090d
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=0409506f9a09
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=7f506f9a09
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=0801
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=040e
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=06
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=0a07
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=0a11
D/wpa_supplicant( 6087): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x558248d100 match=0a1a
D/wpa_supplicant( 6087): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6087): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6087): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6087): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6087): htc_wext_command_init +
I/wpa_supplicant( 6087): htc_wext_command_init -
I/wpa_supplicant( 6087): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6087): Don't set 00 to countryID.conf
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
I/qcom-bluetooth( 6154): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/wpa_supplicant( 6087): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6087): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/Tethering(  971): interfaceLinkStateChanged wlan0, false
D/Tethering(  971): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6087): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6087): P2P: Add operating class 81
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6087): P2P: Update channel list
D/wpa_supplicant( 6087): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6087): P2P: cli_channels:
D/wpa_supplicant( 6087): p2p0: Updating hw mode
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6087): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6087): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6087): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/HtcWiFiWidget_WiFiWidgetProvider( 6124): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 6124): updateWidget(context) for widget: 
I/qcom-bluetooth( 6155): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/Process (  971): killProcessQuiet, pid=4621
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
I/qcom-bluetooth( 6156): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6157): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,I/ActivityManager(  971): Recipient 4621
,I/wpa_supplicant( 6087): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 6087):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6087):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6087):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6087): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6087): nl80211: Flush PMKIDs
,D/wpa_supplicant( 6087): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 6087): TDLS: Driver uses external link setup
D/wpa_supplicant( 6087): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6087): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6087): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6087): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6087): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6087): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6087): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6087): Using existing control interface directory.
,I/wpa_supplicant( 6087): set country (DE) from /data/misc/wifi/countryID.conf,
I/wpa_supplicant( 6087): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6087): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6087): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6087): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6087): P2P: Add operating class 81
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6087): P2P: Add operating class 115
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6087): P2P: Add operating class 116
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6087): P2P: Add operating class 117
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6087): P2P: Update channel list
D/wpa_supplicant( 6087): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/wpa_supplicant( 6087): P2P: cli_channels:
D/wpa_supplicant( 6087): p2p0: Updating hw mode
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6087): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6087): Auto country group 1: ch36
D/wpa_supplicant( 6087): wlan0: Added interface wlan0
D/wpa_supplicant( 6087): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 6087): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6087): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 6087): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 6087): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6087): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_971-2\x00
D/wpa_supplicant( 6087): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6087): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6087): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6087): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6087): nl80211: Regulatory domain change
D/wpa_supplicant( 6087):  * initiator=1
D/wpa_supplicant( 6087):  * type=0
D/wpa_supplicant( 6087):  * alpha2=DE
D/wpa_supplicant( 6087): wlan0: Event CHANNEL_LIST_CHANGED (30) received
,I/wpa_supplicant( 6087): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6087): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
E/WifiStateMachine(  971): transitionTo: destState=SupplicantStartingState
D/wpa_supplicant( 6087): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
E/WifiStateMachine(  971): handleMessage: new destination call exit/enter
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6087): P2P: Add operating class 81
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
E/WifiStateMachine(  971): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/wpa_supplicant( 6087): P2P: Add operating class 115
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=4): 24 28 2c 30
E/WifiStateMachine(  971): invokeExitMethods: InitialState
D/wpa_supplicant( 6087): P2P: Add operating class 116
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=2): 24 2c
E/WifiStateMachine(  971): moveTempStackToStateStack: i=0,j=1
D/wpa_supplicant( 6087): P2P: Add operating class 117
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=2): 28 30
E/WifiStateMachine(  971): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  971): invokeEnterMethods: SupplicantStartingState
D/wpa_supplicant( 6087): P2P: Update channel list
E/WifiStateMachine(  971): handleMessage: X
D/wpa_supplicant( 6087): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6087): P2P: cli_channels:
E/WifiStateMachine(  971): handleMessage: E msg.what=131144
D/wpa_supplicant( 6087): p2p0: Updating hw mode
E/WifiStateMachine(  971): processMsg: SupplicantStartingState
E/WifiStateMachine(  971):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  971): deferMessage: msg=131144
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=DE
E/WifiStateMachine(  971): handleMessage: X
D/wpa_supplicant( 6087): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
E/WifiStateMachine(  971): handleMessage: E msg.what=131085
D/wpa_supplicant( 6087): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
E/WifiStateMachine(  971): processMsg: SupplicantStartingState
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  971): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  971): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  971):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  971): deferMessage: msg=131085
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131149
E/WifiStateMachine(  971): processMsg: SupplicantStartingState
E/WifiStateMachine(  971):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  971): setSuspendOptimizations: 2 true
E/WifiStateMachine(  971): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131101
E/WifiStateMachine(  971): ,processMsg: SupplicantStartingState
E/WifiStateMachine(  971):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  971): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  971): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131101
E/WifiStateMachine(  971): processMsg: SupplicantStartingState
E/WifiStateMachine(  971):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  971): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  971): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=147457
E/WifiStateMachine(  971): processMsg: SupplicantStartingState
E/WifiStateMachine(  971):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  971): Supplicant connection established
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6087): set wifi ON
E/WifiStateMachine(  971): setWifiState: enabled
E/WifiStateMachine(  971): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  971):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6087): SET_SCREEN_ON:Off
I/wpa_supplicant( 6087): htc_wext_set_keepalive +
I/wpa_supplicant( 6087): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6087): getPrivFuncNum +	
I/wpa_supplicant( 6087): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6087): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6087): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6087): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6087): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6087): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  971): startHal
E/wifi    (  971): getStaticLongField sWifiHalHandle 0x7f66663300
,I/WifiNative-HAL(  971): Could not start hal
E/WifiStateMachine(  971): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
D/WifiStateMachine(  971): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  971): handleScreenStateChanged Exit: false
I/qcom-bluetooth( 6161): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED enabled
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER MACADDR'
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
,D/wpa_supplicant( 6087): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6087): update_config=1
D/wpa_supplicant( 6087): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/HtcWiFiWidget_WiFiWidgetProvider( 6124): onWiFiStateChanged() for widget: 
D/WifiConfigStore(  971): Loading config and enabling all networks 
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6087): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6087): wpa_supplicant_ctrl_iface_list_networks: return size = 47
D/HtcWiFiWidget_WiFiWidgetProvider( 6124): updateWidget(context) for widget: 
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6087): Do not allow key_data field to be exposed
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='group'
I/qcom-bluetooth( 6162): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
,D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6087): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6087): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,E/WifiConfigStore(  971): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
,D/wpa_supplicant( 6087): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6087): device_name='m8qlul_htc_europe'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
,D/wpa_supplicant( 6087): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6087): manufacturer='HTC'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET model_name HTC One M8s'
,D/wpa_supplicant( 6087): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6087): model_name='HTC One M8s'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6087): model_number='HTC One M8s'
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6087): config_methods='physical_display virtual_push_button'
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,E/WifiStateMachine(  971): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  971): handleMessage: new destination call exit/enter
E/WifiStateMachine(  971): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  971): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  971): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  971): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  971): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  971): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/WifiP2pService(  971): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6087): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/WifiP2pService(  971): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6087): wlan0: Setting scan interval: 15 sec
W/Settings( 5759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  971): Setting external_sim to 1
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6087): external_sim=1
D/WifiStateMachine(  971): Setting OUI to DA-A1-19
I/WifiNative-HAL(  971): startHal
E/wifi    (  971): getStaticLongField sWifiHalHandle 0x7f66663360
I/WifiNative-HAL(  971): Could not start hal
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6087): wlan0: Control interface command 'STA_AUTOCONNECT 0'
,E/WifiStateMachine(  971): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  971): Driverstarted State enter
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
,E/WifiStateMachine(  971): DriverStartedState call setCountryCode()
E/WifiStateMachine(  971): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  971): NetworkAgent == null
,E/WifiStateMachine(  971): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  971): setDhcpActive: false
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6087): wlan0: Control interface command 'STATUS'
E/WifiTrafficPoller(  971): ENABLE_TRAFFIC_STATS_POLL false Token 0
E/WifiStateMachine(  971): transitionTo: destState=DisconnectedState
E/native  (  971): do suspend false
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiP2pService(  971): P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6087): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  971): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  971): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  971): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  971): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  971): [NET] android_getaddrinfofornet-, SUCCESS
,D/WifiMonitor(  971): startMonitoring(p2p0) with mConnected = true
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  971): Driverstarted State enter done
E/WifiStateMachine(  971): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  971): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  971): handleMessage: new destination call exit/enter
E/WifiStateMachine(  971): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  971): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  971): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  971): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  971): invokeEnterMethods: ConnectModeState
D/WifiP2pService(  971): P2pEnablingState
E/WifiStateMachine(  971): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  971): DisconnectedState call setCountryCode()
E/WifiStateMachine(  971):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiScanningService(  971): SCAN_AVAILABLE : 3
D/wpa_supplicant( 6087): wlan0: Control interface command 'SET pno 1'
,D/wpa_supplicant( 6087): CTRL_IFACE SET 'pno'='1'
D/RttService(  971): SCAN_AVAILABLE : 3
D/wpa_supplicant( 6087): wlan0: nl80211: sched_scan request
D/WifiScanningService(  971): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  971): startHal
D/RttService(  971): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  971): P2pEnablingState{ when=-12ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  971): P2p socket connection successful
D/WifiP2pService(  971): P2pEnabledState
D/WifiP2pService(  971): sending p2p connection changed broadcast
D/WifiDisplayController(  971): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController(  971): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/bt-btu  ( 6053): btu_task received preload complete event
D/WifiDisplayController(  971): mWfdEnabled :false, networkInfo.isConnected() :false
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0001
D/WifiDisplayAdapter(  971): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  971):     Client/Owner: Client
D/WifiDisplayAdapter(  971):     GroupId: 
D/WifiDisplayAdapter(  971):     Passphrase: 
D/WifiDisplayAdapter(  971):     SessionId: 0
D/WifiDisplayAdapter(  971):     IP Address: }
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x1487
D/WISPrService( 5390): >>>>>WISPrService start isConnected = false<<<<<
,V/AudioService(  971): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  971):     Client/Owner: Client
V/AudioService(  971):     GroupId: 
V/AudioService(  971):     Passphrase: 
V/AudioService(  971):     SessionId: 0
V/AudioService(  971):     IP Address: }
D/HtcEffectManagerBase(  971): onEventChanged id=5 status=false
D/PMS     (  971): acquireWL(23ed7172): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6053 1002 null
D/HtcEffectManager(  971): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  971): convertEffect before=902
D/HtcEffectManager(  971): convertEffect after=902
D/wpa_supplicant( 6087): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6087): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6087): wlan0: nl80211: Sched scan started
E/wifi    (  971): getStaticLongField sWifiHalHandle 0x7f641c5520
I/WifiNative-HAL(  971): Could not start hal
E/WifiStateMachine(  971): handleMessage: X
E/WifiScanningService(  971): could not start HAL
E/WifiStateMachine(  971): handleMessage: E msg.what=131144
E/WifiStateMachine(  971): processMsg: DisconnectedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6087): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6087): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6087): persistent_reconnect=1
D/wpa_supplicant( 6087): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6087): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6087): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  971):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131085
E/WifiStateMachine(  971): processMsg: DisconnectedState
E/WifiStateMachine(  971):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  971): processMsg: ConnectModeState
D/WifiP2pService(  971): DeviceAddress: 92:e7:c4:e6:4c:f8
W/WifiHW  (  971): QCOM Debug wifi_send_command "SET device_name Android_608e"
D/WifiDisplayController(  971): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  971):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  971):  primary type: 10-0050F204-5
D/WifiDisplayController(  971):  secondary type: null
D/WifiDisplayController(  971):  wps: 0
D/WifiDisplayController(  971):  grpcapab: 0
D/WifiDisplayController(  971):  devcapab: 0
D/WifiDisplayController(  971):  status: 3
D/WifiDisplayController(  971):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  971):  WFD CtrlPort: 0
D/WifiDisplayController(  971):  WFD MaxThroughput: 0
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6087): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6087): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6087): device_name='Android_608e'
E/WifiStateMachine(  971):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  971): processMsg: DriverStartedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -,Android_608e"
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6087): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
E/WifiStateMachine(  971):  DriverStartedState CMD_START_DRIVER 0 0
D/wpa_supplicant( 6087): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6087): p2p_ssid_postfix='-Android_608e'
E/WifiStateMachine(  971): handleMessage: X
D/wpa_supplicant( 6087): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  971): handleMessage: E msg.what=131154
E/WifiStateMachine(  971): processMsg: DisconnectedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
E/WifiStateMachine(  971):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  971): processMsg: ConnectModeState
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6087): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6087): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiP2pService(  971): sending p2p persistent groups changed broadcast
E/WifiStateMachine(  971):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  971): processMsg: DriverStartedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6087): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6087): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6087): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
E/WifiStateMachine(  971):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
D/WifiP2pService(  971): InactiveState
,D/wpa_supplicant( 6087): config_methods='virtual_push_button physical_display keypad'
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
W/WifiHW  (  971): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
E/WifiStateMachine(  971):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
D/wpa_supplicant( 6087): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6087): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6087): Single channel concurrency preference: sta
E/WifiStateMachine(  971):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131323
E/WifiStateMachine(  971): processMsg: DisconnectedState
D/WifiNative-HAL(  971): p2pGetDeviceAddress
W/WifiHW  (  971): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
E/WifiStateMachine(  971):  DisconnectedState what:131323 0 0
D/WifiNative-HAL(  971): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
E/WifiStateMachine(  971):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  971): processMsg: DefaultState
W/WifiHW  (  971): QCOM Debug wifi_send_command "P2P_FLUSH"
E/WifiStateMachine(  971):  DefaultState what:131323 0 0
E/WifiStateMachine(  971): setOperatorSSID enter
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=131104
E/WifiStateMachine(  971): processMsg: DisconnectedState
D/bt-btm  ( 6053): btm_acl_device_down
D/bt-btm  ( 6053): btm_acl_reset_paging
D/bt-btm  ( 6053): btm_acl_set_discing
D/wpa_supplicant( 6087): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6087): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6087): P2P: Stopping find
E/WifiStateMachine(  971):  DisconnectedState what:131104 0 0
D/wpa_supplicant( 6087): P2P: Clear timeout (state=IDLE)
E/WifiStateMachine(  971): processMsg: ConnectModeState
D/wpa_supplicant( 6087): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6087): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6087): P2P: Stopping find
D/wpa_supplicant( 6087): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6087): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6087): wpa_driver_set_ap_wps_p2p_ie: Entry
E/WifiStateMachine(  971):  ConnectModeState what:131104 0 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
,W/Settings(  971): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 6087): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6087): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6087): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6087): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6087): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  971): handleMessage: X
W/WifiHW  (  971): QCOM Debug wifi_send_command "LIST_NETWORKS"
E/WifiStateMachine(  971): handleMessage: E msg.what=131162
D/WifiService(  971): New client listening to asynchronous messages
E/WifiStateMachine(  971): processMsg: DisconnectedState
D/wpa_supplicant( 6087): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6087): wpa_supplicant_ctrl_iface_list_networks: return size = 34
,E/WifiStateMachine(  971):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  971): processMsg: ConnectModeState
W/WifiHW  (  971): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 6087): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6087): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiStateMachine(  971):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/wpa_supplicant( 6087): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6087): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6087): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
E/WifiStateMachine(  971): set frequency band 0
D/wpa_supplicant( 6087): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6087): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6087): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6087): SETBAND: 0
D/wpa_supplicant( 6087): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6087): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6087): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6087): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
,D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/WifiMonitor(  971): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
D/wpa_supplicant( 6087): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6087): P2P: Add operating class 81
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6087): P2P: Add operating class 115
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6087): P2P: Add operating class 116
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6087): P2P: Add operating class 117
D/wpa_supplicant( 6087): P2P: Channels - hexdump(len=2): 28 30
E/WifiMonitor(  971): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6087): P2P: Update channel list
E/WifiMonitor(  971): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6087): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
E/WifiMonitor(  971): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6087): P2P: cli_channels:
D/wpa_supplicant( 6087): p2p0: Updating hw mode
D/wpa_supplicant( 6087): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6087): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6087): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6087): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6087): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  971): did set frequency band 0
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6087): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  971): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
,D/wpa_supplicant( 6087): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6087): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6087): wlan0: Cancelling sched scan
D/wpa_supplicant( 6087): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6087): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6087): wpa_supplicant_scan enter
D/wpa_supplicant( 6087): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6087): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6087): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6087): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  971): done set frequency band 0
E/WifiTrafficPoller(  971): ADD_CLIENT: 9
D/WISPrService( 5390): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WifiStateMachine(  971): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  971): [MLHD] enter handleMediaLinkEvent DriverStartedState
,E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=147462
E/WifiStateMachine(  971): processMsg: DisconnectedState
E/WifiStateMachine(  971):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=130683  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  971): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  971): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  971): processMsg: ConnectModeState
E/WifiStateMachine(  971):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=130683  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  971): handleMessage: X
E/WifiStateMachine(  971): handleMessage: E msg.what=143371
E/WifiStateMachine(  971): processMsg: DisconnectedState
,E/WifiStateMachine(  971):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  971): processMsg: ConnectModeState
,E/WifiStateMachine(  971):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  971): processMsg: DriverStartedState
E/WifiStateMachine(  971):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  971): processMsg: SupplicantStartedState
,E/WifiStateMachine(  971):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  971): processMsg: DefaultState
E/WifiStateMachine(  971):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  971): handleMessage: X
,I/bt-btm  ( 6053): btm_reset_complete
,I/bt-btm  ( 6053): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 6053): Start reading local supported commands
,D/bt-btm  ( 6053): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 6053): BTM reads next extended features page (1)
,D/bt-btm  ( 6053): BTM reads next extended features page (2)
D/bt-btm  ( 6053): BTM reached last extended features page (2)
D/bt-btm  ( 6053): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,D/bt-btm  ( 6053): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 6053): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 6053): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 6053): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 6053): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 6053): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 6053): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6053): btm_read_ble_wl_size ,
,D/bt-btm  ( 6053): btm_read_white_list_size_complete 
D/bt-btm  ( 6053): btm_get_ble_buffer_size 
,D/bt-btm  ( 6053): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6053): btm_read_ble_local_supported_states 
D/bt-btm  ( 6053): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 6053): btm_read_ble_local_supported_features 
,D/bt-btm  ( 6053): btm_read_ble_local_supported_features_complete ,
D/bt-btm  ( 6053): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6053): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6053): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6053): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6053): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6053):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6053): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6053): BTM_SetInquiryMode
I/bt-btm  ( 6053): BTM_SetPageScanType
I/bt-btm  ( 6053): BTM_SetInquiryScanType
D/bt-btm  ( 6053): btm_decode_ext_features_page page: 1
,W/bt-btm  ( 6053): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6053): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6053): btm_decode_ext_features_page Secure conn Controller support Enabled
,D/bt-btm  ( 6053): BTM_BleLoadLocalKeys
D/bt-btm  ( 6053): BTM_BleLoadLocalKeys
I/bt-btm  ( 6053): BTM_Sec: application registered
E/bt-btm  ( 6053): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf6e74d5 
I/bt-btm  ( 6053): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6053): SMP_Register state=0
E/bt-btm  ( 6053): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf6e74d5 
,I/bt-btm  ( 6053): BTM_Sec: application registered
D/bt-btm  ( 6053): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6053): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6053): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6053): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6053): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6053): BTM_RegBusyLevelNotif
D/bt-btm  ( 6053): BTM_BleReadControllerFeatures
,I/bt-btm  ( 6053): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6053): GATT_Register
D/bt-att  ( 6053): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6053): allocated gatt_if=3
I/bt-att  ( 6053): GATT_StartIf gatt_if=3
D/bt-att  ( 6053): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6053): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 6053): btm_ble_vendor_capability_vsc_cmpl_cback,
D/bt-btm  ( 6053): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6053): BTM Register For VSEvents is successfully
D/bt-btm  ( 6053): BTM_BleGetVendorCapabilities
I/bt-btif ( 6053): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6053): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6053): bta_dm_set_dev_name: name: HTC One M8s 
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btm  ( 6053):  BTM_BleConfigPrivacy
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
,I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
,I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): Calling BTA_HhEnableettings: Settings: 0x0060.
E/bt-btif ( 6053): Calling BTA_HhEnable
I/bt-btif ( 6053): BTA_MceEnable
D/bt-btif ( 6053): AG evt (hdl 0x0001): State 0, Event 0x0500
,D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6053): BTM_AllocateSCN
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6053): BTM_AllocateSCN
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
,I/bt-btm  ( 6053): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6053):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6053):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6053): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6053): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6053):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6053):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0019
E/bt-btif ( 6053): btif_storage_]: id 37, is_orig 1, psm 0x0019, proto_id 7
I/bt-btm  ( 6053): btif_storage_]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btif ( 6053):                : sec: 0x2090roperties_cb
I/bt-btm  ( 6053):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6053):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6053): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
,I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
,I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6053): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6053):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6053):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:5
,I/bt-avp  ( 6053): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6053): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
D/BluetoothAdapterProperties( 6053): Address is:90:E7:C4:F6:69:77
D/bt-btif ( 6053):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6053): AVRC_AddRecord uuid: 110e
,I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btm  ( 6053): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6053):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6053):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6053): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6053):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6053): GATT_Register
D/bt-att  ( 6053): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6053): allocated gatt_if=4
I/bt-att  ( 6053): GATT_StartIf gatt_if=4
D/bt-att  ( 6053): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6053): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 6053): Scan Mode:21
D/BluetoothAdapterProperties( 6053): Discoverable Timeout:120
I/bt-btif ( 6053): BTA_JvEnable
I/bt-btif ( 6053): BTA_JvRegisterL2cCback
I/bt-btm  ( 6053): BTM_ReadConnectability
I/bt-btm  ( 6053): BTM_ReadDiscoverability
I/bt-btm  ( 6053): BTM_SetDiscoverability
I/bt-btm  ( 6053): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6053): disc_mode 0002
D/bt-btm  ( 6053): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6053): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6053): BTM_SetConnectability
I/bt-btm  ( 6053): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6053): disc_mode 0002
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6053): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6053): BTM_SetDiscoverability
I/bt-btm  ( 6053): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6053): disc_mode 0000
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6053): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6053): BTM_SetConnectability
I/bt-btm  ( 6053): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6053): disc_mode 0000
D/bt-btm  ( 6053): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6053): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
I/bt-btm  ( 6053): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6053): bta_pan_co_init
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6053): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6053):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6053):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btm  ( 6053): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6053):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6053): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6053):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
D/bt-smp  ( 6,053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 5b b9 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 67 f3 c7 7b 38 a8 66 24 8b ff aa fa 66 c0 ad 23 
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 6053): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6053): ScanMode =  21
D/BluetoothAdapterProperties( 6053): State =  11
D/BluetoothAdapterProperties( 6053): Setting state to 12
I/BluetoothAdapterState( 6053): Bluetooth adapter state changed: 11-> 12
D/bt-btif ( 6053): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6053): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6053): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6053): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6053): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothManagerService(  971): +onBluetoothStateChange prev=11 new=12
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
I/bt-btif ( 6053): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 0c 95 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = f6 7b 1d 92 80 c7 5d af 90 9c f0 39 51 41 ee 38 
D/BluetoothAdapterProperties( 6053): Discoverable Timeout:120
I/BluetoothAdapterState( 6053): Entering On State
E/bt_mct  ( 6053): hci lib postload completed
D/BluetoothManagerService(  971): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  971): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  971): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1475): onBluetoothStateChange: up=true
D/BluetoothHeadset(  971): onBluetoothStateChange: up=true
D/BluetoothA2dp(  971): onBluetoothStateChange: up=true,
D/BluetoothHeadset( 1475): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1475): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 09 2c 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 89 49 fc 09 d0 5f 77 88 27 e2 31 19 82 24 e5 7e 
,D/BluetoothManagerService(  971): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  971): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  971): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  971): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
,I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 2b 3e 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = f6 e5 79 19 fe 9b 84 8b 4c c6 17 2a e2 80 e0 9d 
D/NGFService( 3528): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3528): Bluetooth Adapter: ON
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 78 97 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 1d ac 18 bf 62 0f e6 fa d1 e1 e7 e3 f9 2e 90 f0 
V/BluetoothPbapReceiver( 6053): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6053): ***********state = 12
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
,I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 1d 9c 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 41 ac 4d a1 1a e4 d1 4a 7c e2 d7 ef 73 d6 97 bc 
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 00 b3 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = ac 59 07 55 9f 85 0f d8 72 3d 4a 32 f1 4d d8 48 
,D/PMS     (  971): acquireWL(11df1579): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5390 1000 null
,W/ContextImpl( 5390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = d5 57 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = c9 3d 37 11 e0 e7 5d 05 40 e7 96 bc ce 62 2a 2f 
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = b5 84 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 33 e3 0e 61 f3 c1 37 6a 65 c6 d4 39 ab 50 22 23 
,D/HtcBtWidget_BTWidgetProvider( 6090): onBTStateChanged() for widget: 
V/BluetoothPbapService( 6053): Pbap Service onCreate
V/BluetoothPbapService( 6053): Starting PBAP service
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6053): smp_encrypt_data
D/HtcBtWidget_BTWidgetProvider( 6090): updateWidget(context) for widget: 
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
D/PMS     (  971): releaseWL(11df1579): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = f7 8d 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/BluetoothAdapter( 6053): 735209698: getState(). Returning 12
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = d2 a9 80 9f d2 3f 1b 93 10 6c a8 03 24 4d 18 b5 
V/BluetoothPbapService( 6053): Handler(): got msg=1
V/BluetoothPbapService( 6053): Pbap Service startRfcommSocketListener
,D/wpa_supplicant( 6087): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/PMS     (  971): acquireWL(23d8af1f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5390 1000 null
D/Tethering(  971): interfaceLinkStateChanged p2p0, false
D/Tethering(  971): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  971): WiFiDisplay: getWifidisplayApEnabled=false
V/BluetoothPbapService( 6053): Pbap Service initSocket
,D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  971): java.lang.Throwable: stack dump
W/System.err(  971): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  971): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  971): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  971): 	at android.os.Binder.execTransact(Binder.java:454)
D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 73 a2 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = f4 b6 48 22 d6 03 65 b4 08 9f 4e fa e2 b6 13 a3 
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 39 0b 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = e3 a9 66 c8 64 40 2d d9 21 2f e3 a7 0d 3c 61 85 
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
I/bt-btm  ( 6053): BTM_SetDiscoverability
I/bt-btm  ( 6053): btm_ble_set_discoverability mode=0x0 combined_mode=0x0,
D/bt-btm  ( 6053): disc_mode 0000
I/bt-btm  ( 6053): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6053): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6053): BTA_JvCreateRecordByU
I/bt-btif ( 6053): BTA_JvCreateRecordByUser
,I/bt-btm  ( 6053): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6053): disc_mode 0000
D/bt-btm  ( 6053): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6053): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6053): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6053): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): BTA_JvRfcommStartServer
D/BluetoothAdapter( 1222): 319860267: getState(). Returning 12
I/bt-btm  ( 6053): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6053):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/BluetoothAdapterProperties( 6053): Scan Mode:21
D/BluetoothAdapter( 1222): 319860267: getState(). Returning 12
D/BluetoothAdapter( 5390): 195292764: getState(). Returning 12
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1222): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
V/BluetoothPbapService( 6053): Succeed to create listening socket 
V/BluetoothPbapService( 6053): Accepting socket connection...
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
,D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
D/BluetoothInputDevice( 5390): BluetoothInputDevice()
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = f2 a6 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = c0 e0 07 9b 64 83 a2 89 1b 10 ae 0f c0 c7 5f 9f 
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  971): registerStateChangeCallback+
,D/BluetoothPan( 5390): BluetoothPan()
D/BluetoothManagerService(  971): registerStateChangeCallback+
,D/BluetoothMap( 5390): Create BluetoothMap proxy object
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = f9 e2 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = b9 40 45 fb e1 13 48 f1 e0 cb 2c 94 ef 22 66 d7 
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  971): registerStateChangeCallback+
,E/BluetoothMap( 5390): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  971): registerStateChangeCallback+
D/BluetoothSap( 5390): BluetoothSap() call bindService
,W/ContextImpl( 5390): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5390): BluetoothPbap(),
,D/BluetoothManagerService(  971): registerStateChangeCallback+
,D/BluetoothManagerService(  971): registerStateChangeCallback+,
,D/BluetoothHeadset( 5390): BluetoothHeadset(),
D/BluetoothManagerService(  971): registerStateChangeCallback+
,D/LocalBluetoothProfileManager( 5390): LocalBluetoothProfileManager construction complete,
,D/DockEventReceiver( 5390): finishStartingService: stopping service,
D/BluetoothA2dp( 5390): Proxy object connected
V/BluetoothPbapService( 6053): Pbap Service onBind
D/A2dpProfile( 5390): Bluetooth service connected
,D/BluetoothAdapter( 5390): 195292764: getState(). Returning 12
,D/BluetoothHeadset( 5390): Proxy object connected
,D/HeadsetProfile( 5390): Bluetooth service connected
,D/BluetoothAdapter( 5390): 195292764: getState(). Returning 12
,D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothInputDevice( 5390): Proxy object connected
W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback,
I/bt-btif ( 6053): BTA_JvCreateRecordByUser
D/HidProfile( 5390): Bluetooth service connected
,D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): BTA_JvRfcommStartServer
I/bt-btm  ( 6053): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6053):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6053): Accept thread started.
,D/BluetoothAdapter( 5390): 195292764: getState(). Returning 12
,D/BluetoothPan( 5390): BluetoothPAN Proxy object connected
,D/PanProfile( 5390): Bluetooth service connected
D/BluetoothAdapter( 6053): 735209698: getState(). Returning 12
D/PMS     (  971): releaseWL(23d8af1f): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/BluetoothFtpService( 6053): ACTION_STATE_CHANGED: state: 12mHasStarted: true
,D/BluetoothMasReceiver( 6053): Bluetooth STATE CHANGED to 12
D/BluetoothPbap( 5390): Proxy object connected
D/BluetoothMasReceiver( 6053):  call MAP start service
D/PbapServerProfile( 5390): Bluetooth service connected
,D/BluetoothFtpService( 6053): htc sense version is 6.0
,D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6053): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): BTA_JvRfcommStartServer
,I/bt-btm  ( 6053): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6053):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6053): Run Accept thread
,E/BluetoothMasService( 6053): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 6053): Add permission for SmsProvider.,
V/BluetoothMasService( 6053): Starting MAS instances
D/BluetoothAdapter( 6053): 735209698: getState(). Returning 12
,I/MailMessageReceiver( 6053): reg:com.android.bluetooth.btservice.AdapterApp@27e33eeb with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@daf9448
,I/MailManager( 6053): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@daf9448
V/EmailUtils( 6053): Manager Instance is not NULL
,I/ActivityManager(  971): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6182 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,I/art     (  971): Explicit concurrent mark sweep GC freed 32828(1749KB) AllocSpace objects, 4(644KB) LOS objects, 33% free, 16MB/24MB, paused 1.339ms total 183.841ms,
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bfce81e:true
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  971): Registered receivers: 7
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  971): Registered receivers: 8
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  971): Registered receivers: 9
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  971): Registered receivers: 10
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  971): Registered receivers: 11
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  971): Registered receivers: 12
D/BluetoothManagerService(  971): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  971): Registered receivers: 13
,D/HtcAdjCursorFactory( 6182): Set CursorWindow size to: 4194304 KB, Tid: 6203,
,D/EmailUtils( 6053): ============NULL aList========,
V/EmailUtils( 6053): <-getEmailAccountIdList
V/BluetoothMasService( 6053): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 6053): 735209698: getState(). Returning 12,
,V/BluetoothMasService( 6053): parseIntent 1: mIsEmailEnabled: true,
,V/EmailUtils( 6053): Manager Instance is not NULL
,D/EmailUtils( 6053): ============NULL aList========
,V/EmailUtils( 6053): <-getEmailAccountIdList
,V/BluetoothSapReceiver( 6053): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6053): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6053):  Bluetooth Adapter state = 12
,V/BluetoothSapReceiver( 6053): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6053): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 6053): BluetoothMns: isEmailEnabled: true,
,D/AuthorizationBluetoothService( 1865): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback,
I/bt-btif ( 6053): BTA_JvCreateRecordByUser
D/bt-btm  ( 6053): BTM_AllocateSCN
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): BTA_JvRfcommStartServer
I/bt-btm  ( 6053): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6053):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback,
,I/bt-btif ( 6053): BTA_JvCreateRecordByUser,
D/bt-btm  ( 6053): BTM_AllocateSCN
D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): BTA_JvRfcommStartServer
I/bt-btm  ( 6053): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6053):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  971): killProcessQuiet, pid=5704
I/ActivityManager(  971): Killing 5704:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,D/wpa_supplicant( 6087): EAPOL: disable timer tick,
,I/ActivityManager(  971): Recipient 5704
,V/BluetoothSapService( 6053): Sap Service onCreate,
V/BluetoothSapService( 6053): initBinder
,V/BluetoothSapService( 6053): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@2c34dec7,
,V/BluetoothSapService( 6053): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@b7d2c1d,
,V/BluetoothSapService( 6053): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6053): state: 12
,D/SapServerProfile( 5390): Bluetooth service connected
,V/BluetoothSapService( 6053): Starting SAP server process,
,D/A2dpService( 6053): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@3b16a063
D/A2dpSinkService( 6053): getA2dpSinkService(): service is NULL
,V/BluetoothSapService( 6053): SAP Service startRfcommListenerThread,
V/BluetoothSapService( 6053): Sap Service initRfcommSocket,
D/BluetoothManagerService(  971): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6053): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6053): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6053): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6053): Write Extended Inquiry Response to controller
I/bt-btif ( 6053): BTA_JvRfcommStartServer
,I/bt-btm  ( 6053): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6053):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothSapService( 6053): Succeed to create listening socket 
V/BluetoothSapService( 6053): Accepting socket connection...
,D/wpa_supplicant( 6087): EAPOL: disable timer tick,
,D/BluetoothAdapter( 5999): 61803511: getState(). Returning 12
,I/jxcore-log( 5999): BLE supported!!
I/jxcore-log( 5999): 
,D/PMS     (  971): releaseWL(23ed7172): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  971): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  971): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  971): acquireWL(365e09cd): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{10024}
V/AlarmManager(  971): sending alarm PendingIntent{2e94d282: PendingIntentRecord{d6d93 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143032, Int=0,
,V/AlarmManager(  971): sending alarm PendingIntent{20bad5d2: PendingIntentRecord{f1f36a3 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=149181, Int=0
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  971): releaseWL(365e09cd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  971): [NET] android_getaddrinfofornet-, err=8
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  971): [NET] android_getaddrinfo_proxy+
D/libc    (  971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  971): [NET] android_getaddrinfo_proxy-, NODATA
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  971): acquireWL(2fcca1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  971): n_update end
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/PMS     (  971): releaseWL(2fcca1d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): handleMessage: E msg.what=155652
I/HtcPowerSaver(  971): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  971): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1475): switchBindHtcMsgCursor: null
,D/PMS     (  971): acquireWL(2a4e75c9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000},
V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177562, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{dc194ce: PendingIntentRecord{2c789a9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=160184, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{3c174fef: PendingIntentRecord{22357720 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185546, Int=0
,D/PMS     (  971): acquireWL(32220afc): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1865): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1865): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1865): [NET] android_getaddrinfo_proxy+
D/libc    ( 1865): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1865): [NET] android_getaddrinfo_proxy-, NODATA,
D/PMS     (  971): acquireWL(32bfa585): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(32220afc): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(32bfa585): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(2a4e75c9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  971): acquireWL(9e62fda): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{20bad5d2: PendingIntentRecord{f1f36a3 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=209195, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{3632fc0b: PendingIntentRecord{1802dae8 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=209714, Int=0
,D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/PMS     (  971): releaseWL(9e62fda): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  971): [NET] android_getaddrinfofornet-, err=8
D/libc    (  971): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  971): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  971): [NET] android_getaddrinfo_proxy+
D/libc    (  971): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    (  971): [NET] android_getaddrinfo_proxy-, NODATA
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcAppUPService( 1443): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@2066568d
D/Process (  971): killProcessQuiet, pid=5484
I/ActivityManager(  971): Killing 5484:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,I/ActivityManager(  971): Recipient 5484
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  971): acquireWL(f5a1501): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end,
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): releaseWL(f5a1501): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  971): updateBatteryInfo
,D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100,
,D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): handleMessage: E msg.what=155652
I/HtcPowerSaver(  971): >> updateStatus
,D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DefaultState
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  971): acquireWL(3b876fa6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(3b876fa6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  971): updateBatteryInfo
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): Checking...
I/HtcPowerSaver(  971): >> updateStatus
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
,D/WifiController(  971): handleMessage: E msg.what=155652
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  971): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  971): processMsg: DeviceActiveState
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/WifiController(  971): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  971): acquireWL(1d134de7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
,V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237562, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{2a9ebd94: PendingIntentRecord{2c789a9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=316712, Int=0
,D/PMS     (  971): acquireWL(2caae032): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  971): sending alarm PendingIntent{2dbce183: PendingIntentRecord{34741f00 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450100564215, Int=0
D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1865): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1865): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1865): [NET] android_getaddrinfo_proxy+
D/libc    ( 1865): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1865): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): releaseWL(2caae032): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  971): releaseWL(1d134de7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  971): acquireWL(30e36339): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
,D/PMS     (  971): releaseWL(30e36339): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): runPSCheck
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  971): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1865): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1865): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1865): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1865): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
W/GLSActivity( 1865): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1865): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1865): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1865): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5414): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5414): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5414): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5414): Ignoring header User-Agent because its value was null.
,D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5414): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5414): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5414): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5414): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5414): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PMS     (  971): acquireWL(38e93173): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(38e93173): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): updateBatteryInfo
D/WifiController(  971): handleMessage: E msg.what=155652
,D/PMS     (  971): runPSCheck
D/WifiController(  971): processMsg: DeviceActiveState
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: StaEnabledState
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  971): handleMessage: X
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  971): acquireWL(3a4d4830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(3a4d4830): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  971): updateBatteryInfo
,D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  971): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/WifiController(  971): battery changed pluggedType: 2
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  426): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  971): acquireWL(24068ca9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=357562, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{95b922e: PendingIntentRecord{2c789a9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=604078, Int=0
D/PMS     (  971): acquireWL(201b71cf): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1865): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1865): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 1865): [NET] android_getaddrinfo_proxy+
D/libc    ( 1865): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1865): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): releaseWL(201b71cf): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,D/WeatherUtility( 1222): Weather sync is On
D/PMS     (  971): releaseWL(24068ca9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1475): MSG_CHECK_DELETION >>
D/ContactMessageStore( 1475): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1475): sku_id=118,
D/ContactMessageStore( 1475): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1475): start background delete task...
,D/ContactMessageStore( 1475): size: 0 , 0
,D/ContactMessageStore( 1475): Background delete complete
,D/PMS     (  971): acquireWL(1d76b75c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(1d76b75c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
,D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: StaEnabledState
D/HtcPowerSaver(  971): updateBatteryInfo
D/WifiController(  971): processMsg: DefaultState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): handleMessage: X
D/PMS     (  971): runPSCheck
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  971): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1865): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1865): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1865): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1865): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1865): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1865): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1865): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1865): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5414): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5414): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5414): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5414): Ignoring header User-Agent because its value was null.
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5414): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5414): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5414): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5414): [NET] android_getaddrinfo_proxy get netid:0
,I/RemoteViews( 1222): reapply : com.google.android.gms 6 40
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/libc    ( 5414): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): acquireWL(1466e2de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
,I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(1466e2de): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo,
D/UsbnetService(  971): BroadcastReceiver::onReceive+
,D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
,D/PMS     (  971): runPSCheck
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): << updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(1ea26cbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(1ea26cbf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo,
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true,
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  971): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
,D/WifiController(  971): handleMessage: E msg.what=155652
,D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1865): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1865): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1865): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1865): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1865): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1865): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1865): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1865): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5414): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5414): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5414): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
W/System  ( 5414): Ignoring header User-Agent because its value was null.
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5414): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5414): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5414): [NET] android_getaddrinfo_proxy+
D/libc    ( 5414): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
D/libc    ( 5414): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): acquireWL(17d39389): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
,V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=657562, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{ffbf8e: PendingIntentRecord{f1603af com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450101235826, Int=0
,D/SmartSyncUtils( 5894): isEpsOn(), nState = 0,
,D/PMS     (  971): releaseWL(17d39389): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  971): acquireWL(29d913bc): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5894 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5894): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5894): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5894): AlarmOnTime = -1,
D/SmartSyncScreenOnOffTimeReceiver( 5894): SettingOnTime = 1450159200000, randomSettingOnTime = 1450157408000
,D/SmartSyncScreenOnOffTimeReceiver( 5894): SettingOffTime = 1450137600000, randomSettingOffTime = 1450138642000
D/SmartSyncScreenOnOffTimeReceiver( 5894): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5894): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5894): bNightModeTurnOffOnce = false
,D/PMS     (  971): releaseWL(29d913bc): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  971): acquireWL(34d8df45): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/BatteryService(  971): n_update end
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): releaseWL(34d8df45): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): handleMessage: E msg.what=155652
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(8bc469a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1017562, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{ac92bcb: PendingIntentRecord{d01afa8 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1030658, Int=0,
,I/bt-btm  ( 6053): Received oneshot timer event complete,
D/PMS     (  971): acquireWL(112d2ac1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6053 1002 null
I/bt-btm  ( 6053): btm_ble_timeout
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = 3c be 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = 40 0c 97 88 a8 7d 72 b7 e4 0b 93 ff 9e 59 b6 61 ,
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  971): releaseWL(8bc469a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  971): releaseWL(112d2ac1): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  971): acquireWL(25883266): PARTIAL_WAKE_LOCK  *alarm* 0x1 971 1000 WorkSource{1000}
V/AlarmManager(  971): sending alarm PendingIntent{359c1234: PendingIntentRecord{2937c85d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=809183, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1077562, Int=0
V/AlarmManager(  971): sending alarm PendingIntent{1b3cb9a7: PendingIntentRecord{17961e54 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450101241865, Int=1800000
,V/AlarmManager(  971): sending alarm PendingIntent{1120b1fd: PendingIntentRecord{2c789a9d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1128648, Int=0
,D/PMS     (  971): acquireWL(27d50ef2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4251 10024 WorkSource{10024 com.google.android.gms},
,I/ActivityManager(  971): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6233 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  971): sending alarm PendingIntent{21714943: PendingIntentRecord{2e60cbc0 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450101048658, Int=0
,V/AlarmManager(  971): sending alarm PendingIntent{13cb70f9: PendingIntentRecord{ccc7c86 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450101184169, Int=0
,D/PMS     (  971): acquireWL(3d5369f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1865 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
D/libc    ( 1865): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1865): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1865): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1865): [NET] android_getaddrinfo_proxy+
D/libc    ( 1865): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/PMS     (  971): acquireWL(3666e3ec): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4251 10024 WorkSource{10024 com.google.android.gms}
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/PMS     (  971): releaseWL(27d50ef2): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1865): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  971): releaseWL(3d5369f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  971): releaseWL(25883266): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 5894): MY_DEBUG = false
,D/PowerUsageService( 5894): repeat time = 1450102251186
,I/EventLogService( 4251): Aggregate from 1450099441826 (log), 1450099441826 (data)
,I/PowerUsageList:PowerUsageHelper( 5894): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PMS     (  971): releaseWL(3666e3ec): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
D/PowerUsageList:BatterySipperExt( 5894): gen(), null == sipper.uidObj, userId = 0
,E/cutils-trace( 6258): Error opening trace file: Permission denied (13),
I/dex2oat ( 6258): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6258): dex2oat: override thread count:4
,I/dex2oat ( 6258): dex2oat took 863.222ms (threads: 4),
,I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6233): ApplicationMonitor {242894cd}: logBasicAppInfo(): BuildConfig.DEBUG:       false,
,I/PushClient( 6233): PnsModel {1f378a64}: update(): Update registration caused by: alarm
,I/PushClient( 6233): PnsConfigModel {aa15f0b}: <init>(): Use dm-client for provisioning.
,W/System.err( 6233): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6233): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6233): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6233): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  971): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6265 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6265): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6265 dbg=false s=true
,I/DeviceManagement( 6265): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
,I/DeviceManagement( 6265): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6265): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6265): WorkflowService: Starting workflow service,
,I/DeviceManagement( 6265): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3af0bf7] args=[Bundle[mParcelledData.dataSize=88]],
I/DeviceManagement( 6265): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6265): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6265): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6265): SessionStateController: Checking invariants...
,I/DeviceManagement( 6265): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 6265): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6265): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6265): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@3af0bf7],
,I/DeviceManagement( 6265): WorkflowService: Stopping workflow service,
,D/Process (  971): killProcessQuiet, pid=4512
I/ActivityManager(  971): Killing 4512:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 4512
,D/WifiService(  971): Client connection lost with reason: 4
,I/PushClient( 6233): PnsModel {1f378a64}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  971): killProcessQuiet, pid=5594
I/ActivityManager(  971): Killing 5594:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  971): Recipient 5594,
,D/PMS     (  971): acquireWL(c4b6425): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/BatteryService(  971): n_update end
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): releaseWL(c4b6425): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  971): updateBatteryInfo
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/PMS     (  971): runPSCheck
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  971): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(e3b19fa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  971): n_update end
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  971): releaseWL(e3b19fa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  971): Checking...
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  971): User[0] Flushing usage stats to disk
,D/PMS     (  971): acquireWL(22706bab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
,I/BatteryService(  971): n_update end
,D/PMS     (  971): releaseWL(22706bab): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  971): BroadcastReceiver::onReceive+,
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
,D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PMS     (  971): runPSCheck
D/WifiController(  971): handleMessage: E msg.what=155652
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: DeviceActiveState
I/HtcPowerSaver(  971): >> updateStatus
,D/WifiController(  971): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1865): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1865): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1865): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1865): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1865): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1865): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1865): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1865): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5414): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5414): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5414): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5414): Ignoring header User-Agent because its value was null.
,D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5414): [NET] android_getaddrinfofornet-, err=8
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
D/libc    ( 5414): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5414): [NET] android_getaddrinfo_proxy+
D/libc    ( 5414): [NET] android_getaddrinfo_proxy get netid:0
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5414): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  971): acquireWL(28d6a095): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
,D/PMS     (  971): releaseWL(28d6a095): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): handleMessage: E msg.what=155652
D/PMS     (  971): runPSCheck
D/WifiController(  971): processMsg: DeviceActiveState
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: StaEnabledState
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(108df5aa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(108df5aa): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo,
,D/PMS     (  971): runPSCheck,
D/HtcPowerSaver(  971): Checking...
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  971): >> updateStatus
,D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  971): << updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): handleMessage: E msg.what=155652
,D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  971): acquireWL(38c7959b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
,I/BatteryService(  971): n_update end
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): releaseWL(38c7959b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  971): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  971): updateBatteryInfo
,D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
,D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1865): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1865): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1865): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1865): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1865): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1865): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1865): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1865): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5414): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5414): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5414): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5414): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5414): Ignoring header User-Agent because its value was null.,
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5414): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5414): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5414): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5414): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5414): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  971): Explicit concurrent mark sweep GC freed 25194(1355KB) AllocSpace objects, 12(936KB) LOS objects, 33% free, 16MB/24MB, paused 2.617ms total 192.081ms
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
,D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  971): acquireWL(fa1d905): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
D/UsbnetService(  971): BroadcastReceiver::onReceive+
I/BatteryService(  971): n_update end
,D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/PMS     (  971): releaseWL(fa1d905): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  971): processMsg: DeviceActiveState
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: StaEnabledState
D/HtcPowerSaver(  971): updateBatteryInfo
D/WifiController(  971): processMsg: DefaultState
D/PMS     (  971): runPSCheck
D/WifiController(  971): handleMessage: X
D/HtcPowerSaver(  971): Checking...
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  971): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  971): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(16e71d5a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(16e71d5a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo,
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  971): Checking...
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6053): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 6053): Disconnected process message: 11, size: 0
,D/PowerUI ( 1222): closing low battery warning: level=98
D/DotMatrix( 1306): [EventService] reorderNotification, total:1
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/HtcPowerSaver(  971): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,W/ContextImpl( 5894): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5390): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5390): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5390): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5390): Cust_ConnectToPC   : spcsc>false
D/        ( 5390): Cust_ConnectToPC   : IPT>true
D/        ( 5390): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5390): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5390): Index of the first 1 = -1
,W/ContextImpl( 5390): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5390): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5390): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5390): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5390): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true,
,D/SmartNS_Utility( 5390): [ACC]android_networking:tethering_guard_support=false
,W/SystemReader( 5390): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/PMS     (  971): acquireWL(7434468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
D/UsbnetService(  971): BroadcastReceiver::onReceive+
I/BatteryService(  971): n_update end
D/UsbnetService(  971): onReceive BATTERY_CHANGED
,D/PMS     (  971): releaseWL(7434468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  971): updateBatteryInfo
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/NotificationService(  971): plugged=true pluggin=true
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): battery changed pluggedType: 2
,D/WifiController(  971): processMsg: DeviceActiveState
D/PMS     (  971): runPSCheck
D/WifiController(  971): processMsg: StaEnabledState
D/HtcPowerSaver(  971): Checking...
D/WifiController(  971): processMsg: DefaultState
I/HtcPowerSaver(  971): >> updateStatus
D/WifiController(  971): handleMessage: X
D/PowerUI ( 1222): closing low battery warning: level=98
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  971): updateStatus (8000,98,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  971): << updateStatus
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true
,E/PNP_UPDATERD(  388): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  971): acquireWL(26ec0081): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null,
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(26ec0081): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=98
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): Checking...
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/WifiController(  971): battery changed pluggedType: 2
D/WifiController(  971): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
,D/WifiController(  971): handleMessage: X
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true
,I/ProcessStatsService(  971): Prepared write state in 16ms,
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1865): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1865): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1865): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1865): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1865): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1865): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1865): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1865): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1865): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1865): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5414): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5414): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5414): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5414): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5414): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5414): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5414): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5414): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5414): [NET] android_getaddrinfo_proxy+
D/libc    ( 5414): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  395): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  395): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  395): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  395): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5414): [NET] android_getaddrinfo_proxy-, NODATA
,I/ProcessStatsService(  971): Pruning old procstats: /data/system/procstats/state-2015-12-13-12-16-27.bin,
,D/PMS     (  971): acquireWL(3d049798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 971 1000 null
I/BatteryService(  971): n_update end
D/PMS     (  971): releaseWL(3d049798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  971): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  971): plugged=true pluggin=true
D/UsbnetService(  971): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=99
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  971): runPSCheck
D/UsbnetService(  971): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  971): Checking...
D/HeadsetStateMachine( 6053): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  971): >> updateStatus
D/UsbnetService(  971):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  971): battery changed pluggedType: 2
D/UsbnetService(  971): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  971): handleMessage: E msg.what=155652
D/WifiController(  971): processMsg: DeviceActiveState
D/WifiController(  971): processMsg: StaEnabledState
D/WifiController(  971): processMsg: DefaultState
D/WifiController(  971): handleMessage: X
I/HtcPowerSaver(  971): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  971): << updateStatus
,I/BatteryController( 1222): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  971): acquireWL(38b50bf1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 971 1000 WorkSource{1000},
,V/AlarmManager(  971): sending alarm PendingIntent{2145e2ea: PendingIntentRecord{20e119db android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1137562, Int=0
,D/Process (  971): killProcessQuiet, pid=6124
V/AlarmManager(  971): sending alarm PendingIntent{3c1fb3d6: PendingIntentRecord{2fcef657 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1930670, Int=0
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
I/ActivityManager(  971): Killing 6124:com.htc.widget.hmsproc2/u0a40 (adj 13): empty for 1800s
I/bt-btm  ( 6053): Received oneshot timer event complete
I/bt-btm  ( 6053): btm_ble_timeout
I/bt-btm  ( 6053): btm_gen_resolvable_private_addr
,D/PMS     (  971): acquireWL(8779544): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6053 1002 null
,D/bt-btm  ( 6053): btm_ble_rand_enc_complete
I/bt-btm  ( 6053): btm_gen_resolve_paddr_low
,D/bt-smp  ( 6053): smp_encrypt_data
W/bt-smp  ( 6053): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6053): Plain text(LSB ~ MSB) = bd 55 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6053): Encrypted text(LSB ~ MSB) = a0 7b 79 87 5c 2e 53 7a 46 a7 64 31 ad bd e0 29 
I/bt-btm  ( 6053): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6053): Stopping oneshot timer
D/bt-btm  ( 6053): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  971): Recipient 6124,
,I/ActivityManager(  971): Killing 5951:com.htc.calendar/u0a10 (adj 13): empty for 1816s,
D/Process (  971): killProcessQuiet, pid=5951
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 5951
,D/Process (  971): killProcessQuiet, pid=5927
I/ActivityManager(  971): Killing 5927:com.htc.mobiledata/u0a46 (adj 13): empty for 1817s
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 5927
,D/Process (  971): killProcessQuiet, pid=5864
I/ActivityManager(  971): Killing 5864:com.htc.bgp/u0a11 (adj 13): empty for 1817s
D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 5864
,D/Process (  971): killProcessQuiet, pid=5841
I/ActivityManager(  971): Killing 5841:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1823s
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 5841
,D/Process (  971): killProcessQuiet, pid=5414
I/ActivityManager(  971): Killing 5414:com.android.vending/u0a72 (adj 15): empty for 1827s
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 5414
,D/Process (  971): killProcessQuiet, pid=5789
I/ActivityManager(  971): Killing 5789:com.htc.sense.mms/u0a64 (adj 15): empty for 1833s
,D/Process (  971): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  971): Recipient 5789
,D/PMS     (  971): releaseWL(38b50bf1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  971): releaseWL(8779544): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,TIME-OUT KILL (timeout was 1800000ms)
```
