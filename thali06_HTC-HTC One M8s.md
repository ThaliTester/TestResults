#### Test 5615109370bee58_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,D/PMS     (  948): acquireWL(39f1d219): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/NotificationService(  948): plugged=true pluggin=true
--------- beginning of main
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/UsbnetService(  948): onReceive BATTERY_CHANGED
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: ApStaDisabledState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=97
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  948): updateBatteryInfo
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 97, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  948): releaseWL(39f1d219): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  948): runPSCheck
D/HtcPowerSaver(  948): Checking...
I/HtcPowerSaver(  948): >> updateStatus
I/HtcPowerSaver(  948): updateStatus (8000,97,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
I/BatteryController( 1221): status:2 level:97 unsupport:false plugged:true
W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
E/cutils-trace( 5843): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5843): ====startRecUseTime====
D/htc.customization.log.level( 5843):  is 
W/CustomizationLogLevel( 5843): Level value is invalid, use default level 2
D/CustomizationManager( 5843):  Read ACC file spent 0.047 (s)
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5843): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5843): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5843): Parsing tag category name = system
I/CustomizationCIDLoader( 5843): Parsing tag category name = application
I/CustomizationCIDLoader( 5843): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5843): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5843): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5843): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5843): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5843): add string-array item, value = 42507
I/CustomizationCIDLoader( 5843): add string-array item, value = 21902
I/CustomizationCIDLoader( 5843): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5843): add string-array item, value = 23420
I/CustomizationCIDLoader( 5843): add string-array item, value = 22299
I/CustomizationCIDLoader( 5843): add string-array item, value = 24002
I/CustomizationCIDLoader( 5843): add string-array item, value = 23210
I/CustomizationCIDLoader( 5843): add string-array item, value = 23205
I/CustomizationCIDLoader( 5843): add string-array item, value = 23806
I/CustomizationCIDLoader( 5843): add string-array item, value = 23430
I/CustomizationCIDLoader( 5843): add string-array item, value = 23408
I/CustomizationCIDLoader( 5843): add string-array item, value = 27205
I/CustomizationCIDLoader( 5843): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5843): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5843):  Read CID file spent 0.098 (s)
D/CustomizationManager( 5843):  All configurations done spent 0.098 (s)
I/ActivityManager(  948): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5843 on display 0
D/PMS     (  948): acquireHCC(325042de): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 948 1000 null
D/PMS     (  948): acquireHCC(36404cbf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 948 1000 null
W/asset   (  948): Copying FileAsset 0x55c3b97790 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  948): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5861 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  948): Display changed displayId=0
D/DotMatrix( 1304): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1304): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 5861): Copying FileAsset 0xac28a170 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1497): [trimMemory] 20
I/WebViewFactory( 5861): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5861): Time to load native libraries: 9 ms (timestamps 4706-4715),
,I/LibraryLoader( 5861): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 5861): Binding Chromium to main looper Looper (main, tid 1) {123b322a},
I/LibraryLoader( 5861): Expected native library version number "",actual native library version number ""
,I/chromium( 5861): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 5861): Initializing chromium process, singleProcess=true
,W/art     ( 5861): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5861): ApplicationContext is null in ApplicationStatus
,W/chromium( 5861): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5861): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5861): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5861): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
I/Adreno-EGL( 5861): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5861): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5861): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5861): Local Branch: 
I/Adreno-EGL( 5861): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5861): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5861):                  d74aa161a12b9c6fc6332151
,W/System.err(  948): java.lang.Throwable: stack dump
W/System.err(  948): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  948): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  948): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18a3c424:true
,D/BluetoothAdapter( 5861): 37189521: getState() :  mService = null. Returning STATE_OFF,
,I/art     (  948): Explicit concurrent mark sweep GC freed 32719(1795KB) AllocSpace objects, 4(908KB) LOS objects, 33% free, 16MB/24MB, paused 1.491ms total 129.304ms
,W/ActivityManager(  948): Activity pause timeout for ActivityRecord{b7d0f8c u0 com.test.thalitest/.MainActivity t8}
,W/HtcSystemUPManager(  948): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/art     ( 5861): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5861): onDetachedFromWindow called when already detached. Ignoring,
,D/SystemWebViewEngine( 5861): CordovaWebView is running on device made by: HTC
,W/art     ( 5861): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5861): Attempt to remove local handle scope entry from IRT, ignoring
,D/GpsLocationProvider(  948): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  948): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,W/chromium( 5861): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,D/StatusBarManagerService(  948): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
D/StatusBarManagerService(  948): setSystemUiVisibility(0x0)
,D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
,D/FindExtension( 5861): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 5861): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2312b794, mServedView=org.apache.cordova.engine.SystemWebView{335f723d VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@ca06a32
I/InputMethodManagerService(  948): Disable input method client, pid=1497
D/StatusBarManagerService(  948): swetImeWindowStatus vis=0 backDisposition=0
,I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
,W/IInputConnectionWrapper( 5861): reportFullscreenMode on inactive InputConnection,
,I/ActivityManager(  948): Displayed com.test.thalitest/.MainActivity: +774ms (total +819ms)
,W/BindingManager( 5861): Cannot call determinedVisibility() - never saw a connection for the pid: 5861
,D/JsMessageQueue( 5861): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5861): JniHelper::setJavaVM(0xab11e8f8), pthread_self() = -1404693480
,D/JX-Cordova( 5861): jxcore cordova android initializing
,D/PMS     (  948): releaseHCC(325042de): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,D/PMS     (  948): releaseHCC(36404cbf): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5861): Initializing JXcore engine,
W/jxcore-log( 5861): JXcore engine is ready
,W/jxcore-log( 5861): Starting JXcore engine,
,W/jxcore-log( 5861): Platform android,
W/jxcore-log( 5861): 
,W/jxcore-log( 5861): Process ARCH arm
W/jxcore-log( 5861): 
,I/jxcore-log( 5861): JXcore Cordova bridge is ready!,
I/jxcore-log( 5861): 
W/jxcore-log( 5861): JXcore engine is started
I/Choreographer( 5861): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5861): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5861): Toggling radios to true
I/jxcore-log( 5861): 
,D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  948): checking for enable restriction...
D/BluetoothManagerService(  948): checkBTEasState, ret=true
I/BluetoothManagerService(  948): isBluetoothRestricted(): false
D/BluetoothManagerService(  948): enable(): region ID = 6
D/BluetoothManagerService(  948): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  948): MONITOR_LOG
W/Settings:Agent(  948): name: bluetooth_on
W/Settings:Agent(  948): value: 1
W/Settings:Agent(  948): >> traceCallingStack()
W/Settings:Agent(  948): Process.myPid(): 948
W/Settings:Agent(  948): Process.myTid(): 977
W/Settings:Agent(  948): Process.myUid(): 1000
W/Settings:Agent(  948): 
W/Settings:Agent(  948): 
W/System.err(  948): java.lang.Throwable: stack dump
,W/System.err(  948): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  948): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  948): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  948): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
,W/System.err(  948): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  948): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  948): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
,W/System.err(  948): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  948): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
,W/Settings:Agent(  948): 
W/Settings:Agent(  948): << traceCallingStack(): 5(ms)
,D/BluetoothManagerService(  948): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  948): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  948): New client listening to asynchronous messages
,E/WifiTrafficPoller(  948): ADD_CLIENT: 7
D/WifiManager( 5861): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
W/Settings:Agent(  948): MONITOR_LOG
D/WifiService(  948): setWifiEnabled: true pid=5861, uid=10366
W/Settings:Agent(  948): name: wifi_on
E/WifiService(  948): Invoking mWifiStateMachine.setWifiEnabled
W/Settings:Agent(  948): value: 2
I/WifiService(  948): isSprintWifiRestricted(): false
W/Settings:Agent(  948): >> traceCallingStack()
I/WifiService(  948): isMdmWifiRestricted(): false
W/Settings:Agent(  948): Process.myPid(): 948
W/Settings:Agent(  948): Process.myTid(): 1712
W/Settings:Agent(  948): Process.myUid(): 1000
W/Settings:Agent(  948): 
,W/Settings:Agent(  948): 
W/System.err(  948): java.lang.Throwable: stack dump
,W/System.err(  948): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  948): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  948): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  948): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  948): 	at android.provider.Settings$Global.putString(Settings.java:7403)
,W/System.err(  948): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
I/ActivityManager(  948): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5915 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
W/System.err(  948): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  948): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  948): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
,W/System.err(  948): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  948): 
W/Settings:Agent(  948): << traceCallingStack(): 13(ms)
,D/WifiController(  948): handleMessage: E msg.what=155656,
D/WifiController(  948): processMsg: ApStaDisabledState,
D/WifiController(  948): transitionTo: destState=DeviceActiveState
D/PMS     (  948): acquireWL(166c7dbb): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 948 1000 null
D/WifiController(  948): handleMessage: new destination call exit/enter
D/WifiController(  948): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  948): invokeExitMethods: ApStaDisabledState
,D/WifiController(  948): moveTempStackToStateStack: i=1,j=1
D/WifiController(  948): moveTempStackToStateStack: i=0,j=2
,D/WifiController(  948): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  948): invokeEnterMethods: StaEnabledState
D/WifiController(  948): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  948): setting operational mode to 1
,E/WifiStateMachine(  948): handleMessage: E msg.what=131083
E/WifiStateMachine(  948): processMsg: InitialState
D/WifiController(  948): handleMessage: X
,D/WifiManager( 5861): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  948):  InitialState CMD_START_SUPPLICANT 0 0
D/WifiManager( 5861): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 5861): Radios toggled
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): My device name is: HTC-HTC One M8s
I/jxcore-log( 5861): 
,W/ResourcesManager( 5915): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 5915): Adding HeadsetService,
D/AdapterServiceConfig( 5915): Adding A2dpService
D/AdapterServiceConfig( 5915): Adding HidService
D/AdapterServiceConfig( 5915): Adding HealthService
,D/AdapterServiceConfig( 5915): Adding PanService
D/AdapterServiceConfig( 5915): Adding GattService
,W/linker  ( 5915): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  948): java.lang.Throwable: stack dump
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@125d6116:true
W/System.err(  948): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  948): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  948): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
,D/BluetoothAdapterState( 5915): make
,I/BluetoothAdapterState( 5915): Entering OffState,
,E/bt_osi_config( 5915): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
D/BluetoothAdapterProperties( 5915): Address is:90:E7:C4:F6:69:77
D/BluetoothManagerService(  948): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  948): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  948): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  948): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  948): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapter( 5861): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2536db26
D/BluetoothAdapter( 5861): onBluetoothServiceUp done
D/BluetoothAdapter( 1221): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1c2c9dbb
,D/BluetoothAdapter( 1221): onBluetoothServiceUp done
D/BluetoothAdapter( 1434): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@29275273
D/BluetoothAdapter( 1434): onBluetoothServiceUp done
,D/BluetoothAdapter( 1455): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@19b8c4fc
D/BluetoothAdapter( 1455): onBluetoothServiceUp done
D/BluetoothAdapter(  948): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1c4678a2
D/BluetoothAdapter(  948): onBluetoothServiceUp done
,D/BluetoothAdapter( 5915): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@264b5af7
,D/BluetoothAdapter( 5915): onBluetoothServiceUp done,
,D/BluetoothAdapter( 3487): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1c946701
D/BluetoothAdapter( 3487): onBluetoothServiceUp done
D/BluetoothAdapter( 1817): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@366d2124
D/BluetoothAdapter( 1817): onBluetoothServiceUp done
D/BluetoothAdapter( 2349): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@25414b46
D/BluetoothAdapter( 2349): onBluetoothServiceUp done
D/BluetoothManagerService(  948): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 5915): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 5915): Setting state to 11
I/BluetoothAdapterState( 5915): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  948): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  948): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  948): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  948): Bluetooth State Change Intent: 10 -> 11
,I/IntentController( 1221): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,V/BluetoothPbapReceiver( 5915): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5915): ***********state = 11
,D/BluetoothBondStateMachine( 5915): make
,I/BluetoothBondStateMachine( 5915): StableState(): Entering Off State
D/BluetoothAdapterService( 5915): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 5915): checkA2dpState: returning
D/BluetoothAdapterService( 5915): checkHfpState: isHfpClientEnabled = false
,E/BluetoothAdapterService( 5915): checkHfpState: returning
,D/NGFService( 3487): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,I/BluetoothAdapterState( 5915): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,D/BluetoothHeadset(  948): Proxy object connected,
D/BluetoothHeadset( 1221): Proxy object connected
D/BluetoothHeadset( 1434): Proxy object connected
,D/HeadsetService( 5915): Received start request. Starting profile...,
D/HeadsetStateMachine( 5915): Version 1.5
,D/PMS     (  948): releaseWL(166c7dbb): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/HeadsetStateMachine( 5915): make
D/Tethering(  948): interfaceAdded wlan0
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothPhoneService( 1434): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1434): Proxy object connected
D/BluetoothHeadset( 1434): Proxy object connected
D/Tethering(  948): interfaceLinkStateChanged wlan0, false
D/Tethering(  948): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
V/Tethering(  948): TetherInterfaceSM: wlan0: enter InitialState
D/Tethering(  948): interfaceAdded p2p0
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  948): p2p0 is not a tetherable iface, ignoring
D/Tethering(  948): interfaceLinkStateChanged p2p0, false,
D/Tethering(  948): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false,
D/libc    (  948): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  948): [NET] android_getaddrinfofornet-, SUCCESS
,I/ActivityManager(  948): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=5951 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a,
,D/Tethering(  948): sendTetherStateChangedBroadcast 0, 0, 0,
D/HeadsetStateMachine( 5915): max_hf_connections = 2
D/Tethering(  948): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  948): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  948): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
D/PMS     (  948): acquireWL(3813284c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 948 1000 null
,D/Tethering(  948): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkPolicy(  948): updateNetworkEnabledLocked()
V/NetworkPolicy(  948): updateNotificationsLocked()
D/PMS     (  948): releaseWL(3813284c): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
D/PMS     (  948): acquireWL(2d378095): PARTIAL_WAKE_LOCK  NetworkStats 0x1 948 1000 null
,D/TetherSettings( 5354): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5354): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5354): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5354): Cust_ConnectToPC   : spcsc>false
D/        ( 5354): Cust_ConnectToPC   : IPT>true
D/        ( 5354): Cust_ConnectToPC   : Singel_USB>false
,D/PMS     (  948): releaseWL(2d378095): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  948): updateNetworkEnabledLocked()
V/NetworkPolicy(  948): updateNotificationsLocked()
,W/Settings( 5354): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
,E/WifiStateMachine(  948): setWifiState: enabling
E/WifiStateMachine(  948): Supplicant start successful
D/WifiMonitor(  948): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  948): connecting to supplicant
E/SmartNS_Utility( 5354): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5354): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5354): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
D/BluetoothAdapter(  948): 839734698: getState(). Returning 11
E/WifiHW  (  948): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
I/IntentController( 1221): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetPhoneState( 5915): listenForPhoneState..for service and signal ,
,D/HeadsetDualPhoneStateListener_SLOT1( 5915): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 5915): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 5915): Enter Disconnected: -2, size: 0
,D/BluetoothAdapter( 1434): 794564009: getState(). Returning 11,
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f9581b
D/HeadsetDualPhoneStateListener_SLOT1( 5915): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 5915): listen phone state by slot:SLOT2  id:-100
,I/HeadsetStateMachine( 5915): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 5915): BTHF: set_current_device
,D/A2dpService( 5915): Received start request. Starting profile...
,V/Avrcp   ( 5915): make
,W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,I/SmartNS_Utility( 5354): setISNotification
,D/UsbnetService(  948): BroadcastReceiver::onReceive+,
,E/RemoteController( 5915): Cannot set synchronization mode on an unregistered RemoteController,
D/A2dpStateMachine( 5915): make
D/bt-btif ( 5915): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/A2dpService( 5915): setA2dpService(): set to: null,
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f9581b
D/A2dpStateMachine( 5915): Enter Disconnected: -2
,D/SmartNS_Utility( 5354): usb_cable_connect = 1,
D/SmartNS_Utility( 5354): usb_denied = 0
I/SmartNS_PSService( 5354): usb notificaiton:true
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActionCombine( 5354): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/HidService( 5915): Received start request. Starting profile...
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f9581b
,D/UsbnetService(  948): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbDeviceManager(  948): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  948): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/UsbnetService(  948): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
,D/BluetoothA2dp(  948): Proxy object connected
,D/HealthService( 5915): Received start request. Starting profile...
,D/BluetoothAdapter(  948): 839734698: getState(). Returning 11,
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f9581b
,D/PanService( 5915): Received start request. Starting profile...
D/SmartNS_Utility( 5354): usb_cable_connect = 1
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_Utility( 5354): usb_denied = 0
I/SmartNS_PSService( 5354): usb notificaiton:true
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
,D/HtcBtWidget_BTWidgetProvider( 5951): onBTStateChanged() for widget: ,
D/HtcBtWidget_BTWidgetProvider( 5951): updateWidget(context) for widget: 
,D/SmartNS_NSReceiver( 5354): Tethered state change:false isNSOpening:false,
,I/QuickSettingMiniLite( 1221): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@10b052d8,
D/PanService( 5915): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f9581b
D/TetherSettings( 5354): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5354): Cust_ConnectToPC   : Internet_Sharing>true
W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/        ( 5354): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5354): Cust_ConnectToPC   : spcsc>false
D/        ( 5354): Cust_ConnectToPC   : IPT>true
D/        ( 5354): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5354): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5354): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5354): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5354): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/BtGatt.DebugUtils( 5915): handleDebugAction() action=null
,I/SmartNS_Utility( 5354): setISNotification
D/BtGatt.GattService( 5915): Received start request. Starting profile...
D/BtGatt.GattService( 5915): start()
,D/BtGatt.AdvertiseManager( 5915): advertise manager created
D/SmartNS_Utility( 5354): usb_cable_connect = 1
,D/SmartNS_Utility( 5354): usb_denied = 0
I/SmartNS_PSService( 5354): usb notificaiton:true
,E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
,D/wpa_supplicant( 5972): wpa_supplicant v2.3-devel-5.0.2
,I/QuickSettingBluetooth( 1221): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/WIFI_ICON( 1221): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/wpa_supplicant( 5972): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5972): random: Trying to read entropy from /dev/random
D/BluetoothAdapterService( 5915): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f9581b
,I/QuickSettingWifi( 1221): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/wpa_supplicant( 5972): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5972): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 5972): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 5972): Successfully initialized wpa_supplicant
D/wpa_supplicant( 5972): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5972): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5972): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 5972): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5972): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5972): update_config=1
D/wpa_supplicant( 5972): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5972): device_name='Android_608e'
D/wpa_supplicant( 5972): manufacturer='HTC'
D/wpa_supplicant( 5972): model_name='HTC_PHONE'
D/wpa_supplicant( 5972): model_number='1234'
D/wpa_supplicant( 5972): config_methods='virtual_push_button physical_display keypad'
,D/wpa_supplicant( 5972): p2p_oper_reg_class=126
,D/wpa_supplicant( 5972): p2p_oper_channel=149
D/wpa_supplicant( 5972): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 5972): persistent_reconnect=1
D/wpa_supplicant( 5972): key_mgmt_offload=1
I/RemoteViews( 1221): reapply : com.android.settings 1 36
I/wpa_supplicant( 5972): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5972): nl80211: RFKILL status not available
D/wpa_supplicant( 5972): nl80211: Using driver-based roaming
D/wpa_supplicant( 5972): nl80211: TDLS supported
D/wpa_supplicant( 5972): nl80211: TDLS external setup
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5972): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Su,pported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/SmartNS_Utility( 5354): usb_cable_connect = 1
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/SmartNS_Utility( 5354): usb_denied = 0
D/wpa_supplicant( 5972): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5972): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5972): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5972): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 5972): nl80211: Set mode ifindex 30 iftype 2 (STATION)
I/SmartNS_PSService( 5354): usb notificaiton:true
D/wpa_supplicant( 5972): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a7a6dfd0
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=0104
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=040a
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=040b
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=040c
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=040d
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=090a
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=090b
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=090c
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=090d
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=0409506f9a09
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=7f506f9a09
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=0801
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=040e
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=06
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=0a07
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=0a11
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a6dfd0 match=0a1a
D/wpa_supplicant( 5972): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5972): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 5972): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 5972): htc_wext_command_init +
E/wpa_supplicant( 5972): htc_wext_command_init: ifname=p2p0, ignore
D/Tethering(  948): interfaceLinkStateChanged p2p0, false
D/Tethering(  948): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5972): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  948): interfaceLinkStateChanged p2p0, false
D/Tethering(  948): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
I/HeadsetPhoneState( 5915): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 5915): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetStateMachine( 5915): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 5915): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 5915): Disconnected process message: 11, size: 0
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_NSReceiver( 5354): Tethered state change:false isNSOpening:false
D/BluetoothAdapter( 1434): 794564009: getState(). Returning 11
W/BluetoothHeadset( 1434): Proxy not attached to service
D/BluetoothAdapterState( 5915): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 5915): btu_task pending for preload complete event
I/RemoteViews( 1221): reapply : com.android.settings 1 36
D/BluetoothHeadset( 1434): java.lang.Throwable
D/BluetoothHeadset( 1434): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1434): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1434): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1434): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1434): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1434): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1434): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1434): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1434): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1434): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1434): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
E/bt_vendor( 5915): get_bt_soc_type: Failed to get soc type
I/ActivityManager(  948): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=5986 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/Process (  948): killProcessQuiet, pid=5603
I/ActivityManager(  948): Killing 5603:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/qcom-bluetooth( 6000): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
D/BluetoothAdapter( 1221): 454791546: getState(). Returning 11,
I/QuickSettingMiniLite( 1221): updateLiteState:no connect device!
,I/qcom-bluetooth( 6014): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6015): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** ,
,I/ActivityManager(  948): Recipient 5603
,I/qcom-bluetooth( 6017): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
I/qcom-bluetooth( 6018): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 6019): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/wpa_supplicant( 5972): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 5972):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5972):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5972):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5972): nl80211: Flush PMKIDs
D/wpa_supplicant( 5972): p2p0: State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 6020): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,D/BluetoothMasReceiver( 5915): Bluetooth STATE CHANGED to 11,
,I/RemoteViews( 1221): reapply : com.android.settings 1 36
,V/BluetoothSapReceiver( 5915): SapReceiver onReceive 
V/BluetoothSapReceiver( 5915): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 5915):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 5915): startService = false
D/AuthorizationBluetoothService( 1840): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 5986): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 5986): updateWidget(context) for widget: 
,D/Process (  948): killProcessQuiet, pid=5626
I/ActivityManager(  948): Killing 5626:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/wpa_supplicant( 5972): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 5972): TDLS: Driver uses external link setup
D/wpa_supplicant( 5972): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 5972): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5972): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 5972): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5972): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5972): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5972): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5972): Using existing control interface directory.
D/wpa_supplicant( 5972): P2P: Add operating class 81
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 5972): P2P: Own listen channel: 81:1
D/wpa_supplicant( 5972): P2P: Configured operating channel: 126:149
D/wpa_supplicant( 5972): P2P: initialized
D/wpa_supplicant( 5972): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5972): P2P: cli_channels:
D/wpa_supplicant( 5972): p2p0: Added interface p2p0
D/wpa_supplicant( 5972): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 5972): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 5972): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5972): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 5972): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5972): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 5972): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 5972): disable_scan_offload=1
D/wpa_supplicant( 5972): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 5972): update_config=1
D/wpa_supplicant( 5972): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5972): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 5972): manufacturer='HTC'
D/wpa_supplicant( 5972): model_name='HTC One M8s'
D/wpa_supplicant( 5972): model_number='HTC One M8s'
D/wpa_supplicant( 5972): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 5972): hs20=1
D/wpa_supplicant( 5972): interworking=1
D/wpa_supplicant( 5972): external_sim=1
D/wpa_supplicant( 5972): key_mgmt_offload=1
,D/wpa_supplicant( 5972): Priority group 524
D/wpa_supplicant( 5972):    id=0 ssid='NG700'
I/wpa_supplicant( 5972): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 5972): nl80211: RFKILL status not available
,D/wpa_supplicant( 5972): nl80211: Using driver-based roaming
D/wpa_supplicant( 5972): nl80211: TDLS supported
D/wpa_supplicant( 5972): nl80211: TDLS external setup
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 5972): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 5972): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Using driver-based off-channel TX
,D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
,D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
,D/wpa_supplicant( 5972): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
,D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 5972): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 5972): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 5972): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 5972): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 5972): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 5972): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 5972): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 5972): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a7a8d100
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=0104
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=040a
,D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=040b
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=040c
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=040d
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=090a
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=090b
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=090c
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=090d
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=0409506f9a09
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=7f506f9a09
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=0801
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=040e
,D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=06
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=0a07
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=0a11
D/wpa_supplicant( 5972): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a7a8d100 match=0a1a
D/wpa_supplicant( 5972): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5972): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 5972): nl80211: Use separate P2P group interface
D/wpa_supplicant( 5972): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 5972): htc_wext_command_init +
I/wpa_supplicant( 5972): htc_wext_command_init -
I/wpa_supplicant( 5972): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
,I/wpa_supplicant( 5972): Don't set 00 to countryID.conf
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 5972): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5972): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5972): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 5972): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5972): P2P: Add operating class 81
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 5972): P2P: Update channel list
D/wpa_supplicant( 5972): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 5972): P2P: cli_channels:
D/wpa_supplicant( 5972): p2p0: Updating hw mode
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5972): nl80211: 2402-2472 @ 40 MHz 20 mBm
,D/wpa_supplicant( 5972): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=00
D/wpa_supplicant( 5972): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
,D/wpa_supplicant( 5972): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 5972): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  948): interfaceLinkStateChanged wlan0, false
D/Tethering(  948): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  948): Recipient 5626
,I/qcom-bluetooth( 6023): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 
,I/qcom-bluetooth( 6024): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** ,
,I/wpa_supplicant( 5972): wapi_supplicant_init: Init WAI packet wlan0,
D/wpa_supplicant( 5972):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 5972):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 5972):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 5972): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 5972): nl80211: Flush PMKIDs
,I/bt-btu  ( 5915): btu_task received preload complete event,
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x001f
,W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/PMS     (  948): acquireWL(3d84576f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5915 1002 null,
D/bt-btm  ( 5915): btm_acl_device_down
D/bt-btm  ( 5915): btm_acl_reset_paging
,D/bt-btm  ( 5915): btm_acl_set_discing
,D/wpa_supplicant( 5972): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 5972): TDLS: Driver uses external link setup
D/wpa_supplicant( 5972): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5972): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 5972): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 5972): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 5972): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 5972): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 5972): EAP: EAP entering state DISABLED
D/wpa_supplicant( 5972): Using existing control interface directory.
,I/wpa_supplicant( 5972): set country (DE) from /data/misc/wifi/countryID.conf,
I/wpa_supplicant( 5972): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 5972): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5972): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5972): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5972): P2P: Add operating class 81
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5972): P2P: Add operating class 115
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5972): P2P: Add operating class 116
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5972): P2P: Add operating class 117
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5972): P2P: Update channel list
D/wpa_supplicant( 5972): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5972): P2P: cli_channels:
D/wpa_supplicant( 5972): p2p0: Updating hw mode
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5972): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 5972): Auto country group 1: ch36
D/wpa_supplicant( 5972): wlan0: Added interface wlan0
D/wpa_supplicant( 5972): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 5972): nl80211: Set wlan0 operstate 0->0 (DORMANT)
,D/wpa_supplicant( 5972): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 5972): random: Got 20/20 bytes from /dev/random
D/wpa_supplicant( 5972): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 5972): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 5972): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 5972): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 5972): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 5972): nl80211: Regulatory domain change
D/wpa_supplicant( 5972):  * initiator=1
D/wpa_supplicant( 5972):  * type=0
D/wpa_supplicant( 5972):  * alpha2=DE
D/wpa_supplicant( 5972): wlan0: Event CHANNEL_LIST_CHANGED (30) received
,I/wpa_supplicant( 5972): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5972): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
,D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5972): P2P: Add operating class 81
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5972): P2P: Add operating class 115
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5972): P2P: Add operating class 116
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=2): 24 2c
,D/wpa_supplicant( 5972): P2P: Add operating class 117
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5972): P2P: Update channel list
D/wpa_supplicant( 5972): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5972): P2P: cli_channels:
,D/wpa_supplicant( 5972): p2p0: Updating hw mode
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5972): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
,D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
I/bt-btm  ( 5915): btm_reset_complete
I/bt-btm  ( 5915): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
,D/bt-btm  ( 5915): Start reading local supported commands
D/bt-btm  ( 5915): btm_read_local_supported_cmds_complete status (0x00)
D/bt-btm  ( 5915): BTM reads next extended features page (1)
D/bt-btm  ( 5915): BTM reads next extended features page (2)
D/bt-btm  ( 5915): BTM reached last extended features page (2)
,D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 5915): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
,D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
I/bt-btm  ( 5915): btm_vendor_capability_vsc_cmpl_cback: status=0
,D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
,D/bt-btm  ( 5915): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
,D/bt-btm  ( 5915): btm_read_ble_wl_size 
,D/bt-btm  ( 5915): btm_read_white_list_size_complete 
D/bt-btm  ( 5915): btm_get_ble_buffer_size 
,D/bt-btm  ( 5915): btm_read_ble_buf_size_complete 
D/bt-btm  ( 5915): btm_read_ble_local_supported_states 
,D/bt-btm  ( 5915): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 5915): btm_read_ble_local_supported_features 
,D/bt-btm  ( 5915): btm_read_ble_local_supported_features_complete 
,D/bt-btm  ( 5915): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 5915): btm_decode_ext_features_page page: 0
D/bt-btm  ( 5915): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 5915): Local supported SCO packet types: 0x038f
I/bt-btm  ( 5915): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 5915): btm_sec_dev_reset sec mode: 4
,I/bt-btm  ( 5915): BTM_SetInquiryMode
I/bt-btm  ( 5915): BTM_SetPageScanType
I/bt-btm  ( 5915): BTM_SetInquiryScanType
D/bt-btm  ( 5915): btm_decode_ext_features_page page: 1
W/bt-btm  ( 5915): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 5915): btm_decode_ext_features_page page: 2
W/bt-btm  ( 5915): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 5915): BTM_BleLoadLocalKeys
D/bt-btm  ( 5915): BTM_BleLoadLocalKeys
I/bt-btm  ( 5915): BTM_Sec: application registered
E/bt-btm  ( 5915): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf4dd4d5 
I/bt-btm  ( 5915): BTM_Sec: SMP_Register( btm_proc_smp_cback )
,I/bt-smp  ( 5915): SMP_Register state=0
E/bt-btm  ( 5915): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf4dd4d5 
I/bt-btm  ( 5915): BTM_Sec: application registered
D/bt-btm  ( 5915): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 5915): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 5915): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 5915): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 5915): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 5915): BTM_RegBusyLevelNotif,
D/bt-btm  ( 5915): BTM_BleReadControllerFeatures
I/bt-btm  ( 5915): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 5915): GATT_Register
D/bt-att  ( 5915): UUID=[0x87878787878787878787878787878787]
,I/bt-att  ( 5915): allocated gatt_if=3
I/bt-att  ( 5915): GATT_StartIf gatt_if=3
D/bt-att  ( 5915): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5915): gatt_find_the_connected_bda found=0 found_idx=16
,D/bt-btm  ( 5915): btm_ble_vendor_capability_vsc_cmpl_cback,
D/bt-btm  ( 5915): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1,
I/bt-btm  ( 5915): BTM Register For VSEvents is successfully,
D/bt-btm  ( 5915): BTM_BleGetVendorCapabilities
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5915): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 5915): Calling BTA_HhEnable
D/bt-btm  ( 5915): bta_dm_set_dev_name: name: HTC One M8s 
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915):  BTM_BleConfigPrivacy
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 5915): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 5915): BTM_AllocateSCN
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 5915): BTM_AllocateSCN
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 5915):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 5915): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 5915): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
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
,I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 5915): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:5
I/bt-btif ( 5915): BTA_MceEnable
I/bt-avp  ( 5915): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:6
E/bt-btif ( 5915): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-a2d  ( 5915): A2D_AddRecord uuid: 110a
D/BluetoothAdapterProperties( 5915): Address is:90:E7:C4:F6:69:77
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/bt-btif ( 5915):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:7
,I/bt-avp  ( 5915): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5915):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 5915):                : sec: 0xb6, service name [] (up to 21 chars saved)
,I/bt-btm  ( 5915): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 5915):                : sec: 0x80, service name [] (up to 21 chars saved),
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 5915): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 5915): GATT_Register
D/bt-att  ( 5915): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 5915): allocated gatt_if=4
,I/bt-att  ( 5915): GATT_StartIf gatt_if=4
D/bt-att  ( 5915): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 5915): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 5915): Scan Mode:21
D/BluetoothAdapterProperties( 5915): Discoverable Timeout:120
I/bt-btif ( 5915): BTA_JvEnable
,I/bt-btif ( 5915): BTA_JvRegisterL2cCback
I/bt-btm  ( 5915): BTM_ReadConnectability
I/bt-btm  ( 5915): BTM_ReadDiscoverability
I/bt-btm  ( 5915): BTM_SetDiscoverability
I/bt-btm  ( 5915): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 5915): disc_mode 0002
,D/bt-btm  ( 5915): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 5915): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5915): BTM_SetConnectability
I/bt-btm  ( 5915): btm_ble_set_connectability mode=0x0 combined_mode=0x1
,D/bt-btm  ( 5915): disc_mode 0002
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
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
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
I/bt-btm  ( 5915): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 5915): bta_pan_co_init
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 5915): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5915):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 5915):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
,I/bt-btm  ( 5915):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5915): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 5915):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
,D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/bt-btif ( 5915): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 5915): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5915): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 5915): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 5915): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 5915): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5915): ScanMode =  21
D/BluetoothAdapterProperties( 5915): State =  11
I/bt-btif ( 5915): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 5915): Setting state to 12
I/BluetoothAdapterState( 5915): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 5915): Discoverable Timeout:120
D/BluetoothManagerService(  948): +onBluetoothStateChange prev=11 new=12
I/BluetoothAdapterState( 5915): Entering On State
D/BluetoothManagerService(  948): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  948): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  948): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothA2dp(  948): onBluetoothStateChange: up=true
D/BluetoothHeadset(  948): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=true
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 7a 15 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 36 6d 2e a0 eb fe 9d 71 3f 02 ab 3e 16 f0 9b 2c 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1434): onBluetoothStateChange: up=true
,E/bt_mct  ( 5915): hci lib postload completed
D/BluetoothManagerService(  948): Bluetooth State Change Intent: 11 -> 12
D/NGFService( 3487): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3487): Bluetooth Adapter: ON
I/IntentController( 1221): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/BluetoothManagerService(  948): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  948): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  948): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
V/BluetoothPbapReceiver( 5915): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 5915): ***********state = 12
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 9a 8a 54 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 17 9b 41 cf e2 91 f1 a5 36 35 b1 1a 7d 04 60 3d 
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
,I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 3c 0e 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 25 c5 04 5c 63 78 01 38 55 36 fb 8c 8c c5 e7 b1 
D/PMS     (  948): acquireWL(6fe7d5a): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5354 1000 null
,W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothPbapService( 5915): Pbap Service onCreate
V/BluetoothPbapService( 5915): Starting PBAP service
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
D/PMS     (  948): releaseWL(6fe7d5a): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 26 cf 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = f6 4f 25 68 65 7b c2 2f cf ba 42 51 fe ae c4 0b 
D/BluetoothAdapter( 5915): 251028653: getState(). Returning 12
,V/BluetoothPbapService( 5915): Handler(): got msg=1
V/BluetoothPbapService( 5915): Pbap Service startRfcommSocketListener
D/HtcBtWidget_BTWidgetProvider( 5951): onBTStateChanged() for widget: 
D/PMS     (  948): acquireWL(1099a468): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5354 1000 null
,D/HtcBtWidget_BTWidgetProvider( 5951): updateWidget(context) for widget: 
,V/BluetoothPbapService( 5915): Pbap Service initSocket
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 21 c6 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 8a 6d 48 6d 1c 64 d2 9c f2 ec ce 7c cd 21 fc d4 
,D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
,W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 0b 48 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 97 7a 88 6d 7c d5 77 f7 be 7c 07 84 cd d0 fd 89 
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  948): java.lang.Throwable: stack dump
D/BluetoothManagerService(  948): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f29c567:true
W/System.err(  948): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  948): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  948): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  948): 	at android.os.Binder.execTransact(Binder.java:454)
,I/bt-btm  ( 5915): BTM_SetDiscoverability
I/bt-btif ( 5915): btm_ble_set_discoverability mode=0x0 com
I/bt-btm  ( 5915): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 5915): BTA_JvCreateRe
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
I/bt-btm  ( 5915): evt_type=0x0 p-cb->evt_type=0x0 ,
I/bt-btm  ( 5915): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 5915): BTM_SetConnectability
I/bt-btm  ( 5915): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 5915): disc_mode 0000
D/bt-btm  ( 5915): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 5915): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 5915): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 5915):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 5915): Succeed to create listening socket 
V/BluetoothPbapService( 5915): Accepting socket connection...
D/BluetoothAdapterProperties( 5915): Scan Mode:21
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 05 ad 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 67 43 5f 9b 05 84 60 6a 2b 9c 92 b9 ce 09 62 34 
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete,
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 9b 83 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = c4 94 cb 0e 1c 7f 6c bb 6f 25 ea 0b 3e 19 53 c6 
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete,
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = f7 8e 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = 26 54 58 8d 1d c7 d6 f3 a3 2c 75 cd 93 77 75 78 
,D/BluetoothAdapter( 1221): 454791546: getState(). Returning 12
,D/BluetoothAdapter( 5354): 1013171170: getState(). Returning 12
D/BluetoothAdapter( 1221): 454791546: getState(). Returning 12
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 3b 82 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = c6 d2 b6 90 70 9e 70 40 85 76 a6 fa e3 6d 08 85 
,I/QuickSettingBluetooth( 1221): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
,D/PhoneStatusBar( 1221): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/BluetoothInputDevice( 5354): BluetoothInputDevice()
D/BluetoothManagerService(  948): registerStateChangeCallback+
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): Registered receivers: 7
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete,
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 96 9a 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = c7 54 74 c9 c0 85 dd 93 f4 24 49 2f 7e db 15 53 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/BluetoothPan( 5354): BluetoothPan()
D/BluetoothManagerService(  948): registerStateChangeCallback+
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): Registered receivers: 8
,D/BluetoothMap( 5354): Create BluetoothMap proxy object
,D/BluetoothManagerService(  948): registerStateChangeCallback+
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): Registered receivers: 9
E/BluetoothMap( 5354): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  948): registerStateChangeCallback+,
D/BluetoothSap( 5354): BluetoothSap() call bindService
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): Registered receivers: 10
D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = d2 43 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = ae 9e 61 dd 2b 15 84 4a 3b 1b 76 7c e0 6c 17 6a 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
,D/BluetoothPbap( 5354): BluetoothPbap(),
D/BluetoothManagerService(  948): registerStateChangeCallback+
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): Registered receivers: 11
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
,I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = ee 1d 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = a7 63 15 a9 2a df ab f8 26 b1 88 ff 98 09 3c 88 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/BluetoothManagerService(  948): registerStateChangeCallback+
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): Registered receivers: 12
,D/BluetoothHeadset( 5354): BluetoothHeadset()
,D/BluetoothManagerService(  948): registerStateChangeCallback+
D/BluetoothManagerService(  948): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  948): Registered receivers: 13
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 5915): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:11
D/LocalBluetoothProfileManager( 5354): LocalBluetoothProfileManager construction complete
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 5915):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 5915): Accept thread started.
,D/BluetoothAdapter( 5915): 251028653: getState(). Returning 12
D/BluetoothFtpService( 5915): ACTION_STATE_CHANGED: state: 12mHasStarted: true
,D/BluetoothMasReceiver( 5915): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 5915):  call MAP start service
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = e9 2d 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = c8 da 1b a5 b8 6a 61 b0 a4 a5 1f 43 4c 4a b6 d4 
I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
,D/DockEventReceiver( 5354): finishStartingService: stopping service
,D/BluetoothInputDevice( 5354): Proxy object connected
V/BluetoothPbapService( 5915): Pbap Service onBind
D/HidProfile( 5354): Bluetooth service connected
D/BluetoothFtpService( 5915): htc sense version is 6.0
,D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
D/wpa_supplicant( 5972): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
,D/Tethering(  948): interfaceLinkStateChanged p2p0, false
D/Tethering(  948): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  948): WiFiDisplay: getWifidisplayApEnabled=false
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 5915):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothAdapter( 5354): 1013171170: getState(). Returning 12
,D/BluetoothPan( 5354): BluetoothPAN Proxy object connected
V/BluetoothFtpService:RfcommSocketAcceptThread( 5915): Run Accept thread
E/BluetoothMasService( 5915): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/PanProfile( 5354): Bluetooth service connected
,D/BluetoothA2dp( 5354): Proxy object connected
,D/A2dpProfile( 5354): Bluetooth service connected
D/BluetoothAdapter( 5354): 1013171170: getState(). Returning 12
,D/BluetoothHeadset( 5354): Proxy object connected
D/BluetoothMasService( 5915): Add permission for SmsProvider.
,D/HeadsetProfile( 5354): Bluetooth service connected
,V/BluetoothMasService( 5915): Starting MAS instances
D/BluetoothAdapter( 5915): 251028653: getState(). Returning 12
D/BluetoothAdapter( 5354): 1013171170: getState(). Returning 12
,I/MailMessageReceiver( 5915): reg:com.android.bluetooth.btservice.AdapterApp@15b5ed3a with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2199ddeb
,D/PMS     (  948): releaseWL(1099a468): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/MailManager( 5915): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@2199ddeb
V/EmailUtils( 5915): Manager Instance is not NULL
,D/BluetoothPbap( 5354): Proxy object connected
D/PbapServerProfile( 5354): Bluetooth service connected
,I/ActivityManager(  948): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6041 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/HtcAdjCursorFactory( 6041): Set CursorWindow size to: 4194304 KB, Tid: 6061,
,D/wpa_supplicant( 5972): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_948-3\x00
E/WifiStateMachine(  948): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  948): handleMessage: new destination call exit/enter
E/WifiStateMachine(  948): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  948): invokeExitMethods: InitialState
E/WifiStateMachine(  948): moveTempStackToStateStack: i=0,j=1
E/WifiStateMachine(  948): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  948): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131144
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  948): deferMessage: msg=131144
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131085
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  948): deferMessage: msg=131085
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131149
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  948): setSuspendOptimizations: 2 true
E/WifiStateMachine(  948): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131145
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131146
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131101
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  948): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  948): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131101
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  948): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  948): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=147457
E/WifiStateMachine(  948): processMsg: SupplicantStartingState
E/WifiStateMachine(  948):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  948): Supplicant connection established
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 5972): set wifi ON
E/WifiStateMachine(  948): setWifiState: enabled
E/WifiState,Machine(  948): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  948):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 5972): SET_SCREEN_ON:Off
I/wpa_supplicant( 5972): htc_wext_set_keepalive +
I/wpa_supplicant( 5972): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 5972): getPrivFuncNum +	
I/wpa_supplicant( 5972): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 5972): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 5972): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 5972): get_ip_address source addr = ffffffff
I/wpa_supplicant( 5972): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 5972): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  948): startHal
,E/wifi    (  948): getStaticLongField sWifiHalHandle 0x7f73552300
,I/WifiNative-HAL(  948): Could not start hal
E/WifiStateMachine(  948): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiDisplayAdapter(  948): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  948):     Client/Owner: Client
D/WifiDisplayAdapter(  948):     GroupId: 
D/WifiDisplayAdapter(  948):     Passphrase: 
D/WifiDisplayAdapter(  948):     SessionId: 0
D/WifiDisplayAdapter(  948):     IP Address: }
,D/WifiStateMachine(  948): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  948): handleScreenStateChanged Exit: false
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/WIFI_ICON( 1221): updateWifiState: WIFI_STATE_CHANGED enabled
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER MACADDR'
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 5972): update_config=1
I/IntentController( 1221): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/wpa_supplicant( 5972): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  948): Loading config and enabling all networks 
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 5972): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 5972): wpa_supplicant_ctrl_iface_list_networks: return size = 47
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='priority'
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/HtcWiFiWidget_WiFiWidgetProvider( 5986): onWiFiStateChanged() for widget: 
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
,D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
,D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 5972): Do not allow key_data field to be exposed
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/HtcWiFiWidget_WiFiWidgetProvider( 5986): updateWidget(context) for widget: 
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='proto'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/EmailUtils( 5915): ============NULL aList========
V/EmailUtils( 5915): <-getEmailAccountIdList
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
,D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
V/BluetoothMasService( 5915): onCreate: mIsEmailEnabled: true
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
,D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 eap'
,D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
,D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
,D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='engine'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
,D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 5972): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 5972): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,D/BluetoothAdapter( 5915): 251028653: getState(). Returning 12
V/BluetoothMasService( 5915): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 5915): Manager Instance is not NULL
E/WifiConfigStore(  948): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/EmailUtils( 5915): ============NULL aList========
V/EmailUtils( 5915): <-getEmailAccountIdList
V/BluetoothSapReceiver( 5915): SapReceiver onReceive 
V/BluetoothSapReceiver( 5915): action = android.bluetooth.adapter.action.STATE_CHANGED,
V/BluetoothSapReceiver( 5915):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 5915): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothMasService( 5915): handleMessage: mIsEmailEnabledtrue
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 5972): device_name='m8qlul_htc_europe'
V/BtMns   ( 5915): BluetoothMns: isEmailEnabled: true,
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 5972): manufacturer='HTC'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 5972): model_name='HTC One M8s'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 5972): model_number='HTC One M8s'
D/AuthorizationBluetoothService( 1840): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 5972): config_methods='physical_display virtual_push_button'
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  948): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  948): handleMessage: new destination call exit/enter
E/WifiStateMachine(  948): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  948): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  948): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  948): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  948): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  948): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 5972): wlan0: Setting scan interval: 15 sec
D/WifiP2pService(  948): P2pDisabledState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-HAL(  948): Setting external_sim to 1
D/WifiP2pService(  948): DefaultState{ when=0 what=131332 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 5972): external_sim=1
D/WifiStateMachine(  948): Setting OUI to DA-A1-19
I/WifiNative-HAL(  948): startHal
E/wifi    (  948): getStaticLongField sWifiHalHandle 0x7f73552360
I/WifiNative-HAL(  948): Could not start hal
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 5972): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  948): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  948): Driverstarted State enter
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd, BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  948): DriverStartedState call setCountryCode()
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine(  948): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  948): NetworkAgent == null
I/QuickSettingWifi( 1221): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
,I/bt-btif ( 5915): BTA_JvCreateRecordByUser
,D/bt-btm  ( 5915): BTM_AllocateSCN
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 5915):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine(  948): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/bt-btm  ( 5915): BTM_AllocateSCN
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 5915):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
E/WifiTrafficPoller(  948): ENABLE_TRAFFIC_STATS_POLL false Token 0
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
W/Settings( 5178): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
I/IntentController( 1221): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WIFI_ICON( 1221): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/Process (  948): killProcessQuiet, pid=4556
I/ActivityManager(  948): Killing 4556:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/StatusBar.NetworkController( 1221): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  948): setDhcpActive: false
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 5972): wlan0: Control interface command 'STATUS'
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiStateMachine(  948): transitionTo: destState=DisconnectedState
E/native  (  948): do suspend false
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
D/HTCRequest(  948): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  948): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  948): WifiMonitor:handleSupplicantStateChange(): SSID
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 5972): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  948): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/WifiP2pService(  948): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  948): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  948): [NET] android_getaddrinfofornet-, SUCCESS
D/WifiMonitor(  948): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  948): P2pEnablingState
,D/WifiP2pService(  948): P2pEnablingState{ when=-7ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  948): P2p socket connection successful
D/WifiP2pService(  948): P2pEnabledState
,I/QuickSettingWifi( 1221): receive.wifiConnect:false wifiAPname:null elapse:0,
,I/ActivityManager(  948): Recipient 4556
,V/BluetoothSapService( 5915): Sap Service onCreate,
D/WifiP2pService(  948): sending p2p connection changed broadcast
,V/BluetoothSapService( 5915): initBinder
D/WifiDisplayController(  948): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,E/WifiStateMachine(  948): Driverstarted State enter done
D/WifiDisplayController(  948): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  948): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiDisplayController(  948): mWfdEnabled :false, networkInfo.isConnected() :false,
E/WifiStateMachine(  948): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  948): handleMessage: new destination call exit/enter
D/WifiDisplayAdapter(  948): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  948):     Client/Owner: Client
D/WifiDisplayAdapter(  948):     GroupId: 
D/WifiDisplayAdapter(  948):     Passphrase: 
D/WifiDisplayAdapter(  948):     SessionId: 0
D/WifiDisplayAdapter(  948):     IP Address: }
,E/WifiStateMachine(  948): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  948): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  948): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  948): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  948): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  948): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  948): DisconnectedState call setCountryCode()
E/WifiStateMachine(  948):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 5972): wlan0: nl80211: sched_scan request
V/BluetoothSapService( 5915): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@385a306
V/BluetoothSapService( 5915): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@1f898ff4
D/WifiScanningService(  948): SCAN_AVAILABLE : 3
D/RttService(  948): SCAN_AVAILABLE : 3
D/WifiScanningService(  948): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  948): startHal
D/RttService(  948): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,V/BluetoothSapService( 5915): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 5915): state: 12
V/BluetoothSapService( 5915): Starting SAP server process
V/AudioService(  948): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  948):     Client/Owner: Client
V/AudioService(  948):     GroupId: 
V/AudioService(  948):     Passphrase: 
V/AudioService(  948):     SessionId: 0
V/AudioService(  948):     IP Address: }
D/HtcEffectManagerBase(  948): onEventChanged id=5 status=false
D/HtcEffectManager(  948): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
,D/HtcEffectManager(  948): convertEffect before=902
D/HtcEffectManager(  948): convertEffect after=902
D/A2dpService( 5915): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@448e992
D/A2dpSinkService( 5915): getA2dpSinkService(): service is NULL
V/BluetoothSapService( 5915): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 5915): Sap Service initRfcommSocket
D/BluetoothManagerService(  948): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/wpa_supplicant( 5972): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
,D/wpa_supplicant( 5972): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 5972): wlan0: nl80211: Sched scan started
W/BluetoothAdapter( 5915): getBluetoothService() called with no BluetoothManagerCallback
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131144
,E/WifiStateMachine(  948): processMsg: DisconnectedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/WifiP2pService(  948): DeviceAddress: 92:e7:c4:e6:4c:f8
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/WifiDisplayController(  948): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  948):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  948):  primary type: 10-0050F204-5
D/WifiDisplayController(  948):  secondary type: null
D/WifiDisplayController(  948):  wps: 0
D/WifiDisplayController(  948):  grpcapab: 0
D/WifiDisplayController(  948):  devcapab: 0
D/WifiDisplayController(  948):  status: 3
D/WifiDisplayController(  948):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  948):  WFD CtrlPort: 0
D/WifiDisplayController(  948):  WFD MaxThroughput: 0
D/wpa_supplicant( 5972): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
,D/wpa_supplicant( 5972): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 5972): persistent_reconnect=1
D/wpa_supplicant( 5972): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 5972): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  948):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
D/wpa_supplicant( 5972): P2P: Set Operating channel: reg_class 126 channel 149
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131085
E/WifiStateMachine(  948): processMsg: DisconnectedState
E/wifi    (  948): getStaticLongField sWifiHalHandle 0x7f70477520
I/WifiNative-HAL(  948): Could not start hal
I/bt-btif ( 5915): BTA_JvCreateRecordByUser
E/WifiScanningService(  948): could not start HAL
W/WifiHW  (  948): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  948):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  948): processMsg: ConnectModeState
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 5972): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 5972): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'device_name'='Android_608e'
D/WifiP2pService(  948): sending p2p persistent groups changed broadcast
D/wpa_supplicant( 5972): device_name='Android_608e'
D/bt-sdp  ( 5915): SDP_CreateRecord ok, num_records:15
D/WifiP2pService(  948): InactiveState
E/WifiStateMachine(  948):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  948): processMsg: DriverStartedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
I/bt-btm  ( 5915): Write Extended Inquiry Response to controller
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 5972): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
E/WifiStateMachine(  948):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131154
E/WifiStateMachine(  948): processMsg: DisconnectedState
D/wpa_supplicant( 5972): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
E/WifiStateMachine(  948):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  948): processMsg: ConnectModeState
D/wpa_supplicant( 5972): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 5972): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 5972): P2P: New SSID postfix: -Android_608e
E/WifiStateMachine(  948):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  948): processMsg: DriverStartedState
I/bt-btif ( 5915): BTA_JvRfcommStartServer
I/bt-btm  ( 5915): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 5915):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
E/WifiStateMachine(  948):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  948): processMsg: SupplicantStartedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 5972): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 5972): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'device_type'='10-0050F204-5'
V/BluetoothSapService( 5915): Succeed to create listening socket 
V/BluetoothSapService( 5915): Accepting socket connection...
E/WifiStateMachine(  948):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  948):, processMsg: DefaultState
W/WifiHW  (  948): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  948):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  948): handleMessage: X
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 5972): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5972): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 5972): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 5972): config_methods='virtual_push_button physical_display keypad'
E/WifiStateMachine(  948): handleMessage: E msg.what=131323
E/WifiStateMachine(  948): processMsg: DisconnectedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 5972): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 5972): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 5972): Single channel concurrency preference: sta
E/WifiStateMachine(  948):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  948): processMsg: ConnectModeState
D/WifiNative-HAL(  948): p2pGetDeviceAddress
W/WifiHW  (  948): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
E/WifiStateMachine(  948):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  948): processMsg: DriverStartedState
D/WifiNative-HAL(  948): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
E/WifiStateMachine(  948):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  948): processMsg: SupplicantStartedState
E/WifiStateMachine(  948):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  948): processMsg: DefaultState
E/WifiStateMachine(  948):  DefaultState what:131323 0 0
E/WifiStateMachine(  948): setOperatorSSID enter
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=131104
E/WifiStateMachine(  948): processMsg: DisconnectedState
W/WifiHW  (  948): QCOM Debug wifi_send_command "P2P_FLUSH"
D/wpa_supplicant( 5972): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 5972): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 5972): P2P: Stopping find
D/wpa_supplicant( 5972): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 5972): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5972): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 5972): P2P: Stopping find
D/wpa_supplicant( 5972): P2P: Clear timeout (state=IDLE)
,D/wpa_supplicant( 5972): P2P: State IDLE -> IDLE
D/wpa_supplicant( 5972): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  948): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
E/WifiStateMachine(  948):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  948): processMsg: ConnectModeState
,D/wpa_supplicant( 5972): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 5972): [p2p command] (P2P_SERVICE_FLUSH)
E/WifiStateMachine(  948):  ConnectModeState what:131104 0 0
W/Settings(  948): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  948): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 5972): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 5972): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
,D/wpa_supplicant( 5972): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 5972): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 5972): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
W/WifiHW  (  948): QCOM Debug wifi_send_command "SAVE_CONFIG"
E/WifiStateMachine(  948): handleMessage: X
D/wpa_supplicant( 5972): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
E/WifiStateMachine(  948): handleMessage: E msg.what=131162
D/wpa_supplicant( 5972): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
E/WifiStateMachine(  948): processMsg: DisconnectedState
D/wpa_supplicant( 5972): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 5972): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 5972): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
E/WifiStateMachine(  948):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/wpa_supplicant( 5972): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 5972): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
,E/WifiStateMachine(  948): processMsg: ConnectModeState
E/WifiStateMachine(  948):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  948): processMsg: DriverStartedState
E/WifiStateMachine(  948):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  948): set frequency band 0
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 5972): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 5972): SETBAND: 0
D/wpa_supplicant( 5972): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 5972): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 5972): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  948): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  948): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  948): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  948): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5972): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 5972): P2P: Add operating class 81
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 5972): P2P: Add operating class 115
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 5972): P2P: Add operating class 116
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 5972): P2P: Add operating class 117
D/wpa_supplicant( 5972): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 5972): P2P: Update channel list
D/wpa_supplicant( 5972): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 5972): P2P: cli_channels:
D/wpa_supplicant( 5972): p2p0: Updating hw mode
D/wpa_supplicant( 5972): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 5972): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 5972): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 5972): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 5972): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  948): did set frequency band 0
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 5972): wlan0: Control interface command 'BSS_FLUSH 0'
D/wpa_supplicant( 5972): EAPOL: disable timer tick
W/WifiHW  (  948): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 5972): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 5972): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 5972): wlan0: Cancelling sched scan
D/wpa_supplicant( 5972): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 5972): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 5972): wpa_supplicant_scan enter
D/wpa_supplicant( 5972): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 5972): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/wpa_supplicant( 5972): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 5972): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  948): done set frequency band 0
D/SapServerProfile( 5354): Bluetooth service connected
D/WISPrService( 5354): >>>>>WISPrService start isConnected = false<<<<<
D/WifiService(  948): New client listening to asynchronous messages
E/WifiTrafficPoller(  948): ADD_CLIENT: 8
,D/WifiStateMachine(  948): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  948): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=147462
E/WifiStateMachine(  948): processMsg: DisconnectedState
,E/WifiStateMachine(  948):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=149199  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  948): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  948): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  948): processMsg: ConnectModeState
,E/WifiStateMachine(  948):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 0 0 rt=149200  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
D/WISPrService( 5354): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/WifiStateMachine(  948): handleMessage: X
E/WifiStateMachine(  948): handleMessage: E msg.what=143371
E/WifiStateMachine(  948): processMsg: DisconnectedState
,E/WifiStateMachine(  948):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  948): processMsg: ConnectModeState
E/WifiStateMachine(  948):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  948): processMsg: DriverStartedState
,E/WifiStateMachine(  948):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  948): processMsg: SupplicantStartedState
E/WifiStateMachine(  948):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  948): processMsg: DefaultState
,E/WifiStateMachine(  948):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  948): handleMessage: X
,D/PMS     (  948): acquireWL(2d2a143f): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{10024},
V/AlarmManager(  948): sending alarm PendingIntent{34d0010c: PendingIntentRecord{382a4a55 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=141546, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{1f65bc6a: PendingIntentRecord{1cac419d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=145871, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{ef8c304: PendingIntentRecord{46e70ed android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=149318, Int=0
,D/PMS     (  948): acquireWL(1b5b55b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
,D/libc    (  948): [NET] android_getaddrinfofornet-, err=8
D/PMS     (  948): releaseWL(2d2a143f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  948): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  948): [NET] android_getaddrinfo_proxy+
D/libc    (  948): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    (  948): [NET] android_getaddrinfo_proxy-, NODATA
,D/libc    ( 1840): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1840): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    ( 1840): [NET] android_getaddrinfo_proxy+
D/libc    ( 1840): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  948): releaseWL(1b5b55b): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1840): [NET] android_getaddrinfo_proxy-, NODATA
,D/wpa_supplicant( 5972): EAPOL: disable timer tick,
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 5861): 
,I/jxcore-log( 5861): Test app app.js loaded,
I/jxcore-log( 5861): 
,I/Choreographer( 5861): Skipped 251 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 5861): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5861): setDiscoveryMode: Mode set to BLE,
,I/jxcore-log( 5861): BLE advertisement is supported,
I/jxcore-log( 5861): 
,D/PMS     (  948): releaseWL(3d84576f): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,W/ContextImpl(  948): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1434): switchBindHtcMsgCursor: null
,D/PMS     (  948): acquireWL(370221f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null,
I/BatteryService(  948): n_update end
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/PMS     (  948): releaseWL(370221f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/NotificationService(  948): plugged=true pluggin=true
D/WifiController(  948): handleMessage: E msg.what=155652
,D/PMS     (  948): runPSCheck
D/WifiController(  948): processMsg: DeviceActiveState
D/HtcPowerSaver(  948): Checking...
D/WifiController(  948): processMsg: StaEnabledState
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): handleMessage: X
D/PowerUI ( 1221): closing low battery warning: level=98
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  948): updateStatus (8000,98,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,D/PMS     (  948): acquireWL(101236d1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000}
,V/AlarmManager(  948): sending alarm PendingIntent{3c9d412d: PendingIntentRecord{e9ea662 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=181634, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{ef8c304: PendingIntentRecord{46e70ed android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=209336, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{1b1b3536: PendingIntentRecord{32904c37 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=210284, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{283365a4: PendingIntentRecord{7b26f0d com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=184193, Int=0
D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  948): [NET] android_getaddrinfofornet-, err=8
D/libc    (  948): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  948): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  948): [NET] android_getaddrinfo_proxy+
D/libc    (  948): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    (  948): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  948): acquireWL(15dd6ec2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1221): Weather sync is On
,W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  948): releaseWL(101236d1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  948): releaseWL(15dd6ec2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1221): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1399): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@8aade24,
,I/ActivityManager(  948): Killing 5657:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=5657
,D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5657,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  948): acquireWL(1897b50e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null,
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/BatteryService(  948): n_update end
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  948): releaseWL(1897b50e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  948): Checking...
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  948): >> updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): handleMessage: E msg.what=155652
D/PowerUI ( 1221): closing low battery warning: level=98
D/WifiController(  948): processMsg: DeviceActiveState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): processMsg: StaEnabledState
I/HtcPowerSaver(  948): updateStatus (8000,98,-1,false,false,false,-1)
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): << updateStatus
D/WifiController(  948): handleMessage: X
,I/BatteryController( 1221): status:2 level:98 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/PMS     (  948): acquireWL(8968b2f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000}
V/AlarmManager(  948): sending alarm PendingIntent{3c9d412d: PendingIntentRecord{e9ea662 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=241634, Int=0,
V/AlarmManager(  948): sending alarm PendingIntent{1bdbc53c: PendingIntentRecord{1cac419d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=262462, Int=0
D/PMS     (  948): acquireWL(1b1372c5): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1840): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1840): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1840): [NET] android_getaddrinfo_proxy+
,D/libc    ( 1840): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1840): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  948): releaseWL(1b1372c5): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(8968b2f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  948): acquireWL(3d9e141a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null,
I/BatteryService(  948): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  948): releaseWL(3d9e141a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1221): closing low battery warning: level=99
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/NotificationService(  948): plugged=true pluggin=true
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
,D/WifiController(  948): handleMessage: E msg.what=155652
D/PMS     (  948): runPSCheck
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: StaEnabledState
D/HtcPowerSaver(  948): Checking...
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): handleMessage: X
,I/HtcPowerSaver(  948): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     (  948): Explicit concurrent mark sweep GC freed 28327(1503KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.941ms total 180.374ms,
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1840): Explicit concurrent mark sweep GC freed 17333(969KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 1.007ms total 66.965ms
,I/ActionCombine( 1840): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 1221): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1221): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GLSActivity( 1840): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1840): ,	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1840): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1840): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1840): 	at android.os.Binder.execTransact(Binder.java:454)
,W/ResourcesManager( 1304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5379): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5379): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5379): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5379): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1221): apply : com.google.android.gms 0 19 8 40,
,W/System  ( 5379): Ignoring header User-Agent because its value was null.,
,D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5379): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5379): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5379): [NET] android_getaddrinfo_proxy+
D/libc    ( 5379): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5379): [NET] android_getaddrinfo_proxy-, NODATA
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  948): acquireWL(3538f56c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(3538f56c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  948): Checking...
D/WifiController(  948): handleMessage: E msg.what=155652
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): battery changed pluggedType: 2
,D/WifiController(  948): processMsg: StaEnabledState
D/PowerUI ( 1221): closing low battery warning: level=99
,D/WifiController(  948): processMsg: DefaultState
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  948): handleMessage: X
I/HtcPowerSaver(  948): updateStatus (8000,99,-1,false,false,false,-1)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/HtcPowerSaver(  948): << updateStatus
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  948): acquireWL(18f9735): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/PMS     (  948): releaseWL(18f9735): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/PMS     (  948): runPSCheck
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  948): >> updateStatus
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
,I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1221): closing low battery warning: level=99
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  948): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1221): status:2 level:99 unsupport:false plugged:true
,D/PMS     (  948): acquireWL(1233b7ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000},
,V/AlarmManager(  948): sending alarm PendingIntent{3c9d412d: PendingIntentRecord{e9ea662 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=301634, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{975fc58: PendingIntentRecord{3e2f71b1 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1453126839102, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{ebd8696: PendingIntentRecord{1cac419d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=488727, Int=0
D/PMS     (  948): acquireWL(33b83217): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1840): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1840): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1840): [NET] android_getaddrinfo_proxy+
D/libc    ( 1840): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1840): [NET] android_getaddrinfo_proxy-, NODATA
,I/ActivityManager(  948): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6086 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
V/AlarmManager(  948): sending alarm PendingIntent{397a8604: PendingIntentRecord{391877ed com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1453126943962, Int=0
,D/PMS     (  948): releaseWL(33b83217): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  948): releaseWL(1233b7ca): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,E/cutils-trace( 6107): Error opening trace file: Permission denied (13)
,I/dex2oat ( 6107): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6107): dex2oat: override thread count:4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 3
,I/dex2oat ( 6107): dex2oat took 575.148ms (threads: 4)
,I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6086): ApplicationMonitor {15d72d64}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6086): PnsModel {264b5af7}: update(): Update registration caused by: alarm
,I/PushClient( 6086): PnsConfigModel {269c79da}: <init>(): Use dm-client for provisioning.
,W/System.err( 6086): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,W/System.err( 6086): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6086): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6086): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  948): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6114 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6114): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6114 dbg=false s=true,
,I/DeviceManagement( 6114): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6114): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,I/DeviceManagement( 6114): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]],
,I/DeviceManagement( 6114): WorkflowService: Starting workflow service
,I/DeviceManagement( 6114): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@233246f6] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6114): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6114): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6114): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6114): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6114): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6114): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6114): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6114): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@233246f6],
,I/DeviceManagement( 6114): WorkflowService: Stopping workflow service
,D/Process (  948): killProcessQuiet, pid=5448,
I/ActivityManager(  948): Killing 5448:com.google.android.apps.plus/u0a167 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5448
,I/PushClient( 6086): PnsModel {264b5af7}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  948): killProcessQuiet, pid=5305
I/ActivityManager(  948): Killing 5305:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  948): Recipient 5305
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  469): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  948): acquireWL(782c146): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
I/BatteryService(  948): n_update end
D/DotMatrix( 1304): [EventService] reorderNotification, total:0
D/PMS     (  948): releaseWL(782c146): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false),
D/NotificationService(  948): plugged=true pluggin=true
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
D/PowerUI ( 1221): closing low battery warning: level=100
D/HeadsetPhoneState( 5915): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HtcPowerSaver(  948): updateBatteryInfo
D/HeadsetStateMachine( 5915): Disconnected process message: 11, size: 0
D/WifiController(  948): battery changed pluggedType: 2
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/PMS     (  948): runPSCheck
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  948): Checking...
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  948): >> updateStatus
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  948): << updateStatus
,W/ContextImpl( 5759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
,D/TetherSettings( 5354): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5354): Cust_ConnectToPC   : Internet_Sharing>true
,D/        ( 5354): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5354): Cust_ConnectToPC   : spcsc>false
,D/        ( 5354): Cust_ConnectToPC   : IPT>true
D/        ( 5354): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 5354): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
D/SmartNS_NSReceiver( 5354): Index of the first 1 = -1
,W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
W/Settings( 5354): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 5354): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5354): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5354): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 5354): [ACC]android_networking:tethering_guard_support=false,
W/SystemReader( 5354): Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,D/ContactMessageStore( 1434): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1434): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1434): sku_id=118
D/ContactMessageStore( 1434): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1434): start background delete task...
,D/ContactMessageStore( 1434): size: 0 , 0
,D/ContactMessageStore( 1434): Background delete complete
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1840): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1840): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1840): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1840): 	at android.os.Binder.execTransact(Binder.java:454)
,I/RemoteViews( 1221): reapply : com.google.android.gms 2 40
D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5379): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5379): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5379): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
,E/PlayEventLogger( 5379): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5379): Ignoring header User-Agent because its value was null.
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5379): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5379): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5379): [NET] android_getaddrinfo_proxy+,
D/libc    ( 5379): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 5379): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  948): acquireWL(37c39c91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null,
I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(37c39c91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/PowerUI ( 1221): closing low battery warning: level=100
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/WifiController(  948): battery changed pluggedType: 2
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): processMsg: DeviceActiveState
D/WifiController(  948): processMsg: StaEnabledState
D/WifiController(  948): processMsg: DefaultState
D/WifiController(  948): handleMessage: X
D/PMS     (  948): runPSCheck
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  948): Checking...
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  948): >> updateStatus
,I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  948): << updateStatus
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  948): acquireWL(12407f6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000},
V/AlarmManager(  948): sending alarm PendingIntent{3c9d412d: PendingIntentRecord{e9ea662 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=541634, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{3be7dab1: PendingIntentRecord{3c403b96 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=809321, Int=0
,D/Finsky  ( 5379): [1] DailyHygiene.onStartCommand: Beginning daily hygiene,
V/AlarmManager(  948): sending alarm PendingIntent{2e195664: PendingIntentRecord{8a79d0b com.android.vending startService}}, i=null, t=0, cnt=1, w=1453127135801, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{e7470cd: PendingIntentRecord{1cac419d com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=941244, Int=0
V/AlarmManager(  948): sending alarm PendingIntent{2d80ad82: PendingIntentRecord{244356a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453127458062, Int=0
D/PMS     (  948): acquireWL(933ac93): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1840): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1840): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1840): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1840): [NET] android_getaddrinfo_proxy+
D/libc    ( 1840): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1840): [NET] android_getaddrinfo_proxy-, NODATA
,W/ContextImpl( 5759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  948): releaseWL(933ac93): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:PowerUsageHelper( 5759): MY_DEBUG = false,
,D/PowerUsageService( 5759): repeat time = 1453128358131,
D/PMS     (  948): releaseWL(12407f6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5379): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/PowerUsageList:PowerUsageHelper( 5759): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 5759): gen(), null == sipper.uidObj, userId = 0
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5379): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 5379): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5379): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5379): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5379): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1817): client connected with version: 7571000
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1840): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1840): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1840): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1840): 	at android.os.Binder.execTransact(Binder.java:454)
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/PlayEventLogger( 5379): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5379): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
,E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5379): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5379): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5379): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1221): reapply : com.google.android.gms 4 40
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5379): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5379): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5379): [NET] android_getaddrinfo_proxy+
D/libc    ( 5379): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5379): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  948): acquireWL(59d9ab6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000},
V/AlarmManager(  948): sending alarm PendingIntent{3c9d412d: PendingIntentRecord{e9ea662 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=961634, Int=0,
,V/AlarmManager(  948): sending alarm PendingIntent{3be0724: PendingIntentRecord{27ee328d com.android.vending startService}}, i=null, t=0, cnt=1, w=1453127473353, Int=0
,D/PMS     (  948): releaseWL(59d9ab6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/Finsky  ( 5379): [557] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5379): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  948): acquireWL(39e0ac42): PARTIAL_WAKE_LOCK  *alarm* 0x1 948 1000 WorkSource{1000}
V/AlarmManager(  948): sending alarm PendingIntent{1631a453: PendingIntentRecord{3e667190 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453127510015, Int=0
,D/SmartSyncUtils( 5759): isEpsOn(), nState = 0,
D/PMS     (  948): releaseWL(39e0ac42): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/PMS     (  948): acquireWL(2d986a89): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 5759 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 5759): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 5759): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 5759): AlarmOnTime = -1
,D/SmartSyncScreenOnOffTimeReceiver( 5759): SettingOnTime = 1453183200000, randomSettingOnTime = 1453179804000
D/SmartSyncScreenOnOffTimeReceiver( 5759): SettingOffTime = 1453161600000, randomSettingOffTime = 1453163631000
,D/SmartSyncScreenOnOffTimeReceiver( 5759): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 5759): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 5759): bNightModeTurnOffOnce = false
,D/PMS     (  948): releaseWL(2d986a89): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  948): acquireWL(9514a8e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 948 1000 WorkSource{1000},
V/AlarmManager(  948): sending alarm PendingIntent{3c9d412d: PendingIntentRecord{e9ea662 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1021634, Int=0
,V/AlarmManager(  948): sending alarm PendingIntent{342832af: PendingIntentRecord{16e916bc com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1048485, Int=0
I/bt-btm  ( 5915): Received oneshot timer event complete
,I/bt-btm  ( 5915): btm_ble_timeout
I/bt-btm  ( 5915): btm_gen_resolvable_private_addr
,D/PMS     (  948): acquireWL(17942645): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5915 1002 null,
,D/bt-btm  ( 5915): btm_ble_rand_enc_complete,
I/bt-btm  ( 5915): btm_gen_resolve_paddr_low,
D/bt-smp  ( 5915): smp_encrypt_data
W/bt-smp  ( 5915): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 5915): Plain text(LSB ~ MSB) = 14 52 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 5915): Encrypted text(LSB ~ MSB) = bd fd 9b 78 b4 74 fd db 1b e3 da 9a e7 4c 51 9f 
,I/bt-btm  ( 5915): btm_gen_resolve_paddr_cmpl,
W/bt-btm  ( 5915): Stopping oneshot timer
D/bt-btm  ( 5915): Starting oneshot timer type:103 timeout:900s
D/PMS     (  948): releaseWL(9514a8e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1221): Weather sync is On,
W/WeatherTimeKeeper( 1221): [refreshWeatherData] no weather data
,D/PMS     (  948): releaseWL(17942645): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/PMS     (  948): acquireWL(c1b819a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 948 1000 null
,I/BatteryService(  948): n_update end
D/PMS     (  948): releaseWL(c1b819a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  948): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  948): updateBatteryInfo
D/UsbnetService(  948): onReceive BATTERY_CHANGED
D/NotificationService(  948): plugged=true pluggin=true
D/UsbnetService(  948):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  948): BroadcastReceiver::onReceive-
D/PMS     (  948): runPSCheck
D/HtcPowerSaver(  948): Checking...
I/HtcPowerSaver(  948): >> updateStatus
,D/WifiController(  948): handleMessage: E msg.what=155652
D/WifiController(  948): battery changed pluggedType: 2
D/WifiController(  948): processMsg: DeviceActiveState
D/PowerUI ( 1221): closing low battery warning: level=100
,D/WifiController(  948): processMsg: StaEnabledState
I/HtcPowerSaver(  948): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  948): processMsg: DefaultState
I/HtcPowerSaver(  948): << updateStatus
D/WifiController(  948): handleMessage: X
D/PowerUI ( 1221): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 97, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HeadsetStateMachine( 5915): Disconnected process message: 10, size: 0
I/IntentController( 1221): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1304): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1221): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory),
,I/UsageStatsService(  948): User[0] Flushing usage stats to disk
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1840): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1840): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1840): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1840): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1840): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1840): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1840): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1840): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1840): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5379): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5379): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5379): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5379): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5379): 	at android.os.Binder.execTransact(Binder.java:454),
W/System  ( 5379): Ignoring header User-Agent because its value was null.
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5379): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5379): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5379): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5379): [NET] android_getaddrinfo_proxy+
D/libc    ( 5379): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  402): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  402): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  402): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  402): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5379): [NET] android_getaddrinfo_proxy-, NODATA
,D/DotMatrix( 1304): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/art     (  948): Explicit concurrent mark sweep GC freed 21490(1043KB) AllocSpace objects, 10(944KB) LOS objects, 33% free, 16MB/24MB, paused 1.682ms total 168.268ms,
,I/RemoteViews( 1221): reapply : com.google.android.gms 3 40,
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 6158): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6158): ====startRecUseTime====
D/htc.customization.log.level( 6158):  is 
W/CustomizationLogLevel( 6158): Level value is invalid, use default level 2
D/CustomizationManager( 6158):  Read ACC file spent 0.050 (s)
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6158): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6158): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6158): Parsing tag category name = system
I/CustomizationCIDLoader( 6158): Parsing tag category name = application
I/CustomizationCIDLoader( 6158): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6158): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6158): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6158): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6158): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6158): add string-array item, value = 42507
I/CustomizationCIDLoader( 6158): add string-array item, value = 21902
I/CustomizationCIDLoader( 6158): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6158): add string-array item, value = 23420
I/CustomizationCIDLoader( 6158): add string-array item, value = 22299
I/CustomizationCIDLoader( 6158): add string-array item, value = 24002
I/CustomizationCIDLoader( 6158): add string-array item, value = 23210
I/CustomizationCIDLoader( 6158): add string-array item, value = 23205
I/CustomizationCIDLoader( 6158): add string-array item, value = 23806
I/CustomizationCIDLoader( 6158): add string-array item, value = 23430
I/CustomizationCIDLoader( 6158): add string-array item, value = 23408
I/CustomizationCIDLoader( 6158): add string-array item, value = 27205
I/CustomizationCIDLoader( 6158): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6158): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6158):  Read CID file spent 0.109 (s)
D/CustomizationManager( 6158):  All configurations done spent 0.109 (s)
D/PackageManager(  948): deletePackageAsUser: pkg=com.test.thalitest, pid=6158, uid=2000 userid=0
D/Process (  948): killProcessQuiet, pid=5861
I/ActivityManager(  948): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
I/ActivityManager(  948): Killing 5861:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
W/PackageSettings(  948): Skipping PackageSetting{395bb73d com.example.hello/10374} due to missing metadata
I/ActivityManager(  948): Recipient 5861
I/WindowState(  948): WIN DEATH: Window{e612943 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  948): Client connection lost with reason: 4
E/InputEventReceiver( 1357): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{3fe3169f uid 10366 pid 5861} (c)'
I/ActivityManager(  948):   Force finishing activity ActivityRecord{b7d0f8c u0 com.test.thalitest/.MainActivity t8}
I/ActivityManager(  948): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  948):   Force finishing activity ActivityRecord{b7d0f8c u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager(  948): Duplicate finish request for ActivityRecord{b7d0f8c u0 com.test.thalitest/.MainActivity t8 f}
D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1304): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1304): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/ActivityManager(  948): Spurious death for ProcessRecord{24fda6ec 5861:com.test.thalitest/u0a366}, curProc for 5861: null
D/PMS     (  948): acquireWL(fa7854a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1817 10024 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1660): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/VoicemailCleanupService( 1643): Cleaning up data for package: com.test.thalitest
W/GeofencerStateMachine( 1817): Ignoring removeGeofence because network location is disabled.
W/SystemReader(  948): Cannot find grip_rejection_width, use default value instead
D/PMS     (  948): releaseWL(fa7854a): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1660): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
D/PhoneApp( 1434): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/art     ( 1497): Explicit concurrent mark sweep GC freed 5955(340KB) AllocSpace objects, 6(488KB) LOS objects, 34% free, 29MB/45MB, paused 964us total 99.367ms
D/Prism.PackageStateRece_( 1497): action: android.intent.action.PACKAGE_REMOVED
I/Prism.ItemManager( 1497): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1497): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Launcher( 1497): Deferring update until onResume
I/InputMethodManagerService(  948): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/Launcher( 1497): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1660): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  948): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1660): Unsupported attribute readOnly
I/art     (  437): Explicit concurrent mark sweep GC freed 8639(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 220us total 26.477ms
W/ResourcesManager(  948): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     (  437): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 142us total 18.193ms
I/art     (  437): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 158KB/4MB, paused 148us total 17.624ms
I/art     (  948): Explicit concurrent mark sweep GC freed 13596(1178KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 16MB/24MB, paused 1.860ms total 213.440ms
I/art     (  948): WaitForGcToComplete blocked for 211.873ms for cause Explicit
W/PackageManager(  948): Unable to load service info ResolveInfo{2979585a com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  948): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  948): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  948): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  948): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  948): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  948): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  948): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  948): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  948): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  948): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  948): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  948): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
W/ContextImpl( 6178): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
D/StatusBarManagerService(  948): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
D/StatusBarManagerService(  948): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  948): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  948): hiding MENU key
D/JobSchedulerService(  948): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  948): removeObsoleteFile: deleting file=8_task.xml
D/FindExtension( 1497): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1497): Defer allocateBuffers to drawing time
I/art     (  948): Explicit concurrent mark sweep GC freed 5822(366KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 6.964ms total 175.645ms
W/InputMethodManagerService(  948): Got RemoteException sending setActive(false) notification to pid 5861 uid 10366
D/StatusBarManagerService(  948): swetImeWindowStatus vis=0 backDisposition=0
I/PhoneStatusBar( 1221): setImeWindowStatus(false,false)
W/asset   (  948): Copying FileAsset 0x55c3e25040 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  948): Killing 5570:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=5570
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
I/ActivityManager(  948): Recipient 5570
E/NetworkScheduler.SchedulerReceiver( 1840): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1840): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  948): acquireWL(12d3d9c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1840 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  948): releaseWL(12d3d9c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
D/PackageBroadcastService( 4204): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4204): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/AccountUtils( 4204): Clearing selected account for com.test.thalitest
D/ChimeraModuleLdr( 4204): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4204): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4204): Module APK com.google.android.play.games already loaded
I/ActivityManager(  948): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6211 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
I/LocationSettingsChecker( 4204): Removing dialog suppression flag for package com.test.thalitest
D/GOOGLEHELP_CompatibleDatabase( 4204): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4204): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4204): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4204): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4204): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4204): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4204): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  948): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6235 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/GOOGLEHELP_CompatibleDatabase( 4204): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4204): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4204): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4204): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4204): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4204): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/PMS     (  948): acquireWL(74d6379): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4204 10024 null
I/ConfigService( 1840): onCreate
D/PMS     (  948): releaseWL(74d6379): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
I/ConfigFetchService( 4204): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
W/BaseAppContext( 4204): Using Auth Proxy for data requests.
W/ResourcesManager( 6235): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6235): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BaseAppContext( 4204): Using Auth Proxy for data requests.
I/PeopleContactsSync( 4204): CP2 sync disabled
D/PMS     (  948): acquireWL(c072117): PARTIAL_WAKE_LOCK  Icing 0x1 4204 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  948):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4204, uid=10024, userID:0
I/Icing   ( 4204): doRemovePackageData com.test.thalitest
D/PMS     (  948): releaseWL(c072117): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
I/MultiDex( 6235): VM with version 2.1.0 has multidex support
I/MultiDex( 6235): install
I/MultiDex( 6235): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6235): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 6235): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6235): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14366dc7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6235): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 6235): Failed to open lock file
W/NativeLibraryUtils( 6235): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6235): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6235): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6235): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6235): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6235): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6235): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6235): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6235): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6235): 	... 3 more
W/DriveInitializer( 4204): Awaiting to be initialized
W/DriveInitializer( 4204): Background init thread started
E/SQLiteLog( 4204): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/SQLiteDBG( 4204): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55c3a68280
E/DocListDatabase( 4204): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 4204): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4204): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4204): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4204): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4204): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4204): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4204): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4204): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4204): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 4204): Background init thread ended
E/AndroidRuntime( 4204): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4204): Process: com.google.android.gms, PID: 4204
E/AndroidRuntime( 4204): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4204): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4204): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4204): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4204): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4204): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4204): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4204): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4204): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteLog( 4204): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4204): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55c3a68280
E/DriveAsyncService( 4204): disk I/O error (code 3850)
E/DriveAsyncService( 4204): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4204): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4204): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4204): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4204): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4204): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4204): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4204): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4204): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4204): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4204): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4204): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4204): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4204): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4204): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager(  948): App crashed! Process: com.google.android.gms
D/Process ( 4204): killProcess, pid=4204
D/Process ( 4204): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  948): Can't write: system_app_crash
E/DropBoxManagerService(  948): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  948): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  948): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  948): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  948): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  948): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  948): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  948): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  948): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  948): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  948): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  948): 	... 5 more
I/GAv4    ( 6211): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6211):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6211):   adb logcat -s GAv4
W/GAv4    ( 6211): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6211): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6211): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 6211): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteDatabase( 6211): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6211): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6211): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6211): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6211): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6211): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6211): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6211): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6211): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6211): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6211): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6211): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6211): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 6211): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6211): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6211): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6211): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6211): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6211): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6211): 	at aen.run(PG:536)
I/ActivityManager(  948): Recipient 4204
I/ActivityManager(  948): Process com.google.android.gms (pid 4204) has died
W/ActivityManager(  948): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
I/ConfigService( 1840): onDestroy
W/ActivityManager(  948): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  948): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  948): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=6277 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/VoldConnector(  948): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  383): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
I/ActivityManager(  948): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6302 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 6211): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6211): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 6211): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  948): Killing 5707:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
D/Process (  948): killProcessQuiet, pid=5707
D/Process (  948): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.trimApplications:19127 
E/SQLiteDatabase( 6211): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6211): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6211): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6211): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6211): 	at aej.c(PG:139)
E/SQLiteDatabase( 6211): 	at aej.b(PG:398)
E/SQLiteDatabase( 6211): 	at agf.f(PG:417)
E/SQLiteDatabase( 6211): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6211): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6211): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 6211): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6211): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6211): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6211): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6211): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6211): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6211): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6211): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6211): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6211): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6211): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6211): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6211): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6211): 	at java.lang.Thread.run(Thread.java:818)
I/art     (  439): Explicit concurrent mark sweep GC freed 8676(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 462us total 31.967ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 300us total 21.709ms
I/art     (  439): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 296us total 26.485ms
I/ActivityManager(  948): Recipient 5707
W/ResourcesManager( 6277): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6277): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6302): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 6211): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/MultiDex( 6277): VM with version 2.1.0 has multidex support
I/MultiDex( 6277): install
I/MultiDex( 6277): VM has multidex support, MultiDex support library is disabled.
E/SQLiteDatabase( 6277): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 6277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6277): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 6277): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 6277): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 6277): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6277): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6277): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6277): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6277): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6277): 	at java.lang.Thread.run(Thread.java:818)
W/System  ( 6211): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6211): Installed default security provider GmsCore_OpenSSL
E/SQLiteDatabase( 6277): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 6277): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6277): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6277): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6277): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6277): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 6277): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 6277): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 6277): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6277): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6277): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6277): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6277): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6277): 	at java.lang.Thread.run(Thread.java:818)
V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Prism.ItemManager( 1497): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1497): loadItems() com.htc.launcher.pageview.WidgetManager@161d9e0f +
I/Prism.WidgetManager( 1497): onLoadItems() +
W/ResourcesManager( 1497): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/art     ( 1840): Explicit concurrent mark sweep GC freed 21766(1258KB) AllocSpace objects, 11(796KB) LOS objects, 49% free, 4MB/8MB, paused 739us total 44.793ms
E/SharedPreferencesImpl( 6211): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
V/JNIHelp ( 6277): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 6277): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6277): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1aee5ba7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6277): Installed default security provider GmsCore_OpenSSL
D/PMS     (  948): acquireWL(1e2166d2): PARTIAL_WAKE_LOCK  AsyncService 0x1 6302 10167 null
W/NativeLibraryUtils( 6277): Failed to open lock file
W/NativeLibraryUtils( 6277): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6277): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 6277): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 6277): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 6277): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6277): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 6277): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 6277): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 6277): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 6277): 	... 3 more
D/PMS     (  948): releaseWL(1e2166d2): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  948): acquireWL(3c4d96a0): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6302 10167 null

```
