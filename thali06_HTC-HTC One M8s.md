#### Test 51986340a77003b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
D/PMS     (  944): acquireWL(1c6c32a9): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024}
V/AlarmManager(  944): sending alarm PendingIntent{2937402e: PendingIntentRecord{35b8c74b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=121853, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{33a887cf: PendingIntentRecord{313d155c android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1448876898351, Int=0
D/PMS     (  944): acquireWL(34ac5065): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1883 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): acquireWL(fb313a): PARTIAL_WAKE_LOCK  *backup* 0x1 944 1000 null
--------- beginning of main
D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
W/BackupManagerService(  944): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
D/libc    ( 1883): [NET] android_getaddrinfofornet-, err=8
E/BackupManagerService(  944): Requested init for com.google.android.gms.backup.BackupTransportService but not found
D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/PMS     (  944): releaseWL(fb313a): PARTIAL_WAKE_LOCK  *backup* 0x1 null
D/libc    ( 1883): [NET] android_getaddrinfofornet-, pass to proxy
D/PMS     (  944): releaseWL(1c6c32a9): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
D/libc    ( 1883): [NET] android_getaddrinfo_proxy+
D/libc    ( 1883): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1883): [NET] android_getaddrinfo_proxy-, NODATA
D/PMS     (  944): releaseWL(34ac5065): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/Process (  944): killProcessQuiet, pid=5301
I/ActivityManager(  944): Killing 5301:com.htc.musicenhancer/u0a49 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
I/ActivityManager(  944): Recipient 5301
E/cutils-trace( 6146): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6146): ====startRecUseTime====
D/htc.customization.log.level( 6146):  is 
W/CustomizationLogLevel( 6146): Level value is invalid, use default level 2
D/CustomizationManager( 6146):  Read ACC file spent 0.035 (s)
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6146): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6146): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6146): Parsing tag category name = system
I/CustomizationCIDLoader( 6146): Parsing tag category name = application
I/CustomizationCIDLoader( 6146): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6146): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6146): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6146): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6146): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6146): add string-array item, value = 42507
I/CustomizationCIDLoader( 6146): add string-array item, value = 21902
I/CustomizationCIDLoader( 6146): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6146): add string-array item, value = 23420
I/CustomizationCIDLoader( 6146): add string-array item, value = 22299
I/CustomizationCIDLoader( 6146): add string-array item, value = 24002
I/CustomizationCIDLoader( 6146): add string-array item, value = 23210
I/CustomizationCIDLoader( 6146): add string-array item, value = 23205
I/CustomizationCIDLoader( 6146): add string-array item, value = 23806
I/CustomizationCIDLoader( 6146): add string-array item, value = 23430
I/CustomizationCIDLoader( 6146): add string-array item, value = 23408
I/CustomizationCIDLoader( 6146): add string-array item, value = 27205
I/CustomizationCIDLoader( 6146): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6146): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6146):  Read CID file spent 0.071 (s)
D/CustomizationManager( 6146):  All configurations done spent 0.071 (s)
I/ActivityManager(  944): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6146 on display 0
D/PMS     (  944): acquireHCC(cfd1eb): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 944 1000 null
D/PMS     (  944): acquireHCC(31342b48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 944 1000 null
W/asset   (  944): Copying FileAsset 0x559724c180 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  944): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6164 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  944): Display changed displayId=0
D/DotMatrix( 1306): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1306): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 6164): Copying FileAsset 0xabf480d0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1523): [trimMemory] 20
I/WebViewFactory( 6164): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 6164): Time to load native libraries: 10 ms (timestamps 5922-5932),
,I/LibraryLoader( 6164): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6164): Binding Chromium to main looper Looper (main, tid 1) {1fe3353e},
I/LibraryLoader( 6164): Expected native library version number "",actual native library version number ""
,I/chromium( 6164): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6164): Initializing chromium process, singleProcess=true,
,W/art     ( 6164): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6164): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6164): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 6164): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6164): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6164): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6164): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6164): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6164): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6164): Local Branch: 
I/Adreno-EGL( 6164): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6164): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6164):                  d74aa161a12b9c6fc6332151
,W/System.err(  944): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c1e8d8c:true
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): ,	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapter( 6164): 257517386: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 6164): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6164): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6164): CordovaWebView is running on device made by: HTC
,W/art     ( 6164): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6164): Attempt to remove local handle scope entry from IRT, ignoring
,W/HtcSystemUPManager(  944): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch,
W/chromium( 6164): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  944): setSystemUiVisibility(0xc0000000),
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
D/StatusBarManagerService(  944): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
,D/FindExtension( 6164): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 6164): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@acb0708, mServedView=org.apache.cordova.engine.SystemWebView{2cc69ea1 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@266cc8c6,
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
,I/InputMethodManagerService(  944): Disable input method client, pid=1523
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 6164): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  944): Displayed com.test.thalitest/.MainActivity: +615ms (total +660ms)
,W/BindingManager( 6164): Cannot call determinedVisibility() - never saw a connection for the pid: 6164,
,D/JsMessageQueue( 6164): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 6164): JniHelper::setJavaVM(0xaaddb8f8), pthread_self() = -1408110680
D/JX-Cordova( 6164): jxcore cordova android initializing
,W/jxcore-log( 6164): Initializing JXcore engine,
W/jxcore-log( 6164): JXcore engine is ready
,W/jxcore-log( 6164): Starting JXcore engine
,W/jxcore-log( 6164): Platform android,
W/jxcore-log( 6164): 
W/jxcore-log( 6164): Process ARCH arm
W/jxcore-log( 6164): 
,D/PMS     (  944): releaseHCC(cfd1eb): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
D/PMS     (  944): releaseHCC(31342b48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,I/jxcore-log( 6164): JXcore Cordova bridge is ready!,
I/jxcore-log( 6164): 
W/jxcore-log( 6164): JXcore engine is started
I/Choreographer( 6164): Skipped 94 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 6164): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6164): Toggling radios to true,
I/jxcore-log( 6164): 
,D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  944): checking for enable restriction...
D/BluetoothManagerService(  944): checkBTEasState, ret=true
I/BluetoothManagerService(  944): isBluetoothRestricted(): false
D/BluetoothManagerService(  944): enable(): region ID = 6
D/BluetoothManagerService(  944): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  944): MONITOR_LOG
W/Settings:Agent(  944): name: bluetooth_on
W/Settings:Agent(  944): value: 1
W/Settings:Agent(  944): >> traceCallingStack()
W/Settings:Agent(  944): Process.myPid(): 944
W/Settings:Agent(  944): Process.myTid(): 1616,
W/Settings:Agent(  944): Process.myUid(): 1000
W/Settings:Agent(  944): 
W/Settings:Agent(  944): 
W/System.err(  944): java.lang.Throwable: stack dump
,W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  944): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  944): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  944): 	,at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  944): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  944): 
,W/Settings:Agent(  944): << traceCallingStack(): 4(ms)
,D/BluetoothManagerService(  944): Message: MESSAGE_ENABLE
,D/BluetoothManagerService(  944): MESSAGE_ENABLE: mBluetooth = null
,E/WifiTrafficPoller(  944): ADD_CLIENT: 7,
D/WifiService(  944): New client listening to asynchronous messages
D/WifiManager( 6164): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
D/WifiService(  944): setWifiEnabled: true pid=6164, uid=10366
E/WifiService(  944): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  944): isSprintWifiRestricted(): false
,I/WifiService(  944): isMdmWifiRestricted(): false
,W/Settings:Agent(  944): MONITOR_LOG
W/Settings:Agent(  944): name: wifi_on
W/Settings:Agent(  944): value: 2
W/Settings:Agent(  944): >> traceCallingStack()
W/Settings:Agent(  944): Process.myPid(): 944
W/Settings:Agent(  944): Process.myTid(): 1528
W/Settings:Agent(  944): Process.myUid(): 1000
W/Settings:Agent(  944): 
W/Settings:Agent(  944): 
W/System.err(  944): java.lang.Throwable: stack dump
,I/ActivityManager(  944): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6218 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a
,W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
,W/System.err(  944): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  944): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  944): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  944): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  944): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  944): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  944): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
W/System.err(  944): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  944): 
W/Settings:Agent(  944): << traceCallingStack(): 17(ms)
,D/WifiController(  944): handleMessage: E msg.what=155656
D/WifiController(  944): processMsg: ApStaDisabledState
D/WifiController(  944): transitionTo: destState=DeviceActiveState,
D/WifiController(  944): handleMessage: new destination call exit/enter
D/PMS     (  944): acquireWL(6713c54): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 944 1000 null
D/WifiController(  944): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
,D/WifiController(  944): invokeExitMethods: ApStaDisabledState
D/WifiController(  944): moveTempStackToStateStack: i=1,j=1
D/WifiController(  944): moveTempStackToStateStack: i=0,j=2
D/WifiController(  944): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiController(  944): invokeEnterMethods: StaEnabledState
D/WifiController(  944): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  944): setting operational mode to 1
E/WifiStateMachine(  944): handleMessage: E msg.what=131083
E/WifiStateMachine(  944): processMsg: InitialState
D/WifiController(  944): handleMessage: X
D/WifiManager( 6164): disconnect: Base Package Name=com.test.thalitest, uid=10366
E/WifiStateMachine(  944):  InitialState CMD_START_SUPPLICANT 0 0
I/art     (  458): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 321us total 27.096ms
D/WifiManager( 6164): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 6164): Radios toggled
I/jxcore-log( 6164): 
,I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 297us total 24.488ms,
,I/art     (  458): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 330us total 21.219ms,
,W/ResourcesManager( 6218): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 6218): Adding HeadsetService
,D/AdapterServiceConfig( 6218): Adding A2dpService
D/AdapterServiceConfig( 6218): Adding HidService
,D/AdapterServiceConfig( 6218): Adding HealthService
D/AdapterServiceConfig( 6218): Adding PanService
,D/AdapterServiceConfig( 6218): Adding GattService
,W/linker  ( 6218): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  944): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12657f43:true
,W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55),
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 6218): make
,I/BluetoothAdapterState( 6218): Entering OffState,
,E/bt_osi_config( 6218): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,D/BluetoothAdapterProperties( 6218): Address is:90:E7:C4:F6:69:77,
D/BluetoothManagerService(  944): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  944): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/BluetoothManagerService(  944): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  944): Calling onBluetoothServiceUp callbacks,
D/BluetoothManagerService(  944): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/Tethering(  944): interfaceAdded wlan0
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 1488): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@db7e9f0
D/BluetoothAdapter( 1488): onBluetoothServiceUp done
D/BluetoothAdapter( 1222): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2d90b06c
D/BluetoothAdapter( 1222): onBluetoothServiceUp done
,D/BluetoothAdapter( 2375): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@181c86f2
D/BluetoothAdapter( 2375): onBluetoothServiceUp done
D/BluetoothAdapter(  944): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@56510d8
,D/BluetoothAdapter(  944): onBluetoothServiceUp done
D/Tethering(  944): interfaceLinkStateChanged wlan0, false
D/Tethering(  944): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 6218): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@33c5b6bb
D/BluetoothAdapter( 6218): onBluetoothServiceUp done
D/Tethering(  944): interfaceAdded p2p0
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 1797): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@11c9157b
D/Tethering(  944): p2p0 is not a tetherable iface, ignoring
D/Tethering(  944): interfaceLinkStateChanged p2p0, false
D/Tethering(  944): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapter( 1797): onBluetoothServiceUp done
,D/BluetoothAdapter( 6164): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@168579f0,
D/PMS     (  944): releaseWL(6713c54): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
D/BluetoothAdapter( 6164): onBluetoothServiceUp done
D/BluetoothAdapter( 1470): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3537ba76
D/BluetoothAdapter( 1470): onBluetoothServiceUp done
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, SUCCESS
D/BluetoothAdapter( 3703): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@3c38d525
D/BluetoothAdapter( 3703): onBluetoothServiceUp done
D/BluetoothManagerService(  944): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6218): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
V/Tethering(  944): TetherInterfaceSM: wlan0: enter InitialState
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  944): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothAdapterProperties( 6218): Setting state to 11
,I/BluetoothAdapterState( 6218): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  944): +onBluetoothStateChange prev=10 new=11
D/PMS     (  944): acquireWL(2f21ef16): PARTIAL_WAKE_LOCK  NetworkStats 0x1 944 1000 null
D/Tethering(  944): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  944): TetherInterfaceSM: wlan0: exit InitialState
V/Tethering(  944): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  944): sendTetherStateChangedBroadcast 0, 0, 0
D/BluetoothManagerService(  944): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  944): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  944): Bluetooth State Change Intent: 10 -> 11
D/PMS     (  944): releaseWL(2f21ef16): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
V/NetworkPolicy(  944): updateNetworkEnabledLocked()
D/BluetoothBondStateMachine( 6218): make
V/NetworkPolicy(  944): updateNotificationsLocked()
D/PMS     (  944): acquireWL(1bc5e6a2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 944 1000 null
E/WifiStateMachine(  944): setWifiState: enabling
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
E/WifiStateMachine(  944): Supplicant start successful
D/WifiMonitor(  944): startMonitoring(wlan0) with mConnected = false
D/PMS     (  944): releaseWL(1bc5e6a2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiMonitor(  944): connecting to supplicant
V/NetworkPolicy(  944): updateNetworkEnabledLocked()
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
V/NetworkPolicy(  944): updateNotificationsLocked()
,V/BluetoothPbapReceiver( 6218): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService( 6218): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 6218): checkA2dpState: returning
V/BluetoothPbapReceiver( 6218): ***********state = 11
D/BluetoothAdapterService( 6218): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6218): checkHfpState: returning
I/BluetoothBondStateMachine( 6218): StableState(): Entering Off State
D/TetherSettings( 5655): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5655): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5655): Cust_ConnectToPC   : Modem_Link>false
D/UsbDeviceManager(  944): [USBNET] bCheckSuppFunc: cdc_network
D/        ( 5655): Cust_ConnectToPC   : spcsc>false
D/        ( 5655): Cust_ConnectToPC   : IPT>true
D/        ( 5655): Cust_ConnectToPC   : Singel_USB>false
D/UsbnetService(  944): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/UsbDeviceManager(  944): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/UsbnetService(  944): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
,W/Settings( 5655): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/NGFService( 3703): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
E/SmartNS_Utility( 5655): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 5655): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5655): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
,I/BluetoothAdapterState( 6218): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothHeadset(  944): Proxy object connected
,D/BluetoothHeadset( 1470): Proxy object connected
D/HeadsetService( 6218): Received start request. Starting profile...
,D/HeadsetStateMachine( 6218): Version 1.5
D/HeadsetStateMachine( 6218): make
,W/ContextImpl( 5655): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/SmartNS_Utility( 5655): setISNotification
,D/HeadsetStateMachine( 6218): max_hf_connections = 2
,D/SmartNS_Utility( 5655): usb_cable_connect = 1,
D/SmartNS_Utility( 5655): usb_denied = 0
I/SmartNS_PSService( 5655): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothPhoneService( 1470): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1470): Proxy object connected
,D/BluetoothAdapter(  944): 661122439: getState(). Returning 11
,D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/BluetoothHeadset( 1222): Proxy object connected
,D/HeadsetPhoneState( 6218): listenForPhoneState..for service and signal 
,D/BluetoothHeadset( 1470): Proxy object connected
,I/ActionCombine( 5655): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal],
,D/HeadsetDualPhoneStateListener_SLOT1( 6218): listen phone state by slot:SLOT1  id:-1,
,D/HeadsetDualPhoneStateListener_SLOT2( 6218): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6218): Enter Disconnected: -2, size: 0
,D/BluetoothAdapter( 1470): 411995364: getState(). Returning 11
D/HeadsetDualPhoneStateListener_SLOT1( 6218): listen phone state by slot:SLOT1  id:-1
,D/SmartNS_Utility( 5655): usb_cable_connect = 1
D/BluetoothAdapterService( 6218): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39eabf9f
D/SmartNS_Utility( 5655): usb_denied = 0
I/SmartNS_PSService( 5655): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetDualPhoneStateListener_SLOT2( 6218): listen phone state by slot:SLOT2  id:-100
I/HeadsetStateMachine( 6218): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6218): BTHF: set_current_device
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 6251): wpa_supplicant v2.3-devel-5.0.2
D/BluetoothA2dp(  944): Proxy object connected
D/A2dpService( 6218): Received start request. Starting profile...
D/SmartNS_NSReceiver( 5655): Tethered state change:false isNSOpening:false
V/Avrcp   ( 6218): make
,D/BluetoothAdapter(  944): 661122439: getState(). Returning 11
,D/wpa_supplicant( 6251): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/QuickSettingMiniLite( 1222): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@1be43635
D/wpa_supplicant( 6251): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 6251): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6251): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6251): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6251): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6251): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6251): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6251): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
,E/RemoteController( 6218): Cannot set synchronization mode on an unregistered RemoteController,
D/A2dpStateMachine( 6218): make
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
D/bt-btif ( 6218): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
,D/wpa_supplicant( 6251): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6251): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6251): update_config=1
D/wpa_supplicant( 6251): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6251): device_name='Android_608e'
D/wpa_supplicant( 6251): manufacturer='HTC'
D/wpa_supplicant( 6251): model_name='HTC_PHONE'
D/wpa_supplicant( 6251): model_number='1234'
,D/wpa_supplicant( 6251): config_methods='virtual_push_button physical_display keypad'
I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
D/wpa_supplicant( 6251): p2p_oper_reg_class=126
D/wpa_supplicant( 6251): p2p_oper_channel=149
D/wpa_supplicant( 6251): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6251): persistent_reconnect=1
D/wpa_supplicant( 6251): key_mgmt_offload=1
D/A2dpService( 6218): setA2dpService(): set to: null
D/BluetoothAdapterService( 6218): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39eabf9f
D/A2dpStateMachine( 6218): Enter Disconnected: -2
I/wpa_supplicant( 6251): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6251): nl80211: RFKILL status not available
D/wpa_supplicant( 6251): nl80211: Using driver-based roaming
D/wpa_supplicant( 6251): nl80211: TDLS supported
D/wpa_supplicant( 6251): nl80211: TDLS external setup
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6251): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
I/ActivityManager(  944): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6258 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment ,offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
I/RemoteViews( 1222): reapply : com.android.settings 0 36
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
,D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6251): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6251): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6251): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6251): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6251): nl80211: Subscribe to mgmt frames with non-AP handle 0x55ba6f5fd0
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=0104
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=040a
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=040b
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=040c
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=040d
D/w,pa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=090a
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=090b
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=090c
W/ContextImpl( 5655): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=090d
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=0409506f9a09
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=7f506f9a09
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=0801
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=040e
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=06
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=0a07
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=0a11
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba6f5fd0 match=0a1a
D/wpa_supplicant( 6251): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6251): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6251): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6251): htc_wext_command_init +
E/wpa_supplicant( 6251): htc_wext_command_init: ifname=p2p0, ignore
D/Tethering(  944): interfaceLinkStateChanged p2p0, false
D/Tethering(  944): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6251): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  944): interfaceLinkStateChanged p2p0, false
D/Tethering(  944): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/HidService( 6218): Received start request. Starting profile...
D/BluetoothAdapterService( 6218): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39eabf9f
D/TetherSettings( 5655): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5655): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5655): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5655): Cust_ConnectToPC   : spcsc>false
D/        ( 5655): Cust_ConnectToPC   : IPT>true
D/        ( 5655): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5655): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5655): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5655): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5655): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/HealthService( 6218): Received start request. Starting profile...
I/SmartNS_Utility( 5655): setISNotification
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/SmartNS_Utility( 5655): usb_cable_connect = 1
D/SmartNS_Utility( 5655): usb_denied = 0
I/SmartNS_PSService( 5655): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/BluetoothAdapterService( 6218): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39eabf9f
D/PanService( 6218): Received start request. Starting profile...
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/SmartNS_Utility( 5655): usb_cable_connect = 1
D/SmartNS_Utility( 5655): usb_denied = 0
I/SmartNS_PSService( 5655): usb notificaiton:true
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/PanService( 6218): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 6218): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39eabf9f
D/SmartNS_NSReceiver( 5655): Tethered state change:false isNSOpening:false
D/BtGatt.DebugUtils( 6218): handleDebugAction() action=null
D/BtGatt.GattService( 6218): Received start request. Starting profile...
D/BtGatt.GattService( 6218): start()
D/BtGatt.AdvertiseManager( 6218): advertise manager created
I/RemoteViews( 1222): reapply : com.android.settings 1 36
,I/ActivityManager(  944): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6286 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/BluetoothAdapterService( 6218): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39eabf9f
I/RemoteViews( 1222): reapply : com.android.settings 1 36
D/BluetoothAdapter( 1470): 411995364: getState(). Returning 11
W/BluetoothHeadset( 1470): Proxy not attached to service
D/BluetoothHeadset( 1470): java.lang.Throwable
D/BluetoothHeadset( 1470): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1470): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1470): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1470): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1470): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1470): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1470): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1470): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1470): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1470): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/BluetoothAdapter( 1222): 105356207: getState(). Returning 11
I/QuickSettingMiniLite( 1222): updateLiteState:no connect device!
I/HeadsetPhoneState( 6218): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 6218): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 6218): Disconnected process message: 11, size: 0
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6218): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6218): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 6218): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bt-btu  ( 6218): btu_task pending for preload complete event
E/bt_vendor( 6218): get_bt_soc_type: Failed to get soc type
,D/HtcBtWidget_BTWidgetProvider( 6258): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 6258): updateWidget(context) for widget: 
I/ActivityManager(  944): Killing 5900:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  944): killProcessQuiet, pid=5900
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,I/qcom-bluetooth( 6311): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,I/wpa_supplicant( 6251): wapi_supplicant_init: Init WAI packet p2p0,
D/wpa_supplicant( 6251):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6251):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6251):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6251): nl80211: Flush PMKIDs
D/wpa_supplicant( 6251): p2p0: State: DISCONNECTED -> INACTIVE
,I/qcom-bluetooth( 6317): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd 
,I/qcom-bluetooth( 6318): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/ActivityManager(  944): Recipient 5900
I/qcom-bluetooth( 6320): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6321): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 6322): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6323): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,D/BluetoothMasReceiver( 6218): Bluetooth STATE CHANGED to 11
V/BluetoothSapReceiver( 6218): SapReceiver onReceive 
,V/BluetoothSapReceiver( 6218): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6218):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6218): startService = false
,D/AuthorizationBluetoothService( 1883): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HtcWiFiWidget_WiFiWidgetProvider( 6286): onWiFiStateChanged() for widget: 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6286): updateWidget(context) for widget: 
,D/Process (  944): killProcessQuiet, pid=5922
I/ActivityManager(  944): Killing 5922:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
D/wpa_supplicant( 6251): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 6251): TDLS: Driver uses external link setup
D/wpa_supplicant( 6251): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6251): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6251): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6251): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6251): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6251): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6251): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6251): Using existing control interface directory.
D/wpa_supplicant( 6251): P2P: Add operating class 81
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
,D/wpa_supplicant( 6251): P2P: Own listen channel: 81:11
D/wpa_supplicant( 6251): P2P: Configured operating channel: 126:149
,D/wpa_supplicant( 6251): P2P: initialized
,D/wpa_supplicant( 6251): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6251): P2P: cli_channels:
D/wpa_supplicant( 6251): p2p0: Added interface p2p0
D/wpa_supplicant( 6251): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6251): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6251): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
,D/wpa_supplicant( 6251): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6251): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6251): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
,D/wpa_supplicant( 6251): ctrl_interface='/data/misc/wifi/sockets'
,D/wpa_supplicant( 6251): disable_scan_offload=1
D/wpa_supplicant( 6251): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6251): update_config=1
D/wpa_supplicant( 6251): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6251): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6251): manufacturer='HTC'
D/wpa_supplicant( 6251): model_name='HTC One M8s'
D/wpa_supplicant( 6251): model_number='HTC One M8s'
D/wpa_supplicant( 6251): config_methods='physical_display virtual_push_button'
,D/wpa_supplicant( 6251): hs20=1
D/wpa_supplicant( 6251): interworking=1
D/wpa_supplicant( 6251): external_sim=1
D/wpa_supplicant( 6251): key_mgmt_offload=1
,D/wpa_supplicant( 6251): Priority group 192,
D/wpa_supplicant( 6251):    id=0 ssid='NG700'
I/wpa_supplicant( 6251): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6251): nl80211: RFKILL status not available
D/wpa_supplicant( 6251): nl80211: Using driver-based roaming
D/wpa_supplicant( 6251): nl80211: TDLS supported
D/wpa_supplicant( 6251): nl80211: TDLS external setup
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:1
,D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6251): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6251): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6251): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6251): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6251): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6251): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6251): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6251): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6251): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6251): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6251): nl80211: Subscribe to mgmt frames with non-AP handle 0x55ba715100
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=0104
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=040a
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=040b
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=040c
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=040d
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=090a
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=090b
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=090c
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=090d
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=0409506f9a09
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=7f506f9a09
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=0801
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=040e
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=06
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=0a07
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=0a11
D/wpa_supplicant( 6251): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55ba715100 match=0a1a
D/wpa_supplicant( 6251): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6251): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6251): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6251): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6251): htc_wext_command_init +
I/wpa_supplicant( 6251): htc_wext_command_init -
I/wpa_supplicant( 6251): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6251): Don't set 00 to countryID.conf
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6251): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6251): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6251): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6251): P2P: Add operating class 81
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6251): P2P: Update channel list
D/wpa_supplicant( 6251): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6251): P2P: cli_channels:
D/wpa_supplicant( 6251): p2p0: Updating hw mode
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6251): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6251): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6251): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  944): interfaceLinkStateChanged wlan0, false
D/Tethering(  944): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
,I/ActivityManager(  944): Recipient 5922
,I/qcom-bluetooth( 6326): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 ,
,I/qcom-bluetooth( 6327): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/wpa_supplicant( 6251): wapi_supplicant_init: Init WAI packet wlan0
D/wpa_supplicant( 6251):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT ,
D/wpa_supplicant( 6251):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6251):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6251): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6251): nl80211: Flush PMKIDs
,I/bt-btu  ( 6218): btu_task received preload complete event,
D/PMS     (  944): acquireWL(1039db38): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6218 1002 null
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x1487
D/bt-btm  ( 6218): btm_acl_device_down
D/bt-btm  ( 6218): btm_acl_reset_paging
D/bt-btm  ( 6218): btm_acl_set_discing
,D/wpa_supplicant( 6251): TDLS: TDLS operation supported by driver,
D/wpa_supplicant( 6251): TDLS: Driver uses external link setup
D/wpa_supplicant( 6251): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6251): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6251): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6251): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6251): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6251): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6251): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6251): Using existing control interface directory.
,I/wpa_supplicant( 6251): set country (DE) from /data/misc/wifi/countryID.conf,
I/wpa_supplicant( 6251): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6251): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6251): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6251): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6251): P2P: Add operating class 81
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6251): P2P: Add operating class 115
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6251): P2P: Add operating class 116
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6251): P2P: Add operating class 117
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6251): P2P: Update channel list
D/wpa_supplicant( 6251): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6251): P2P: cli_channels:
D/wpa_supplicant( 6251): p2p0: Updating hw mode
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6251): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
,D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6251): Auto country group 1: ch36
D/wpa_supplicant( 6251): wlan0: Added interface wlan0
D/wpa_supplicant( 6251): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6251): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6251): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6251): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 6251): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/wpa_supplicant( 6251): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_944-2\x00
D/wpa_supplicant( 6251): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6251): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6251): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6251): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6251): nl80211: Regulatory domain change
D/wpa_supplicant( 6251):  * initiator=1
D/wpa_supplicant( 6251):  * type=0
D/wpa_supplicant( 6251):  * alpha2=DE
D/wpa_supplicant( 6251): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6251): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
I/bt-btm  ( 6218): btm_reset_complete
E/WifiStateMachine(  944): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  944): handleMessage: new destination call exit/enter
E/WifiStateMachine(  944): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  944): invokeExitMethods: InitialState
E/WifiStateMachine(  944): moveTempStackToStateStack: i=0,j=1
I/bt-btm  ( 6218): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
E/WifiStateMachine(  944): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  944): invokeEnterMethods: SupplicantStartingState
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131144
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6251): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6251): P2P: Add operating class 81
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6251): P2P: Add operating class 115
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6251): P2P: Add operating class 116
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6251): P2P: Add operating class 117
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6251): P2P: Update channel list
E/WifiStateMachine(  944):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
D/wpa_supplicant( 6251): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6251): P2P: cli_channels:
D/wpa_supplicant( 6251): p2p0: Updating hw mode
E/WifiStateMachine(  944): deferMessage: msg=131144
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131085
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
E/WifiStateMachine(  944):  SupplicantStartingState CMD_START_DRIVER 0 0
E/WifiStateMachine(  944): deferMessage: msg=131085
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131149
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
,D/bt-btm  ( 6218): Start reading local supported commands
E/WifiStateMachine(  944):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6251): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
,D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  944):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  944): setSuspendOptimizations: 2 true
E/WifiStateMachine(  944): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  944): handleMessage: X
,E/WifiStateMachine(  944): handleMessage: E msg.what=131145
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
D/bt-btm  ( 6218): btm_read_local_supported_cmds_complete status (0x00)
E/WifiStateMachine(  944):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  944): handleMessage: X
,E/WifiStateMachine(  944): handleMessage: E msg.what=131146
D/bt-btm  ( 6218): BTM reads next extended features page (1)
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
E/WifiStateMachine(  944):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
D/bt-btm  ( 6218): BTM reads next extended features page (2)
E/WifiStateMachine(  944):  DefaultState CMD_RECONNECT 0 0
,E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131101
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
D/bt-btm  ( 6218): BTM reached last extended features page (2)
D/bt-btm  ( 6218): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
,E/WifiStateMachine(  944):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
D/bt-btm  ( 6218): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
E/WifiStateMachine(  944):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  944): Default got CMD_TETHER_STATE_CHANGE
,E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131101
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
D/bt-btm  ( 6218): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
,I/bt-btm  ( 6218): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
E/WifiStateMachine(  944):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
D/bt-btm  ( 6218): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
E/WifiStateMachine(  944):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  944): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  944): handleMessage: X
I/bt-btm  ( 6218): btm_vendor_capability_vsc_cmpl_cback: status=0
E/WifiStateMachine(  944): handleMessage: E msg.what=147457
E/WifiStateMachine(  944): processMsg: SupplicantStartingState
E/WifiStateMachine(  944):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
,E/WifiStateMachine(  944): Supplicant connection established
D/bt-btm  ( 6218): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
,D/wpa_supplicant( 6251): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6251): set wifi ON
E/WifiStateMachine(  944): setWifiState: enabled
D/WIFI_ICON( 1222): updateWifiState: WIFI_STATE_CHANGED enabled
,E/WifiStateMachine(  944): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/WifiStateMachine(  944):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6251): SET_SCREEN_ON:Off
I/wpa_supplicant( 6251): htc_wext_set_keepalive +
I/wpa_supplicant( 6251): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6251): getPrivFuncNum +	
,I/wpa_supplicant( 6251): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6251): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6251): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6251): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6251): htc_wext_set_keepalive gateway addr = 00000000
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
,I/wpa_supplicant( 6251): htc_wext_set_keepalive - ret = 0
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
I/WifiNative-HAL(  944): startHal
E/WifiMonitor(  944): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  944): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/bt-btm  ( 6218): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6218): btm_read_ble_wl_size 
D/bt-btm  ( 6218): btm_read_white_list_size_complete 
,D/bt-btm  ( 6218): btm_get_ble_buffer_size 
D/bt-btm  ( 6218): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6218): btm_read_ble_local_supported_states 
E/wifi    (  944): getStaticLongField sWifiHalHandle 0x7f79300300
I/WifiNative-HAL(  944): Could not start hal
E/WifiStateMachine(  944): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  944): backgroundScan enabled=true startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  944): handleScreenStateChanged Exit: false
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER MACADDR'
I/IntentController( 1222): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/bt-btm  ( 6218): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 6218): btm_read_ble_local_supported_features 
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6251): update_config=1
D/wpa_supplicant( 6251): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/WifiConfigStore(  944): Loading config and enabling all networks 
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6251): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6251): wpa_supplicant_ctrl_iface_list_networks: return size = 47
D/bt-btm  ( 6218): btm_read_ble_local_supported_features_complete 
,D/bt-btm  ( 6218): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6218): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6218): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6218): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6218): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
,D/bt-btm  ( 6218): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6218): BTM_SetInquiryMode
,I/bt-btm  ( 6218): BTM_SetPageScanType
I/bt-btm  ( 6218): BTM_SetInquiryScanType
D/bt-btm  ( 6218): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6218): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6218): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6218): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6218): BTM_BleLoadLocalKeys
,D/bt-btm  ( 6218): BTM_BleLoadLocalKeys
I/bt-btm  ( 6218): BTM_Sec: application registered
E/bt-btm  ( 6218): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf7734d5 
I/bt-btm  ( 6218): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6218): SMP_Register state=0
E/bt-btm  ( 6218): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf7734d5 
,I/bt-btm  ( 6218): BTM_Sec: application registered
D/bt-btm  ( 6218): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6218): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6218): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6218): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6218): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6218): BTM_RegBusyLevelNotif
,D/bt-btm  ( 6218): BTM_BleReadControllerFeatures
I/bt-btm  ( 6218): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6218): GATT_Register
D/bt-att  ( 6218): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6218): allocated gatt_if=3
I/bt-att  ( 6218): GATT_StartIf gatt_if=3
D/bt-att  ( 6218): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6218): gatt_find_the_connected_bda found=0 found_idx=16
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/HtcWiFiWidget_WiFiWidgetProvider( 6286): onWiFiStateChanged() for widget: 
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='priority'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
,D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6251): Do not allow key_data field to be exposed
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/HtcWiFiWidget_WiFiWidgetProvider( 6286): updateWidget(context) for widget: 
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
,D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiP2pService(  944): P2pDisabledState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/WifiP2pService(  944): DefaultState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
,D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
,D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='engine'
,W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6251): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6251): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
E/WifiConfigStore(  944): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6251): device_name='m8qlul_htc_europe'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6251): manufacturer='HTC'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET model_name HTC One M8s'
D/WifiP2pService(  944): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6251): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6251): model_name='HTC One M8s'
D/WIFI_ICON( 1222): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6251): model_number='HTC One M8s'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6251): config_methods='physical_display virtual_push_button'
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  944): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  944): handleMessage: new destination call exit/enter
E/WifiStateMachine(  944): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  944): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  944): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  944): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  944): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  944): invokeEnterMethods: SupplicantStartedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6251): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  944): Setting external_sim to 1
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6,251): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6251): external_sim=1
D/WifiStateMachine(  944): Setting OUI to DA-A1-19
I/WifiNative-HAL(  944): startHal
E/wifi    (  944): getStaticLongField sWifiHalHandle 0x7f79300360
W/Settings( 5474): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiNative-HAL(  944): Could not start hal
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6251): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  944): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  944): Driverstarted State enter
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  944): DriverStartedState call setCountryCode()
E/WifiStateMachine(  944): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  944): NetworkAgent == null
E/WifiStateMachine(  944): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
D/WifiDataStallTracker(  944): setDhcpActive: false
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
D/wpa_supplicant( 6251): wlan0: Control interface command 'STATUS'
E/WifiStateMachine(  944): transitionTo: destState=DisconnectedState
E/native  (  944): do suspend false
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
E/WifiTrafficPoller(  944): ENABLE_TRAFFIC_STATS_POLL false Token 0
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6251): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
E/WifiStateMachine(  944): Driverstarted State enter done
E/WifiStateMachine(  944): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  944): moveDeferredMessageAtFrontOfQueue; what=131144
E/Wifi,StateMachine(  944): handleMessage: new destination call exit/enter
E/WifiStateMachine(  944): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  944): moveTempStackToStateStack: i=1,j=3
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
E/WifiStateMachine(  944): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  944): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
E/WifiStateMachine(  944): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  944): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  944): DisconnectedState call setCountryCode()
D/libc    (  944): [NET] android_getaddrinfofornet-, SUCCESS
E/WifiStateMachine(  944):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'pno'='1'
D/wpa_supplicant( 6251): wlan0: nl80211: sched_scan request
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  944): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  944): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  944): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiScanningService(  944): SCAN_AVAILABLE : 3
D/RttService(  944): SCAN_AVAILABLE : 3
D/WifiScanningService(  944): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  944): startHal
D/WifiMonitor(  944): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
I/IntentController( 1222): receive(android.net.wifi.STATE_CHANGE,1,false)
D/bt-btm  ( 6218): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 6218): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6218): BTM Register For VSEvents is successfully
D/bt-btm  ( 6218): BTM_BleGetVendorCapabilities
I/bt-btif ( 6218): HAL bt_hal_cbacks->adapter_properties_cb
D/RttService(  944): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterProperties( 6218): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
D/bt-btm  ( 6218): bta_dm_set_dev_name: name: HTC One M8s 
D/StatusBar.NetworkController( 1222): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
E/bt-btif ( 6218): Calling BTA_HhEnable
I/bt-btif ( 6218): BTA_MceEnable
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btm  ( 6218):  BTM_BleConfigPrivacy
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 6218): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6218): BTM_AllocateSCN
I/bt-btm  ( 6218): btif_storage_get_adapter_propertyo controller
E/bt-btif ( 6218): SDPf_storage_get_adapter_property service_mask:0x2140040
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:4
D/bt-btm  ( 6218): BTM_AllocateSCN
I/bt-btif ( 6218): BTM_AllocateSCN
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btm  ( 6218): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6218):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6218):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6218): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6218): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6218):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6218):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6218): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6218): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 6218): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
D/BluetoothAdapterProperties( 6218): Address is:90:E7:C4:F6:69:77
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6218): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
D/bt-btif ( 6218):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6218): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btm  ( 6218): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6218):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6218):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6218):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6218): GATT_Register
D/bt-att  ( 6218): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6218): allocated gatt_if=4
I/bt-att  ( 6218): GATT_StartIf gatt_if=4
D/bt-att  ( 6218): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6218): gatt_find_the_connected_bda found=0 found_idx=16
D/BluetoothAdapterProperties( 6218): Scan Mode:21
D/BluetoothAdapterProperties( 6218): Discoverable Timeout:120
I/bt-btif ( 6218): BTA_JvEnable
I/bt-btif ( 6218): BTA_JvRegisterL2cCback
I/bt-btm  ( 6218): BTM_ReadConnectability
I/bt-btm  ( 6218): BTM_ReadDiscoverability
I/bt-btm  ( 6218): BTM_SetDiscoverability
I/bt-btm  ( 6218): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6218): disc_mode 0002
D/bt-btm  ( 6218): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): evt_type=0x0 p-cb->evt_type=0x3 
I/bt-btm  ( 6218): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6218): BTM_SetConnectability
I/bt-btm  ( 6218): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6218): disc_mode 0002
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6218): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6218): BTM_SetDiscoverability
I/bt-btm  ( 6218): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6218): disc_mode 0000
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6218): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6218): BTM_SetConnectability
I/bt-btm  ( 6218): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6218): disc_mode 0000
I/QuickSettingWifi( 1222): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
D/bt-btm  ( 6218): btm_ble_update_adv_flag new=0x1c
D/bt-btm  ( 6218): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
I/bt-btm  ( 6218): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6218): bta_pan_co_init
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6218): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6218):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6218):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btm  ( 6218): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6218):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6218): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6218):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = ce d7 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = d2 0e 40 4f e1 1c 41 14 28 67 be 59 07 8d 8b 41 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6218): Stopping oneshot timer
D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = f5 73 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 1e bf bb c5 cb 41 76 24 1e ac ce 94 5c 11 12 95 
E/bt_mct  ( 6218): hci lib postload completed
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 6218): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6218): ScanMode =  21
D/BluetoothAdapterProperties( 6218): State =  11
D/BluetoothAdapterProperties( 6218): Setting state to 12
I/BluetoothAdapterState( 6218): Bluetooth adapter state changed: 11-> 12
D/bt-btif ( 6218): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6218): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6218): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6218): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6218): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothManagerService(  944): +onBluetoothStateChange prev=11 new=12
I/bt-btif ( 6218): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  944): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  944): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothAdapterProperties( 6218): Discoverable Timeout:120
I/BluetoothAdapterState( 6218): Entering On State
D/BluetoothManagerService(  944): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  944): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1470): onBluetoothStateChange: up=true
D/BluetoothA2dp(  944): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1470): onBluetoothStateChange: up=true
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = ab d8 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 94 53 1b cb 99 87 78 d0 1a 4e 4a d8 4f cf a1 e0 
D/BluetoothHeadset( 1470): onBluetoothStateChange: up=true
D/BluetoothManagerService(  944): Bluetooth State Change Intent: 11 -> 12
I/IntentController( 1222): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3703): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
D/NGFService( 3703): Bluetooth Adapter: ON
D/BluetoothManagerService(  944): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  944): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
D/BluetoothManagerService(  944): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = f5 d5 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = ed 61 7b cb c4 64 4f 17 f0 30 7a 5e da 68 dd 4e 
V/BluetoothPbapReceiver( 6218): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6218): ***********state = 12
D/WISPrService( 5655): >>>>>WISPrService start isConnected = false<<<<<
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 1d fc 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 98 f4 75 47 30 1c 9a a0 bb 39 f5 12 9d 3f 12 11 
D/PMS     (  944): acquireWL(114d72e4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5655 1000 null
W/ContextImpl( 5655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 38 9c 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 72 f4 33 88 a8 db d5 29 20 fe f9 41 c1 e1 00 30 
E/WifiTrafficPoller(  944): ADD_CLIENT: 8
D/WifiService(  944): New client listening to asynchronous messages
D/WISPrService( 5655): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/PMS     (  944): releaseWL(114d72e4): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/HtcBtWidget_BTWidgetProvider( 6258): onBTStateChanged() for widget: 
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
D/PMS     (  944): acquireWL(55e02): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5655 1000 null
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 02 d1 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 5d b5 72 9f b1 b4 1a 3c b7 00 4b ba 72 d0 e1 43 
V/BluetoothPbapService( 6218): Pbap Service onCreate
V/BluetoothPbapService( 6218): Starting PBAP service
D/HtcBtWidget_BTWidgetProvider( 6258): updateWidget(context) for widget: 
D/BluetoothAdapter( 6218): 225809: getState(). Returning 12
V/BluetoothPbapService( 6218): Handler(): got msg=1
V/BluetoothPbapService( 6218): Pbap Service startRfcommSocketListener
I/QuickSettingWifi( 1222): receive.wifiConnect:false wifiAPname:null elapse:2
V/BluetoothPbapService( 6218): Pbap Service initSocket
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 2a 63 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 8f 0a 47 fc 02 13 5e f8 e4 91 a4 0c 03 54 90 22 
D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/System.err(  944): java.lang.Throwable: stack dump
W/System.err(  944): 	at java.lang.Thread.dumpStack(Thread.java:490)
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  944): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  944): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  944): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  944): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d31749:true
W/BluetoothAdapter( 6218): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btm  ( 6218): HAL bt_hal_cbacksility
I/bt-btif ( 6218): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btm  ( 6218): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
I/bt-btif ( 6218): BTA_JvCreateRecordByUser
D/bt-btm  ( 6218): disc_mode 0000
I/bt-btm  ( 6218): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6218): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6218): BTM_SetConnectability
I/bt-btm  ( 6218): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6218): disc_mode 0000
D/bt-btm  ( 6218): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6218): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6218): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): BTA_JvRfcommStartServer
I/bt-btm  ( 6218): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6218):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6218): Succeed to create listening socket 
V/BluetoothPbapService( 6218): Accepting socket connection...
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 03 43 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = c0 01 c4 0d 86 b0 42 c9 95 9f f1 15 12 25 ec 3e 
D/BluetoothAdapterProperties( 6218): Scan Mode:21
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = d3 19 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 4e be ae 1f 96 db ce 6b 51 13 76 41 9f 92 9d dd 
D/BluetoothAdapter( 5655): 507677954: getState(). Returning 12
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = d5 14 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = ac 40 0f c5 d1 62 6d 51 84 ff de 12 9a f6 c8 e9 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6218): Stopping oneshot timer
D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
D/BluetoothInputDevice( 5655): BluetoothInputDevice()
D/BluetoothManagerService(  944): registerStateChangeCallback+
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  944): Registered receivers: 7
D/BluetoothPan( 5655): BluetoothPan()
D/BluetoothManagerService(  944): registerStateChangeCallback+
D/BluetoothAdapter( 1222): 105356207: getState(). Returning 12
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  944): Registered receivers: 8
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 08 c6 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = ef ef aa 2d 49 ad 70 2b 68 db 65 b7 68 76 43 4e 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6218): Stopping oneshot timer
,D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 1222): 105356207: getState(). Returning 12
I/QuickSettingBluetooth( 1222): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1222): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
D/BluetoothMap( 5655): Create BluetoothMap proxy object
,D/BluetoothManagerService(  944): registerStateChangeCallback+
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  944): Registered receivers: 9
,E/BluetoothMap( 5655): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 73 f9 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = b6 e1 9f 2b d8 7a bd 64 a4 e2 68 a5 fe cd 86 74 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
,W/bt-btm  ( 6218): Stopping oneshot timer
D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
,D/BluetoothManagerService(  944): registerStateChangeCallback+
D/wpa_supplicant( 6251): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6251): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6251): wlan0: nl80211: Sched scan started
D/BluetoothSap( 5655): BluetoothSap() call bindService
E/wifi    (  944): getStaticLongField sWifiHalHandle 0x7f769af520
I/WifiNative-HAL(  944): Could not start hal
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131144
E/WifiStateMachine(  944): processMsg: DisconnectedState
E/WifiScanningService(  944): could not start HAL
E/WifiStateMachine(  944):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131085
E/WifiStateMachine(  944): processMsg: DisconnectedState
E/WifiStateMachine(  944):  DisconnectedState CMD_START_DRIVER 0 0
,E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState CMD_START_DRIVER 0 0
W/ContextImpl( 5655): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131154
E/WifiStateMachine(  944): processMsg: DisconnectedState
D/WifiMonitor(  944): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  944): P2pEnablingState
E/WifiStateMachine(  944):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/WifiStateMachine(  944):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
D/BluetoothManagerService(  944): Registered receivers: 10
E/WifiStateMachine(  944):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131323
E/WifiStateMachine(  944): processMsg: DisconnectedState
E/WifiStateMachine(  944):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
,E/WifiStateMachine(  944):  ConnectModeState what:131323 0 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  944): processMsg: DefaultState
D/WifiP2pService(  944): P2pEnablingState{ when=-3ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  944): P2p socket connection successful
D/WifiP2pService(  944): P2pEnabledState
D/BluetoothPbap( 5655): BluetoothPbap()
D/WifiP2pService(  944): sending p2p connection changed broadcast
D/BluetoothManagerService(  944): registerStateChangeCallback+
,D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  944): Registered receivers: 11
W/WifiHW  (  944): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
,D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6251): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6251): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6251): persistent_reconnect=1
D/wpa_supplicant( 6251): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6251): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6251): P2P: Set Operating channel: reg_class 126 channel 149
D/WifiDisplayController(  944): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
W/WifiHW  (  944): QCOM Debug wifi_send_command "SET device_name Android_608e"
D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6251): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6251): p2p0: Control interface command 'SET device_name Android_608e'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6251): device_name='Android_608e'
W/WifiHW  (  944): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6251): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6251): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6251): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6251): P2P: New SSID postfix: -Android_608e
W/WifiHW  (  944): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6251): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6251): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'device_type'='10-0050F204-5'
W/WifiHW  (  944): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6251): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6251): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6251): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6251): config_methods='virtual_push_button physical_display keypad'
W/WifiHW  (  944): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
D/wpa_supplicant( 6251): p2p0: Control interface command 'P2P_SET conc_pref sta'
I/wpa_supplicant( 6251): [p2p command] (P2P_SET conc_pref sta)
D/wpa_supplicant( 6251): Single channel concurrency preference: sta
D/WifiNative-HAL(  944): p2pGetDeviceAddress
W/WifiHW  (  944): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  944): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
E/WifiStateMachine(  944):  DefaultState what:131323 0 0
E/WifiStateMachine(  944): setOperatorSSID enter
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131104
E/WifiStateMachine(  944): processMsg: DisconnectedState
E/WifiStateMachine(  944):  DisconnectedState what:131104 0 0
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState what:131104 0 0
W/Settings(  ,944): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/WifiDisplayController(  944): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/wpa_supplicant( 6251): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/WifiDisplayController(  944): mWfdEnabled :false, networkInfo.isConnected() :false
D/wpa_supplicant( 6251): CTRL_IFACE: field=AIR_MODE id=0
D/WifiDisplayAdapter(  944): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  944):     Client/Owner: Client
D/WifiDisplayAdapter(  944):     GroupId: 
D/WifiDisplayAdapter(  944):     Passphrase: 
D/WifiDisplayAdapter(  944):     SessionId: 0
D/WifiDisplayAdapter(  944):     IP Address: }
D/wpa_supplicant( 6251): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
D/WifiP2pService(  944): DeviceAddress: 92:e7:c4:e6:4c:f8
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=131162
E/WifiStateMachine(  944): processMsg: DisconnectedState
V/AudioService(  944): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  944):     Client/Owner: Client
V/AudioService(  944):     GroupId: 
V/AudioService(  944):     Passphrase: 
V/AudioService(  944):     SessionId: 0
V/AudioService(  944):     IP Address: }
D/WifiDisplayController(  944): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  944):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  944):  primary type: 10-0050F204-5
D/WifiDisplayController(  944):  secondary type: null
D/WifiDisplayController(  944):  wps: 0
D/WifiDisplayController(  944):  grpcapab: 0
D/WifiDisplayController(  944):  devcapab: 0
D/WifiDisplayController(  944):  status: 3
D/WifiDisplayController(  944):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  944):  WFD CtrlPort: 0
D/WifiDisplayController(  944):  WFD MaxThroughput: 0
E/WifiStateMachine(  944):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
D/HtcEffectManagerBase(  944): onEventChanged id=5 status=false
E/WifiStateMachine(  944): processMsg: ConnectModeState
D/HtcEffectManager(  944): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false
D/HtcEffectManager(  944): convertEffect before=902
D/HtcEffectManager(  944): convertEffect after=902
E/WifiStateMachine(  944):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  944): processMsg: DriverStartedState
W/WifiHW  (  944): QCOM Debug wifi_send_command "P2P_FLUSH"
E/WifiStateMachine(  944):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  944): set frequency band 0
D/wpa_supplicant( 6251): p2p0: Control interface command 'P2P_FLUSH'
D/BluetoothManagerService(  944): registerStateChangeCallback+
I/wpa_supplicant( 6251): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6251): P2P: Stopping find
D/wpa_supplicant( 6251): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6251): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6251): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6251): P2P: Stopping find
D/wpa_supplicant( 6251): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6251): P2P: State IDLE -> IDLE
,D/wpa_supplicant( 6251): wpa_driver_set_ap_wps_p2p_ie: Entry
D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 4a e4 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 73 38 ec e9 39 aa 76 2d d8 3e 00 69 e8 9d 02 d0 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6218): Stopping oneshot timer
D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6251): wlan0: Control interface command 'DRIVER SETBAND 0'
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/wpa_supplicant( 6251): SETBAND: 0
D/wpa_supplicant( 6251): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/BluetoothManagerService(  944): Registered receivers: 12
D/wpa_supplicant( 6251): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6251): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  944): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  944): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  944): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  944): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6251): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6251): P2P: Add operating class 81
,D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6251): P2P: Add operating class 115
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6251): P2P: Add operating class 116
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6251): P2P: Add operating class 117
D/wpa_supplicant( 6251): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6251): P2P: Update channel list
D/wpa_supplicant( 6251): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6251): P2P: cli_channels:
D/wpa_supplicant( 6251): p2p0: Updating hw mode
D/wpa_supplicant( 6251): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6251): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6251): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6251): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6251): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  944): did set frequency band 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6251): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6251): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6251): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  944): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6251): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6251): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  944): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6251): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6251): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6251): wlan0: Cancelling sched scan
D/BluetoothHeadset( 5655): BluetoothHeadset()
D/wpa_supplicant( 6251): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6251): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6251): wpa_supplicant_scan enter
D/wpa_supplicant( 6251): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6251): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6251): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6251): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  944): done set frequency band 0
W/WifiHW  (  944): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/BluetoothManagerService(  944): registerStateChangeCallback+
D/BluetoothManagerService(  944): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  944): Registered receivers: 13
D/wpa_supplicant( 6251): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/WifiP2pService(  944): sending p2p persistent groups changed broadcast
D/wpa_supplicant( 6251): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6251): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/WifiP2pService(  944): InactiveState
D/wpa_supplicant( 6251): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6251): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6251): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6251): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/LocalBluetoothProfileManager( 5655): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5655): finishStartingService: stopping service
,D/BluetoothA2dp( 5655): Proxy object connected
D/A2dpProfile( 5655): Bluetooth service connected
,D/wpa_supplicant( 6251): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/BluetoothAdapter( 5655): 507677954: getState(). Returning 12
D/Tethering(  944): interfaceLinkStateChanged p2p0, false
,D/Tethering(  944): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  944): WiFiDisplay: getWifidisplayApEnabled=false
,D/BluetoothHeadset( 5655): Proxy object connected
,D/HeadsetProfile( 5655): Bluetooth service connected
,D/BluetoothAdapter( 5655): 507677954: getState(). Returning 12,
,D/PMS     (  944): releaseWL(55e02): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,V/BluetoothPbapService( 6218): Pbap Service onBind
D/BluetoothInputDevice( 5655): Proxy object connected
D/HidProfile( 5655): Bluetooth service connected
,D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 5655): 507677954: getState(). Returning 12
,D/BluetoothPan( 5655): BluetoothPAN Proxy object connected
D/PanProfile( 5655): Bluetooth service connected
D/BluetoothPbap( 5655): Proxy object connected
,D/PbapServerProfile( 5655): Bluetooth service connected
W/BluetoothAdapter( 6218): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiStateMachine(  944): Wifi band: 0, ScanBroadCastCounter: 0
D/WifiStateMachine(  944): [MLHD] enter handleMediaLinkEvent DriverStartedState
E/WifiStateMachine(  944): handleMessage: X
I/bt-btif ( 6218): BTA_JvCreateRecordByUser
E/WifiStateMachine(  944): handleMessage: E msg.what=147462
E/WifiStateMachine(  944): processMsg: DisconnectedState
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): BTA_JvRfcommStartServer
I/bt-btm  ( 6218): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6218):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6218): Accept thread started.
E/WifiStateMachine(  944):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129632  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  944): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  944): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=129633  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  944): handleMessage: X
E/WifiStateMachine(  944): handleMessage: E msg.what=143371
E/WifiStateMachine(  944): processMsg: DisconnectedState
E/WifiStateMachine(  944):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  944): processMsg: ConnectModeState
E/WifiStateMachine(  944):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  944): processMsg: DriverStartedState
E/WifiStateMachine(  944):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  944): processMsg: SupplicantStartedState
E/WifiStateMachine(  944):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  944): processMsg: DefaultState
E/WifiStateMachine(  944):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  944): handleMessage: X
,D/BluetoothAdapter( 6218): 225809: getState(). Returning 12
,D/BluetoothFtpService( 6218): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothMasReceiver( 6218): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6218):  call MAP start service
,D/BluetoothFtpService( 6218): htc sense version is 6.0
,D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6218): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6218): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): BTA_JvRfcommStartServer
I/bt-btm  ( 6218): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6218):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,V/BluetoothFtpService:RfcommSocketAcceptThread( 6218): Run Accept thread
,E/BluetoothMasService( 6218): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
,D/BluetoothMasService( 6218): Add permission for SmsProvider.,
,V/BluetoothMasService( 6218): Starting MAS instances
D/BluetoothAdapter( 6218): 225809: getState(). Returning 12
,I/MailMessageReceiver( 6218): reg:com.android.bluetooth.btservice.AdapterApp@6d0774e with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@3f70c06f,
,I/MailManager( 6218): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@3f70c06f
V/EmailUtils( 6218): Manager Instance is not NULL
,I/ActivityManager(  944): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6348 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a,
,D/HtcAdjCursorFactory( 6348): Set CursorWindow size to: 4194304 KB, Tid: 6367,
,D/EmailUtils( 6218): ============NULL aList========
V/EmailUtils( 6218): <-getEmailAccountIdList
V/BluetoothMasService( 6218): onCreate: mIsEmailEnabled: true
,D/BluetoothAdapter( 6218): 225809: getState(). Returning 12,
V/BluetoothMasService( 6218): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 6218): Manager Instance is not NULL
,D/EmailUtils( 6218): ============NULL aList========,
V/EmailUtils( 6218): <-getEmailAccountIdList
V/BluetoothSapReceiver( 6218): SapReceiver onReceive 
V/BluetoothSapReceiver( 6218): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6218):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6218): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6218): handleMessage: mIsEmailEnabledtrue
,V/BtMns   ( 6218): BluetoothMns: isEmailEnabled: true
,D/AuthorizationBluetoothService( 1883): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
W/BluetoothAdapter( 6218): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6218): BTA_JvCreateRecordByUser
D/bt-btm  ( 6218): BTM_AllocateSCN
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:13
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): BTA_JvRfcommStartServer
I/bt-btm  ( 6218): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
,I/bt-btm  ( 6218):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6218): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6218): BTA_JvCreateRecordByUser
D/bt-btm  ( 6218): BTM_AllocateSCN
D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): BTA_JvRfcommStartServer
I/bt-btm  ( 6218): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6218):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,D/Process (  944): killProcessQuiet, pid=4793
I/ActivityManager(  944): Killing 4793:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  944): Recipient 4793
,V/BluetoothSapService( 6218): Sap Service onCreate,
V/BluetoothSapService( 6218): initBinder
V/BluetoothSapService( 6218): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@540ba5a
,V/BluetoothSapService( 6218): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@c76a968
V/BluetoothSapService( 6218): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6218): state: 12
,D/SapServerProfile( 5655): Bluetooth service connected
,V/BluetoothSapService( 6218): Starting SAP server process
,D/A2dpService( 6218): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@16402226
,D/A2dpSinkService( 6218): getA2dpSinkService(): service is NULL
V/BluetoothSapService( 6218): SAP Service startRfcommListenerThread
,D/wpa_supplicant( 6251): EAPOL: disable timer tick
V/BluetoothSapService( 6218): Sap Service initRfcommSocket
,D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6218): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6218): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6218): SDP_CreateRecord ok, num_records:15
I/bt-btm  ( 6218): Write Extended Inquiry Response to controller
I/bt-btif ( 6218): BTA_JvRfcommStartServer
I/bt-btm  ( 6218): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6218):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6218): Succeed to create listening socket 
V/BluetoothSapService( 6218): Accepting socket connection...
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 6251): EAPOL: disable timer tick,
,D/BluetoothManagerService(  944): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/jxcore-log( 6164): Got Device Bluetooth address: 90:E7:C4:F6:69:77
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): my name is : HTC-HTC One M8s_PT5089
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): attempting to connect to test coordinator
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): check test folder
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): found test : ./testFindPeers.js
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): found test : ./testReConnect.js
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): found test : ./testSendData.js
I/jxcore-log( 6164): 
,I/art     (  944): Explicit concurrent mark sweep GC freed 26806(1401KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.532ms total 188.423ms
,I/jxcore-log( 6164): Test app app.js loaded
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/chromium( 6164): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): releaseWL(1039db38): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,I/jxcore-log( 6164): BLE advertisement not supported: Not supported
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  944): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  944): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/PMS     (  944): acquireWL(ac354c8): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10024}
V/AlarmManager(  944): sending alarm PendingIntent{33b03961: PendingIntentRecord{358a2c86 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143594, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{29700428: PendingIntentRecord{24e62541 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=146871, Int=0
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(ac354c8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,W/ContextImpl(  944): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(1b09f947): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): releaseWL(1b09f947): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): Checking...
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
,D/WifiController(  944): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/TelephonyReceiver( 1470): switchBindHtcMsgCursor: null
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(211cf574): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=166831, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{29700428: PendingIntentRecord{24e62541 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=206885, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{37d60a9d: PendingIntentRecord{fcc8b12 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=207831, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{2e62e2e3: PendingIntentRecord{3fcdf4e0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186991, Int=0,
V/AlarmManager(  944): sending alarm PendingIntent{308db399: PendingIntentRecord{35b8c74b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=195151, Int=0
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  944): [NET] android_getaddrinfofornet-, err=8
D/libc    (  944): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  944): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  944): [NET] android_getaddrinfo_proxy+
D/libc    (  944): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
,D/libc    (  944): [NET] android_getaddrinfo_proxy-, NODATA,
,D/PMS     (  944): acquireWL(1a64465e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1883 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
D/PMS     (  944): releaseWL(1a64465e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): acquireWL(14d6ca3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1883 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  944): releaseWL(211cf574): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1883): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1883): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1883): [NET] android_getaddrinfo_proxy+
D/libc    ( 1883): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1883): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(14d6ca3f): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,D/HtcUPManager( 1222): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1437): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@102625e3,
,I/ActivityManager(  944): Killing 5953:com.google.android.apps.docs/u0a101 (adj 15): empty #17,
D/Process (  944): killProcessQuiet, pid=5953
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5953,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(3ccd7f0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3ccd7f0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  944): acquireWL(f7cf055): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=226831, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{1677cb5b: PendingIntentRecord{34597ff8 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1448877115959, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{e93cd1: PendingIntentRecord{35b8c74b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=347793, Int=0
,D/PMS     (  944): acquireWL(e7cc336): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1883 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1883): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1883): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1883): [NET] android_getaddrinfo_proxy+
D/libc    ( 1883): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1883): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(e7cc336): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(f7cf055): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(205dc237): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(205dc237): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): runPSCheck
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
,D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,W/GLSActivity( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1883): 	,at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1883): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1883): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1883): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5681): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5681): 	,at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5681): Ignoring header User-Agent because its value was null.
,D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 5681): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5681): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5681): [NET] android_getaddrinfo_proxy+
D/libc    ( 5681): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024,
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504,
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5681): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6164): ,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(2ee1fc41): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  944): battery changed pluggedType: 2
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): releaseWL(2ee1fc41): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): processMsg: StaEnabledState
,D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 1
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(2c5a65e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(2c5a65e6): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 2
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 3
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(236da727): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(236da727): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  944): updateBatteryInfo
,D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
,D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: E msg.what=155652
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): processMsg: StaEnabledState
I/HtcPowerSaver(  944): << updateStatus
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  471): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(2dc83dd4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(2dc83dd4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(27111b7d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=406831, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{1856fa72: PendingIntentRecord{35b8c74b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=627632, Int=0
D/PMS     (  944): acquireWL(3838ec3): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1883 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1883): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1883): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1883): [NET] android_getaddrinfo_proxy+
D/libc    ( 1883): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1883): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(3838ec3): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  944): releaseWL(27111b7d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/ContactMessageStore( 1470): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1470): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1470): sku_id=118,
D/ContactMessageStore( 1470): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1470): start background delete task...
,D/ContactMessageStore( 1470): size: 0 , 0
D/ContactMessageStore( 1470): Background delete complete
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1883): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1883): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1883): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5681): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5681): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
,W/System  ( 5681): Ignoring header User-Agent because its value was null.
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5681): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5681): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5681): [NET] android_getaddrinfo_proxy+
D/libc    ( 5681): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5681): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
,I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): acquireWL(1804dded): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  944): n_update end
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(1804dded): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
,D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(7fee422): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(7fee422): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(2555aeb3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(2555aeb3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): << updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  944): plugged=true pluggin=true
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/WifiController(  944): battery changed pluggedType: 2
,D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): closing low battery warning: level=100
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
,D/WifiController(  944): handleMessage: X
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(12281c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(12281c70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): closing low battery warning: level=100
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(225e6be9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=646831, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{3641be09: PendingIntentRecord{25dad80e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806874, Int=0
,D/Finsky  ( 5681): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  944): sending alarm PendingIntent{14f2830f: PendingIntentRecord{952b946 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448877414768, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{3bca8f9c: PendingIntentRecord{1ba8dda5 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1448877722752, Int=1800000
,I/ActivityManager(  944): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6394 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/AlarmManager(  944): sending alarm PendingIntent{dde412b: PendingIntentRecord{31bf0988 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1448877440541, Int=0
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  944): Start proc com.htc.launcher:biclient for service com.htc.launcher/com.htc.BiLogClient.BiLogUploadService: pid=6410 uid=10074 gids={50074, 9997, 3003, 1028, 1015, 5001, 1023} abi=arm64-v8a
,V/AlarmManager(  944): sending alarm PendingIntent{12ff3634: PendingIntentRecord{39661c5d com.htc.launcher startService}}, i=com.htc.BiLogClient.ACTION_SEND_LOG, t=3, cnt=1, w=900000, Int=1800000
V/AlarmManager(  944): sending alarm PendingIntent{1a0c99d2: PendingIntentRecord{356b9384 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448877735605, Int=0
,D/PMS     (  944): acquireWL(271f17cc): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4418 10024 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  944): acquireWL(3b05912a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4418 10024 WorkSource{10024 com.google.android.gms}
W/ContextImpl( 6061): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
D/PMS     (  944): releaseWL(271f17cc): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  944): releaseWL(225e6be9): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PowerUsageList:PowerUsageHelper( 6061): MY_DEBUG = false
,D/PowerUsageService( 6061): repeat time = 1448878635711,
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/EventLogService( 4418): Aggregate from 1448875922711 (log), 1448875922711 (data)
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5681): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ImageRamCache( 6410): create image Cache, size: 31457280.
I/ImageRamCache( 6410): [resize] ImageRamCache resized to: 30Mb.
,I/ImageRamCache( 6410): create image Cache, size: 31457280.
,I/FeedSettings( 6410): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
,I/FeedSettings( 6410): GroupBudget 0.500000 0.380000
I/FeedSettings( 6410): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 6410): changeLocale(): en_GB
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/cutils-trace( 6442): Error opening trace file: Permission denied (13)
I/dex2oat ( 6442): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 6442): dex2oat: override thread count:4
V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Prism.AllAppsOptionsMa_( 6410): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 6410): loadGridSize() with Alternative
,I/PowerUsageList:PowerUsageHelper( 6061): PowerProfile::POWER_SCREEN_FULL = 154.8,
V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  944): releaseWL(3b05912a): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,D/PowerUsageList:BatterySipperExt( 6061): gen(), null == sipper.uidObj, userId = 0,
D/PowerUsageList:BatterySipperExt( 6061): gen(), null == sipper.uidObj, userId = 0
D/PowerUsageList:BatterySipperExt( 6061): gen(), null == sipper.uidObj, userId = 0
,D/libc    ( 6410): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 4
D/libc    ( 6410): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 6410): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024,
D/libc    ( 6410): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 6410): [NET] android_getaddrinfo_proxy+
D/libc    ( 6410): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 17(0x637362692e6874),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 6410): [NET] android_getaddrinfo_proxy-, NODATA
E/[CSBICLIENT][v12][BiLogUploadService]( 6410): Exception on getConfig()
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
D/PowerUsageService( 6061): calcPower(), no data
,W/Finsky  ( 5681): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5681): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5681): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5681): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5681): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 1797): client connected with version: 7571000
,D/Finsky  ( 5681): [1] VerifyInstalledPackagesReceiver.checkPrerequisites: Skipping verification because network inactive
,I/dex2oat ( 6442): dex2oat took 666.226ms (threads: 4)
,D/Process (  944): killProcessQuiet, pid=5753
I/ActivityManager(  944): Killing 5753:com.google.android.apps.plus/u0a167 (adj 15): empty #17
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5753
,I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): PackageName:             com.htc.cs.pns,
,I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): VersionCode:             148001224
,I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): Htc_DEBUG_flag:          false
I/PushClient( 6394): ApplicationMonitor {187df7d8}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/PushClient( 6394): PnsModel {33c5b6bb}: update(): Update registration caused by: alarm
,I/PushClient( 6394): PnsConfigModel {e569ee}: <init>(): Use dm-client for provisioning.
,W/System.err( 6394): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6394): SLF4J: Defaulting to no-operation (NOP) logger implementation
,W/System.err( 6394): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,W/ContextImpl( 6394): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  944): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6458 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6458): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6458 dbg=false s=true,
,I/DeviceManagement( 6458): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
I/DeviceManagement( 6458): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6458): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6458): WorkflowService: Starting workflow service
,I/DeviceManagement( 6458): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@f59674a] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6458): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6458): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6458): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6458): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6458): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6458): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6458): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6458): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@f59674a],
,I/DeviceManagement( 6458): WorkflowService: Stopping workflow service
,D/Process (  944): killProcessQuiet, pid=5604
I/ActivityManager(  944): Killing 5604:com.google.android.googlequicksearchbox:search/u0a85 (adj 15): empty #17
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/PushClient( 6394): PnsModel {33c5b6bb}: update(): The registration record has not expired yet. No need to update.,
,I/ActivityManager(  944): Recipient 5604
,I/ActivityManager(  944): Killing 5868:com.android.defcontainer/u0a15 (adj 15): empty #17
,D/Process (  944): killProcessQuiet, pid=5868
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  944): Recipient 5868
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,W/SQLiteConnectionPool( 6410): A SQLiteConnection object for database '/data/data/com.htc.launcher/databases/BiLogClient' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1883): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1883): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1883): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5681): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 5681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5681): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5681): Ignoring header User-Agent because its value was null.
,D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5681): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5681): [NET] android_getaddrinfofornet-, pass to proxy
,D/libc    ( 5681): [NET] android_getaddrinfo_proxy+
D/libc    ( 5681): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5681): [NET] android_getaddrinfo_proxy-, NODATA
,I/art     (  944): Explicit concurrent mark sweep GC freed 22649(1135KB) AllocSpace objects, 6(880KB) LOS objects, 33% free, 16MB/24MB, paused 1.932ms total 172.417ms
,D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true,
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1222): reapply : com.google.android.gms 3 40
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(21ba68af): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{10072},
,V/AlarmManager(  944): sending alarm PendingIntent{e9e14bc: PendingIntentRecord{13422393 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448877750957, Int=0
D/PMS     (  944): releaseWL(21ba68af): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5681): [577] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
,D/Finsky  ( 5681): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(29084c45): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1006831, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{223af9a: PendingIntentRecord{33cee0cb com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1448877786943, Int=0
,D/SmartSyncUtils( 6061): isEpsOn(), nState = 0
,D/PMS     (  944): releaseWL(29084c45): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/PMS     (  944): acquireWL(3f95c0a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6061 1000 null
,D/WeatherUtility( 1222): Weather sync is On,
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6061): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6061): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6061): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 6061): SettingOnTime = 1448949600000, randomSettingOnTime = 1448946987000
D/SmartSyncScreenOnOffTimeReceiver( 6061): SettingOffTime = 1448928000000, randomSettingOffTime = 1448931218000
,D/SmartSyncScreenOnOffTimeReceiver( 6061): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 6061): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6061): bNightModeTurnOffOnce = false
,D/PMS     (  944): releaseWL(3f95c0a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): acquireWL(1d6667c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
I/BatteryService(  944): n_update end
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  944): releaseWL(1d6667c1): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(387d2b66): PARTIAL_WAKE_LOCK  *alarm* 0x1 944 1000 WorkSource{1002},
V/AlarmManager(  944): sending alarm PendingIntent{2768bea7: PendingIntentRecord{dda3f54 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1029352, Int=0
,I/bt-btm  ( 6218): Received oneshot timer event complete
D/PMS     (  944): releaseWL(387d2b66): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1002}
I/bt-btm  ( 6218): btm_ble_timeout
,D/PMS     (  944): acquireWL(3430befd): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6218 1002 null
I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
,D/bt-btm  ( 6218): btm_ble_rand_enc_complete,
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = 0c 80 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = cb 79 06 48 51 9b 8a af 81 4a fd cb 3d 70 4b e4 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6218): Stopping oneshot timer
D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
,D/PMS     (  944): releaseWL(3430befd): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(7a097f2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
,D/PMS     (  944): releaseWL(7a097f2): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  944): plugged=true pluggin=true
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/PMS     (  944): runPSCheck
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(24d89e43): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1066830, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{1b45fcc0: PendingIntentRecord{35b8c74b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1187270, Int=0
D/PMS     (  944): acquireWL(2c4f4df9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1883 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1883): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1883): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1883): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1883): [NET] android_getaddrinfo_proxy+
D/libc    ( 1883): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
,D/libc    ( 1883): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  944): releaseWL(2c4f4df9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1222): Weather sync is On
W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,D/PMS     (  944): releaseWL(24d89e43): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): ,
,D/PMS     (  944): acquireWL(f1c413e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null,
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(f1c413e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  944): << updateStatus
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/WifiController(  944): battery changed pluggedType: 2
,D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/UsageStatsService(  944): User[0] Flushing usage stats to disk
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(3edcdb9f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(3edcdb9f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/HtcPowerSaver(  944): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1883): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1883): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1883): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5681): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5681): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/System  ( 5681): Ignoring header User-Agent because its value was null.
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5681): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5681): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5681): [NET] android_getaddrinfo_proxy+
,D/libc    ( 5681): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
,D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5681): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(26a2a769): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
,I/BatteryService(  944): n_update end
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): releaseWL(26a2a769): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): handleMessage: E msg.what=155652
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DefaultState
D/PowerUI ( 1222): closing low battery warning: level=100
D/WifiController(  944): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/HtcPowerSaver(  944): << updateStatus
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(267975ee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(267975ee): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
,D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  944): runPSCheck
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
,D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(7b9ea8f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
,I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): releaseWL(7b9ea8f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1222): closing low battery warning: level=100
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1883): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1883): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1883): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5681): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69),
E/PlayEventLogger( 5681): 	at android.os.Binder.execTransact(Binder.java:454)
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1222): reapply : com.google.android.gms 2 40
W/System  ( 5681): Ignoring header User-Agent because its value was null.
,D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5681): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5681): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5681): [NET] android_getaddrinfo_proxy+
D/libc    ( 5681): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5681): [NET] android_getaddrinfo_proxy-, NODATA
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(1ff73cd9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(1ff73cd9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/PMS     (  944): runPSCheck
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  944): >> updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  944): handleMessage: E msg.what=155652
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1222): closing low battery warning: level=100
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(19a5369e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(19a5369e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/WifiController(  944): battery changed pluggedType: 2
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/PMS     (  944): runPSCheck
,D/WifiController(  944): handleMessage: E msg.what=155652
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DeviceActiveState
I/HtcPowerSaver(  944): >> updateStatus
D/WifiController(  944): processMsg: StaEnabledState
D/PowerUI ( 1222): closing low battery warning: level=100
,D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  944): handleMessage: X
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/HtcPowerSaver(  944): << updateStatus
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(1e30957f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(1e30957f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  944): updateBatteryInfo
D/PMS     (  944): runPSCheck
D/HtcPowerSaver(  944): Checking...
I/HtcPowerSaver(  944): >> updateStatus
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  944): battery changed pluggedType: 2
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,E/PNP_UPDATERD(  387): inotify_add_watch failed. (No such file or directory)
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(815cd95): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  944): releaseWL(815cd95): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  944): updateBatteryInfo
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  944): plugged=true pluggin=true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/PMS     (  944): runPSCheck
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  944): Checking...
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
I/HtcPowerSaver(  944): >> updateStatus
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): processMsg: DeviceActiveState
D/WifiController(  944): processMsg: StaEnabledState
D/WifiController(  944): processMsg: DefaultState
D/WifiController(  944): handleMessage: X
,D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1),
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(2c2a1eaa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1246831, Int=0,
V/AlarmManager(  944): sending alarm PendingIntent{3641be09: PendingIntentRecord{25dad80e android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1682516, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{21ebb794: PendingIntentRecord{13c4723d android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1825579, Int=1800000
V/AlarmManager(  944): sending alarm PendingIntent{4c30a9b: PendingIntentRecord{328ee38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1854100, Int=0
,V/AlarmManager(  944): sending alarm PendingIntent{852ae11: PendingIntentRecord{356b9384 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1448878635711, Int=0
V/AlarmManager(  944): sending alarm PendingIntent{2e637b76: PendingIntentRecord{33db577 com.google.android.gms broadcastIntent}}, i=null, t=3, cnt=1, w=1867040, Int=0
,I/ProcessStatsService(  944): Prepared write state in 28ms,
,D/PMS     (  944): acquireWL(3f9ab5e4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 944 1000 null
,D/WeatherUtility( 1222): Weather sync is On
D/PMS     (  944): releaseWL(3f9ab5e4): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,V/NetworkPolicy(  944): updateNetworkEnabledLocked()
V/NetworkPolicy(  944): updateNotificationsLocked()
,W/ContextImpl( 6061): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6061): MY_DEBUG = false
D/PMS     (  944): releaseWL(2c2a1eaa): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,D/PowerUsageService( 6061): repeat time = 1448879540321
,D/LocationManagerService(  944): getAllProviders()=[passive, gps, network]
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2: email,
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PowerUsageList:PowerUsageHelper( 6061): PowerProfile::POWER_SCREEN_FULL = 154.8
,D/PowerUsageList:BatterySipperExt( 6061): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6061): gen(), null == sipper.uidObj, userId = 0
,D/PowerUsageList:BatterySipperExt( 6061): gen(), null == sipper.uidObj, userId = 0
,I/ProcessStatsService(  944): Pruning old procstats: /data/system/procstats/state-2015-11-29-09-32-11.bin
,D/PowerUsageService( 6061): calcPower(), no data,
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1883): Explicit concurrent mark sweep GC freed 29502(1718KB) AllocSpace objects, 11(924KB) LOS objects, 49% free, 4MB/8MB, paused 1.234ms total 89.016ms
,I/GLSUser ( 1883): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1883): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1883): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1883): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1883): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1883): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173),
W/GLSActivity( 1883): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1883): 	,at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1883): 	at android.os.Binder.execTransact(Binder.java:454)
E/PlayEventLogger( 5681): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5681): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5681): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5681): 	at android.os.Binder.execTransact(Binder.java:454)
W/System  ( 5681): Ignoring header User-Agent because its value was null.
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 5681): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5681): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    ( 5681): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5681): [NET] android_getaddrinfo_proxy+
D/libc    ( 5681): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  399): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  399): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  399): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  399): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 5681): [NET] android_getaddrinfo_proxy-, NODATA
I/RemoteViews( 1222): reapply : com.google.android.gms 11 40
D/DotMatrix( 1306): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(10d33b57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 944 1000 null
I/BatteryService(  944): n_update end
D/PMS     (  944): releaseWL(10d33b57): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): closing low battery warning: level=100
D/DotMatrix( 1306): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PowerUI ( 1222): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1306): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 6218): Disconnected process message: 10, size: 0
D/NotificationService(  944): plugged=true pluggin=true
I/IntentController( 1222): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  944): BroadcastReceiver::onReceive+
D/UsbnetService(  944): onReceive BATTERY_CHANGED
D/UsbnetService(  944):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  944): updateBatteryInfo
D/UsbnetService(  944): BroadcastReceiver::onReceive-
D/WifiController(  944): handleMessage: E msg.what=155652
D/WifiController(  944): battery changed pluggedType: 2
D/WifiController(  944): processMsg: DeviceActiveState
D/PMS     (  944): runPSCheck
D/WifiController(  944): processMsg: StaEnabledState
D/HtcPowerSaver(  944): Checking...
D/WifiController(  944): processMsg: DefaultState
I/HtcPowerSaver(  944): >> updateStatus
,D/WifiController(  944): handleMessage: X
,I/HtcPowerSaver(  944): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  944): << updateStatus
,I/BatteryController( 1222): status:5 level:100 unsupport:false plugged:true
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,D/PMS     (  944): acquireWL(24ef644): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 944 1000 WorkSource{1000}
,V/AlarmManager(  944): sending alarm PendingIntent{1af93381: PendingIntentRecord{926c26 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1906831, Int=0
I/bt-btm  ( 6218): Received oneshot timer event complete
V/AlarmManager(  944): sending alarm PendingIntent{73fc32d: PendingIntentRecord{256c0062 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=1929364, Int=0
I/bt-btm  ( 6218): btm_ble_timeout
I/ActivityManager(  944): Killing 6117:com.htc.calendar/u0a10 (adj 13): empty for 1814s
,I/bt-btm  ( 6218): btm_gen_resolvable_private_addr
,D/PMS     (  944): acquireWL(4e635f3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6218 1002 null
D/Process (  944): killProcessQuiet, pid=6117
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,D/bt-btm  ( 6218): btm_ble_rand_enc_complete
I/bt-btm  ( 6218): btm_gen_resolve_paddr_low
D/bt-smp  ( 6218): smp_encrypt_data
W/bt-smp  ( 6218): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6218): Plain text(LSB ~ MSB) = d9 57 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6218): Encrypted text(LSB ~ MSB) = 03 be 3d be fb 6b fc 43 db 6a 3f e7 ff 9d 87 f9 
I/bt-btm  ( 6218): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6218): Stopping oneshot timer
D/bt-btm  ( 6218): Starting oneshot timer type:103 timeout:900s
,I/ActivityManager(  944): Recipient 6117
,D/Process (  944): killProcessQuiet, pid=6093
I/ActivityManager(  944): Killing 6093:com.htc.mobiledata/u0a46 (adj 13): empty for 1815s
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 6093
,D/Process (  944): killProcessQuiet, pid=6031
I/ActivityManager(  944): Killing 6031:com.htc.bgp/u0a11 (adj 15): empty for 1815s,
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 6031
,D/Process (  944): killProcessQuiet, pid=6008
I/ActivityManager(  944): Killing 6008:com.htc.mms.backupagent/u0a76 (adj 15): empty for 1821s
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.trimApplications:19127 
,I/ActivityManager(  944): Recipient 6008
,I/ActivityManager(  944): Killing 6258:com.htc.widget.hmsproc3/u0a34 (adj 13): empty for 1800s
D/Process (  944): killProcessQuiet, pid=6258
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  944): Recipient 6258
,D/Process (  944): killProcessQuiet, pid=5655
I/ActivityManager(  944): Killing 5655:com.android.settings/1000 (adj 13): empty for 1800s
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  944): Recipient 5655
D/WifiService(  944): Client connection lost with reason: 4
,I/ActivityManager(  944): Killing 6286:com.htc.widget.hmsproc2/u0a40 (adj 13): empty for 1800s
D/Process (  944): killProcessQuiet, pid=6286
,D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.BroadcastQueue.processNextBroadcast:706 ,
,I/ActivityManager(  944): Recipient 6286
,V/BluetoothSapService( 6218): onUnbind
,D/PMS     (  944): releaseWL(4e635f3): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
D/PMS     (  944): releaseWL(24ef644): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1222): Weather sync is On
,W/WeatherTimeKeeper( 1222): [refreshWeatherData] no weather data
,I/jxcore-log( 6164): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 6164): 
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 6505): Error opening trace file: Permission denied (13)
D/CustomizationManager( 6505): ====startRecUseTime====
D/htc.customization.log.level( 6505):  is 
W/CustomizationLogLevel( 6505): Level value is invalid, use default level 2
D/CustomizationManager( 6505):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6505): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6505): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6505): Parsing tag category name = system
I/CustomizationCIDLoader( 6505): Parsing tag category name = application
I/CustomizationCIDLoader( 6505): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6505): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6505): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6505): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6505): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6505): add string-array item, value = 42507
I/CustomizationCIDLoader( 6505): add string-array item, value = 21902
I/CustomizationCIDLoader( 6505): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6505): add string-array item, value = 23420
I/CustomizationCIDLoader( 6505): add string-array item, value = 22299
I/CustomizationCIDLoader( 6505): add string-array item, value = 24002
I/CustomizationCIDLoader( 6505): add string-array item, value = 23210
I/CustomizationCIDLoader( 6505): add string-array item, value = 23205
I/CustomizationCIDLoader( 6505): add string-array item, value = 23806
I/CustomizationCIDLoader( 6505): add string-array item, value = 23430
I/CustomizationCIDLoader( 6505): add string-array item, value = 23408
I/CustomizationCIDLoader( 6505): add string-array item, value = 27205
I/CustomizationCIDLoader( 6505): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6505): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6505):  Read CID file spent 0.123 (s)
D/CustomizationManager( 6505):  All configurations done spent 0.123 (s)
D/PackageManager(  944): deletePackageAsUser: pkg=com.test.thalitest, pid=6505, uid=2000 userid=0
I/ActivityManager(  944): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
D/Process (  944): killProcessQuiet, pid=6164
I/ActivityManager(  944): Killing 6164:com.test.thalitest/u0a366 (adj 0): stop com.test.thalitest
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.removeProcessLocked:6363 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:6161 
W/PackageSettings(  944): Skipping PackageSetting{3c4813a1 com.example.hello/10373} due to missing metadata
I/ActivityManager(  944): Recipient 6164
I/WindowState(  944): WIN DEATH: Window{42671bc u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  944): Client connection lost with reason: 4
E/InputEventReceiver( 1356): Looper::removeFd(68) is failed, result(0), input channel 'ClientState{21c6eda8 uid 10366 pid 6164} (c)'
I/ActivityManager(  944):   Force finishing activity ActivityRecord{1a168de1 u0 com.test.thalitest/.MainActivity t10}
I/ActivityManager(  944): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/ActivityManager(  944):   Force finishing activity ActivityRecord{1a168de1 u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  944): Duplicate finish request for ActivityRecord{1a168de1 u0 com.test.thalitest/.MainActivity t10 f}
W/ActivityManager(  944): Spurious death for ProcessRecord{276732b0 6164:com.test.thalitest/u0a366}, curProc for 6164: null
W/SystemReader(  944): Cannot find grip_rejection_width, use default value instead
D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/InputMethodManagerService(  944): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/DotMatrix( 1306): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1306): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/PMS     (  944): acquireWL(3684c9dc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1797 10024 WorkSource{10024 com.google.android.gms}
W/GeofencerStateMachine( 1797): Ignoring removeGeofence because network location is disabled.
D/PMS     (  944): releaseWL(3684c9dc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/AccTypeManager( 1678): Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
D/AccTypeManager( 1678): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 6410): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 6410): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/art     ( 1523): Explicit concurrent mark sweep GC freed 6738(378KB) AllocSpace objects, 12(980KB) LOS objects, 35% free, 29MB/45MB, paused 1.049ms total 115.068ms
I/Prism.ItemManager( 1523): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1523): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/ResourcesManager(  944): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/PhoneApp( 1470): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/Launcher( 1523): Deferring update until onResume
D/Launcher( 1523): waitUntilResume // bindAppsRemoved
D/AccTypeManager( 1678): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/VoicemailCleanupService( 1642): Cleaning up data for package: com.test.thalitest
D/Prism.PackageStateRece_( 1523): action: android.intent.action.PACKAGE_REMOVED
I/[PluginManager]RegisterService( 1437): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1437): handle notify Blinkfeed plugin client changed
I/ActivityManager(  944): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
E/ExternalAccountType( 1678): Unsupported attribute readOnly
I/art     (  944): Explicit concurrent mark sweep GC freed 35922(2MB) AllocSpace objects, 15(1276KB) LOS objects, 33% free, 16MB/24MB, paused 1.796ms total 251.925ms
I/art     (  944): WaitForGcToComplete blocked for 234.028ms for cause Explicit
D/StatusBarManagerService(  944): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
D/StatusBarManagerService(  944): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  944): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  944): hiding MENU key
D/FindExtension( 1523): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
I/ThreadedRenderer( 1523): Defer allocateBuffers to drawing time
W/ContextImpl( 6526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2712 
W/InputMethodManagerService(  944): Got RemoteException sending setActive(false) notification to pid 6164 uid 10366
D/StatusBarManagerService(  944): swetImeWindowStatus vis=0 backDisposition=0
I/ActivityManager(  944): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=6554 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
D/Process (  944): killProcessQuiet, pid=6348
I/ActivityManager(  944): Killing 6348:com.htc.android.mail:sync/u0a62 (adj 15): empty for 1807s
D/Process (  944): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18850 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
W/PackageManager(  944): Unable to load service info ResolveInfo{3fda631f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  944): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:475)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:331)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:160)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  944): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:169)
W/PackageManager(  944): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:950)
W/PackageManager(  944): 	at android.os.Handler.handleCallback(Handler.java:739)
W/PackageManager(  944): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  944): 	at android.os.Looper.loop(Looper.java:155)
W/PackageManager(  944): 	at com.android.server.SystemServer.run(SystemServer.java:324)
W/PackageManager(  944): 	at com.android.server.SystemServer.main(SystemServer.java:225)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager(  944): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
W/PackageManager(  944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
I/ActivityManager(  944): Recipient 6348
I/art     (  944): Explicit concurrent mark sweep GC freed 8080(449KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/24MB, paused 2.162ms total 271.724ms
W/asset   (  944): Copying FileAsset 0x55978554e0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/JobSchedulerService(  944): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  944): removeObsoleteFile: deleting file=10_task.xml
I/PhoneStatusBar( 1222): setImeWindowStatus(false,false)
D/Fingerprint/ HtcFingerPrintQuickLaunchProvider( 6554): -onCreate()
V/Settings:HtcSettingsApplication( 6554): [6554/6554] onCreate()
D/Settings:HtcWirelessFeatureFlags( 6554): id/is att sku: 118/false
E/NetworkScheduler.SchedulerReceiver( 1883): Invalid parameter app
D/PMS     (  944): acquireWL(15ccf739): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1883 10024 WorkSource{10024 com.google.android.gms}
E/NetworkScheduler.SchedulerReceiver( 1883): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/PMS     (  944): releaseWL(15ccf739): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
E/Settings:HtcWrapHeaderInfo( 6554): no such activity!
D/PackageBroadcastService( 4418): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4418): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4418): Module APK com.google.android.play.games already loaded
D/AccountUtils( 4418): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4418): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4418): Module APK com.google.android.play.games already loaded
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6554): The wrap header doesn't exist in header list.
I/ActivityManager(  944): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6589 uid=10101 gids={50101, 9997, 1028, 3003, 1015} abi=arm64-v8a
E/Settings:HtcWrapHeaderInfo( 6554): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 6554): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportRecentAppsButton]support         :false
I/LocationSettingsChecker( 4418): Removing dialog suppression flag for package com.test.thalitest
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]support         :false
D/GOOGLEHELP_CompatibleDatabase( 4418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4418): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 4418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  944): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6613 uid=10024 gids={50024, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=arm64-v8a
D/GOOGLEHELP_CompatibleDatabase( 4418): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 4418): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 4418): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 4418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 4418): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 6554): Failed to find provider info for com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6554): isSupportVoWifi: null
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 6554): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 6554): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 6554): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportRecentAppsButton]support         :false
D/PMS     (  944): acquireWL(307d20a9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4418 10024 null
I/ConfigService( 1883): onCreate
I/ConfigFetchService( 4418): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
D/PMS     (  944): releaseWL(307d20a9): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 6554): [supportHomeButton]support         :false
W/ResourcesManager( 6613): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6613): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  944): Cannot resolve ContentProvider=com.htc.vowifi
E/Settings:HtcVoWifiWidgetEnabler( 6554): isSupportVoWifi: null
E/ActivityThread( 6554): Failed to find provider info for com.htc.vowifi
W/BaseAppContext( 4418): Using Auth Proxy for data requests.
W/BaseAppContext( 4418): Using Auth Proxy for data requests.
I/MultiDex( 6613): VM with version 2.1.0 has multidex support
I/MultiDex( 6613): install
I/MultiDex( 6613): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6613): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/art     ( 4418): Suspending all threads took: 7.967ms
I/PeopleContactsSync( 4418): CP2 sync disabled
D/PMS     (  944): acquireWL(e294feb): PARTIAL_WAKE_LOCK  Icing 0x1 4418 10024 WorkSource{10024 com.google.android.gms}
I/PackageManager(  944):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4418, uid=10024, userID:0
I/Icing   ( 4418): doRemovePackageData com.test.thalitest
D/PMS     (  944): releaseWL(e294feb): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10024 com.google.android.gms}
W/ActivityThread( 6613): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6613): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30f2f48b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6613): Installed default security provider GmsCore_OpenSSL
W/DriveInitializer( 4418): Awaiting to be initialized
W/DriveInitializer( 4418): Background init thread started
E/SQLiteLog( 4418): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock112] disk I/O error
E/SQLiteDBG( 4418): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5597392480
I/GAv4    ( 6589): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6589):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6589):   adb logcat -s GAv4
E/DocListDatabase( 4418): Failed to delete from ContentFileDeletionLock112
E/DocListDatabase( 4418): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4418): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4418): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/DocListDatabase( 4418): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4418): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4418): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/DocListDatabase( 4418): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 4418): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/DocListDatabase( 4418): 	at com.google.android.gms.drive.r.run(SourceFile:69)
W/DriveInitializer( 4418): Background init thread ended
E/AndroidRuntime( 4418): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4418): Process: com.google.android.gms, PID: 4418
E/AndroidRuntime( 4418): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4418): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1577)
E/AndroidRuntime( 4418): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/AndroidRuntime( 4418): 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
E/AndroidRuntime( 4418): 	at com.google.android.gms.drive.r.run(SourceFile:69)
E/SQLiteLog( 4418): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 4418): func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5597392480
E/ActivityManager(  944): App crashed! Process: com.google.android.gms
E/DriveAsyncService( 4418): disk I/O error (code 3850)
E/DriveAsyncService( 4418): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4418): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4418): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
E/DriveAsyncService( 4418): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4418): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4418): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:548)
E/DriveAsyncService( 4418): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:459)
E/DriveAsyncService( 4418): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 4418): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 4418): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 4418): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 4418): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 4418): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4418): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4418): 	at java.lang.Thread.run(Thread.java:818)
D/Process ( 4418): killProcess, pid=4418
D/Process ( 4418): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.d.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
W/GAv4    ( 6589): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/DropBoxManagerService(  944): Can't write: system_app_crash
E/DropBoxManagerService(  944): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  944): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  944): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  944): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  944): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
E/DropBoxManagerService(  944): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  944): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12658)
E/DropBoxManagerService(  944): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  944): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  944): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  944): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  944): 	... 5 more
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6589): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 6589): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 6589): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.25.45
E/SQLiteDatabase( 6589): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6589): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6589): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6589): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6589): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6589): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6589): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 6589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6589): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 6589): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 6589): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6589): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6589): 	at gir$c.run(Unknown Source)
E/GAv4    ( 6589): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 6589): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 6589): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 6589): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6589): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6589): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6589): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6589): 	at aen.run(PG:536)
E/lowmemorykiller(  382): Error writing /proc/4418/oom_score_adj; errno=22
W/ActivityManager(  944): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
E/JavaBinder(  944): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  944): Recipient 4418
I/ActivityManager(  944): Process com.google.android.gms (pid 4418) has died
W/ActivityManager(  944): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10936ms
I/ConfigService( 1883): onDestroy
W/ActivityManager(  944): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10936ms
W/ActivityManager(  944): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10935ms
D/VoldConnector(  944): SND -> {23 volume mkdirs /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/}
E/Vold    (  384): Failed to find mounted volume for /storage/ext_sd/Android/data/com.google.android.apps.docs/cache/
W/ContextImpl( 6589): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  944): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6661 uid=10167 gids={50167, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 6589): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
E/SQLiteDatabase( 6589): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 6589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/SQLiteDatabase( 6589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/SQLiteDatabase( 6589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6589): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 6589): 	at ael.a(PG:1521)
E/SQLiteDatabase( 6589): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 6589): 	at aej.c(PG:139)
E/SQLiteDatabase( 6589): 	at aej.b(PG:398)
E/SQLiteDatabase( 6589): 	at agf.f(PG:417)
E/SQLiteDatabase( 6589): 	at oe.run(PG:1112)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6589): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 6589): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/AbstractDatabaseInstance( 6589): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 6589): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:854)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:834)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:737)
E/AbstractDatabaseInstance( 6589): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1280)
E/AbstractDatabaseInstance( 6589): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 6589): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 6589): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 6589): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 6589): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 6589): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 6589): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 6589): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 6589): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 6589): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 6589): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 6589): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 6589): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 6589): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 6661): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Prism.ItemManager( 6410): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 6410): loadItems() com.htc.launcher.pageview.WidgetManager@3e8f0397 +
I/Prism.WidgetManager( 6410): onLoadItems() +
V/JNIHelp ( 6589): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/Prism.ItemManager( 1523): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1523): loadItems() com.htc.launcher.pageview.WidgetManager@12b4e197 +
I/Prism.WidgetManager( 1523): onLoadItems() +
W/ResourcesManager( 6410): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/ResourcesManager( 1523): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
W/System  ( 6589): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm64, /vendor/lib64, /system/lib64]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6589): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1883): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SharedPreferencesImpl( 6589): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/google_apps_features_per_account_prefs.xml.bak
D/PMS     (  944): acquireWL(23a209db): PARTIAL_WAKE_LOCK  AsyncService 0x1 6661 10167 null
D/PMS     (  944): acquireWL(1dd5df51): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 6661 10167 null
D/PMS     (  944): releaseWL(23a209db): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/ResourcesManager( 1523): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  944): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6690 uid=10085 gids={50085, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=arm64-v8a
W/ResourcesManager( 6410): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/PMS     (  944): releaseWL(1dd5df51): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.PhotosAppTransitionService 0x1 null
W/asset   ( 1523): Copying FileAsset 0x55975fc5f0 (zip:/data/app/com.gameloft.android.gdc-2/base.apk:/resources.arsc) to buffer size 405676 to make it aligned.,

```
