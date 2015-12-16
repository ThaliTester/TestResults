#### Test 50650278dbf8a2a_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  960): acquireWL(3c2f3469): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=119362, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{34477eee: PendingIntentRecord{2531bf8f android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1450226404329, Int=0
D/PMS     (  960): acquireWL(3626521c): PARTIAL_WAKE_LOCK  *backup* 0x1 960 1000 null
W/BackupManagerService(  960): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  960): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  960): releaseWL(3626521c): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  960): releaseWL(3c2f3469): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1254): Weather sync is On
W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
E/cutils-trace( 6057): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6057): ====startRecUseTime====
D/htc.customization.log.level( 6057):  is 
W/CustomizationLogLevel( 6057): Level value is invalid, use default level 2
D/CustomizationManager( 6057):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6057): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6057): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6057): Parsing tag category name = system
I/CustomizationCIDLoader( 6057): Parsing tag category name = application
I/CustomizationCIDLoader( 6057): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6057): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6057): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6057): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6057): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6057): add string-array item, value = 42507
I/CustomizationCIDLoader( 6057): add string-array item, value = 21902
I/CustomizationCIDLoader( 6057): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6057): add string-array item, value = 23420
I/CustomizationCIDLoader( 6057): add string-array item, value = 22299
I/CustomizationCIDLoader( 6057): add string-array item, value = 24002
I/CustomizationCIDLoader( 6057): add string-array item, value = 23210
I/CustomizationCIDLoader( 6057): add string-array item, value = 23205
I/CustomizationCIDLoader( 6057): add string-array item, value = 23806
I/CustomizationCIDLoader( 6057): add string-array item, value = 23430
I/CustomizationCIDLoader( 6057): add string-array item, value = 23408
I/CustomizationCIDLoader( 6057): add string-array item, value = 27205
I/CustomizationCIDLoader( 6057): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6057): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6057):  Read CID file spent 0.106 (s)
D/CustomizationManager( 6057):  All configurations done spent 0.106 (s)
D/PMS     (  960): acquireHCC(18fdae25): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 960 1000 null
I/ActivityManager(  960): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6057 on display 0
D/PMS     (  960): acquireHCC(4b09bfa): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 960 1000 null
W/asset   (  960): Copying FileAsset 0x55a39486b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  960): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6075 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1340): [EventService]  onDisplayChanged: 0
V/ActivityManager(  960): Display changed displayId=0
D/DotMatrix( 1340): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6075): Copying FileAsset 0xac919620 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1588): [trimMemory] 20
I/WebViewFactory( 6075): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/Process (  960): killProcessQuiet, pid=5150
I/ActivityManager(  960): Killing 5150:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/LibraryLoader( 6075): Time to load native libraries: 9 ms (timestamps 4507-4516)
I/LibraryLoader( 6075): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6075): Binding Chromium to main looper Looper (main, tid 1) {38106852}
I/LibraryLoader( 6075): Expected native library version number "",actual native library version number ""
I/chromium( 6075): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6075): Initializing chromium process, singleProcess=true
W/art     ( 6075): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6075): ApplicationContext is null in ApplicationStatus
W/chromium( 6075): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 6075): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/ActivityManager(  960): Recipient 5150
E/libEGL  ( 6075): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6075): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6075): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6075): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6075): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6075): Local Branch: 
I/Adreno-EGL( 6075): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6075): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6075):                  d74aa161a12b9c6fc6332151
W/System.err(  960): java.lang.Throwable: stack dump
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fc0c8b4:true
D/BluetoothAdapter( 6075): 121905625: getState() :  mService = null. Returning STATE_OFF
W/art     ( 6075): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6075): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6075): CordovaWebView is running on device made by: HTC
W/art     ( 6075): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6075): Attempt to remove local handle scope entry from IRT, ignoring
W/HtcSystemUPManager(  960): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/ActivityManager(  960): Activity pause timeout for ActivityRecord{2c14c5ab u0 com.test.thalitest/.MainActivity t8}
W/chromium( 6075): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/StatusBarManagerService(  960): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
D/StatusBarManagerService(  960): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  960): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  960): hiding MENU key
D/FindExtension( 6075): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/InputMethodManager( 6075): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@37ab067c, mServedView=org.apache.cordova.engine.SystemWebView{fb3bb05 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1d60575a
I/PhoneStatusBar( 1254): setImeWindowStatus(false,false)
I/InputMethodManagerService(  960): Disable input method client, pid=1588
D/StatusBarManagerService(  960): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6075): reportFullscreenMode on inactive InputConnection
I/ActivityManager(  960): Displayed com.test.thalitest/.MainActivity: +679ms (total +722ms)
W/BindingManager( 6075): Cannot call determinedVisibility() - never saw a connection for the pid: 6075
D/JsMessageQueue( 6075): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6075): JniHelper::setJavaVM(0xab7ad8f8), pthread_self() = -1398004536
D/JX-Cordova( 6075): jxcore cordova android initializing
,W/jxcore-log( 6075): Initializing JXcore engine
W/jxcore-log( 6075): JXcore engine is ready
,W/jxcore-log( 6075): Starting JXcore engine
,W/jxcore-log( 6075): Platform android,
W/jxcore-log( 6075): 
W/jxcore-log( 6075): Process ARCH arm
W/jxcore-log( 6075): 
,D/PMS     (  960): releaseHCC(18fdae25): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  960): releaseHCC(4b09bfa): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6075): JXcore Cordova bridge is ready!
I/jxcore-log( 6075): 
,W/jxcore-log( 6075): JXcore engine is started
,I/Choreographer( 6075): Skipped 95 frames!  The application may be doing too much work on its main thread.,
I/chromium( 6075): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6075): Toggling radios to true,
I/jxcore-log( 6075): 
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  960): checking for enable restriction...
D/BluetoothManagerService(  960): checkBTEasState, ret=true
I/BluetoothManagerService(  960): isBluetoothRestricted(): false
D/BluetoothManagerService(  960): enable(): region ID = 6
D/BluetoothManagerService(  960): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  960): MONITOR_LOG
W/Settings:Agent(  960): name: bluetooth_on
W/Settings:Agent(  960): value: 1
W/Settings:Agent(  960): >> traceCallingStack()
W/Settings:Agent(  960): Process.myPid(): 960
W/Settings:Agent(  960): Process.myTid(): 1193
W/Settings:Agent(  960): Process.myUid(): 1000
W/Settings:Agent(  960): 
W/Settings:Agent(  960): 
W/System.err(  960): java.lang.Throwable: stack dump
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  960): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  960): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  960): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  960): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  960): 
W/Settings:Agent(  960): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  960): Message: MESSAGE_ENABLE,
D/BluetoothManagerService(  960): MESSAGE_ENABLE: mBluetooth = null
,E/WifiTrafficPoller(  960): ADD_CLIENT: 7,
D/WifiService(  960): New client listening to asynchronous messages
D/WifiManager( 6075): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  960): setWifiEnabled: true pid=6075, uid=10366
W/Settings:Agent(  960): MONITOR_LOG
,E/WifiService(  960): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  960): name: wifi_on
,I/WifiService(  960): isSprintWifiRestricted(): false
W/Settings:Agent(  960): value: 2
I/WifiService(  960): isMdmWifiRestricted(): false
W/Settings:Agent(  960): >> traceCallingStack()
W/Settings:Agent(  960): Process.myPid(): 960
W/Settings:Agent(  960): Process.myTid(): 1576
W/Settings:Agent(  960): Process.myUid(): 1000
W/Settings:Agent(  960): 
W/Settings:Agent(  960): 
W/System.err(  960): java.lang.Throwable: stack dump
,W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  960): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64),
,W/System.err(  960): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  960): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  960): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  960): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
,W/System.err(  960): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  960): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
,W/System.err(  960): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  960): 
W/Settings:Agent(  960): << traceCallingStack(): 11(ms)
,I/ActivityManager(  960): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6129 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiController(  960): handleMessage: E msg.what=155656,
D/WifiController(  960): processMsg: ApStaDisabledState
D/WifiController(  960): transitionTo: destState=DeviceActiveState
,D/WifiController(  960): handleMessage: new destination call exit/enter
D/WifiManager( 6075): disconnect: Base Package Name=com.test.thalitest, uid=10366
,D/PMS     (  960): acquireWL(3f2e5726): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 960 1000 null
D/WifiController(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  960): invokeExitMethods: ApStaDisabledState
D/WifiController(  960): moveTempStackToStateStack: i=1,j=1
D/WifiController(  960): moveTempStackToStateStack: i=0,j=2
D/WifiController(  960): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  960): invokeEnterMethods: StaEnabledState
D/WifiController(  960): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  960): handleMessage: E msg.what=131083
E/WifiStateMachine(  960): setting operational mode to 1
E/WifiStateMachine(  960): processMsg: InitialState
D/WifiController(  960): handleMessage: X
E/WifiStateMachine(  960):  InitialState CMD_START_SUPPLICANT 0 0
D/WifiManager( 6075): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 6075): Radios toggled
I/jxcore-log( 6075): 
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/jxcore-log( 6075): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6075): 
,I/jxcore-log( 6075): Perf Test app loaded loaded
I/jxcore-log( 6075): 
,I/art     (  407): Explicit concurrent mark sweep GC freed 8670(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 410us total 49.572ms
,I/jxcore-log( 6075): check test folder
I/jxcore-log( 6075): 
,I/jxcore-log( 6075): found test : ./testFindPeers.js
I/jxcore-log( 6075): 
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 352us total 28.321ms,
,W/ResourcesManager( 6129): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/art     (  407): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 304us total 19.957ms,
,I/jxcore-log( 6075): found test : ./testSendData.js,
I/jxcore-log( 6075): 
,D/AdapterServiceConfig( 6129): Adding HeadsetService,
,D/AdapterServiceConfig( 6129): Adding A2dpService,
,D/AdapterServiceConfig( 6129): Adding HidService
D/AdapterServiceConfig( 6129): Adding HealthService,
I/chromium( 6075): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/AdapterServiceConfig( 6129): Adding PanService
,D/AdapterServiceConfig( 6129): Adding GattService
,W/linker  ( 6129): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  960): java.lang.Throwable: stack dump,
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
,D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2855adbd:true
D/BluetoothAdapterState( 6129): make
,I/BluetoothAdapterState( 6129): Entering OffState
,E/bt_osi_config( 6129): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,D/BluetoothAdapterProperties( 6129): Address is:90:E7:C4:F6:69:77,
D/BluetoothManagerService(  960): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  960): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  960): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  960): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapter( 1837): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2027665c
D/BluetoothAdapter( 1837): onBluetoothServiceUp done
,D/BluetoothAdapter( 1553): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@a90a134
D/BluetoothAdapter( 1553): onBluetoothServiceUp done
,D/Tethering(  960): interfaceAdded wlan0
D/PMS     (  960): releaseWL(3f2e5726): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 6129): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@287c827f
D/BluetoothAdapter( 6129): onBluetoothServiceUp done
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  960): [NET] android_getaddrinfofornet-, SUCCESS
D/BluetoothAdapter( 2412): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@249461ee
,D/BluetoothAdapter( 2412): onBluetoothServiceUp done
,D/BluetoothAdapter( 1527): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4f476da
D/BluetoothAdapter( 1527): onBluetoothServiceUp done
D/Tethering(  960): interfaceLinkStateChanged wlan0, false
D/Tethering(  960): interfaceStatusChanged wlan0, false
,E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): interfaceAdded p2p0
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false,
D/BluetoothAdapter(  960): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@202bd77b
,D/Tethering(  960): p2p0 is not a tetherable iface, ignoring
D/Tethering(  960): interfaceLinkStateChanged p2p0, false
D/BluetoothAdapter(  960): onBluetoothServiceUp done
D/Tethering(  960): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothAdapter( 1254): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@14c85684
D/BluetoothAdapter( 1254): onBluetoothServiceUp done
,D/BluetoothAdapter( 6075): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@30899ff
D/BluetoothAdapter( 6075): onBluetoothServiceUp done
,D/BluetoothAdapter( 3472): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@33e43349
D/BluetoothAdapter( 3472): onBluetoothServiceUp done,
D/BluetoothManagerService(  960): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6129): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
V/Tethering(  960): TetherInterfaceSM: wlan0: enter InitialState
D/BluetoothAdapterProperties( 6129): Setting state to 11
D/PMS     (  960): acquireWL(32746998): PARTIAL_WAKE_LOCK  NetworkStats 0x1 960 1000 null
I/BluetoothAdapterState( 6129): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  960): +onBluetoothStateChange prev=10 new=11
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  960): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  960): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  960): TetherInterfaceSM: wlan0: enter UnavailableState
,E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  960): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  960): Bluetooth State Change Intent: 10 -> 11
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/IntentController( 1254): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothBondStateMachine( 6129): make
,V/NetworkPolicy(  960): updateNetworkEnabledLocked()
D/PMS     (  960): releaseWL(32746998): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  960): updateNotificationsLocked()
V/BluetoothPbapReceiver( 6129): ***********action = android.bluetooth.adapter.action.STATE_CHANGED,
I/BluetoothBondStateMachine( 6129): StableState(): Entering Off State
D/BluetoothAdapterService( 6129): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 6129): checkA2dpState: returning
D/BluetoothAdapterService( 6129): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6129): checkHfpState: returning
V/BluetoothPbapReceiver( 6129): ***********state = 11
,D/TetherSettings( 5456): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5456): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5456): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5456): Cust_ConnectToPC   : spcsc>false
D/        ( 5456): Cust_ConnectToPC   : IPT>true
D/        ( 5456): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5456): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5456): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5456): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5456): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
,I/BluetoothAdapterState( 6129): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5456): setISNotification
D/NGFService( 3472): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothHeadset( 1254): Proxy object connected
,D/UsbnetService(  960): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  960): [USBNET] bCheckSuppFunc: cdc_network
D/BluetoothHeadset( 1527): Proxy object connected
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/BluetoothHeadset(  960): Proxy object connected
D/HeadsetService( 6129): Received start request. Starting profile...
D/HeadsetStateMachine( 6129): Version 1.5,
D/HeadsetStateMachine( 6129): make
,D/SmartNS_Utility( 5456): usb_cable_connect = 1
,D/SmartNS_Utility( 5456): usb_denied = 0
,D/HeadsetStateMachine( 6129): max_hf_connections = 2
,I/SmartNS_PSService( 5456): usb notificaiton:true
,E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothPhoneService( 1527): BluetoothHeadset onServiceConnected
,D/BluetoothHeadset( 1527): Proxy object connected
D/BluetoothHeadset( 1527): Proxy object connected
,D/wpa_supplicant( 6162): wpa_supplicant v2.3-devel-5.0.2
,D/HeadsetPhoneState( 6129): listenForPhoneState..for service and signal 
E/WifiStateMachine(  960): setWifiState: enabling
E/WifiStateMachine(  960): Supplicant start successful
D/WifiMonitor(  960): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  960): connecting to supplicant
I/IntentController( 1254): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,I/ActionCombine( 5456): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
D/BluetoothAdapter(  960): 320956616: getState(). Returning 11,
D/HeadsetDualPhoneStateListener_SLOT1( 6129): listen phone state by slot:SLOT1  id:-1
D/HeadsetDualPhoneStateListener_SLOT2( 6129): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6129): Enter Disconnected: -2, size: 0
D/wpa_supplicant( 6162): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2),
D/wpa_supplicant( 6162): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 6162): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6162): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6162): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6162): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6162): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6162): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6162): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/SmartNS_Utility( 5456): usb_cable_connect = 1
D/SmartNS_Utility( 5456): usb_denied = 0
I/SmartNS_PSService( 5456): usb notificaiton:true
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetDualPhoneStateListener_SLOT1( 6129): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6129): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6129): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6129): BTHF: set_current_device
,D/BluetoothAdapterService( 6129): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20319723
D/wpa_supplicant( 6162): ctrl_interface='/data/misc/wifi/sockets',
D/wpa_supplicant( 6162): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6162): update_config=1
D/wpa_supplicant( 6162): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6162): device_name='Android_608e',
D/wpa_supplicant( 6162): manufacturer='HTC'
D/wpa_supplicant( 6162): model_name='HTC_PHONE',
D/wpa_supplicant( 6162): model_number='1234'
,D/wpa_supplicant( 6162): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6162): p2p_oper_reg_class=126
D/wpa_supplicant( 6162): p2p_oper_channel=149
D/wpa_supplicant( 6162): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6162): persistent_reconnect=1
D/wpa_supplicant( 6162): key_mgmt_offload=1
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/wpa_supplicant( 6162): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6162): nl80211: RFKILL status not available
D/wpa_supplicant( 6162): nl80211: Using driver-based roaming
D/wpa_supplicant( 6162): nl80211: TDLS supported
D/wpa_supplicant( 6162): nl80211: TDLS external setup
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6162): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/SmartNS_NSReceiver( 5456): Tethered state change:false isNSOpening:false
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Su,pported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6162): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6162): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6162): nl80211: interface p2p0 in phy phy0
D/A2dpService( 6129): Received start request. Starting profile...
D/wpa_supplicant( 6162): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6162): nl80211: Subscribe to mgmt frames with non-AP handle 0x5595954fd0
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=0104
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=040a
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=040b
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=040c
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=040d
I/ActivityManager(  960): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6169 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=090a
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=090b
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=090c
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=090d
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=0409506f9a09
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=7f506f9a09
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=0801
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=040e
V/Avrcp   ( 6129): make
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=06
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=0a07
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=0a11
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595954fd0 match=0a1a
D/wpa_supplicant( 6162): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6162): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6162): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6162): htc_wext_command_init +
E/wpa_supplicant( 6162): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6162): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  960): interfaceLinkStateChanged p2p0, false
D/Tethering(  960): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  960): interfaceLinkStateChanged p2p0, false
D/Tethering(  960): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 1527): 362019304: getState(). Returning 11
E/RemoteController( 6129): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 6129): make
D/bt-btif ( 6129): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
D/A2dpService( 6129): setA2dpService(): set to: null
D/BluetoothAdapterService( 6129): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20319723
D/A2dpStateMachine( 6129): Enter Disconnected: -2
D/BluetoothA2dp(  960): Proxy object connected
I/QuickSettingMiniLite( 1254): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@11c13e6d
D/TetherSettings( 5456): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5456): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5456): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5456): Cust_ConnectToPC   : spcsc>false
D/        ( 5456): Cust_ConnectToPC   : IPT>true
D/        ( 5456): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5456): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5456): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5456): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5456): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/BluetoothAdapter(  960): 320956616: getState(). Returning 11
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/HidService( 6129): Received start request. Starting profile...
D/BluetoothAdapterService( 6129): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20319723
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5456): setISNotification
D/HealthService( 6129): Received start request. Starting profile...
D/BluetoothAdapterService( 6129): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20319723
D/SmartNS_Utility( 5456): usb_cable_connect = 1
D/SmartNS_Utility( 5456): usb_denied = 0
I/SmartNS_PSService( 5456): usb notificaiton:true
I/QuickSettingBluetooth( 1254): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/WIFI_ICON( 1254): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/RemoteViews( 1254): reapply : com.android.settings 0 36
D/PanService( 6129): Received start request. Starting profile...
I/QuickSettingWifi( 1254): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
D/SmartNS_Utility( 5456): usb_cable_connect = 1
I/RemoteViews( 1254): reapply : com.android.settings 1 36
D/PanService( 6129): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 6129): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20319723
D/SmartNS_Utility( 5456): usb_denied = 0
I/SmartNS_PSService( 5456): usb notificaiton:true
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
,D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/BtGatt.DebugUtils( 6129): handleDebugAction() action=null
D/BtGatt.GattService( 6129): Received start request. Starting profile...
D/BtGatt.GattService( 6129): start()
D/BtGatt.AdvertiseManager( 6129): advertise manager created
D/SmartNS_NSReceiver( 5456): Tethered state change:false isNSOpening:false
I/RemoteViews( 1254): reapply : com.android.settings 1 36
D/BluetoothAdapterService( 6129): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@20319723
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
I/RemoteViews( 1254): reapply : com.android.settings 1 36
I/HeadsetPhoneState( 6129): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 6129): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
I/ActivityManager(  960): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6198 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/HeadsetStateMachine( 6129): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6129): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6129): Disconnected process message: 11, size: 0
D/HtcBtWidget_BTWidgetProvider( 6169): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 6169): updateWidget(context) for widget: 
,D/BluetoothAdapterState( 6129): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/BluetoothAdapter( 1527): 362019304: getState(). Returning 11
W/BluetoothHeadset( 1527): Proxy not attached to service
D/Process (  960): killProcessQuiet, pid=5755
,I/ActivityManager(  960): Killing 5755:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/bt-btu  ( 6129): btu_task pending for preload complete event
,E/bt_vendor( 6129): get_bt_soc_type: Failed to get soc type
,D/BluetoothHeadset( 1527): java.lang.Throwable
D/BluetoothHeadset( 1527): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1527): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1527): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1527): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1527): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1527): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1527): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1527): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1527): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1527): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/qcom-bluetooth( 6222): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,D/BluetoothAdapter( 1254): 312383602: getState(). Returning 11
I/QuickSettingMiniLite( 1254): updateLiteState:no connect device!
,I/wpa_supplicant( 6162): wapi_supplicant_init: Init WAI packet p2p0,
D/wpa_supplicant( 6162):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6162):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6162):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6162): nl80211: Flush PMKIDs
D/wpa_supplicant( 6162): p2p0: State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 6228): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6229): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/qcom-bluetooth( 6231): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6232): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6233): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/ActivityManager(  960): Recipient 5755
,I/qcom-bluetooth( 6234): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/wpa_supplicant( 6162): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6162): TDLS: Driver uses external link setup,
D/wpa_supplicant( 6162): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6162): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 6162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6162): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6162): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6162): EAPOL: SUPP_BE entering state INITIALIZE
,D/wpa_supplicant( 6162): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 6162): Using existing control interface directory.
D/wpa_supplicant( 6162): P2P: Add operating class 81
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6162): P2P: Own listen channel: 81:1
D/wpa_supplicant( 6162): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6162): P2P: initialized,
D/wpa_supplicant( 6162): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6162): P2P: cli_channels:
D/wpa_supplicant( 6162): p2p0: Added interface p2p0,
D/wpa_supplicant( 6162): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6162): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6162): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6162): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6162): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6162): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 6162): ctrl_interface='/data/misc/wifi/sockets',
D/wpa_supplicant( 6162): disable_scan_offload=1
D/wpa_supplicant( 6162): driver_param='use_p2p_group_interface=1'
,D/wpa_supplicant( 6162): update_config=1,
D/wpa_supplicant( 6162): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6162): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6162): manufacturer='HTC'
,D/wpa_supplicant( 6162): model_name='HTC One M8s'
,D/wpa_supplicant( 6162): model_number='HTC One M8s'
,D/wpa_supplicant( 6162): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6162): hs20=1
D/wpa_supplicant( 6162): interworking=1
,D/wpa_supplicant( 6162): external_sim=1
D/wpa_supplicant( 6162): key_mgmt_offload=1
,D/BluetoothMasReceiver( 6129): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 6129): SapReceiver onReceive ,
V/BluetoothSapReceiver( 6129): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6129):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6129): startService = false
,D/AuthorizationBluetoothService( 1913): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/wpa_supplicant( 6162): Priority group 340,
D/wpa_supplicant( 6162):    id=0 ssid='NG700'
I/wpa_supplicant( 6162): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6162): nl80211: RFKILL status not available
D/wpa_supplicant( 6162): nl80211: Using driver-based roaming
D/wpa_supplicant( 6162): nl80211: TDLS supported
D/wpa_supplicant( 6162): nl80211: TDLS external setup
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6162): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6162): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6162): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
,D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6162): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6162): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6162): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6162): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6162): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6162): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6162): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6162): nl80211: Subscribe to mgmt frames with non-AP handle 0x5595974100
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=0104
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=040a
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=040b
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=040c
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=040d
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=090a
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=090b
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=090c
,D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=090d
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=0409506f9a09
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=7f506f9a09
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=0801
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=040e
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=06
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=0a07
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=0a11
D/wpa_supplicant( 6162): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x5595974100 match=0a1a
D/wpa_supplicant( 6162): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6162): nl80211: driver param='use_p2p_group_interface=1'
,D/wpa_supplicant( 6162): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6162): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6162): htc_wext_command_init +
I/wpa_supplicant( 6162): htc_wext_command_init -
I/wpa_supplicant( 6162): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6162): Don't set 00 to countryID.conf
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6162): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6162): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
,D/Tethering(  960): interfaceLinkStateChanged wlan0, false
D/Tethering(  960): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6162): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 6162): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6162): P2P: Add operating class 81
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6162): P2P: Update channel list
D/wpa_supplicant( 6162): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6162): P2P: cli_channels:
D/wpa_supplicant( 6162): p2p0: Updating hw mode
,D/wpa_supplicant( 6162): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6162): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 6162): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6162): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6162): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/HtcWiFiWidget_WiFiWidgetProvider( 6198): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 6198): updateWidget(context) for widget: 
,I/ActivityManager(  960): Killing 4738:com.google.android.gms.wearable/u0a24 (adj 15): empty #17,
D/Process (  960): killProcessQuiet, pid=4738
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/qcom-bluetooth( 6237): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 ,
,I/ActivityManager(  960): Recipient 4738
,I/qcom-bluetooth( 6238): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** ,
,I/bt-btu  ( 6129): btu_task received preload complete event,
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x001f
,W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x0003,
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/PMS     (  960): acquireWL(2d9c3455): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6129 1002 null,
,D/bt-btm  ( 6129): btm_acl_device_down,
D/bt-btm  ( 6129): btm_acl_reset_paging
D/bt-btm  ( 6129): btm_acl_set_discing
,I/bt-btm  ( 6129): btm_reset_complete,
I/bt-btm  ( 6129): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 6129): Start reading local supported commands
,D/bt-btm  ( 6129): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 6129): BTM reads next extended features page (1)
D/bt-btm  ( 6129): BTM reads next extended features page (2)
D/bt-btm  ( 6129): BTM reached last extended features page (2)
D/bt-btm  ( 6129): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 6129): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
I/wpa_supplicant( 6162): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 6162):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6162):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6162):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/bt-btm  ( 6129): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 6129): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6162): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6162): nl80211: Flush PMKIDs
D/bt-btm  ( 6129): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
,I/bt-btm  ( 6129): btm_vendor_capability_vsc_cmpl_cback: status=0
D/bt-btm  ( 6129): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 6129): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6129): btm_read_ble_wl_size 
,D/bt-btm  ( 6129): btm_read_white_list_size_complete 
D/bt-btm  ( 6129): btm_get_ble_buffer_size 
D/bt-btm  ( 6129): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6129): btm_read_ble_local_supported_states 
,D/bt-btm  ( 6129): btm_read_ble_local_supported_states_complete 
,D/bt-btm  ( 6129): btm_read_ble_local_supported_features 
D/bt-btm  ( 6129): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 6129): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6129): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6129): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6129): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6129): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0,
I/bt-btm  ( 6129):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6129): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6129): BTM_SetInquiryMode
I/bt-btm  ( 6129): BTM_SetPageScanType
I/bt-btm  ( 6129): BTM_SetInquiryScanType
D/bt-btm  ( 6129): btm_decode_ext_features_page page: 1,
W/bt-btm  ( 6129): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6129): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6129): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6129): BTM_BleLoadLocalKeys
D/bt-btm  ( 6129): BTM_BleLoadLocalKeys
I/bt-btm  ( 6129): BTM_Sec: application registered,
E/bt-btm  ( 6129): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf8164d5 
I/bt-btm  ( 6129): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6129): SMP_Register state=0
E/bt-btm  ( 6129): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf8164d5 
,I/bt-btm  ( 6129): BTM_Sec: application registered
D/bt-btm  ( 6129): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6129): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6129): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6129): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
,D/bt-btm  ( 6129): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6129): BTM_RegBusyLevelNotif
D/bt-btm  ( 6129): BTM_BleReadControllerFeatures
I/bt-btm  ( 6129): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,I/bt-att  ( 6129): GATT_Register,
D/bt-att  ( 6129): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6129): allocated gatt_if=3
,I/bt-att  ( 6129): GATT_StartIf gatt_if=3
D/bt-att  ( 6129): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6129): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 6129): btm_ble_vendor_capability_vsc_cmpl_cback,
D/bt-btm  ( 6129): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6129): BTM Register For VSEvents is successfully
D/bt-btm  ( 6129): BTM_BleGetVendorCapabilities
,I/bt-btif ( 6129): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6129): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6129): bta_dm_set_dev_name: name: HTC One M8s 
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btm  ( 6129):  BTM_BleConfigPrivacy
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr,
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 6129): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6129): BTM_AllocateSCN
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6129): BTM_AllocateSCN
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btm  ( 6129): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6129):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
,I/bt-btm  ( 6129):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6129): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6129): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6129):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6129):                : sec: 0x1086, service name [] (up to 21 chars saved)
E/bt-btif ( 6129): Calling BTA_HhEnable
I/bt-btif ( 6129): BTA_MceEnable
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6129): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6129):                : sec: 0x2090, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6129): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6129):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
E/bt-btif ( 6129): btif_storage_get_adapter_p, servi service_] (up to 21 ch
I/bt-btm  ( 6129): btif_storage_get_adapter_p, servi service_] (up to 21 chars saved)
I/bt-btif ( 6129): BTM_SEC_REG[6]: id 38apter_properties_cb
I/bt-btm  ( 6129): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6129): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6129):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6129):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:5
,I/bt-avp  ( 6129): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6129): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
D/BluetoothAdapterProperties( 6129): Address is:90:E7:C4:F6:69:77
D/bt-btif ( 6129):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6129): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btm  ( 6129): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6129):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6129):                : sec: 0xb6, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6129): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
,I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
,I/bt-btm  ( 6129): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6129):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6129): GATT_Register
D/bt-att  ( 6129): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6129): allocated gatt_if=4
I/bt-att  ( 6129): GATT_StartIf gatt_if=4
,D/bt-att  ( 6129): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6129): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 6129): Scan Mode:21
D/BluetoothAdapterProperties( 6129): Discoverable Timeout:120
I/bt-btif ( 6129): BTA_JvEnable
I/bt-btif ( 6129): BTA_JvRegisterL2cCback
I/bt-btm  ( 6129): BTM_ReadConnectability
I/bt-btm  ( 6129): BTM_ReadDiscoverability
I/bt-btm  ( 6129): BTM_SetDiscoverability
I/bt-btm  ( 6129): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6129): disc_mode 0002
,D/bt-btm  ( 6129): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6129): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6129): BTM_SetConnectability
I/bt-btm  ( 6129): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6129): disc_mode 0002
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6129): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6129): BTM_SetDiscoverability
I/bt-btm  ( 6129): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6129): disc_mode 0000
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): evt_type=0x0 p-cb->evt_type=0x0 
,I/bt-btm  ( 6129): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6129): BTM_SetConnectability
I/bt-btm  ( 6129): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6129): disc_mode 0000
D/bt-btm  ( 6129): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6129): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
I/bt-btm  ( 6129): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6129): bta_pan_co_init
,D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6129): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6129):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6129):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btm  ( 6129): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6129):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6129): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6129):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = b8 a7 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = fe 5a 8f cb e9 38 08 34 a7 f5 ec b2 21 9b 7a 68 
,I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6129): Stopping oneshot timer
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 6129): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
,D/bt-btif ( 6129): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6129): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
,D/bt-btif ( 6129): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6129): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 6129): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6129): ScanMode =  21
D/BluetoothAdapterProperties( 6129): State =  11
I/bt-btif ( 6129): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6129): Setting state to 12
,I/BluetoothAdapterState( 6129): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 6129): Discoverable Timeout:120
D/BluetoothManagerService(  960): +onBluetoothStateChange prev=11 new=12
D/BluetoothManagerService(  960): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 6129): Entering On State
D/BluetoothManagerService(  960): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp(  960): onBluetoothStateChange: up=true
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = bf 75 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 2d 23 ae e8 76 a9 5a a2 fc fe d2 91 e5 5f 52 25 
D/BluetoothHeadset( 1527): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1527): onBluetoothStateChange: up=true
E/bt_mct  ( 6129): hci lib postload completed
D/BluetoothHeadset(  960): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1527): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1254): onBluetoothStateChange: up=true
D/BluetoothManagerService(  960): Bluetooth State Change Intent: 11 -> 12
I/IntentController( 1254): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3472): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  960): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  960): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  960): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapReceiver( 6129): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
V/BluetoothPbapReceiver( 6129): ***********state = 12
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 89 16 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = a9 40 98 6d d8 a1 52 0f 38 b7 c8 86 32 23 25 da 
D/NGFService( 3472): Bluetooth Adapter: ON
,D/bt-btm  ( 6129): btm_ble_rand_enc_complete
,I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = cf 83 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 52 ff c7 58 9f d8 97 d4 d1 d8 56 c8 cf db 02 cb 
,D/PMS     (  960): acquireWL(2a6493f8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5456 1000 null
,W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/bt-btm  ( 6129): btm_ble_rand_enc_complete
,I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = a8 0d 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = c6 2f 6d 82 eb f2 90 9e c3 12 c1 2f 88 59 ec 4f 
,V/BluetoothPbapService( 6129): Pbap Service onCreate
V/BluetoothPbapService( 6129): Starting PBAP service
,D/BluetoothAdapter( 6129): 1072852853: getState(). Returning 12
V/BluetoothPbapService( 6129): Handler(): got msg=1
V/BluetoothPbapService( 6129): Pbap Service startRfcommSocketListener
D/HtcBtWidget_BTWidgetProvider( 6169): onBTStateChanged() for widget: 
,V/BluetoothPbapService( 6129): Pbap Service initSocket
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = b7 be 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = c9 bd c0 c2 c4 64 b7 90 1d be 6f 9d 54 8b eb 15 
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/PMS     (  960): releaseWL(2a6493f8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6169): updateWidget(context) for widget: 
,D/PMS     (  960): acquireWL(b0ff736): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5456 1000 null
,D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 58 21 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = e4 e9 bd 63 71 92 68 a3 cc 0c f0 50 07 25 9b ad 
,D/wpa_supplicant( 6162): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6162): TDLS: Driver uses external link setup
D/wpa_supplicant( 6162): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6162): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6162): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6162): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6162): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6162): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6162): EAP: EAP entering state DISABLED
W/BluetoothAdapter( 6129): getBluetoothService() called with no BluetoothManagerCallback
D/wpa_supplicant( 6162): Using existing control interface directory.
I/wpa_supplicant( 6162): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6162): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 00 e9 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = bd ec f5 55 93 7c 0a b3 b3 5b 92 8d 3a c5 96 0b 
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6162): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6162): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
,W/System.err(  960): java.lang.Throwable: stack dump
W/System.err(  960): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  960): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  960): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  960): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  960): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2837990d:true
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=DE
,D/wpa_supplicant( 6162): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6162): P2P: Add operating class 81
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6162): P2P: Add operating class 115
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6162): P2P: Add operating class 116
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6162): P2P: Add operating class 117
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6162): P2P: Update channel list
D/wpa_supplicant( 6162): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6162): P2P: cli_channels:
D/wpa_supplicant( 6162): p2p0: Updating hw mode
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6162): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
I/bt-btm  ( 6129): BTM_SetDiscoverability
I/bt-btm  ( 6129): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6129): disc_mode 0000
I/bt-btm  ( 6129): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6129): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6129): BTM_SetConnectability
I/bt-btm  ( 6129): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6129): disc_mode 0000
D/bt-btm  ( 6129): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6129): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6129): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6129): BTA_JvCreateRecordByUser
I/wpa_supplicant( 6162): Auto country group 1: ch36
D/wpa_supplicant( 6162): wlan0: Added interface wlan0
D/wpa_supplicant( 6162): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 6162): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6162): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
I/bt-btif ( 6129): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): BTA_JvRfcommStartServer
I/bt-btm  ( 6129): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6129):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
D/wpa_supplicant( 6162): random: Got 20/20 bytes from /dev/random
V/BluetoothPbapService( 6129): Succeed to create listening socket 
V/BluetoothPbapService( 6129): Accepting socket connection...
D/BluetoothAdapterProperties( 6129): Scan Mode:21
D/wpa_supplicant( 6162): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6162): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_960-2\x00
D/wpa_supplicant( 6162): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 57 92 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 6e 46 5c 7d 5c a2 7d 2c 68 29 5a 17 a9 39 ec db 
E/WifiStateMachine(  960): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/BluetoothAdapter( 1254): 312383602: getState(). Returning 12
E/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  960): invokeExitMethods: InitialState
E/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  960): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131144
E/WifiStateMachine(  960): processMsg: SupplicantStartingState
E/WifiStateMachine(  960):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/wpa_supplicant( 6162): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
E/WifiStateMachine(  960): deferMessage: msg=131144
D/wpa_supplicant( 6162): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6162): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6162): nl80211: Regulatory domain change
D/wpa_supplicant( 6162):  * initiator=1
D/wpa_supplicant( 6162):  * type=0
D/wpa_supplicant( 6162):  * alpha2=DE
D/wpa_supplicant( 6162): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6162): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 31 74 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 72 fb d8 d1 a1 62 47 8f f3 82 a2 b8 a3 bc af e6 
E/WifiStateMachine(  960): handleMessage: X
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=DE
,D/wpa_supplicant( 6162): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6162): P2P: Add operating class 81
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6162): P2P: Add operating class 115
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6162): P2P: Add operating class 116
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6162): P2P: Add operating class 117
E/WifiStateMachine(  960): handleMessage: E msg.what=131085
,D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=2): 28 30
E/WifiStateMachine(  960): processMsg: SupplicantStartingState
D/wpa_supplicant( 6162): P2P: Update channel list
D/wpa_supplicant( 6162): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6162): P2P: cli_channels:
D/wpa_supplicant( 6162): p2p0: Updating hw mode
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6162): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm
,D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  960): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  960): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/BluetoothAdapter( 1254): 312383602: getState(). Returning 12
,E/WifiStateMachine(  960):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  960): deferMessage: msg=131085
E/WifiStateMachine(  960): handleMessage: X
,E/WifiStateMachine(  960): handleMessage: E msg.what=131149
E/WifiStateMachine(  960): processMsg: SupplicantStartingState
E/WifiStateMachine(  960):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  960): setSuspendOptimizations: 2 true
E/WifiStateMachine(  960): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131145
E/WifiStateMachine(  960): processMsg: SupplicantStartingState
I/QuickSettingBluetooth( 1254): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
E/WifiStateMachine(  960):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  960): handleMessage: X
,E/WifiStateMachine(  960): handleMessage: E msg.what=131146
E/WifiStateMachine(  960): processMsg: SupplicantStartingState
E/WifiStateMachine(  960):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
,D/BluetoothAdapter( 5456): 628071386: getState(). Returning 12
E/WifiStateMachine(  960):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131101
E/WifiStateMachine(  960): processMsg: SupplicantStartingState
E/WifiStateMachine(  960):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine(  960): processMsg: DefaultState
,E/WifiStateMachine(  960):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  960): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=147457
,E/WifiStateMachine(  960): processMsg: SupplicantStartingState
E/WifiStateMachine(  960):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  960): Supplicant connection established
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6162): set wifi ON
,E/WifiStateMachine(  960): setWifiState: enabled
E/WifiStateMachine(  960): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  960):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6162): SET_SCREEN_ON:Off
I/wpa_supplicant( 6162): htc_wext_set_keepalive +
I/wpa_supplicant( 6162): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6162): getPrivFuncNum +	
I/wpa_supplicant( 6162): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6162): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6162): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6162): get_ip_address source addr = ffffffff
,I/wpa_supplicant( 6162): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6162): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  960): startHal
,D/BluetoothInputDevice( 5456): BluetoothInputDevice()
,D/PhoneStatusBar( 1254): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothManagerService(  960): registerStateChangeCallback+
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  960): Registered receivers: 7
E/wifi    (  960): getStaticLongField sWifiHalHandle 0x7f8554e300
,I/WifiNative-HAL(  960): Could not start hal
E/WifiStateMachine(  960): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  960): backgroundScan enabled=true startBackgroundScanIfNeeded:false
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
,E/WifiStateMachine(  960): handleScreenStateChanged Exit: false
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 75 86 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 92 52 57 e6 1f b6 48 67 98 76 dc bd 55 b6 e8 ee 
I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 6129): Stopping oneshot timer
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER MACADDR'
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6162): update_config=1
D/wpa_supplicant( 6162): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,I/IntentController( 1254): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WifiConfigStore(  960): Loading config and enabling all networks 
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6162): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6162): wpa_supplicant_ctrl_iface_list_networks: return size = 47,
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 ssid',
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/HtcWiFiWidget_WiFiWidgetProvider( 6198): onWiFiStateChanged() for widget: 
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/HtcWiFiWidget_WiFiWidgetProvider( 6198): updateWidget(context) for widget: 
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6162): Do not allow key_data field to be exposed
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
D/bt-smp  ( 6129): smp_encrypt_data
D/WIFI_ICON( 1254): updateWifiState: WIFI_STATE_CHANGED enabled
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = ba 1b 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 11 2d e8 88 7f 0c 4c 63 9c 01 37 f4 ac f5 ce 53 
I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6129): Stopping oneshot timer
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
,D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/BluetoothPan( 5456): BluetoothPan()
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/BluetoothManagerService(  960): registerStateChangeCallback+
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
D/BluetoothManagerService(  960): Registered receivers: 8
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 7c 6e 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = 7e 8a f7 81 ae 88 7f cf 61 a3 05 a6 67 1f f9 8b 
I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
W/bt-btm  ( 6129): Stopping oneshot timer
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='engine'
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6162): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6162): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/BluetoothMap( 5456): Create BluetoothMap proxy object
,D/BluetoothManagerService(  960): registerStateChangeCallback+
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  960): Registered receivers: 9
,E/BluetoothMap( 5456): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,E/WifiConfigStore(  960): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/BluetoothManagerService(  960): registerStateChangeCallback+
,D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  960): Registered receivers: 10
,D/BluetoothSap( 5456): BluetoothSap() call bindService
D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = e0 24 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = b6 fd 68 ec 29 f4 ea cb 70 20 c4 dd 28 06 8e 11 
I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6129): Stopping oneshot timer
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
W/ContextImpl( 5456): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
,I/QuickSettingWifi( 1254): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
D/wpa_supplicant( 6162): device_name='m8qlul_htc_europe'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6162): manufacturer='HTC'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6162): model_name='HTC One M8s'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/BluetoothPbap( 5456): BluetoothPbap()
,D/wpa_supplicant( 6162): wlan0: Control interface command 'SET model_number HTC One M8s'
,D/wpa_supplicant( 6162): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6162): model_number='HTC One M8s'
D/BluetoothManagerService(  960): registerStateChangeCallback+
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/BluetoothManagerService(  960): Registered receivers: 11
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6162): config_methods='physical_display virtual_push_button'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  960): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  960): handleMessage: new destination call exit/enter
E/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  960): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  960): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6162): wlan0: Setting scan interval: 15 sec
W/Settings( 5838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  960): Setting external_sim to 1
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
,D/WifiP2pService(  960): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6162): external_sim=1
,D/WifiStateMachine(  960): Setting OUI to DA-A1-19
I/WifiNative-HAL(  960): startHal
E/wifi    (  960): getStaticLongField sWifiHalHandle 0x7f8554e360
I/WifiNative-HAL(  960): Could not start hal
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6162): wlan0: Control interface command 'STA_AUTOCONNECT 0'
,E/WifiStateMachine(  960): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  960): Driverstarted State enter
D/BluetoothManagerService(  960): registerStateChangeCallback+
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/BluetoothManagerService(  960): Registered receivers: 12
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  960): DriverStartedState call setCountryCode()
E/WifiStateMachine(  960): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  960): NetworkAgent == null
,E/WifiStateMachine(  960): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/BluetoothHeadset( 5456): BluetoothHeadset()
D/BluetoothManagerService(  960): registerStateChangeCallback+
D/WIFI_ICON( 1254): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1254): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  960): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiTrafficPoller(  960): ENABLE_TRAFFIC_STATS_POLL false Token 0
D/BluetoothManagerService(  960): Registered receivers: 13
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
,D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
I/IntentController( 1254): receive(android.net.wifi.STATE_CHANGE,1,false)
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
,D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  960): setDhcpActive: false
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6162): wlan0: Control interface command 'STATUS'
E/WifiStateMachine(  960): transitionTo: destState=DisconnectedState
E/native  (  960): do suspend false
,D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/HTCRequest(  960): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/WifiP2pService(  960): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/HTCRequest(  960): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/HTCRequest(  960): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6162): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/LocalBluetoothProfileManager( 5456): LocalBluetoothProfileManager construction complete
D/WifiMonitor(  960): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
E/WifiStateMachine(  960): Driverstarted State enter done
E/WifiStateMachine(  960): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  960): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  960): handleMessage: new destination call exit/enter
D/wpa_supplicant( 6162): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
E/WifiStateMachine(  960): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  960): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  960): moveTempStackToStateStack: i=0,j=4
,E/WifiStateMachine(  960): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  960): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  960): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  960): DisconnectedState call setCountryCode()
E/WifiStateMachine(  960):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/Tethering(  960): interfaceLinkStateChanged p2p0, false
D/Tethering(  960): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  960): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6162): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6162): wlan0: nl80211: sched_scan request
D/WifiScanningService(  960): SCAN_AVAILABLE : 3
D/RttService(  960): SCAN_AVAILABLE : 3
D/WifiScanningService(  960): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  960): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  960): startHal
V/BluetoothPbapService( 6129): Pbap Service onBind
,D/DockEventReceiver( 5456): finishStartingService: stopping service
,D/BluetoothA2dp( 5456): Proxy object connected
,D/A2dpProfile( 5456): Bluetooth service connected
,D/BluetoothAdapter( 5456): 628071386: getState(). Returning 12
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6129): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6129): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): BTA_JvRfcommStartServer
I/bt-btm  ( 6129): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6129):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6129): Accept thread started.
,D/BluetoothAdapter( 6129): 1072852853: getState(). Returning 12,
D/BluetoothFtpService( 6129): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/wpa_supplicant( 6162): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6162): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6162): wlan0: nl80211: Sched scan started
D/BluetoothMasReceiver( 6129): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6129):  call MAP start service
D/WifiP2pService(  960): P2pEnablingState
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  960): [NET] android_getaddrinfofornet-, SUCCESS
,E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131144
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131085
E/wifi    (  960): getStaticLongField sWifiHalHandle 0x7f8305e520
I/WifiNative-HAL(  960): Could not start hal
E/WifiScanningService(  960): could not start HAL
D/WifiMonitor(  960): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
D/BluetoothFtpService( 6129): htc sense version is 6.0
E/WifiStateMachine(  960):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131154
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
E/WifiStateMachine(  960):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131323
E/WifiStateMachine(  960): processMsg: DisconnectedState
,E/WifiStateMachine(  960):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
W/BluetoothAdapter( 6129): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine(  960):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
I/bt-btif ( 6129): BTA_JvCreateRecordByUser
E/WifiStateMachine(  960):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  960): processMsg: DefaultState
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:12
,I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): BTA_JvRfcommStartServer
I/bt-btm  ( 6129): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6129):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
E/WifiStateMachine(  960):  DefaultState what:131323 0 0
E/WifiStateMachine(  960): setOperatorSSID enter
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=131104
E/WifiStateMachine(  960): processMsg: DisconnectedState
,D/BluetoothHeadset( 5456): Proxy object connected
D/HeadsetProfile( 5456): Bluetooth service connected
D/WifiP2pService(  960): P2pEnablingState{ when=-8ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  960): P2p socket connection successful
D/WifiP2pService(  960): P2pEnabledState
E/WifiStateMachine(  960):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  960): processMsg: ConnectModeState
D/BluetoothAdapter( 5456): 628071386: getState(). Returning 12
D/WifiP2pService(  960): sending p2p connection changed broadcast
D/WifiDisplayController(  960): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WISPrService( 5456): >>>>>WISPrService start isConnected = false<<<<<
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6129): Run Accept thread
E/BluetoothMasService( 6129): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
W/WifiHW  (  960): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6162): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
,D/wpa_supplicant( 6162): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6162): persistent_reconnect=1
D/wpa_supplicant( 6162): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6162): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6162): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  960):  ConnectModeState what:131104 0 0
W/Settings(  960): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  960): QCOM Debug wifi_send_command "SET device_name Android_608e"
D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6162): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6162): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6162): device_name='Android_608e'
,W/WifiHW  (  960): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6162): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6162): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6162): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6162): P2P: New SSID postfix: -Android_608e
W/WifiHW  (  960): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6162): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6162): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/BluetoothInputDevice( 5456): Proxy object connected
D/wpa_supplicant( 6162): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/WifiService(  960): New client listening to asynchronous messages
D/wpa_supplicant( 6162): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6162): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/BluetoothMasService( 6129): Add permission for SmsProvider.
,D/HidProfile( 5456): Bluetooth service connected
D/WifiDisplayController(  960): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  960): handleMessage: X
D/WifiDisplayController(  960): mWfdEnabled :false, networkInfo.isConnected() :false
E/WifiStateMachine(  960): handleMessage: E msg.what=131162
D/WifiDisplayAdapter(  960): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  960):     Client/Owner: Client
D/WifiDisplayAdapter(  960):     GroupId: 
D/WifiDisplayAdapter(  960):     Passphrase: 
D/WifiDisplayAdapter(  960):     SessionId: 0
D/WifiDisplayAdapter(  960):     IP Address: }
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiTrafficPoller(  960): ADD_CLIENT: 8
V/BluetoothMasService( 6129): Starting MAS instances
E/WifiStateMachine(  960):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  960): processMsg: ConnectModeState
D/BluetoothAdapter( 6129): 1072852853: getState(). Returning 12
E/WifiStateMachine(  960):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  960): processMsg: DriverStartedState
I/QuickSettingWifi( 1254): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  960):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
D/BluetoothAdapter( 5456): 628071386: getState(). Returning 12
E/WifiStateMachine(  960): set frequency band 0
V/AudioService(  960): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  960):     Client/Owner: Client
V/AudioService(  960):     GroupId: 
V/AudioService(  960):     Passphrase: 
V/AudioService(  960):     SessionId: 0
V/AudioService(  960):     IP Address: }
,D/HtcEffectManagerBase(  960): onEventChanged id=5 status=false
D/HtcEffectManager(  960): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  960): convertEffect before=902
D/HtcEffectManager(  960): convertEffect after=902
I/MailMessageReceiver( 6129): reg:com.android.bluetooth.btservice.AdapterApp@16743162 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@a5112f3
D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6162): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6162): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6162): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6162): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6162): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6162): SETBAND: 0
D/wpa_supplicant( 6162): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6162): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6162): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/BluetoothPan( 5456): BluetoothPAN Proxy object connected
D/WifiMonitor(  960): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN],
E/WifiMonitor(  960): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  960): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  960): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
I/MailManager( 6129): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@a5112f3
V/EmailUtils( 6129): Manager Instance is not NULL
D/PMS     (  960): releaseWL(b0ff736): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6162): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6162): P2P: Add operating class 81
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6162): P2P: Add operating class 115
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6162): P2P: Add operating class 116
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=2): 24 2c
,D/PanProfile( 5456): Bluetooth service connected
D/wpa_supplicant( 6162): P2P: Add operating class 117
D/wpa_supplicant( 6162): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6162): P2P: Update channel list
D/wpa_supplicant( 6162): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6162): P2P: cli_channels:
D/wpa_supplicant( 6162): p2p0: Updating hw mode
D/BluetoothPbap( 5456): Proxy object connected
D/wpa_supplicant( 6162): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6162): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6162): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6162): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
,D/wpa_supplicant( 6162): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6162): nl80211: Added 802.11b mode based on 802.11g information
D/PbapServerProfile( 5456): Bluetooth service connected
E/WifiStateMachine(  960): did set frequency band 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6162): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6162): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6162): Single channel concurrency preference: sta
D/WifiNative-HAL(  960): p2pGetDeviceAddress
W/WifiHW  (  960): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  960): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
,W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6162): wlan0: Control interface command 'BSS_FLUSH 0'
D/WISPrService( 5456): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  960): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6162): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6162): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6162): wlan0: Cancelling sched scan
D/wpa_supplicant( 6162): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6162): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6162): wpa_supplicant_scan enter
D/wpa_supplicant( 6162): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6162): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6162): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6162): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  960): done set frequency band 0
,I/ActivityManager(  960): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6258 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/WifiP2pService(  960): DeviceAddress: 92:e7:c4:e6:4c:f8
W/WifiHW  (  960): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 6162): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6162): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6162): P2P: Stopping find
D/wpa_supplicant( 6162): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6162): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6162): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6162): P2P: Stopping find
D/wpa_supplicant( 6162): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6162): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6162): wpa_driver_set_ap_wps_p2p_ie: Entry
,W/WifiHW  (  960): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6162): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6162): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  960): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6162): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6162): wpa_supplicant_ctrl_iface_list_networks: return size = 34
D/WifiDisplayController(  960): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  960):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  960):  primary type: 10-0050F204-5
D/WifiDisplayController(  960):  secondary type: null
D/WifiDisplayController(  960):  wps: 0
D/WifiDisplayController(  960):  grpcapab: 0
D/WifiDisplayController(  960):  devcapab: 0
D/WifiDisplayController(  960):  status: 3
D/WifiDisplayController(  960):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  960):  WFD CtrlPort: 0
D/WifiDisplayController(  960):  WFD MaxThroughput: 0
W/WifiHW  (  960): QCOM Debug wifi_send_command "SAVE_CONFIG"
,D/wpa_supplicant( 6162): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6162): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6162): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
,D/wpa_supplicant( 6162): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6162): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6162): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6162): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  960): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  960): InactiveState
,D/WifiStateMachine(  960): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  960): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=147462
E/WifiStateMachine(  960): processMsg: DisconnectedState
,E/WifiStateMachine(  960):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129455  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  960): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  960): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  960): processMsg: ConnectModeState
E/WifiStateMachine(  960):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129456  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
,E/WifiStateMachine(  960): handleMessage: X
E/WifiStateMachine(  960): handleMessage: E msg.what=143371
E/WifiStateMachine(  960): processMsg: DisconnectedState
E/WifiStateMachine(  960):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  960): processMsg: ConnectModeState
,E/WifiStateMachine(  960):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  960): processMsg: DriverStartedState
E/WifiStateMachine(  960):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  960): processMsg: SupplicantStartedState
E/WifiStateMachine(  960):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,E/WifiStateMachine(  960): processMsg: DefaultState
E/WifiStateMachine(  960):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  960): handleMessage: X
,D/HtcAdjCursorFactory( 6258): Set CursorWindow size to: 4194304 KB, Tid: 6278
,D/EmailUtils( 6129): ============NULL aList========,
V/EmailUtils( 6129): <-getEmailAccountIdList
V/BluetoothMasService( 6129): onCreate: mIsEmailEnabled: true
,I/art     (  960): Explicit concurrent mark sweep GC freed 29304(1558KB) AllocSpace objects, 4(692KB) LOS objects, 33% free, 16MB/24MB, paused 1.317ms total 145.921ms,
D/BluetoothAdapter( 6129): 1072852853: getState(). Returning 12,
V/BluetoothMasService( 6129): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 6129): Manager Instance is not NULL
,D/EmailUtils( 6129): ============NULL aList========
V/EmailUtils( 6129): <-getEmailAccountIdList
V/BluetoothSapReceiver( 6129): SapReceiver onReceive 
V/BluetoothSapReceiver( 6129): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6129):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6129): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6129): handleMessage: mIsEmailEnabledtrue,
V/BtMns   ( 6129): BluetoothMns: isEmailEnabled: true
D/AuthorizationBluetoothService( 1913): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6129): getBluetoothService() called with no BluetoothManagerCallback,
,I/bt-btif ( 6129): BTA_JvCreateRecordByUser
D/bt-btm  ( 6129): BTM_AllocateSCN
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:13
,I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): BTA_JvRfcommStartServer
,I/bt-btm  ( 6129): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6129):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6129): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6129): BTA_JvCreateRecordByUser
D/bt-btm  ( 6129): BTM_AllocateSCN
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): BTA_JvRfcommStartServer
I/bt-btm  ( 6129): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6129):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  960): killProcessQuiet, pid=5787,
I/ActivityManager(  960): Killing 5787:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  960): Recipient 5787
,V/BluetoothSapService( 6129): Sap Service onCreate
V/BluetoothSapService( 6129): initBinder
V/BluetoothSapService( 6129): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@3ce801ae
V/BluetoothSapService( 6129): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@c2372dc
,V/BluetoothSapService( 6129): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6129): state: 12
,D/SapServerProfile( 5456): Bluetooth service connected
,V/BluetoothSapService( 6129): Starting SAP server process
,D/A2dpService( 6129): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@8b68aba
,D/A2dpSinkService( 6129): getA2dpSinkService(): service is NULL
,V/BluetoothSapService( 6129): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6129): Sap Service initRfcommSocket
,D/BluetoothManagerService(  960): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,W/BluetoothAdapter( 6129): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6129): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6129): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6129): Write Extended Inquiry Response to controller
I/bt-btif ( 6129): BTA_JvRfcommStartServer
,I/bt-btm  ( 6129): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6129):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6129): Succeed to create listening socket 
V/BluetoothSapService( 6129): Accepting socket connection...
,D/wpa_supplicant( 6162): EAPOL: disable timer tick,
,D/wpa_supplicant( 6162): EAPOL: disable timer tick,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/ContactMessageStore( 1527): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1527): MSG_NOTIFY_CS_TO_SYNC <<
,I/jxcore-log( 6075): BLE advertisement not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 6075): 
,D/PMS     (  960): releaseWL(2d9c3455): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  960): acquireWL(b9321a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10024},
V/AlarmManager(  960): sending alarm PendingIntent{2c83c97a: PendingIntentRecord{29dc252b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142044, Int=0,
D/PMS     (  960): releaseWL(b9321a5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  960): [handleMessage] DOWNLOAD_XTRA_DATA,
,D/GpsLocationProvider(  960): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true,
,W/ContextImpl(  960): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  960): acquireWL(10511d88): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{10024}
,V/AlarmManager(  960): sending alarm PendingIntent{8b93321: PendingIntentRecord{25a8a4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=169781, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{378cee59: PendingIntentRecord{976ca1e android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146681, Int=0
D/PMS     (  960): acquireWL(10f50346): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  960): [NET] android_getaddrinfofornet-, err=8
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  960): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  960): [NET] android_getaddrinfo_proxy+
D/libc    (  960): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  960): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  960): releaseWL(10511d88): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): releaseWL(10f50346): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): acquireWL(2d75e907): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/BatteryService(  960): n_update end
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): releaseWL(2d75e907): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  960): runPSCheck
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): >> updateStatus
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
D/PowerUI ( 1254): closing low battery warning: level=100
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: StaEnabledState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): << updateStatus
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1527): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HtcUPManager( 1254): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1254): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1497): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@5435c
,D/Process (  960): killProcessQuiet, pid=5551
I/ActivityManager(  960): Killing 5551:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 5551
,D/PMS     (  960): acquireWL(a9e8a34): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=179362, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{2bd4e05d: PendingIntentRecord{2aee0dd2 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=207389, Int=0,
V/AlarmManager(  960): sending alarm PendingIntent{378cee59: PendingIntentRecord{976ca1e android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=229794, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{11fe0ea3: PendingIntentRecord{6b415a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=185686, Int=0
,D/libc    (  960): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/libc    (  960): [NET] android_getaddrinfofornet-, err=8
D/libc    (  960): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  960): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  960): [NET] android_getaddrinfo_proxy+
D/libc    (  960): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  960): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): acquireWL(13042559): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1254): Weather sync is On
W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,D/PMS     (  960): releaseWL(a9e8a34): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/PMS     (  960): releaseWL(13042559): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  960): acquireWL(17fb351e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(17fb351e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): handleMessage: E msg.what=155652
D/PowerUI ( 1254): closing low battery warning: level=100
D/WifiController(  960): processMsg: DeviceActiveState
,D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  960): acquireWL(3358f1ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(3358f1ff): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1254): closing low battery warning: level=100,
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PMS     (  960): runPSCheck
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  960): acquireWL(20d4ebcc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=239362, Int=0,
V/AlarmManager(  960): sending alarm PendingIntent{648be15: PendingIntentRecord{25a8a4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=309094, Int=0
,D/PMS     (  960): acquireWL(3021852a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
V/AlarmManager(  960): sending alarm PendingIntent{144af8b8: PendingIntentRecord{12042691 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1450226620662, Int=0
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): releaseWL(3021852a): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(20d4ebcc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1254): Weather sync is On
W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  960): acquireWL(14aac9f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(14aac9f6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): runPSCheck
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PowerUI ( 1254): closing low battery warning: level=100
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
,D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): battery changed pluggedType: 2
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
I/RemoteViews( 1254): reapply : com.google.android.gms 4 40
D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5482): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5482): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5482): Ignoring header User-Agent because its value was null.
,D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5482): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5482): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5482): [NET] android_getaddrinfo_proxy+
D/libc    ( 5482): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5482): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  960): acquireWL(19c9ffe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end,
D/PMS     (  960): releaseWL(19c9ffe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+,
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): handleMessage: E msg.what=155652
I/HtcPowerSaver(  960): >> updateStatus
,D/WifiController(  960): processMsg: DeviceActiveState
,D/WifiController(  960): battery changed pluggedType: 2
,D/WifiController(  960): processMsg: StaEnabledState
D/PowerUI ( 1254): closing low battery warning: level=100
,D/WifiController(  960): processMsg: DefaultState
,D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): << updateStatus
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 4
,D/UsbnetService(  960): BroadcastReceiver::onReceive+,
,D/PMS     (  960): acquireWL(1c6ad601): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null,
D/UsbnetService(  960): onReceive BATTERY_CHANGED
I/BatteryService(  960): n_update end
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  960): releaseWL(1c6ad601): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/NotificationService(  960): plugged=true pluggin=true
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1254): closing low battery warning: level=100
,D/WifiController(  960): processMsg: StaEnabledState
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: DefaultState
D/HtcPowerSaver(  960): updateBatteryInfo
D/WifiController(  960): handleMessage: X
D/PMS     (  960): runPSCheck
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): Checking...
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  960): >> updateStatus
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  960): << updateStatus
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  419): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  960): acquireWL(2c779ca6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
,D/PMS     (  960): releaseWL(2c779ca6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
,D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/PMS     (  960): runPSCheck
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: E msg.what=155652
D/PowerUI ( 1254): closing low battery warning: level=100
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): battery changed pluggedType: 2
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  960): acquireWL(2f0c76e7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
,V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=359362, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{32333294: PendingIntentRecord{25a8a4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=618647, Int=0
,D/PMS     (  960): acquireWL(2badd13d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms},
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): releaseWL(2f0c76e7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  960): releaseWL(2badd13d): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1254): Weather sync is On,
,W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,D/ContactMessageStore( 1527): MSG_CHECK_DELETION >>,
D/ContactMessageStore( 1527): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1527): sku_id=118
D/ContactMessageStore( 1527): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1527): start background delete task...
,D/ContactMessageStore( 1527): size: 0 , 0,
D/ContactMessageStore( 1527): Background delete complete
,D/PMS     (  960): acquireWL(20f0dd32): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(20f0dd32): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
D/PMS     (  960): runPSCheck
D/HtcPowerSaver(  960): Checking...
I/HtcPowerSaver(  960): >> updateStatus
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): << updateStatus
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1254): closing low battery warning: level=100
,I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268),
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5482): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): ,	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5482): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1254): reapply : com.google.android.gms 4 40
,W/System  ( 5482): Ignoring header User-Agent because its value was null.
,D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5482): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5482): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5482): [NET] android_getaddrinfo_proxy+
D/libc    ( 5482): [NET] android_getaddrinfo_proxy get netid:0,
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND),
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5482): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): acquireWL(3ad268c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
,I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(3ad268c4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/UsbnetService(  960): onReceive BATTERY_CHANGED
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/WifiController(  960): handleMessage: E msg.what=155652
,D/PowerUI ( 1254): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  960): updateBatteryInfo
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/PMS     (  960): runPSCheck
D/WifiController(  960): processMsg: StaEnabledState
D/HtcPowerSaver(  960): Checking...
D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: X
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  960): << updateStatus
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5482): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5482): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5482): Ignoring header User-Agent because its value was null.
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5482): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5482): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5482): [NET] android_getaddrinfo_proxy+
D/libc    ( 5482): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5482): [NET] android_getaddrinfo_proxy-, NODATA
,I/RemoteViews( 1254): reapply : com.google.android.gms 5 40
,D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  960): acquireWL(2c826606): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
,V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=659362, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{1d3f74c7: PendingIntentRecord{22838af4 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1450227292760, Int=0
,D/SmartSyncUtils( 5972): isEpsOn(), nState = 0,
,D/PMS     (  960): releaseWL(2c826606): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1254): Weather sync is On
W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,D/PMS     (  960): acquireWL(3310b21d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5972 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5972): [updateNmRange] bManual = false,
D/SmartSyncScreenOnOffTimeReceiver( 5972): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5972): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 5972): SettingOnTime = 1450245600000, randomSettingOnTime = 1450242931000
D/SmartSyncScreenOnOffTimeReceiver( 5972): SettingOffTime = 1450310400000, randomSettingOffTime = 1450316250000
,D/SmartSyncScreenOnOffTimeReceiver( 5972): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5972): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5972): bNightModeTurnOffOnce = false
,D/PMS     (  960): releaseWL(3310b21d): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  960): acquireWL(33cedc92): PARTIAL_WAKE_LOCK  *alarm* 0x1 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{1349663: PendingIntentRecord{3cc86260 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_TURN_OFF_NETWORK_BY_CHECK, t=0, cnt=1, w=1450227292830, Int=0
,W/ContextImpl( 5972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,V/AlarmManager(  960): sending alarm PendingIntent{dfa2fde: PendingIntentRecord{11d035bf com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1450227003993, Int=1800000
,D/SmartSyncDataLinkTurnOffService( 5972): SMARTSYNC_TURN_OFF_NETWORK, current time = 1450227292843, randomOffTime = 1450316250000, newRandomOffTime = 1450316250000
D/SmartSyncDataLinkTurnOffService( 5972): SMARTSYNC_TURN_OFF_NETWORK, randomWifiOnTime = 0, randomMobileOnTime = 1450242931000
,I/ActivityManager(  960): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6308 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  960): sending alarm PendingIntent{16c1448c: PendingIntentRecord{237507d5 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1450227063988, Int=0,
,V/AlarmManager(  960): sending alarm PendingIntent{311e0734: PendingIntentRecord{1633195d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806685, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{24f56bea: PendingIntentRecord{2ae6a214 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450227242439, Int=0
,D/PMS     (  960): acquireWL(245c6edb): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4188 10024 WorkSource{10024 com.google.android.gms}
,W/ContextImpl( 5972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/SmartSyncUtils( 5972): getMobilePolicyEnabled, result = true
,D/PMS     (  960): acquireWL(1eb65cb6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4188 10024 WorkSource{10024 com.google.android.gms}
D/SmartSyncDataLinkTurnOffService( 5972): turnOffMobile bPolicyEnabled = true
D/PMS     (  960): releaseWL(245c6edb): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/PowerUsageList:PowerUsageHelper( 5972): MY_DEBUG = false
D/PMS     (  960): releaseWL(33cedc92): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PowerUsageService( 5972): repeat time = 1450228192890
,D/SmartSyncUtils( 5972): isWifiHotSpotEnabled = false
,D/SmartSyncDataLinkTurnOffService( 5972): turnOffMobile bCheckMobileData = false,
,D/LocationManagerService(  960): getProviders()=[gps, network]
D/LocationManagerService(  960): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
,D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/SmartSyncDataLinkTurnOffService( 5972): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
,D/SmartSyncUtils( 5972): isCharging status = 5
,D/SmartSyncDataLinkTurnOffService( 5972): turnOffWifi ui setting = true
,D/SmartSyncUtils( 5972): isWifiHotSpotEnabled = false
I/ActivityManager(  960): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 5972): Failed to find provider info for com.htc.vowifi
D/SmartSyncUtils( 5972): state = 0
,D/SmartSyncDataLinkTurnOffService( 5972): turnOffWifi bCheckWifiData = false,
I/EventLogService( 4188): Aggregate from 1450225203934 (log), 1450225203934 (data)
D/SmartSyncDataLinkTurnOffService( 5972): turnOffWifi bWifiConnected = false
D/LocationManagerService(  960): getProviders()=[gps, network]
,D/LocationManagerService(  960): getBestProvider(Criteria[power=NO_REQ acc=---], false)=gps
D/LocationManagerService(  960): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/SmartSyncDataLinkTurnOffService( 5972): isDeviceMoving = false, Postion_different = 0.0, bLatLngValue = true, orgPosLat = 0.0, orgPosLng = 0.0, curPosLat = 0.0, curPosLng = 0.0
D/SmartSyncUtils( 5972): isCharging status = 5
,I/PowerUsageList:PowerUsageHelper( 5972): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 5972): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  960): releaseWL(1eb65cb6): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,E/cutils-trace( 6331): Error opening trace file: Permission denied (13),
I/dex2oat ( 6331): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6331): dex2oat: override thread count:4
,I/dex2oat ( 6331): dex2oat took 583.312ms (threads: 4)
,I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6308): ApplicationMonitor {1a00724c}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6308): PnsModel {287c827f}: update(): Update registration caused by: alarm,
,I/PushClient( 6308): PnsConfigModel {295f8a02}: <init>(): Use dm-client for provisioning.
,W/System.err( 6308): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6308): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6308): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6308): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  960): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6338 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/art     (  406): Explicit concurrent mark sweep GC freed 8626(366KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 416us total 52.996ms
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 237us total 25.034ms,
,I/DeviceManagement( 6338): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6338 dbg=false s=true,
,I/art     (  406): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 177us total 24.941ms,
,I/DeviceManagement( 6338): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6338): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6338): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6338): WorkflowService: Starting workflow service
,I/DeviceManagement( 6338): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@111e736e] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6338): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6338): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6338): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6338): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6338): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6338): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6338): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6338): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@111e736e]
I/DeviceManagement( 6338): WorkflowService: Stopping workflow service
,D/Process (  960): killProcessQuiet, pid=5406
I/ActivityManager(  960): Killing 5406:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 ,
,I/PushClient( 6308): PnsModel {287c827f}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  960): Recipient 5406
,D/Process (  960): killProcessQuiet, pid=5699
,I/ActivityManager(  960): Killing 5699:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 5699
,D/PMS     (  960): acquireWL(18ed5f66): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(18ed5f66): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): onReceive BATTERY_CHANGED,
D/NotificationService(  960): plugged=true pluggin=true
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive-
,D/HtcPowerSaver(  960): Checking...
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): battery changed pluggedType: 2
D/WifiController(  960): processMsg: DeviceActiveState
D/PowerUI ( 1254): closing low battery warning: level=100
,D/WifiController(  960): processMsg: StaEnabledState
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  960): processMsg: DefaultState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
,D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): << updateStatus
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true,
,D/PMS     (  960): acquireWL(1f06e2a7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
,I/bt-btm  ( 6129): Received oneshot timer event complete
,V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1019362, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{3279354: PendingIntentRecord{2db582fd com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1029072, Int=0
,I/bt-btm  ( 6129): btm_ble_timeout
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
,D/PMS     (  960): acquireWL(10e00bf2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6129 1002 null
,D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 8a df 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/PMS     (  960): releaseWL(1f06e2a7): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = cd 78 73 77 d8 c5 d8 b6 d3 b5 53 46 9d 2e 7f b7 
I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6129): Stopping oneshot timer
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
D/WeatherUtility( 1254): Weather sync is On
,W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,D/PMS     (  960): releaseWL(10e00bf2): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  960): acquireWL(22350243): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
,I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(22350243): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  960): updateBatteryInfo
,D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1254): closing low battery warning: level=100
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  960): runPSCheck
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  960): Checking...
D/UsbnetService(  960): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  960): >> updateStatus
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  960): battery changed pluggedType: 2
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/WifiController(  960): handleMessage: E msg.what=155652
D/WifiController(  960): processMsg: DeviceActiveState
D/WifiController(  960): processMsg: StaEnabledState
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  960): << updateStatus
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  960): acquireWL(3a1490c0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000},
V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1079362, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{335c51f9: PendingIntentRecord{25a8a4 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1175862, Int=0
,D/PMS     (  960): acquireWL(1edef53e): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1913 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1913): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1913): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1913): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1913): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1913): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1913): [NET] android_getaddrinfo_proxy-, NODATA,
D/PMS     (  960): releaseWL(1edef53e): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  960): releaseWL(3a1490c0): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1254): Weather sync is On
,W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  960): User[0] Flushing usage stats to disk
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
,W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	,at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5482): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5482): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5482): Ignoring header User-Agent because its value was null.
,D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5482): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5482): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5482): [NET] android_getaddrinfo_proxy+
D/libc    ( 5482): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
I/RemoteViews( 1254): reapply : com.google.android.gms 4 40
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5482): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  960): acquireWL(2ccda9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 960 1000 null
,I/BatteryService(  960): n_update end
D/PMS     (  960): releaseWL(2ccda9f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1254): closing low battery warning: level=100
I/IntentController( 1254): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  960): plugged=true pluggin=true
D/DotMatrix( 1340): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1340): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/UsbnetService(  960): BroadcastReceiver::onReceive+
D/PowerUI ( 1254): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  960): onReceive BATTERY_CHANGED
,D/WifiController(  960): battery changed pluggedType: 2,
D/UsbnetService(  960):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  960): updateBatteryInfo
D/UsbnetService(  960): BroadcastReceiver::onReceive-
D/PMS     (  960): runPSCheck
D/HeadsetStateMachine( 6129): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  960): Checking...,
D/WifiController(  960): handleMessage: E msg.what=155652
I/HtcPowerSaver(  960): >> updateStatus
D/WifiController(  960): processMsg: DeviceActiveState
I/HtcPowerSaver(  960): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  960): processMsg: StaEnabledState
I/HtcPowerSaver(  960): << updateStatus
D/WifiController(  960): processMsg: DefaultState
D/WifiController(  960): handleMessage: X
,I/BatteryController( 1254): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5482): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5482): 	,at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5482): Ignoring header User-Agent because its value was null.
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5482): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5482): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5482): [NET] android_getaddrinfo_proxy+
D/libc    ( 5482): [NET] android_getaddrinfo_proxy get netid:0
D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5482): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  960): Explicit concurrent mark sweep GC freed 23784(1280KB) AllocSpace objects, 12(968KB) LOS objects, 33% free, 16MB/24MB, paused 1.841ms total 167.396ms,
,I/RemoteViews( 1254): reapply : com.google.android.gms 3 40,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/ProcessStatsService(  960): Prepared write state in 23ms
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1913): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1913): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1913): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1913): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1913): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5482): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5482): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5482): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5482): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5482): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5482): Ignoring header User-Agent because its value was null.
,D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5482): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5482): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5482): [NET] android_getaddrinfofornet-, pass to proxy
I/RemoteViews( 1254): reapply : com.google.android.gms 3 40
D/libc    ( 5482): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5482): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5482): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1340): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1340): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  960): acquireWL(289f09e4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000}
V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1199362, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{311e0734: PendingIntentRecord{1633195d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1732249, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{18be61f1: PendingIntentRecord{3c4d51d6 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825769, Int=1800000
V/AlarmManager(  960): sending alarm PendingIntent{b12de4d: PendingIntentRecord{33524d02 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1852409, Int=0
V/AlarmManager(  960): sending alarm PendingIntent{3f0d9613: PendingIntentRecord{2234e050 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1865878, Int=0
,V/AlarmManager(  960): sending alarm PendingIntent{3abc1249: PendingIntentRecord{2ae6a214 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1450228192890, Int=0
D/Process (  960): killProcessQuiet, pid=5943
I/ActivityManager(  960): Killing 5943:com.htc.bgp/u0a11 (adj 13): empty for 1800s
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 5943
,I/ActivityManager(  960): Killing 5919:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1805s
D/Process (  960): killProcessQuiet, pid=5919
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 5919,
,I/ActivityManager(  960): Killing 5867:com.htc.sense.mms/u0a64 (adj 15): empty for 1809s
,D/Process (  960): killProcessQuiet, pid=5867
,D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 5867
,D/Process (  960): killProcessQuiet, pid=5482
I/ActivityManager(  960): Killing 5482:com.android.vending/u0a72 (adj 15): empty for 1812s
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  960): Recipient 5482
,D/PMS     (  960): acquireWL(3d1c374e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 960 1000 null
,V/NetworkPolicy(  960): updateNetworkEnabledLocked()
V/NetworkPolicy(  960): updateNotificationsLocked()
D/PMS     (  960): releaseWL(3d1c374e): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WeatherUtility( 1254): Weather sync is On
W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,D/LocationManagerService(  960): getAllProviders()=[passive, gps, network]
,W/ContextImpl( 5972): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  960): releaseWL(289f09e4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 5972): MY_DEBUG = false
,D/PowerUsageService( 5972): repeat time = 1450229093515,
,I/GLSUser ( 1913): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1913): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1913): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1913): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1913): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PowerUsageList:PowerUsageHelper( 5972): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 5972): gen(), null == sipper.uidObj, userId = 0
,I/ActivityManager(  960): Killing 6030:com.htc.calendar/u0a10 (adj 13): empty for 1804s,
D/Process (  960): killProcessQuiet, pid=6030
D/Process (  960): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  960): Recipient 6030,
,D/PMS     (  960): acquireWL(24bafe75): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 960 1000 WorkSource{1000},
V/AlarmManager(  960): sending alarm PendingIntent{1b8288a8: PendingIntentRecord{16278fc1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1919362, Int=0,
,I/bt-btm  ( 6129): Received oneshot timer event complete
V/AlarmManager(  960): sending alarm PendingIntent{20a42e0a: PendingIntentRecord{11aad67b com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1929087, Int=0
,I/bt-btm  ( 6129): btm_ble_timeout
D/PMS     (  960): acquireWL(3138fc98): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6129 1002 null
I/bt-btm  ( 6129): btm_gen_resolvable_private_addr
,D/bt-btm  ( 6129): btm_ble_rand_enc_complete
I/bt-btm  ( 6129): btm_gen_resolve_paddr_low
,D/bt-smp  ( 6129): smp_encrypt_data
W/bt-smp  ( 6129): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6129): Plain text(LSB ~ MSB) = 52 76 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6129): Encrypted text(LSB ~ MSB) = e5 93 c1 51 b7 f6 28 4c 5e e3 63 d1 1d 50 6f c1 
I/bt-btm  ( 6129): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6129): Stopping oneshot timer
D/bt-btm  ( 6129): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  960): releaseWL(24bafe75): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1254): Weather sync is On
W/WeatherTimeKeeper( 1254): [refreshWeatherData] no weather data
,D/PMS     (  960): releaseWL(3138fc98): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,TIME-OUT KILL (timeout was 1800000ms)
```
