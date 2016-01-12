#### Test 55613145ac448d4_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  926): acquireWL(39357caf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000}
V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=117086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{61d98bc: PendingIntentRecord{3c8b8045 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1452596527759, Int=0
D/PMS     (  926): acquireWL(2d8d39a): PARTIAL_WAKE_LOCK  *backup* 0x1 926 1000 null
W/BackupManagerService(  926): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
E/BackupManagerService(  926): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/PMS     (  926): releaseWL(2d8d39a): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/PMS     (  926): releaseWL(39357caf): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
--------- beginning of main
D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/Process (  926): killProcessQuiet, pid=5109
I/ActivityManager(  926): Killing 5109:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  926): Recipient 5109
E/cutils-trace( 5906): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5906): ====startRecUseTime====
D/htc.customization.log.level( 5906):  is 
W/CustomizationLogLevel( 5906): Level value is invalid, use default level 2
D/CustomizationManager( 5906):  Read ACC file spent 0.040 (s)
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5906): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5906): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5906): Parsing tag category name = system
I/CustomizationCIDLoader( 5906): Parsing tag category name = application
I/CustomizationCIDLoader( 5906): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5906): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5906): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5906): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5906): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5906): add string-array item, value = 42507
I/CustomizationCIDLoader( 5906): add string-array item, value = 21902
I/CustomizationCIDLoader( 5906): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5906): add string-array item, value = 23420
I/CustomizationCIDLoader( 5906): add string-array item, value = 22299
I/CustomizationCIDLoader( 5906): add string-array item, value = 24002
I/CustomizationCIDLoader( 5906): add string-array item, value = 23210
I/CustomizationCIDLoader( 5906): add string-array item, value = 23205
I/CustomizationCIDLoader( 5906): add string-array item, value = 23806
I/CustomizationCIDLoader( 5906): add string-array item, value = 23430
I/CustomizationCIDLoader( 5906): add string-array item, value = 23408
I/CustomizationCIDLoader( 5906): add string-array item, value = 27205
I/CustomizationCIDLoader( 5906): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5906): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5906):  Read CID file spent 0.084 (s)
D/CustomizationManager( 5906):  All configurations done spent 0.084 (s)
D/PMS     (  926): acquireHCC(9e734cb): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 926 1000 null
I/ActivityManager(  926): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5906 on display 0
D/PMS     (  926): acquireHCC(98984a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 926 1000 null
W/asset   (  926): Copying FileAsset 0x55a8c41f60 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  926): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5924 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1309): [EventService]  onDisplayChanged: 0
V/ActivityManager(  926): Display changed displayId=0
D/DotMatrix( 1309): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 5924): Copying FileAsset 0xac1fb348 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1534): [trimMemory] 20
I/WebViewFactory( 5924): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5924): Time to load native libraries: 9 ms (timestamps 5570-5579),
,I/LibraryLoader( 5924): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5924): Binding Chromium to main looper Looper (main, tid 1) {e02f9be},
I/LibraryLoader( 5924): Expected native library version number "",actual native library version number ""
,I/chromium( 5924): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5924): Initializing chromium process, singleProcess=true,
,W/art     ( 5924): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5924): ApplicationContext is null in ApplicationStatus,
,W/chromium( 5924): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.,
,W/chromium( 5924): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 5924): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 5924): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5924): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5924): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5924): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5924): Local Branch: 
I/Adreno-EGL( 5924): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5924): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5924):                  d74aa161a12b9c6fc6332151
,D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  926): java.lang.Throwable: stack dump
W/System.err(  926): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  926): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  926): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  926): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  926): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e2c41f9:true
D/BluetoothAdapter( 5924): 810304309: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5924): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5924): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5924): CordovaWebView is running on device made by: HTC
,W/art     ( 5924): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 5924): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  926): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/chromium( 5924): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  926): setSystemUiVisibility(0xc0000000)
D/StatusBarManagerService(  926): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  926): hiding MENU key
,D/StatusBarManagerService(  926): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  926): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  926): hiding MENU key
,D/FindExtension( 5924): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 5924): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2261c788, mServedView=org.apache.cordova.engine.SystemWebView{99d9521 VFEDH.C. .F....ID 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@140ebd46
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
I/InputMethodManagerService(  926): Disable input method client, pid=1534
D/StatusBarManagerService(  926): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 5924): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  926): Displayed com.test.thalitest/.MainActivity: +633ms (total +678ms),
,W/BindingManager( 5924): Cannot call determinedVisibility() - never saw a connection for the pid: 5924,
,D/JsMessageQueue( 5924): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5924): JniHelper::setJavaVM(0xab08e8f8), pthread_self() = -1405410608
,D/JX-Cordova( 5924): jxcore cordova android initializing
,W/jxcore-log( 5924): Initializing JXcore engine,
W/jxcore-log( 5924): JXcore engine is ready
,W/jxcore-log( 5924): Starting JXcore engine
,W/jxcore-log( 5924): Platform android,
W/jxcore-log( 5924): 
W/jxcore-log( 5924): Process ARCH arm
W/jxcore-log( 5924): 
,D/PMS     (  926): releaseHCC(9e734cb): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  926): releaseHCC(98984a8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 5924): JXcore Cordova bridge is ready!,
I/jxcore-log( 5924): 
W/jxcore-log( 5924): JXcore engine is started
,I/Choreographer( 5924): Skipped 98 frames!  The application may be doing too much work on its main thread.,
I/chromium( 5924): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5924): Toggling radios to true
I/jxcore-log( 5924): 
,D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  926): checking for enable restriction...
D/BluetoothManagerService(  926): checkBTEasState, ret=true
I/BluetoothManagerService(  926): isBluetoothRestricted(): false
D/BluetoothManagerService(  926): enable(): region ID = 6
D/BluetoothManagerService(  926): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  926): MONITOR_LOG
W/Settings:Agent(  926): name: bluetooth_on
W/Settings:Agent(  926): value: 1
W/Settings:Agent(  926): >> traceCallingStack()
W/Settings:Agent(  926): Process.myPid(): 926
W/Settings:Agent(  926): Process.myTid(): 5042
,W/Settings:Agent(  926): Process.myUid(): 1000
W/Settings:Agent(  926): 
W/Settings:Agent(  926): 
W/System.err(  926): java.lang.Throwable: stack dump
,W/System.err(  926): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  926): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  926): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  926): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  926): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  926): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  926): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  926): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  926): 	,at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  926): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  926): 
W/Settings:Agent(  926): << traceCallingStack(): 7(ms)
,D/BluetoothManagerService(  926): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  926): MESSAGE_ENABLE: mBluetooth = null
,D/WifiManager( 5924): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,D/WifiService(  926): New client listening to asynchronous messages
E/WifiTrafficPoller(  926): ADD_CLIENT: 7
D/WifiService(  926): setWifiEnabled: true pid=5924, uid=10366
E/WifiService(  926): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  926): isSprintWifiRestricted(): false
I/WifiService(  926): isMdmWifiRestricted(): false
W/Settings:Agent(  926): MONITOR_LOG
W/Settings:Agent(  926): name: wifi_on
W/Settings:Agent(  926): value: 2
W/Settings:Agent(  926): >> traceCallingStack()
W/Settings:Agent(  926): Process.myPid(): 926
W/Settings:Agent(  926): Process.myTid(): 1711
W/Settings:Agent(  926): Process.myUid(): 1000
W/Settings:Agent(  926): 
W/Settings:Agent(  926): 
W/System.err(  926): java.lang.Throwable: stack dump
,W/System.err(  926): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  926): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  926): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  926): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  926): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  926): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  926): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  926): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  926): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  926): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  926): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  926): 
W/Settings:Agent(  926): << traceCallingStack(): 6(ms)
,I/ActivityManager(  926): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5980 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiController(  926): handleMessage: E msg.what=155656,
D/WifiController(  926): processMsg: ApStaDisabledState
D/WifiManager( 5924): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  926): transitionTo: destState=DeviceActiveState
D/WifiController(  926): handleMessage: new destination call exit/enter
D/WifiController(  926): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  926): invokeExitMethods: ApStaDisabledState
D/WifiController(  926): moveTempStackToStateStack: i=1,j=1
D/WifiController(  926): moveTempStackToStateStack: i=0,j=2
D/WifiController(  926): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  926): invokeEnterMethods: StaEnabledState
D/WifiController(  926): invokeEnterMethods: DeviceActiveState
D/PMS     (  926): acquireWL(36edfbb4): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 926 1000 null
E/WifiStateMachine(  926): handleMessage: E msg.what=131083
E/WifiStateMachine(  926): setting operational mode to 1
E/WifiStateMachine(  926): processMsg: InitialState
D/WifiController(  926): handleMessage: X
E/WifiStateMachine(  926):  InitialState CMD_START_SUPPLICANT 0 0
D/WifiManager( 5924): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 5924): Radios toggled
I/jxcore-log( 5924): 
,I/jxcore-log( 5924): My device name is: HTC-HTC One M8s
I/jxcore-log( 5924): 
,W/ResourcesManager( 5980): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5980): Adding HeadsetService,
,D/AdapterServiceConfig( 5980): Adding A2dpService,
D/AdapterServiceConfig( 5980): Adding HidService
D/AdapterServiceConfig( 5980): Adding HealthService
D/AdapterServiceConfig( 5980): Adding PanService
D/AdapterServiceConfig( 5980): Adding GattService
,W/linker  ( 5980): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  926): java.lang.Throwable: stack dump
,W/System.err(  926): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  926): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  926): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  926): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  926): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29034e23:true
D/BluetoothAdapterState( 5980): make
I/BluetoothAdapterState( 5980): Entering OffState
,E/bt_osi_config( 5980): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
D/BluetoothManagerService(  926): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  926): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  926): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 5980): Address is:90:E7:C4:F6:69:77
,D/Tethering(  926): interfaceAdded wlan0
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  926): releaseWL(36edfbb4): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,D/BluetoothManagerService(  926): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  926): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 1799): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1d1ff018
D/BluetoothAdapter( 1799): onBluetoothServiceUp done
D/libc    (  926): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  926): [NET] android_getaddrinfofornet-, SUCCESS
D/Tethering(  926): interfaceLinkStateChanged wlan0, false
D/Tethering(  926): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 2355): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@35fa764b
D/Tethering(  926): interfaceAdded p2p0
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 2355): onBluetoothServiceUp done
D/Tethering(  926): p2p0 is not a tetherable iface, ignoring
D/Tethering(  926): interfaceLinkStateChanged p2p0, false
D/Tethering(  926): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter(  926): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3242211
D/BluetoothAdapter(  926): onBluetoothServiceUp done
D/BluetoothAdapter( 1475): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@23b842f7
D/BluetoothAdapter( 1475): onBluetoothServiceUp done
D/BluetoothAdapter( 1222): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2765e354
D/BluetoothAdapter( 1222): onBluetoothServiceUp done
D/BluetoothAdapter( 1496): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@22bf4e6e
D/BluetoothAdapter( 1496): onBluetoothServiceUp done
,D/BluetoothAdapter( 5924): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1155faed
D/BluetoothAdapter( 5924): onBluetoothServiceUp done
D/BluetoothAdapter( 5980): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@351b893b
D/BluetoothAdapter( 5980): onBluetoothServiceUp done
,D/BluetoothAdapter( 3514): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@19563a5
D/BluetoothAdapter( 3514): onBluetoothServiceUp done
D/BluetoothManagerService(  926): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 5980): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON,
V/Tethering(  926): TetherInterfaceSM: wlan0: enter InitialState
D/BluetoothAdapterProperties( 5980): Setting state to 11
I/BluetoothAdapterState( 5980): Bluetooth adapter state changed: 10-> 11
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  926): setWifiState: enabling
E/WifiStateMachine(  926): Supplicant start successful
D/WifiMonitor(  926): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  926): connecting to supplicant
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothManagerService(  926): +onBluetoothStateChange prev=10 new=11
,I/ActivityManager(  926): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6015 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
,D/Tethering(  926): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering(  926): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  926): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  926): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  926): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  926): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  926): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  926): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 5980): make
D/UsbnetService(  926): BroadcastReceiver::onReceive+,
,D/PMS     (  926): acquireWL(1317ce4d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 926 1000 null
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothAdapterService( 5980): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 5980): checkA2dpState: returning
D/BluetoothAdapterService( 5980): checkHfpState: isHfpClientEnabled = false
I/BluetoothBondStateMachine( 5980): StableState(): Entering Off State
E/BluetoothAdapterService( 5980): checkHfpState: returning
,V/BluetoothPbapReceiver( 5980): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5980): ***********state = 11
,I/BluetoothAdapterState( 5980): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/PMS     (  926): releaseWL(1317ce4d): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
V/NetworkPolicy(  926): updateNetworkEnabledLocked()
V/NetworkPolicy(  926): updateNotificationsLocked()
,D/NGFService( 3514): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED,
,D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/BluetoothHeadset( 1475): Proxy object connected
D/HeadsetService( 5980): Received start request. Starting profile...
,D/HeadsetStateMachine( 5980): Version 1.5
D/UsbDeviceManager(  926): [USBNET] bCheckSuppFunc: cdc_network
D/HeadsetStateMachine( 5980): make
D/UsbnetService(  926): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/BluetoothHeadset(  926): Proxy object connected
,D/BluetoothPhoneService( 1475): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1475): Proxy object connected
,D/BluetoothHeadset( 1475): Proxy object connected
,I/ActivityManager(  926): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6039 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
,D/BluetoothAdapter(  926): 163849355: getState(). Returning 11
I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
D/BluetoothHeadset( 1222): Proxy object connected
,D/HeadsetStateMachine( 5980): max_hf_connections = 2
D/wpa_supplicant( 6014): wpa_supplicant v2.3-devel-5.0.2
,D/BluetoothAdapter( 1475): 554050509: getState(). Returning 11
,D/wpa_supplicant( 6014): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6014): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 6014): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6014): Global control interface '@android:wpa_wlan0'
,D/wpa_supplicant( 6014): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6014): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6014): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6014): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6014): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
,I/QuickSettingMiniLite( 1222): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@389d92fd,
D/HeadsetPhoneState( 5980): listenForPhoneState..for service and signal 
D/wpa_supplicant( 6014): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6014): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6014): update_config=1
D/wpa_supplicant( 6014): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6014): device_name='Android_608e'
D/wpa_supplicant( 6014): manufacturer='HTC'
D/wpa_supplicant( 6014): model_name='HTC_PHONE'
D/wpa_supplicant( 6014): model_number='1234'
D/wpa_supplicant( 6014): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6014): p2p_oper_reg_class=126
D/wpa_supplicant( 6014): p2p_oper_channel=149
D/wpa_supplicant( 6014): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6014): persistent_reconnect=1
D/wpa_supplicant( 6014): key_mgmt_offload=1
I/wpa_supplicant( 6014): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6014): nl80211: RFKILL status not available
D/wpa_supplicant( 6014): nl80211: Using driver-based roaming
D/wpa_supplicant( 6014): nl80211: TDLS supported
D/wpa_supplicant( 6014): nl80211: TDLS external setup
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6014): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
,D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
,D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6014): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6014): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6014): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6014): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6014): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a0badfd0
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=0104
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=040a
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=040b
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=040c
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=040d
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=090a
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=090b
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=090c
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=090d
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=0409506f9a09
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=7f506f9a09
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=0801
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=040e
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=06
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=0a07
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=0a11
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0badfd0 match=0a1a
D/wpa_supplicant( 6014): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/Tethering(  926): interfaceLinkSta,teChanged p2p0, false
D/Tethering(  926): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6014): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6014): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6014): htc_wext_command_init +
E/wpa_supplicant( 6014): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6014): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  926): interfaceLinkStateChanged p2p0, false
D/Tethering(  926): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetDualPhoneStateListener_SLOT1( 5980): listen phone state by slot:SLOT1  id:-1
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/HeadsetDualPhoneStateListener_SLOT2( 5980): listen phone state by slot:SLOT2  id:-100
D/HeadsetStateMachine( 5980): Enter Disconnected: -2, size: 0
D/HeadsetDualPhoneStateListener_SLOT1( 5980): listen phone state by slot:SLOT1  id:-1
D/BluetoothAdapterService( 5980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6506a1f
D/HeadsetDualPhoneStateListener_SLOT2( 5980): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 5980): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 5980): BTHF: set_current_device
D/BluetoothA2dp(  926): Proxy object connected
D/A2dpService( 5980): Received start request. Starting profile...
D/BluetoothAdapter(  926): 163849355: getState(). Returning 11
V/Avrcp   ( 5980): make
D/HtcWiFiWidget_WiFiWidgetProvider( 6015): onWiFiStateChanged() for widget: 
D/HtcWiFiWidget_WiFiWidgetProvider( 6015): updateWidget(context) for widget: 
E/RemoteController( 5980): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 5980): make
D/HtcBtWidget_BTWidgetProvider( 6039): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 6039): updateWidget(context) for widget: 
D/bt-btif ( 5980): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/ActivityManager(  926): Killing 5659:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  926): killProcessQuiet, pid=5659
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
D/A2dpService( 5980): setA2dpService(): set to: null
D/BluetoothAdapterService( 5980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6506a1f
D/A2dpStateMachine( 5980): Enter Disconnected: -2
D/TetherSettings( 5420): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/HidService( 5980): Received start request. Starting profile...
D/        ( 5420): Cust_ConnectToPC   : Internet_Sharing>true
D/BluetoothAdapterService( 5980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6506a1f
D/        ( 5420): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5420): Cust_ConnectToPC   : spcsc>false
D/        ( 5420): Cust_ConnectToPC   : IPT>true
D/        ( 5420): Cust_ConnectToPC   : Singel_USB>false
D/HealthService( 5980): Received start request. Starting profile...
W/Settings( 5420): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5420): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5420): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/BluetoothAdapterService( 5980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6506a1f
D/SmartNS_NSReceiver( 5420): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/PanService( 5980): Received start request. Starting profile...
,D/PanService( 5980): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 5980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6506a1f
D/BtGatt.DebugUtils( 5980): handleDebugAction() action=null
D/BtGatt.GattService( 5980): Received start request. Starting profile...
D/BtGatt.GattService( 5980): start()
D/BtGatt.AdvertiseManager( 5980): advertise manager created
D/BluetoothAdapter( 1222): 916866108: getState(). Returning 11
I/QuickSettingMiniLite( 1222): updateLiteState:no connect device!
,I/wpa_supplicant( 6014): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 6014):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6014):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6014):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6014): nl80211: Flush PMKIDs
D/wpa_supplicant( 6014): p2p0: State: DISCONNECTED -> INACTIVE
I/ActivityManager(  926): Recipient 5659
,I/SmartNS_Utility( 5420): setISNotification
,D/BluetoothAdapterService( 5980): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6506a1f
,D/SmartNS_Utility( 5420): usb_cable_connect = 1
,D/SmartNS_Utility( 5420): usb_denied = 0
I/SmartNS_PSService( 5420): usb notificaiton:true
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothAdapter( 1475): 554050509: getState(). Returning 11
W/BluetoothHeadset( 1475): Proxy not attached to service
D/wpa_supplicant( 6014): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6014): TDLS: Driver uses external link setup
D/wpa_supplicant( 6014): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,I/ActionCombine( 5420): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,I/HeadsetPhoneState( 5980): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 5980): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/SmartNS_Utility( 5420): usb_cable_connect = 1
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
D/HeadsetStateMachine( 5980): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 5980): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5980): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5980): Disconnected process message: 11, size: 0
I/bt-btu  ( 5980): btu_task pending for preload complete event
D/wpa_supplicant( 6014): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6014): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6014): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6014): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6014): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6014): Using existing control interface directory.
D/wpa_supplicant( 6014): P2P: Add operating class 81
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_Utility( 5420): usb_denied = 0
I/SmartNS_PSService( 5420): usb notificaiton:true
D/wpa_supplicant( 6014): P2P: Own listen channel: 81:1
D/wpa_supplicant( 6014): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6014): P2P: initialized
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6014): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6014): P2P: cli_channels:
D/wpa_supplicant( 6014): p2p0: Added interface p2p0
D/wpa_supplicant( 6014): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6014): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6014): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 6014): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6014): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6014): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/wpa_supplicant( 6014): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6014): disable_scan_offload=1
D/wpa_supplicant( 6014): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6014): update_config=1
D/wpa_supplicant( 6014): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6014): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6014): manufacturer='HTC'
D/wpa_supplicant( 6014): model_name='HTC One M8s'
D/wpa_supplicant( 6014): model_number='HTC One M8s'
D/wpa_supplicant( 6014): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6014): hs20=1
D/wpa_supplicant( 6014): interworking=1
D/wpa_supplicant( 6014): external_sim=1
,D/wpa_supplicant( 6014): key_mgmt_offload=1
E/bt_vendor( 5980): get_bt_soc_type: Failed to get soc type
D/BluetoothMasReceiver( 5980): Bluetooth STATE CHANGED to 11
,V/BluetoothSapReceiver( 5980): SapReceiver onReceive 
,V/BluetoothSapReceiver( 5980): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5980):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 5980): startService = false
D/AuthorizationBluetoothService( 1900): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/SmartNS_NSReceiver( 5420): Tethered state change:false isNSOpening:false
I/ActivityManager(  926): Killing 5682:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
,D/Process (  926): killProcessQuiet, pid=5682
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/qcom-bluetooth( 6074): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
D/wpa_supplicant( 6014): Priority group 481
D/wpa_supplicant( 6014):    id=0 ssid='NG700'
I/wpa_supplicant( 6014): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6014): nl80211: RFKILL status not available
D/wpa_supplicant( 6014): nl80211: Using driver-based roaming
D/wpa_supplicant( 6014): nl80211: TDLS supported
D/wpa_supplicant( 6014): nl80211: TDLS external setup
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6014): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6014): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Su,pported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/w,pa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6014): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6014): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6014): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6014): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6014): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6014): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6014): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6014): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6014): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a0bcd100
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=0104
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=040a
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=040b
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=040c
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=040d
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=090a
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=090b
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=090c
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=090d
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=0409506f9a09
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=7f506f9a09
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=0801
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=040e
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=06
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=0a07
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=0a11
D/wpa_supplicant( 6014): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a0bcd100 match=0a1a
D/wpa_supplicant( 6014): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6014): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6014): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6014): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6014): htc_wext_command_init +
I/wpa_supplicant( 6014): htc_wext_command_init -
I/wpa_supplicant( 6014): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6014): Don't set 00 to countryID.conf
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6014): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6014): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6014): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/Tethering(  926): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6014): P2P: Add operating class 81
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/Tethering(  926): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 6014): P2P: Update channel list
D/wpa_supplicant( 6014): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6014): P2P: cli_channels:
D/wpa_supplicant( 6014): p2p0: Updating hw mode
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6014): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6014): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6014): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
I/qcom-bluetooth( 6080): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6081): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
I/ActivityManager(  926): Recipient 5682
I/qcom-bluetooth( 6083): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
I/qcom-bluetooth( 6084): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 6085): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6086): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/RemoteViews( 1222): reapply : com.android.settings 1 36,
,I/wpa_supplicant( 6014): wapi_supplicant_init: Init WAI packet wlan0,
D/wpa_supplicant( 6014):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6014):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6014):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0,
D/wpa_supplicant( 6014): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6014): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6014): nl80211: Flush PMKIDs
,D/wpa_supplicant( 6014): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 6014): TDLS: Driver uses external link setup
D/wpa_supplicant( 6014): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6014): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6014): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6014): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6014): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6014): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6014): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6014): Using existing control interface directory.
,I/wpa_supplicant( 6014): set country (DE) from /data/misc/wifi/countryID.conf,
I/wpa_supplicant( 6014): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6014): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6014): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6014): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6014): P2P: Add operating class 81
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6014): P2P: Add operating class 115
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6014): P2P: Add operating class 116
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6014): P2P: Add operating class 117
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6014): P2P: Update channel list
D/wpa_supplicant( 6014): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6014): P2P: cli_channels:
D/wpa_supplicant( 6014): p2p0: Updating hw mode
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6014): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6014): Auto country group 1: ch36
D/wpa_supplicant( 6014): wlan0: Added interface wlan0
D/wpa_supplicant( 6014): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6014): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6014): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6014): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 6014): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6014): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_926-2\x00
D/wpa_supplicant( 6014): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6014): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6014): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6014): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6014): nl80211: Regulatory domain change
D/wpa_supplicant( 6014):  * initiator=1
,D/wpa_supplicant( 6014):  * type=0
D/wpa_supplicant( 6014):  * alpha2=DE
D/wpa_supplicant( 6014): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6014): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6014): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
,D/wpa_supplicant( 6014): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6014): P2P: Add operating class 81
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6014): P2P: Add operating class 115
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6014): P2P: Add operating class 116
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6014): P2P: Add operating class 117
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6014): P2P: Update channel list
D/wpa_supplicant( 6014): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6014): P2P: cli_channels:
D/wpa_supplicant( 6014): p2p0: Updating hw mode
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6014): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  926): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  926): handleMessage: new destination call exit/enter
E/WifiStateMachine(  926): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  926): invokeExitMethods: InitialState
E/WifiStateMachine(  926): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  926): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  926): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131144
E/WifiStateMachine(  926): processMsg: SupplicantStartingState
E/WifiStateMachine(  926):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  926): deferMessage: msg=131144
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131085
E/WifiStateMachine(  926): processMsg: SupplicantStartingState
D/WifiMonitor(  926): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
E/WifiStateMachine(  926):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiMonitor(  926): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  926): deferMessage: msg=131085
E/WifiStateMachine(  926): handleMessage: X
E/WifiMonitor(  926): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  926): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  926): handleMessage: E msg.what=131149
E/WifiStateMachine(  926): processMsg: SupplicantStartingState
E/WifiStateMachine(  926):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  926): processMsg: DefaultState
E/WifiStateMachine(  926):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  926): setSuspendOptimizations: 2 true
E/WifiStateMachine(  926): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131145
E/WifiStateMachine(  926): processMsg: SupplicantStartingState
E/WifiStateMachine(  926):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  926): processMsg: DefaultState
E/WifiStateMachine(  926):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131146
,E/WifiStateMachine(  926): processMsg: SupplicantStartingState
E/WifiStateMachine(  926):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  926): processMsg: DefaultState
E/WifiStateMachine(  926):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131101
E/WifiStateMachine(  926): processMsg: SupplicantStartingState
E/WifiStateMachine(  926):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  926): processMsg: DefaultState
E/WifiStateMachine(  926):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  926): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  926): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=147457
E/WifiStateMachine(  926): processMsg: SupplicantStartingState
E/WifiStateMachine(  926):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  926): Supplicant connection established
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6014): set wifi ON
,E/WifiStateMachine(  926): setWifiState: enabled
,E/WifiStateMachine(  926): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  926):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6014): SET_SCREEN_ON:Off
I/wpa_supplicant( 6014): htc_wext_set_keepalive +
,I/wpa_supplicant( 6014): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6014): getPrivFuncNum +	
I/wpa_supplicant( 6014): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6014): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6014): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6014): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6014): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6014): htc_wext_set_keepalive - ret = 0
,I/WifiNative-HAL(  926): startHal
E/wifi    (  926): getStaticLongField sWifiHalHandle 0x7f5cdee300
,I/WifiNative-HAL(  926): Could not start hal
E/WifiStateMachine(  926): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  926): backgroundScan enabled=true startBackgroundScanIfNeeded:false
D/WifiDisplayAdapter(  926): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  926):     Client/Owner: Client
D/WifiDisplayAdapter(  926):     GroupId: 
D/WifiDisplayAdapter(  926):     Passphrase: 
D/WifiDisplayAdapter(  926):     SessionId: 0
D/WifiDisplayAdapter(  926):     IP Address: }
,E/WifiStateMachine(  926): handleScreenStateChanged Exit: false
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER MACADDR'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6014): update_config=1
D/wpa_supplicant( 6014): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED enabled
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiConfigStore(  926): Loading config and enabling all networks 
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6014): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6014): wpa_supplicant_ctrl_iface_list_networks: return size = 47
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/HtcWiFiWidget_WiFiWidgetProvider( 6015): onWiFiStateChanged() for widget: 
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/HtcWiFiWidget_WiFiWidgetProvider( 6015): updateWidget(context) for widget: 
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6014): Do not allow key_data field to be exposed
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
,D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
,D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
,D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 identity'
,D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
,D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
,D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
,D/wpa_supplicant( 6014): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6014): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  926): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6014): device_name='m8qlul_htc_europe'
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6014): manufacturer='HTC'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6014): model_name='HTC One M8s'
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6014): model_number='HTC One M8s'
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6014): config_methods='physical_display virtual_push_button'
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  926): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  926): handleMessage: new destination call exit/enter
E/WifiStateMachine(  926): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  926): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  926): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  926): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  926): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  926): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/WifiP2pService(  926): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6014): wlan0: Setting scan interval: 15 sec
D/WifiP2pService(  926): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-HAL(  926): Setting external_sim to 1
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6014): external_sim=1
I/qcom-bluetooth( 6090): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
D/WifiStateMachine(  926): Setting OUI to DA-A1-19
I/WifiNative-HAL(  926): startHal
E/wifi    (  926): getStaticLongField sWifiHalHandle 0x7f5cdee360
I/WifiNative-HAL(  926): Could not start hal
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6014): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  926): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  926): Driverstarted State enter
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  926): DriverStartedState call setCountryCode()
E/WifiStateMachine(  926): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  926): NetworkAgent == null
W/Settings( 5239): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
,I/qcom-bluetooth( 6091): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2
,E/WifiStateMachine(  926): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/WifiP2pService(  926): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/WifiP2pService(  926): P2pEnablingState
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  926): setDhcpActive: false
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6014): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  926): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  926): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  926): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  926): transitionTo: destState=DisconnectedState
E/native  (  926): do suspend false
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6014): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/HTCRequest(  926): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/HTCRequest(  926): WifiMonitor:handleSupplicantStateChange(): SSID
D/libc    (  926): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  926): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiTrafficPoller(  926): ENABLE_TRAFFIC_STATS_POLL false Token 0
E/WifiStateMachine(  926): Driverstarted State enter done
E/WifiStateMachine(  926): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  926): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  926): handleMessage: new destination call exit/enter
E/WifiStateMachine(  926): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  926): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  926): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  926): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
D/WifiScanningService(  926): SCAN_AVAILABLE : 3
E/WifiStateMachine(  926): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  926): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  926): DisconnectedState call setCountryCode()
D/RttService(  926): SCAN_AVAILABLE : 3
D/RttService(  926): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  926):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6014): wlan0: nl80211: sched_scan request
D/WifiScanningService(  926): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/Wifi,Native-HAL(  926): startHal
D/WifiMonitor(  926): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/WifiMonitor(  926): startMonitoring(p2p0) with mConnected = true
,D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiP2pService(  926): P2pEnablingState{ when=-17ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  926): P2p socket connection successful
D/WifiP2pService(  926): P2pEnabledState
,D/WifiP2pService(  926): sending p2p connection changed broadcast
D/WifiDisplayController(  926): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController(  926): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayController(  926): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiDisplayAdapter(  926): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  926):     Client/Owner: Client
D/WifiDisplayAdapter(  926):     GroupId: 
D/WifiDisplayAdapter(  926):     Passphrase: 
D/WifiDisplayAdapter(  926):     SessionId: 0
D/WifiDisplayAdapter(  926):     IP Address: }
,V/AudioService(  926): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  926):     Client/Owner: Client
V/AudioService(  926):     GroupId: 
V/AudioService(  926):     Passphrase: 
V/AudioService(  926):     SessionId: 0
V/AudioService(  926):     IP Address: }
D/HtcEffectManagerBase(  926): onEventChanged id=5 status=false
D/HtcEffectManager(  926): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  926): convertEffect before=902
D/HtcEffectManager(  926): convertEffect after=902
D/wpa_supplicant( 6014): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6014): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6014): wlan0: nl80211: Sched scan started
,E/wifi    (  926): getStaticLongField sWifiHalHandle 0x7f5a6f6520
I/WifiNative-HAL(  926): Could not start hal
E/WifiScanningService(  926): could not start HAL
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131144
E/WifiStateMachine(  926): processMsg: DisconnectedState
W/WifiHW  (  926): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
E/WifiStateMachine(  926):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131085
E/WifiStateMachine(  926): processMsg: DisconnectedState
,E/WifiStateMachine(  926):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  926): processMsg: ConnectModeState
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6014): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6014): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6014): persistent_reconnect=1
D/wpa_supplicant( 6014): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6014): P2P: New SSID postfix: -Android_608e
,D/wpa_supplicant( 6014): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  926):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  926): processMsg: DriverStartedState
E/WifiStateMachine(  926):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131154
E/WifiStateMachine(  926): processMsg: DisconnectedState
W/WifiHW  (  926): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  926):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  926): processMsg: ConnectModeState
E/WifiStateMachine(  926):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  926): processMsg: DriverStartedState
E/WifiStateMachine(  926):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
E/WifiStateMachine(  926): processMsg: SupplicantStartedState
D/wpa_supplicant( 6014): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6014): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6014): device_name='Android_608e'
E/WifiStateMachine(  926):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  926): processMsg: DefaultState
W/WifiHW  (  926): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
E/WifiStateMachine(  926):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131323
E/WifiStateMachine(  926): processMsg: DisconnectedState
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6014): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6014): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
E/WifiStateMachine(  926):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  926): processMsg: ConnectModeState
D/wpa_supplicant( 6014): p2p_ssid_postfix='-Android_608e'
E/WifiStateMachine(  926):  ConnectModeState what:131323 0 0
D/wpa_supplicant( 6014): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  926): processMsg: DriverStartedState
,E/WifiStateMachine(  926):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  926): processMsg: SupplicantStartedState
W/WifiHW  (  926): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
E/WifiStateMachine(  926):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  926): processMsg: DefaultState
E/WifiStateMachine(  926):  DefaultState what:131323 0 0
E/WifiStateMachine(  926): setOperatorSSID enter
E/WifiStateMachine(  926): handleMessage: X
D/WISPrService( 5420): >>>>>WISPrService start isConnected = false<<<<<
E/WifiStateMachine(  926): handleMessage: E msg.what=131104
E/WifiStateMachine(  926): processMsg: DisconnectedState
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6014): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6014): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  926):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  926): processMsg: ConnectModeState
W/WifiHW  (  926): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
,E/WifiStateMachine(  926):  ConnectModeState what:131104 0 0
W/Settings(  926): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6014): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6014): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6014): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6014): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  926): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6014): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6014): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6014): Single channel concurrency preference: sta
D/WifiNative-HAL(  926): p2pGetDeviceAddress
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6014): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6014): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6014): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
W/WifiHW  (  926): QCOM Debug wifi_send_command "STATUS"
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=131162
E/WifiStateMachine(  926): processMsg: DisconnectedState
,E/WifiStateMachine(  926):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  926): processMsg: ConnectModeState
E/WifiStateMachine(  926):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  926): processMsg: DriverStartedState
E/WifiStateMachine(  926):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  926): set frequency band 0
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 6014): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/WifiNative-HAL(  926): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6014): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6014): SETBAND: 0
D/wpa_supplicant( 6014): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6014): wlan0: Event CHANNEL_LIST_CHANGED (30) received
,I/wpa_supplicant( 6014): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  926): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  926): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  926): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  926): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/Tethering(  926): interfaceLinkStateChanged p2p0, false
D/Tethering(  926): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  926): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=DE
D/WifiP2pService(  926): DeviceAddress: 92:e7:c4:e6:4c:f8
D/wpa_supplicant( 6014): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6014): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6014): P2P: Add operating class 81
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6014): P2P: Add operating class 115
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6014): P2P: Add operating class 116
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6014): P2P: Add operating class 117
D/WifiDisplayController(  926): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  926):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  926):  primary type: 10-0050F204-5
D/WifiDisplayController(  926):  secondary type: null
D/WifiDisplayController(  926):  wps: 0
D/WifiDisplayController(  926):  grpcapab: 0
D/WifiDisplayController(  926):  devcapab: 0
D/WifiDisplayController(  926):  status: 3
D/WifiDisplayController(  926):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  926):  WFD CtrlPort: 0
D/WifiDisplayController(  926):  WFD MaxThroughput: 0
D/wpa_supplicant( 6014): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6014): P2P: Update channel list
D/wpa_supplicant( 6014): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6014): P2P: cli_channels:
D/wpa_supplicant( 6014): p2p0: Updating hw mode
D/wpa_supplicant( 6014): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6014): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6014): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/WifiService(  926): New client listening to asynchronous messages
D/wpa_supplicant( 6014): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
,D/wpa_supplicant( 6014): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6014): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  926): did set frequency band 0
W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6014): wlan0: Control interface command 'BSS_FLUSH 0'
E/WifiTrafficPoller(  926): ADD_CLIENT: 8
W/WifiHW  (  926): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 6014): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6014): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6014): P2P: Stopping find
D/wpa_supplicant( 6014): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6014): P2P: State IDLE -> IDLE
D/WISPrService( 5420): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 6014): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6014): P2P: Stopping find
D/wpa_supplicant( 6014): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6014): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6014): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  926): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6014): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6014): [p2p command] (P2P_SERVICE_FLUSH)
,W/WifiHW  (  926): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6014): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6014): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6014): wlan0: Cancelling sched scan
D/wpa_supplicant( 6014): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6014): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6014): wpa_supplicant_scan enter
D/wpa_supplicant( 6014): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6014): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6014): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6014): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  926): done set frequency band 0
W/WifiHW  (  926): QCOM Debug wifi_send_command "LIST_NETWORKS"
,D/wpa_supplicant( 6014): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6014): wpa_supplicant_ctrl_iface_list_networks: return size = 34
,I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:0
W/WifiHW  (  926): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 6014): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6014): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
I/bt-btu  ( 5980): btu_task received preload complete event
,D/wpa_supplicant( 6014): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6014): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6014): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x1487
D/PMS     (  926): acquireWL(2148ac98): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5980 1002 null
,D/bt-btm  ( 5980): btm_acl_device_down
D/bt-btm  ( 5980): btm_acl_reset_paging
D/bt-btm  ( 5980): btm_acl_set_discing
,D/wpa_supplicant( 6014): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully,
D/wpa_supplicant( 6014): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/WifiP2pService(  926): sending p2p persistent groups changed broadcast
D/WifiP2pService(  926): InactiveState
,D/WifiStateMachine(  926): Wifi band: 0, ScanBroadCastCounter: 0,
D/WifiStateMachine(  926): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=147462
E/WifiStateMachine(  926): processMsg: DisconnectedState
E/WifiStateMachine(  926):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129292  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  926): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  926): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  926): processMsg: ConnectModeState
,E/WifiStateMachine(  926):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129293  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  926): handleMessage: X
E/WifiStateMachine(  926): handleMessage: E msg.what=143371
E/WifiStateMachine(  926): processMsg: DisconnectedState
E/WifiStateMachine(  926):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,E/WifiStateMachine(  926): processMsg: ConnectModeState
E/WifiStateMachine(  926):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  926): processMsg: DriverStartedState
E/WifiStateMachine(  926):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  926): processMsg: SupplicantStartedState
E/WifiStateMachine(  926):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  926): processMsg: DefaultState
,E/WifiStateMachine(  926):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  926): handleMessage: X
,I/bt-btm  ( 5980): btm_reset_complete,
I/bt-btm  ( 5980): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 5980): Start reading local supported commands
,D/bt-btm  ( 5980): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 5980): BTM reads next extended features page (1)
D/bt-btm  ( 5980): BTM reads next extended features page (2)
,D/bt-btm  ( 5980): BTM reached last extended features page (2)
D/bt-btm  ( 5980): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 5980): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 5980): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 5980): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
D/bt-btm  ( 5980): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
,I/bt-btm  ( 5980): btm_vendor_capability_vsc_cmpl_cback: status=0
D/bt-btm  ( 5980): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
D/bt-btm  ( 5980): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 5980): btm_read_ble_wl_size 
,D/bt-btm  ( 5980): btm_read_white_list_size_complete 
D/bt-btm  ( 5980): btm_get_ble_buffer_size 
,D/bt-btm  ( 5980): btm_read_ble_buf_size_complete 
D/bt-btm  ( 5980): btm_read_ble_local_supported_states 
D/bt-btm  ( 5980): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 5980): btm_read_ble_local_supported_features 
,D/bt-btm  ( 5980): btm_read_ble_local_supported_features_complete 
D/bt-btm  ( 5980): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 5980): btm_decode_ext_features_page page: 0
D/bt-btm  ( 5980): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 5980): Local supported SCO packet types: 0x038f
I/bt-btm  ( 5980): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 5980):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 5980): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 5980): BTM_SetInquiryMode
I/bt-btm  ( 5980): BTM_SetPageScanType
I/bt-btm  ( 5980): BTM_SetInquiryScanType
D/bt-btm  ( 5980): btm_decode_ext_features_page page: 1
W/bt-btm  ( 5980): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 5980): btm_decode_ext_features_page page: 2
W/bt-btm  ( 5980): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 5980): BTM_BleLoadLocalKeys
D/bt-btm  ( 5980): BTM_BleLoadLocalKeys
I/bt-btm  ( 5980): BTM_Sec: application registered
E/bt-btm  ( 5980): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf87a4d5 
,I/bt-btm  ( 5980): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 5980): SMP_Register state=0
E/bt-btm  ( 5980): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf87a4d5 
I/bt-btm  ( 5980): BTM_Sec: application registered
D/bt-btm  ( 5980): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 5980): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 5980): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 5980): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 5980): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 5980): BTM_RegBusyLevelNotif
D/bt-btm  ( 5980): BTM_BleReadControllerFeatures
I/bt-btm  ( 5980): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 5980): GATT_Register
,D/bt-att  ( 5980): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 5980): allocated gatt_if=3
I/bt-att  ( 5980): GATT_StartIf gatt_if=3
D/bt-att  ( 5980): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5980): gatt_find_the_connected_bda found=0 found_idx=16
D/bt-btm  ( 5980): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 5980): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 5980): BTM Register For VSEvents is successfully
D/bt-btm  ( 5980): BTM_BleGetVendorCapabilities
I/bt-btif ( 5980): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5980): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 5980): bta_dm_set_dev_name: name: HTC One M8s 
E/bt-btif ( 5980): Calling BTA_HhEnable
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btm  ( 5980):  BTM_BleConfigPrivacy
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btif ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
,I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 5980): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 5980): BTM_AllocateSCN
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 5980): BTM_AllocateSCN
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btm  ( 5980): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5980):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5980):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 5980): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 5980): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5980):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5980):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 5980): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5980):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 5980): btif_storage_get_adapter_property service_mask:0x2140040
E/bt-btif ( 5980): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 5980): HAL bt_hal_cbacks->adapter_prope, psm 0x0019, proto_id 7
I/bt-btm  ( 5980): HAL bt_hal_cbacks->adapter_prope, psm 0x0019, proto_id 7, chan_id 1
,I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 5980): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5980):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5980):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 5980): AVRC_AddRecord uuid: 110c
D/BluetoothAdapterProperties( 5980): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 5980): A2D_AddRecord uuid: 110a
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
D/bt-btif ( 5980):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:7
,I/bt-avp  ( 5980): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btm  ( 5980): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5980):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5980):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5980):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 5980): GATT_Register
D/bt-att  ( 5980): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 5980): allocated gatt_if=4
I/bt-att  ( 5980): GATT_StartIf gatt_if=4
D/bt-att  ( 5980): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5980): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 5980): Scan Mode:21
D/BluetoothAdapterProperties( 5980): Discoverable Timeout:120
I/bt-btif ( 5980): BTA_JvEnable
,I/bt-btif ( 5980): BTA_JvRegisterL2cCback
I/bt-btm  ( 5980): BTM_ReadConnectability
I/bt-btm  ( 5980): BTM_ReadDiscoverability
I/bt-btm  ( 5980): BTM_SetDiscoverability
I/bt-btm  ( 5980): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 5980): disc_mode 0002
D/bt-btm  ( 5980): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 5980): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5980): BTM_SetConnectability
,I/bt-btm  ( 5980): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5980): disc_mode 0002
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 5980): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 5980): BTM_SetDiscoverability
I/bt-btm  ( 5980): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5980): disc_mode 0000
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5980): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 5980): BTM_SetConnectability
I/bt-btm  ( 5980): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5980): disc_mode 0000
D/bt-btm  ( 5980): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 5980): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
I/bt-btm  ( 5980): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5980): bta_pan_co_init
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 5980): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5980):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5980):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btm  ( 5980): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5980):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5980): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5980):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = c0 d1 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 4f 21 7c 34 ae dc cf 01 6a 17 24 f5 61 99 50 6a 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s
,D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:9
,I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
D/bt-btif ( 5980): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 5980): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5980): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5980): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 5980): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 5980): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5980): ScanMode =  21
D/BluetoothAdapterProperties( 5980): State =  11
D/BluetoothAdapterProperties( 5980): Setting state to 12
I/BluetoothAdapterState( 5980): Bluetooth adapter state changed: 11-> 12
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = b2 07 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 3a b6 d5 b5 97 71 f1 38 a0 bd f2 2f 76 d6 62 e8 
I/bt-btif ( 5980): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  926): +onBluetoothStateChange prev=11 new=12
D/BluetoothAdapterProperties( 5980): Discoverable Timeout:120
D/BluetoothManagerService(  926): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  926): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 5980): Entering On State
D/BluetoothManagerService(  926): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
E/bt_mct  ( 5980): hci lib postload completed
,D/BluetoothHeadset( 1475): onBluetoothStateChange: up=true
D/BluetoothHeadset(  926): onBluetoothStateChange: up=true
D/BluetoothA2dp(  926): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1475): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1475): onBluetoothStateChange: up=true
D/BluetoothManagerService(  926): Bluetooth State Change Intent: 11 -> 12
,I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
,I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 7d 42 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 00 2d 61 fa e5 17 e4 17 5c 86 7b 4b 5f 1f cb 5f 
D/NGFService( 3514): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothManagerService(  926): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/NGFService( 3514): Bluetooth Adapter: ON
V/BluetoothPbapReceiver( 5980): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5980): ***********state = 12
,D/BluetoothManagerService(  926): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  926): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 77 14 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 45 08 1a 4f ac 98 eb 5b 09 01 e2 7c 62 a2 2f 09 
D/PMS     (  926): acquireWL(145dcf57): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5420 1000 null
W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = ca 08 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = a1 85 ca c1 48 c8 f9 5a cd 35 4d c6 b7 79 20 83 
V/BluetoothPbapService( 5980): Pbap Service onCreate
V/BluetoothPbapService( 5980): Starting PBAP service
D/PMS     (  926): releaseWL(145dcf57): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6039): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6039): updateWidget(context) for widget: 
D/BluetoothAdapter( 5980): 767887505: getState(). Returning 12
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
D/PMS     (  926): acquireWL(1e772d): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5420 1000 null
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 3d 9f 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 6b b3 fb e3 4a ef ed 29 49 a3 5f 4b a1 47 55 ac 
V/BluetoothPbapService( 5980): Handler(): got msg=1
V/BluetoothPbapService( 5980): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 5980): Pbap Service initSocket
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
,W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 03 ea 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = ad bf 0b f0 af a6 c9 2e 89 17 54 45 dd 14 98 3d 
,D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 2c 4d 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 2d 6d 99 d0 d7 d3 b4 97 33 51 66 b8 e5 6d f5 b5 
,W/System.err(  926): java.lang.Throwable: stack dump
,W/System.err(  926): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  926): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d0c76b0:true
W/System.err(  926): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  926): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
,W/System.err(  926): 	at android.os.Binder.execTransact(Binder.java:454)
W/BluetoothAdapter( 5980): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothAdapter( 1222): 916866108: getState(). Returning 12
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 99 a0 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 45 04 d4 99 63 86 71 4a 4a ac 94 6d 57 65 9b 0f ,
D/BluetoothAdapter( 1222): 916866108: getState(). Returning 12
I/bt-btm  ( 5980): BTM_SetDiscoverability
I/bt-btm  ( 5980): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5980): disc_mode 0000
,I/bt-btm  ( 5980): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 5980): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5980): BTM_SetConnectability
I/bt-btm  ( 5980): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5980): disc_mode 0000
D/bt-btm  ( 5980): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 5980): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 5980): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
I/bt-btif ( 5980): BTA_JvCreateRecordByUser
D/PhoneStatusBar( 1222): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
I/bt-btif ( 5980): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5980): Scan Mode:21
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): BTA_JvRfcommStartServer
I/bt-btm  ( 5980): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 5980):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 5980): Succeed to create listening socket 
V/BluetoothPbapService( 5980): Accepting socket connection...
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 70 db 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 10 77 14 78 e6 90 9c 17 a9 73 1d fb dc 46 eb f4 
D/BluetoothAdapter( 5420): 975648969: getState(). Returning 12
D/BluetoothInputDevice( 5420): BluetoothInputDevice()
D/BluetoothManagerService(  926): registerStateChangeCallback+
D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  926): Registered receivers: 7
,D/BluetoothPan( 5420): BluetoothPan()
,D/BluetoothManagerService(  926): registerStateChangeCallback+
,D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 9f 08 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = a1 56 8b 76 77 3e ba 5b 8d eb fb 81 26 56 b0 57 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  926): Registered receivers: 8
,D/BluetoothMap( 5420): Create BluetoothMap proxy object
,D/BluetoothManagerService(  926): registerStateChangeCallback+
D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  926): Registered receivers: 9
,E/BluetoothMap( 5420): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  926): registerStateChangeCallback+
,D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 5420): BluetoothSap() call bindService
D/BluetoothManagerService(  926): Registered receivers: 10
D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
D/bt-smp  ( 5980): smp_encrypt_data
,W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 93 dc 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = b2 2b a4 63 0d b2 a4 c9 41 b2 56 e3 c6 6d 54 80 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s
,W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5420): BluetoothPbap()
,D/BluetoothManagerService(  926): registerStateChangeCallback+
D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  926): Registered receivers: 11
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
,D/bt-smp  ( 5980): smp_encrypt_data,
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 00 64 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 1e 75 b8 fb 2b 28 f4 80 25 6b d1 be 13 c4 1c 3a 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s,
D/BluetoothManagerService(  926): registerStateChangeCallback+
D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  926): Registered receivers: 12
,D/BluetoothHeadset( 5420): BluetoothHeadset()
D/BluetoothManagerService(  926): registerStateChangeCallback+
,D/BluetoothManagerService(  926): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  926): Registered receivers: 13
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
D/bt-smp  ( 5980): smp_encrypt_data
,W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 57 d3 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = af eb 7d 74 c9 ff 4c e5 6f 84 b0 4a 09 21 48 5c 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s
D/LocalBluetoothProfileManager( 5420): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 5980): Pbap Service onBind
D/DockEventReceiver( 5420): finishStartingService: stopping service
D/BluetoothA2dp( 5420): Proxy object connected
,D/A2dpProfile( 5420): Bluetooth service connected
,D/BluetoothAdapter( 5420): 975648969: getState(). Returning 12
,D/BluetoothHeadset( 5420): Proxy object connected
,D/HeadsetProfile( 5420): Bluetooth service connected
,D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapter( 5420): 975648969: getState(). Returning 12
W/BluetoothAdapter( 5980): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5980): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): BTA_JvRfcommStartServer
I/bt-btm  ( 5980): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
,I/bt-btm  ( 5980):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 5980): Accept thread started.
D/BluetoothInputDevice( 5420): Proxy object connected
D/HidProfile( 5420): Bluetooth service connected
D/BluetoothAdapter( 5420): 975648969: getState(). Returning 12
,D/BluetoothAdapter( 5980): 767887505: getState(). Returning 12
D/BluetoothFtpService( 5980): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 5980): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 5980):  call MAP start service
D/BluetoothPan( 5420): BluetoothPAN Proxy object connected
D/PanProfile( 5420): Bluetooth service connected
D/PMS     (  926): releaseWL(1e772d): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothPbap( 5420): Proxy object connected
D/PbapServerProfile( 5420): Bluetooth service connected
D/BluetoothFtpService( 5980): htc sense version is 6.0
D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5980): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5980): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): BTA_JvRfcommStartServer
I/bt-btm  ( 5980): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
,I/bt-btm  ( 5980):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothFtpService:RfcommSocketAcceptThread( 5980): Run Accept thread
E/BluetoothMasService( 5980): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 5980): Add permission for SmsProvider.
,V/BluetoothMasService( 5980): Starting MAS instances
,D/BluetoothAdapter( 5980): 767887505: getState(). Returning 12
,I/MailMessageReceiver( 5980): reg:com.android.bluetooth.btservice.AdapterApp@2a769bce with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@74d4aef
,I/MailManager( 5980): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@74d4aef
V/EmailUtils( 5980): Manager Instance is not NULL
,I/ActivityManager(  926): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6110 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/HtcAdjCursorFactory( 6110): Set CursorWindow size to: 4194304 KB, Tid: 6130,
,D/EmailUtils( 5980): ============NULL aList========,
V/EmailUtils( 5980): <-getEmailAccountIdList
V/BluetoothMasService( 5980): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 5980): 767887505: getState(). Returning 12
V/BluetoothMasService( 5980): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 5980): Manager Instance is not NULL
D/EmailUtils( 5980): ============NULL aList========
V/EmailUtils( 5980): <-getEmailAccountIdList
V/BluetoothSapReceiver( 5980): SapReceiver onReceive 
V/BluetoothSapReceiver( 5980): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5980):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 5980): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 5980): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 5980): BluetoothMns: isEmailEnabled: true
D/AuthorizationBluetoothService( 1900): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5980): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5980): BTA_JvCreateRecordByUser
D/bt-btm  ( 5980): BTM_AllocateSCN
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): BTA_JvRfcommStartServer
I/bt-btm  ( 5980): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 5980):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5980): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 5980): BTA_JvCreateRecordByUser
D/bt-btm  ( 5980): BTM_AllocateSCN
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): BTA_JvRfcommStartServer
I/bt-btm  ( 5980): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 5980):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
I/ActivityManager(  926): Killing 4613:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  926): killProcessQuiet, pid=4613
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  926): Recipient 4613,
,V/BluetoothSapService( 5980): Sap Service onCreate,
V/BluetoothSapService( 5980): initBinder
V/BluetoothSapService( 5980): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@2a64a6da
V/BluetoothSapService( 5980): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@d77a9e8
,V/BluetoothSapService( 5980): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 5980): state: 12
D/SapServerProfile( 5420): Bluetooth service connected
,V/BluetoothSapService( 5980): Starting SAP server process
V/BluetoothSapService( 5980): SAP Service startRfcommListenerThread
D/wpa_supplicant( 6014): EAPOL: disable timer tick
,V/BluetoothSapService( 5980): Sap Service initRfcommSocket
D/BluetoothManagerService(  926): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5980): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5980): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5980): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 5980): Write Extended Inquiry Response to controller
I/bt-btif ( 5980): BTA_JvRfcommStartServer
I/bt-btm  ( 5980): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 5980):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 5980): Succeed to create listening socket 
V/BluetoothSapService( 5980): Accepting socket connection...
,D/A2dpService( 5980): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@2af656a6
,D/A2dpSinkService( 5980): getA2dpSinkService(): service is NULL
,D/wpa_supplicant( 6014): EAPOL: disable timer tick,
,D/PMS     (  926): releaseWL(2148ac98): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 5924): Test app app.js loaded
I/jxcore-log( 5924): 
,I/chromium( 5924): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PMS     (  926): acquireWL(27f6d44b): PARTIAL_WAKE_LOCK  *alarm* 0x1 926 1000 WorkSource{10024}
V/AlarmManager(  926): sending alarm PendingIntent{35c96e28: PendingIntentRecord{21444741 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143444, Int=0
,D/PMS     (  926): releaseWL(27f6d44b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/GpsLocationProvider(  926): [handleMessage] DOWNLOAD_XTRA_DATA,
D/GpsLocationProvider(  926): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/ContextImpl(  926): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  926): acquireWL(150e54e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 926 1000 WorkSource{10024}
V/AlarmManager(  926): sending alarm PendingIntent{24dc6a27: PendingIntentRecord{3f6e7b93 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=169181, Int=0
,V/AlarmManager(  926): sending alarm PendingIntent{2d603346: PendingIntentRecord{fb95907 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146010, Int=0
,I/art     (  926): Explicit concurrent mark sweep GC freed 26077(1362KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.695ms total 177.931ms,
,D/PMS     (  926): acquireWL(1b5b44d4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1900 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  926): releaseWL(150e54e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    (  926): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    ( 1900): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1900): [NET] android_getaddrinfo_proxy+
D/libc    (  926): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1900): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  926): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  926): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  926): [NET] android_getaddrinfo_proxy+
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  926): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1900): [NET] android_getaddrinfo_proxy-, NODATA
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  926): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): releaseWL(1b5b44d4): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  926): acquireWL(4cd167d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null,
D/UsbnetService(  926): BroadcastReceiver::onReceive+
I/BatteryService(  926): n_update end
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PMS     (  926): releaseWL(4cd167d): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DeviceActiveState
D/HtcPowerSaver(  926): updateBatteryInfo
D/WifiController(  926): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): processMsg: DefaultState
D/PMS     (  926): runPSCheck
D/WifiController(  926): handleMessage: X
D/HtcPowerSaver(  926): Checking...
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  926): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1475): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1446): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@59c99d7
,D/Process (  926): killProcessQuiet, pid=5712
I/ActivityManager(  926): Killing 5712:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  926): Recipient 5712
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  926): acquireWL(29dad972): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000},
V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=177086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{209b81c3: PendingIntentRecord{2391da40 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=206958, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{2d603346: PendingIntentRecord{fb95907 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=229380, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{23199d79: PendingIntentRecord{4791abe com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186155, Int=0
D/libc    (  926): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  926): [NET] android_getaddrinfofornet-, err=8
D/libc    (  926): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  926): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  926): [NET] android_getaddrinfo_proxy+
D/libc    (  926): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    (  926): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): acquireWL(3aaa771f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1900 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  926): releaseWL(3aaa771f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  926): releaseWL(29dad972): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data,
,D/PMS     (  926): acquireWL(2bda5a6c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null,
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(2bda5a6c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  926): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PMS     (  926): runPSCheck
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): processMsg: DeviceActiveState
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): handleMessage: X
D/HtcPowerSaver(  926): Checking...
,I/HtcPowerSaver(  926): >> updateStatus
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  926): acquireWL(f0d9835): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null,
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(f0d9835): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  926): BroadcastReceiver::onReceive+,
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): closing low battery warning: level=100,
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  926): updateBatteryInfo
D/WifiController(  926): handleMessage: E msg.what=155652
D/PMS     (  926): runPSCheck
D/WifiController(  926): processMsg: DeviceActiveState
D/HtcPowerSaver(  926): Checking...
D/WifiController(  926): processMsg: StaEnabledState
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: X
I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  926): << updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  926): acquireWL(3b2824ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000},
V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=237086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{2989663b: PendingIntentRecord{3f6e7b93 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=305317, Int=0
,D/PMS     (  926): acquireWL(2c0c82b1): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1900 10024 WorkSource{10024 com.google.android.gms}
,V/AlarmManager(  926): sending alarm PendingIntent{170bc396: PendingIntentRecord{19e2b17 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1452596744705, Int=0
,D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1900): [NET] android_getaddrinfofornet-, err=8,
,D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1900): [NET] android_getaddrinfo_proxy+
D/libc    ( 1900): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1900): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): releaseWL(2c0c82b1): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  926): releaseWL(3b2824ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  926): acquireWL(c438b04): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null,
I/BatteryService(  926): n_update end
,D/PMS     (  926): releaseWL(c438b04): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  926): runPSCheck
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  926): Checking...
I/HtcPowerSaver(  926): >> updateStatus
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  926): battery changed pluggedType: 2
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  926): << updateStatus
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  926): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): processMsg: DeviceActiveState
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2,
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1900): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
,I/GLSUser ( 1900): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1900): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1900): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 4 40,
,W/GLSActivity( 1900): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1900): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1900): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
,W/GLSActivity( 1900): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5444): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.access$400(AccountManager.java:144),
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5444): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5444): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5444): Ignoring header User-Agent because its value was null.
,D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5444): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5444): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5444): [NET] android_getaddrinfo_proxy+
D/libc    ( 5444): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5444): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/PMS     (  926): acquireWL(25a3e46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  926): n_update end
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/PMS     (  926): releaseWL(25a3e46): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  926): BroadcastReceiver::onReceive+,
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PMS     (  926): runPSCheck
D/WifiController(  926): handleMessage: E msg.what=155652
D/HtcPowerSaver(  926): Checking...
D/WifiController(  926): processMsg: DeviceActiveState
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): processMsg: StaEnabledState,
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  926): acquireWL(2f8a0807): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
,D/UsbnetService(  926): BroadcastReceiver::onReceive+
I/BatteryService(  926): n_update end
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PMS     (  926): releaseWL(2f8a0807): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  926): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  926): updateBatteryInfo
D/WifiController(  926): processMsg: StaEnabledState
D/PMS     (  926): runPSCheck
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  926): Checking...
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  926): >> updateStatus
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  424): AtCmdFwd service not published, waiting... retryCnt : 5
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  926): acquireWL(8a1bd34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/BatteryService(  926): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  926): releaseWL(8a1bd34): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PMS     (  926): runPSCheck
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DeviceActiveState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  926): acquireWL(3ebb975d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000},
V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=357086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{cebf8d2: PendingIntentRecord{3f6e7b93 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=613694, Int=0
D/PMS     (  926): acquireWL(2ab51da3): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1900 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    ( 1900): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
D/libc    ( 1900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1900): [NET] android_getaddrinfo_proxy+
D/libc    ( 1900): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1900): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): releaseWL(2ab51da3): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  926): releaseWL(3ebb975d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/ContactMessageStore( 1475): MSG_CHECK_DELETION >>,
,D/ContactMessageStore( 1475): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1475): sku_id=118
D/ContactMessageStore( 1475): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1475): start background delete task...,
,D/ContactMessageStore( 1475): size: 0 , 0,
D/ContactMessageStore( 1475): Background delete complete
,D/PMS     (  926): acquireWL(2d3778a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
,I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(2d3778a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  926): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  926): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  926): BroadcastReceiver::onReceive-
,D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): processMsg: DeviceActiveState
D/WifiController(  926): processMsg: StaEnabledState
D/PMS     (  926): runPSCheck
D/WifiController(  926): processMsg: DefaultState
D/HtcPowerSaver(  926): Checking...
D/WifiController(  926): handleMessage: X
I/HtcPowerSaver(  926): >> updateStatus
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): closing low battery warning: level=100
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1900): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1900): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1900): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1900): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1900): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1900): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1900): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1900): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5444): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5444): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5444): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5444): Ignoring header User-Agent because its value was null.
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5444): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5444): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5444): [NET] android_getaddrinfo_proxy+
D/libc    ( 5444): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5444): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1222): reapply : com.google.android.gms 5 40
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,D/PMS     (  926): acquireWL(2e803a82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(2e803a82): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): onReceive BATTERY_CHANGED
,D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  926): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): processMsg: DeviceActiveState
D/PMS     (  926): runPSCheck
D/WifiController(  926): processMsg: StaEnabledState
D/HtcPowerSaver(  926): Checking...
,D/WifiController(  926): processMsg: DefaultState
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  926): acquireWL(20f8b593): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
,I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(20f8b593): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  926): plugged=true pluggin=true
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PMS     (  926): runPSCheck
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: E msg.what=155652
D/HtcPowerSaver(  926): Checking...
D/WifiController(  926): processMsg: DeviceActiveState
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1900): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1900): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1900): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1900): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1900): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1900): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1900): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1900): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5444): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5444): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5444): 	,at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5444): Ignoring header User-Agent because its value was null.
,D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5444): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5444): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5444): [NET] android_getaddrinfo_proxy+
D/libc    ( 5444): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
I/RemoteViews( 1222): reapply : com.google.android.gms 5 40
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5444): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): acquireWL(1a3c083d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000}
,V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=657086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{12404832: PendingIntentRecord{240a2983 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452597416456, Int=0
,D/SmartSyncUtils( 5819): isEpsOn(), nState = 0
,D/WeatherUtility( 1222): Weather sync is On,
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data,
D/PMS     (  926): releaseWL(1a3c083d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/PMS     (  926): acquireWL(f4bc700): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5819 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5819): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5819): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5819): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 5819): SettingOnTime = 1452664800000, randomSettingOnTime = 1452662291000
D/SmartSyncScreenOnOffTimeReceiver( 5819): SettingOffTime = 1452643200000, randomSettingOffTime = 1452649965000
,D/SmartSyncScreenOnOffTimeReceiver( 5819): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5819): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 5819): bNightModeTurnOffOnce = false
,D/PMS     (  926): releaseWL(f4bc700): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  926): acquireWL(3e5eb39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
,D/PMS     (  926): releaseWL(3e5eb39): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): processMsg: DeviceActiveState
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  926): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  926): Checking...
I/HtcPowerSaver(  926): >> updateStatus
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  926): acquireWL(1da6b57e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000}
,V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1017086, Int=0,
V/AlarmManager(  926): sending alarm PendingIntent{8bbdadf: PendingIntentRecord{1c26532c com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1029278, Int=0
,I/bt-btm  ( 5980): Received oneshot timer event complete,
,I/bt-btm  ( 5980): btm_ble_timeout
D/PMS     (  926): acquireWL(29b101f5): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5980 1002 null
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
D/bt-smp  ( 5980): smp_encrypt_data
,W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 8d de 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = b1 91 b2 42 de da f5 14 ba ea ed 48 d4 2b 96 49 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s
D/PMS     (  926): releaseWL(1da6b57e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  926): releaseWL(29b101f5): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  926): acquireWL(2774ab8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  926): n_update end
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  926): plugged=true pluggin=true
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PMS     (  926): runPSCheck
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): handleMessage: E msg.what=155652
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): processMsg: DeviceActiveState
D/PMS     (  926): releaseWL(2774ab8a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  926): acquireWL(fad45fb): PARTIAL_WAKE_LOCK  *alarm* 0x1 926 1000 WorkSource{1000}
,V/AlarmManager(  926): sending alarm PendingIntent{379bf97a: PendingIntentRecord{21c8952b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806021, Int=0
,V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1077086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{133b7618: PendingIntentRecord{3cdcc871 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452597121114, Int=1800000
V/AlarmManager(  926): sending alarm PendingIntent{2779f656: PendingIntentRecord{3f6e7b93 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1157462, Int=0
,D/PMS     (  926): acquireWL(148046d7): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4234 10024 WorkSource{10024 com.google.android.gms}
,I/ActivityManager(  926): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6159 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  926): sending alarm PendingIntent{317ddbc4: PendingIntentRecord{29247aad com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1452597266379, Int=0
,V/AlarmManager(  926): sending alarm PendingIntent{21187973: PendingIntentRecord{18cc2b75 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452597365273, Int=0
,D/PMS     (  926): acquireWL(2e5ef030): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1900 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/PMS     (  926): acquireWL(20bb14a9): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4234 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1900): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  926): releaseWL(148046d7): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
D/libc    ( 1900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1900): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1900): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1900): [NET] android_getaddrinfo_proxy-, NODATA
,W/ContextImpl( 5819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  926): releaseWL(2e5ef030): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms},
,I/art     (  408): Explicit concurrent mark sweep GC freed 8682(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 608us total 39.535ms
D/PowerUsageList:PowerUsageHelper( 5819): MY_DEBUG = false
,D/PowerUsageService( 5819): repeat time = 1452598460471
D/PMS     (  926): releaseWL(fad45fb): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 314us total 27.730ms
,I/EventLogService( 4234): Aggregate from 1452595321071 (log), 1452595321071 (data),
,I/art     (  408): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 372us total 20.724ms
,I/PowerUsageList:PowerUsageHelper( 5819): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5819): gen(), null == sipper.uidObj, userId = 0
,D/PMS     (  926): releaseWL(20bb14a9): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,E/cutils-trace( 6184): Error opening trace file: Permission denied (13),
I/dex2oat ( 6184): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6184): dex2oat: override thread count:4
,I/dex2oat ( 6184): dex2oat took 624.281ms (threads: 4),
,I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): VersionName:             1.2.853019
,I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6159): ApplicationMonitor {1f2b9858}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6159): PnsModel {351b893b}: update(): Update registration caused by: alarm
,I/PushClient( 6159): PnsConfigModel {22bf4e6e}: <init>(): Use dm-client for provisioning.,
,W/System.err( 6159): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6159): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6159): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6159): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  926): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6191 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,I/DeviceManagement( 6191): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6191 dbg=false s=true,
,I/DeviceManagement( 6191): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL],
I/DeviceManagement( 6191): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6191): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6191): WorkflowService: Starting workflow service
,I/DeviceManagement( 6191): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1f2b9858] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6191): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6191): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6191): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6191): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6191): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6191): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6191): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6191): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1f2b9858]
,I/DeviceManagement( 6191): WorkflowService: Stopping workflow service
,I/ActivityManager(  926): Killing 5513:com.google.android.apps.plus/u0a167 (adj 15): empty #17,
,D/Process (  926): killProcessQuiet, pid=5513
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6159): PnsModel {351b893b}: update(): Start updating since the registration has expired.
,W/PushClient( 6159): GCMRegistrator {3bd2c759}: update(): com.htc.lib1.cs.account.HtcAccountNotExistsException: No HTC Account presents on the system.,
W/PushClient( 6159):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:223)
W/PushClient( 6159):   	at com.htc.lib1.cs.account.HtcAccountHelper.getAuthToken(HtcAccountHelper.java:269)
W/PushClient( 6159):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:164)
W/PushClient( 6159):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
W/PushClient( 6159):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
W/PushClient( 6159):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/PushClient( 6159):   	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PushClient( 6159):   	at android.os.Looper.loop(Looper.java:155)
W/PushClient( 6159):   	at android.os.HandlerThread.run(HandlerThread.java:61)
W/PushClient( 6159):   
,I/ActivityManager(  926): Recipient 5513,
,D/GCM     ( 1900): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER,
,D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,D/libc    ( 1900): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1900): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
D/libc    ( 1900): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1900): [NET] android_getaddrinfo_proxy+
D/libc    ( 1900): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024,
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1900): [NET] android_getaddrinfo_proxy-, NODATA
,E/PushClient( 6159): PnsModel {351b893b}: update(): com.htc.lib1.cs.push.exception.UpdateRegistrationFailedException: SERVICE_NOT_AVAILABLE,
E/PushClient( 6159):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:198)
E/PushClient( 6159):   	at com.htc.lib1.cs.push.PnsModel.update(PnsModel.java:234)
E/PushClient( 6159):   	at com.htc.lib1.cs.push.service.UpdateRegistrationService.onHandleIntent(UpdateRegistrationService.java:57)
E/PushClient( 6159):   	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PushClient( 6159):   	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PushClient( 6159):   	at android.os.Looper.loop(Looper.java:155)
E/PushClient( 6159):   	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PushClient( 6159):   Caused by: java.io.IOException: SERVICE_NOT_AVAILABLE
E/PushClient( 6159):   	at com.google.android.gms.gcm.GoogleCloudMessaging.register(Unknown Source)
E/PushClient( 6159):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.registerGCM(GCMRegistrator.java:301)
E/PushClient( 6159):   	at com.htc.lib1.cs.push.registrator.GCMRegistrator.update(GCMRegistrator.java:196)
E/PushClient( 6159):   	... 6 more
E/PushClient( 6159):   
,I/PushClient( 6159): CentralClientRetryPolicy {e02f9be}: scheduleUpdateRetry(): Waiting for network connectivity...
,I/PackageManager(  926):  setEnabledSetting(), pkgName=com.htc.cs.pns, clsName=com.htc.cs.pns.receiver.OneTimeOnConnectedReceiver, state=1, flag=1, pid=6159, uid=10071, userID:0,
,D/Process (  926): killProcessQuiet, pid=5369
,I/ActivityManager(  926): Killing 5369:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  926): Recipient 5369
,D/PMS     (  926): acquireWL(2428b6ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(2428b6ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  926): updateBatteryInfo
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  926): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/PMS     (  926): runPSCheck
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  926): >> updateStatus
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): processMsg: DeviceActiveState
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  926): User[0] Flushing usage stats to disk
,D/PMS     (  926): acquireWL(300d5ddb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(300d5ddb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  926): updateBatteryInfo
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/NotificationService(  926): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  926): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  926): >> updateStatus
,D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: E msg.what=155652
I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  926): processMsg: DeviceActiveState,
I/HtcPowerSaver(  926): << updateStatus
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1900): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1900): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1900): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1900): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1900): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1900): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1900): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1900): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5444): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5444): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5444): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5444): Ignoring header User-Agent because its value was null.
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5444): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5444): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5444): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5444): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5444): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 5 40
,D/PMS     (  926): acquireWL(b71e745): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(b71e745): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  926): updateBatteryInfo
D/HeadsetPhoneState( 5980): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/PowerUI ( 1222): closing low battery warning: level=98
D/HeadsetStateMachine( 5980): Disconnected process message: 11, size: 0,
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/PMS     (  926): runPSCheck
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  926): >> updateStatus
D/UsbnetService(  926): BroadcastReceiver::onReceive-
W/ContextImpl( 5819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DeviceActiveState,
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderNotification, total:1
I/HtcPowerSaver(  926): updateStatus (8000,98,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  926): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/TetherSettings( 5420): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5420): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5420): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5420): Cust_ConnectToPC   : spcsc>false
D/        ( 5420): Cust_ConnectToPC   : IPT>true
D/        ( 5420): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 5420): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5420): Index of the first 1 = -1
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true,
,W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
W/Settings( 5420): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5420): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5420): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5420): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5420): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5420): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  926): acquireWL(2e5d73cb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/BatteryService(  926): n_update end
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  926): releaseWL(2e5d73cb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  926): runPSCheck
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  926): Checking...
D/WifiController(  926): handleMessage: E msg.what=155652
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): processMsg: DeviceActiveState
,D/PowerUI ( 1222): closing low battery warning: level=98
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: X
I/HtcPowerSaver(  926): updateStatus (8000,98,-1,false,false,false,-1)
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  926): acquireWL(111457a8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000},
V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1197086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{2c4eb2c1: PendingIntentRecord{4791abe com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=1407002, Int=0,
,D/PMS     (  926): acquireWL(1a3f1a66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1900 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  926): releaseWL(1a3f1a66): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  926): releaseWL(111457a8): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  926): acquireWL(37cd81a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null,
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(37cd81a7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1222): closing low battery warning: level=98
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  926): updateBatteryInfo
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/PMS     (  926): runPSCheck
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  926): >> updateStatus
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DeviceActiveState
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
,I/HtcPowerSaver(  926): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:2 level:98 unsupport:false plugged:true
,D/PMS     (  926): acquireWL(e2b4654): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
,I/BatteryService(  926): n_update end
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  926): releaseWL(e2b4654): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): BroadcastReceiver::onReceive+,
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PMS     (  926): runPSCheck
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DeviceActiveState,
D/PowerUI ( 1222): closing low battery warning: level=99
D/WifiController(  926): processMsg: StaEnabledState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
I/HtcPowerSaver(  926): updateStatus (8000,99,-1,false,false,false,-1)
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  926): << updateStatus
,I/BatteryController( 1222): status:2 level:99 unsupport:false plugged:true,
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1900): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1900): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1900): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1900): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1900): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1900): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1900): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1900): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
E/PlayEventLogger( 5444): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5444): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5444): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5444): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5444): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5444): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5444): [NET] android_getaddrinfo_proxy+
D/libc    ( 5444): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5444): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): acquireWL(2ab8e916): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null,
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(2ab8e916): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  926): BroadcastReceiver::onReceive+
,D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  926): runPSCheck
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  926): Checking...
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  926): >> updateStatus
,D/WifiController(  926): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=99
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  926): updateStatus (8000,99,-1,false,false,false,-1)
D/WifiController(  926): processMsg: DeviceActiveState
I/HtcPowerSaver(  926): << updateStatus
D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DefaultState
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: X
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/BatteryController( 1222): status:2 level:99 unsupport:false plugged:true,
,D/PMS     (  926): acquireWL(24c42297): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(24c42297): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): closing low battery warning: level=99
D/UsbnetService(  926): BroadcastReceiver::onReceive+
D/NotificationService(  926): plugged=true pluggin=true
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/WifiController(  926): battery changed pluggedType: 2
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  926): updateBatteryInfo
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/PMS     (  926): runPSCheck
D/WifiController(  926): handleMessage: E msg.what=155652
D/HtcPowerSaver(  926): Checking...
D/WifiController(  926): processMsg: DeviceActiveState
I/HtcPowerSaver(  926): >> updateStatus
D/WifiController(  926): processMsg: StaEnabledState,
D/WifiController(  926): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  926): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  926): updateStatus (8000,99,-1,false,false,false,-1)
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  926): << updateStatus
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/BatteryController( 1222): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  926): acquireWL(1d6ec84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 926 1000 null
I/BatteryService(  926): n_update end
D/PMS     (  926): releaseWL(1d6ec84): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1309): [EventService] reorderNotification, total:0
D/HtcPowerSaver(  926): updateBatteryInfo
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  926): plugged=true pluggin=true
D/DotMatrix( 1309): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  926): runPSCheck
D/DotMatrix( 1309): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  926): Checking...
D/UsbnetService(  926): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  926): >> updateStatus
D/UsbnetService(  926): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  926):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  926): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 5980): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5980): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5980): Disconnected process message: 11, size: 0
D/WifiController(  926): handleMessage: E msg.what=155652
D/WifiController(  926): processMsg: DeviceActiveState
I/HtcPowerSaver(  926): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  926): << updateStatus
,D/WifiController(  926): processMsg: StaEnabledState
D/WifiController(  926): battery changed pluggedType: 2
D/WifiController(  926): processMsg: DefaultState
D/WifiController(  926): handleMessage: X
,W/ContextImpl( 5819): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5420): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5420): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5420): Cust_ConnectToPC   : Modem_Link>false
,D/        ( 5420): Cust_ConnectToPC   : spcsc>false
D/        ( 5420): Cust_ConnectToPC   : IPT>true
D/        ( 5420): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5420): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5420): Index of the first 1 = -1
,W/ContextImpl( 5420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,W/Settings( 5420): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5420): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5420): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5420): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory),
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  926): Prepared write state in 15ms,
,I/GLSUser ( 1900): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1900): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1900): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1900): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1900): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  926): Explicit concurrent mark sweep GC freed 28528(1560KB) AllocSpace objects, 14(1284KB) LOS objects, 33% free, 16MB/24MB, paused 1.856ms total 151.596ms
,W/GLSActivity( 1900): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1900): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1900): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1900): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1900): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1900): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1900): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5444): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5444): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5444): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5444): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5444): Ignoring header User-Agent because its value was null.
,D/DotMatrix( 1309): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1309): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5444): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5444): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5444): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5444): [NET] android_getaddrinfo_proxy+
D/libc    ( 5444): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  394): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  394): [NET] android_getaddrinfofornet-, err=7
I/RemoteViews( 1222): reapply : com.google.android.gms 4 40
D/libc    ( 5444): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  926): acquireWL(28907eb4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 926 1000 WorkSource{1000}
,V/AlarmManager(  926): sending alarm PendingIntent{1f78aca0: PendingIntentRecord{eba7059 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1437086, Int=0
V/AlarmManager(  926): sending alarm PendingIntent{3f58fadd: PendingIntentRecord{39405652 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1929294, Int=0,
,I/bt-btm  ( 5980): Received oneshot timer event complete
I/ActivityManager(  926): Killing 6015:com.htc.widget.hmsproc2/u0a40 (adj 13): empty for 1800s
I/bt-btm  ( 5980): btm_ble_timeout
D/Process (  926): killProcessQuiet, pid=6015
I/bt-btm  ( 5980): btm_gen_resolvable_private_addr
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/PMS     (  926): acquireWL(101ded23): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5980 1002 null
,D/bt-btm  ( 5980): btm_ble_rand_enc_complete,
I/bt-btm  ( 5980): btm_gen_resolve_paddr_low
D/bt-smp  ( 5980): smp_encrypt_data
W/bt-smp  ( 5980): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5980): Plain text(LSB ~ MSB) = 4b e7 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5980): Encrypted text(LSB ~ MSB) = 04 85 b5 00 cf 23 63 99 6a 2a c3 20 60 3f 3d 33 
I/bt-btm  ( 5980): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5980): Stopping oneshot timer
D/bt-btm  ( 5980): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  926): Recipient 6015
,I/ActivityManager(  926): Killing 5878:com.htc.calendar/u0a10 (adj 13): empty for 1814s
,D/Process (  926): killProcessQuiet, pid=5878
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  926): Recipient 5878,
,D/Process (  926): killProcessQuiet, pid=5853
I/ActivityManager(  926): Killing 5853:com.htc.mobiledata/u0a46 (adj 13): empty for 1815s
,D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  926): Recipient 5853
,D/Process (  926): killProcessQuiet, pid=5790,
I/ActivityManager(  926): Killing 5790:com.htc.bgp/u0a11 (adj 13): empty for 1815s
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  926): Recipient 5790
,I/ActivityManager(  926): Killing 5767:com.htc.mms.backupagent/u0a76 (adj 13): empty for 1821s
D/Process (  926): killProcessQuiet, pid=5767
,D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  926): Recipient 5767
,I/ActivityManager(  926): Killing 5444:com.android.vending/u0a72 (adj 15): empty for 1828s,
D/Process (  926): killProcessQuiet, pid=5444
D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  926): Recipient 5444
,I/ActivityManager(  926): Killing 5624:com.android.defcontainer/u0a15 (adj 15): empty for 1842s
D/Process (  926): killProcessQuiet, pid=5624
,D/Process (  926): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  926): Recipient 5624
,D/PMS     (  926): releaseWL(101ded23): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,D/WeatherUtility( 1222): Weather sync is On
,D/PMS     (  926): releaseWL(28907eb4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,TIME-OUT KILL (timeout was 1800000ms)
```
