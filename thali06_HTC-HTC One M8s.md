#### Test 506502784dae475_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
D/PMS     (  952): acquireWL(262d514e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 952 1000 null
I/BatteryService(  952): n_update end
D/PMS     (  952): releaseWL(262d514e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,--------- beginning of main
D/UsbnetService(  952): BroadcastReceiver::onReceive+
D/NotificationService(  952): plugged=true pluggin=true
D/UsbnetService(  952): onReceive BATTERY_CHANGED
D/WifiController(  952): battery changed pluggedType: 2
D/UsbnetService(  952):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  952): updateBatteryInfo
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/PMS     (  952): runPSCheck
D/WifiController(  952): handleMessage: E msg.what=155652
D/HtcPowerSaver(  952): Checking...
D/WifiController(  952): processMsg: ApStaDisabledState
I/HtcPowerSaver(  952): >> updateStatus
D/WifiController(  952): processMsg: DefaultState
D/PowerUI ( 1269): closing low battery warning: level=100
D/WifiController(  952): handleMessage: X
D/PowerUI ( 1269): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1354): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1354): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1354): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1269): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  952): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  952): << updateStatus
I/BatteryController( 1269): status:5 level:100 unsupport:false plugged:true
E/cutils-trace( 5935): Error opening trace file: Permission denied (13)
D/CustomizationManager( 5935): ====startRecUseTime====
D/htc.customization.log.level( 5935):  is 
W/CustomizationLogLevel( 5935): Level value is invalid, use default level 2
D/CustomizationManager( 5935):  Read ACC file spent 0.046 (s)
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__001
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__102
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__032
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__002
D/CIDMapFileReader( 5935): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 5935): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 5935): Parsing tag category name = system
I/CustomizationCIDLoader( 5935): Parsing tag category name = application
I/CustomizationCIDLoader( 5935): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 5935): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 5935): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 5935): Parsing tag category name = Settings
I/CustomizationCIDLoader( 5935): Parsing tag category name = ACC
I/CustomizationCIDLoader( 5935): add string-array item, value = 42507
I/CustomizationCIDLoader( 5935): add string-array item, value = 21902
I/CustomizationCIDLoader( 5935): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 5935): add string-array item, value = 23420
I/CustomizationCIDLoader( 5935): add string-array item, value = 22299
I/CustomizationCIDLoader( 5935): add string-array item, value = 24002
I/CustomizationCIDLoader( 5935): add string-array item, value = 23210
I/CustomizationCIDLoader( 5935): add string-array item, value = 23205
I/CustomizationCIDLoader( 5935): add string-array item, value = 23806
I/CustomizationCIDLoader( 5935): add string-array item, value = 23430
I/CustomizationCIDLoader( 5935): add string-array item, value = 23408
I/CustomizationCIDLoader( 5935): add string-array item, value = 27205
I/CustomizationCIDLoader( 5935): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 5935): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 5935):  Read CID file spent 0.094 (s)
D/CustomizationManager( 5935):  All configurations done spent 0.095 (s)
I/ActivityManager(  952): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 5935 on display 0
D/PMS     (  952): acquireHCC(65926f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 952 1000 null
D/PMS     (  952): acquireHCC(eb75b7c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 952 1000 null
W/asset   (  952): Copying FileAsset 0x55879b0b90 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/ActivityManager(  952): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5953 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ActivityManager(  952): Display changed displayId=0
D/DotMatrix( 1354): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1354): [EventService] mbHDMIConnect: false, mCoverOn:false
W/asset   ( 5953): Copying FileAsset 0xac22d218 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1571): [trimMemory] 20
I/WebViewFactory( 5953): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,I/LibraryLoader( 5953): Time to load native libraries: 9 ms (timestamps 980-989)
,I/LibraryLoader( 5953): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5953): Binding Chromium to main looper Looper (main, tid 1) {2e7b1124}
,I/LibraryLoader( 5953): Expected native library version number "",actual native library version number ""
,I/chromium( 5953): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5953): Initializing chromium process, singleProcess=true
,W/art     ( 5953): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5953): ApplicationContext is null in ApplicationStatus
,W/chromium( 5953): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5953): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5953): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5953): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5953): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 5953): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 5953): Build Date: 03/09/15 Mon
I/Adreno-EGL( 5953): Local Branch: 
I/Adreno-EGL( 5953): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 5953): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 5953):                  d74aa161a12b9c6fc6332151
,W/System.err(  952): java.lang.Throwable: stack dump
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  952): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  952): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  952): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  952): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@81e96bd:true
D/BluetoothAdapter( 5953): 53589587: getState() :  mService = null. Returning STATE_OFF
,I/art     (  952): Explicit concurrent mark sweep GC freed 28537(1583KB) AllocSpace objects, 4(620KB) LOS objects, 33% free, 16MB/24MB, paused 1.469ms total 127.473ms
,W/HtcSystemUPManager(  952): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
W/ActivityManager(  952): Activity pause timeout for ActivityRecord{1fd9ec05 u0 com.test.thalitest/.MainActivity t8}
,W/art     ( 5953): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 5953): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5953): CordovaWebView is running on device made by: HTC
,W/art     ( 5953): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5953): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 5953): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/StatusBarManagerService(  952): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  952): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  952): hiding MENU key
D/StatusBarManagerService(  952): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  952): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  952): hiding MENU key
,D/FindExtension( 5953): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/InputMethodManager( 5953): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@2cd2ad3e, mServedView=org.apache.cordova.engine.SystemWebView{270d79f VFEDH.C. .F....I. 0,0-0,0 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@fb870ec
,I/InputMethodManagerService(  952): Disable input method client, pid=1571
,I/PhoneStatusBar( 1269): setImeWindowStatus(false,false),
D/StatusBarManagerService(  952): swetImeWindowStatus vis=0 backDisposition=0
,W/IInputConnectionWrapper( 5953): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  952): Displayed com.test.thalitest/.MainActivity: +771ms (total +815ms),
,W/BindingManager( 5953): Cannot call determinedVisibility() - never saw a connection for the pid: 5953
,D/JsMessageQueue( 5953): Set native->JS mode to OnlineEventsBridgeMode,
,D/jxcore_app_log( 5953): JniHelper::setJavaVM(0xab0d38f8), pthread_self() = -1405062432
,D/JX-Cordova( 5953): jxcore cordova android initializing
,W/jxcore-log( 5953): Initializing JXcore engine
,W/jxcore-log( 5953): JXcore engine is ready
,W/jxcore-log( 5953): Starting JXcore engine
,D/PMS     (  952): releaseHCC(65926f): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  952): releaseHCC(eb75b7c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,W/jxcore-log( 5953): Platform android
W/jxcore-log( 5953): 
W/jxcore-log( 5953): Process ARCH arm
,W/jxcore-log( 5953): 
,I/jxcore-log( 5953): JXcore Cordova bridge is ready!,
I/jxcore-log( 5953): 
W/jxcore-log( 5953): JXcore engine is started
,I/chromium( 5953): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 5953): Toggling radios to true,
I/jxcore-log( 5953): 
,D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  952): checking for enable restriction...
D/BluetoothManagerService(  952): checkBTEasState, ret=true
I/BluetoothManagerService(  952): isBluetoothRestricted(): false
D/BluetoothManagerService(  952): enable(): region ID = 6
D/BluetoothManagerService(  952): enable():  mBluetooth =null mBinding = false
W/Settings:Agent(  952): MONITOR_LOG,
W/Settings:Agent(  952): name: bluetooth_on
W/Settings:Agent(  952): value: 1
W/Settings:Agent(  952): >> traceCallingStack()
W/Settings:Agent(  952): Process.myPid(): 952
W/Settings:Agent(  952): Process.myTid(): 1759
W/Settings:Agent(  952): Process.myUid(): 1000
W/Settings:Agent(  952): 
W/Settings:Agent(  952): 
W/System.err(  952): java.lang.Throwable: stack dump
,W/System.err(  952): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  952): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  952): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
,W/System.err(  952): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  952): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  952): 	at android.provider.Settings$Global.putInt(Settings.java:7503),
W/System.err(  952): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:378)
W/System.err(  952): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:598)
,W/System.err(  952): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  952): 
W/Settings:Agent(  952): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  952): Message: MESSAGE_ENABLE
D/BluetoothManagerService(  952): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  952): New client listening to asynchronous messages
E/WifiTrafficPoller(  952): ADD_CLIENT: 7
,D/WifiManager( 5953): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10366
,W/Settings:Agent(  952): MONITOR_LOG
,D/WifiService(  952): setWifiEnabled: true pid=5953, uid=10366
W/Settings:Agent(  952): name: wifi_on
E/WifiService(  952): Invoking mWifiStateMachine.setWifiEnabled,
W/Settings:Agent(  952): value: 2
I/WifiService(  952): isSprintWifiRestricted(): false
W/Settings:Agent(  952): >> traceCallingStack()
I/WifiService(  952): isMdmWifiRestricted(): false
W/Settings:Agent(  952): Process.myPid(): 952
W/Settings:Agent(  952): Process.myTid(): 1765,
W/Settings:Agent(  952): Process.myUid(): 1000
W/Settings:Agent(  952): 
W/Settings:Agent(  952): 
W/System.err(  952): java.lang.Throwable: stack dump
,W/System.err(  952): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  952): 	at android.provider.HtcISettings$Agent.traceCallingStack(HtcISettings.java:56)
W/System.err(  952): 	at android.provider.HtcISettingsGlobal$Agent.monitorKey(HtcISettingsGlobal.java:64)
W/System.err(  952): 	at android.provider.Settings$Global.putStringForUser(Settings.java:7422)
W/System.err(  952): 	at android.provider.Settings$Global.putString(Settings.java:7403)
W/System.err(  952): 	at android.provider.Settings$Global.putInt(Settings.java:7503)
W/System.err(  952): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:154)
W/System.err(  952): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:103)
W/System.err(  952): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:1144)
,W/System.err(  952): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:222)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
W/Settings:Agent(  952): 
W/Settings:Agent(  952): << traceCallingStack(): 11(ms)
,I/ActivityManager(  952): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6009 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 1023, 3005, 1016, 3008} abi=armeabi-v7a,
,D/WifiController(  952): handleMessage: E msg.what=155656
D/WifiController(  952): processMsg: ApStaDisabledState
D/WifiController(  952): transitionTo: destState=DeviceActiveState,
D/PMS     (  952): acquireWL(391605c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 952 1000 null
D/WifiController(  952): handleMessage: new destination call exit/enter
D/WifiController(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiController(  952): invokeExitMethods: ApStaDisabledState
D/WifiController(  952): moveTempStackToStateStack: i=1,j=1
D/WifiController(  952): moveTempStackToStateStack: i=0,j=2
D/WifiController(  952): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DeviceActiveState
D/WifiManager( 5953): disconnect: Base Package Name=com.test.thalitest, uid=10366
D/WifiController(  952): invokeEnterMethods: StaEnabledState
D/WifiController(  952): invokeEnterMethods: DeviceActiveState
E/WifiStateMachine(  952): handleMessage: E msg.what=131083
E/WifiStateMachine(  952): setting operational mode to 1
E/WifiStateMachine(  952): processMsg: InitialState
D/WifiController(  952): handleMessage: X
E/WifiStateMachine(  952):  InitialState CMD_START_SUPPLICANT 0 0
D/WifiManager( 5953): reconnect: Base Package Name=com.test.thalitest, uid=10366
I/jxcore-log( 5953): Radios toggled
I/jxcore-log( 5953): 
,W/ResourcesManager( 6009): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
,D/AdapterServiceConfig( 6009): Adding HeadsetService,
,D/AdapterServiceConfig( 6009): Adding A2dpService,
D/AdapterServiceConfig( 6009): Adding HidService
D/AdapterServiceConfig( 6009): Adding HealthService,
D/AdapterServiceConfig( 6009): Adding PanService
D/AdapterServiceConfig( 6009): Adding GattService
,W/linker  ( 6009): libbt-aptx-4.1.1.so has text relocations. This is wasting memory and prevents security hardening. Please fix.,
,W/System.err(  952): java.lang.Throwable: stack dump,
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  952): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27d1e47:true
,W/System.err(  952): ,	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  952): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  952): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothAdapterState( 6009): make
I/BluetoothAdapterState( 6009): Entering OffState
,E/bt_osi_config( 6009): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
D/BluetoothAdapterProperties( 6009): Address is:90:E7:C4:F6:69:77
,D/BluetoothManagerService(  952): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  952): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  952): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  952): Calling onBluetoothServiceUp callbacks,
D/BluetoothManagerService(  952): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapter( 1540): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@2b2bfd84
D/BluetoothAdapter( 1540): onBluetoothServiceUp done
,D/BluetoothAdapter( 1844): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@5f55efe
D/BluetoothAdapter( 1844): onBluetoothServiceUp done
,D/BluetoothAdapter( 1510): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@24256c95,
D/BluetoothAdapter( 1510): onBluetoothServiceUp done
D/BluetoothAdapter(  952): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@a6357e3
D/BluetoothAdapter(  952): onBluetoothServiceUp done
D/BluetoothAdapter( 3551): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1de4da43
D/BluetoothAdapter( 3551): onBluetoothServiceUp done
D/BluetoothAdapter( 1269): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@817af3f
D/BluetoothAdapter( 1269): onBluetoothServiceUp done
,D/BluetoothAdapter( 5953): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@247eb9c3
D/BluetoothAdapter( 5953): onBluetoothServiceUp done
,D/BluetoothAdapter( 2437): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@1d07911d
D/BluetoothAdapter( 2437): onBluetoothServiceUp done
,D/BluetoothAdapter( 6009): onBluetoothServiceUp: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@1173cc89
D/BluetoothAdapter( 6009): onBluetoothServiceUp done
D/BluetoothManagerService(  952): Broadcasting onBluetoothServiceUp() done
,D/BluetoothAdapterState( 6009): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 6009): Setting state to 11
,I/BluetoothAdapterState( 6009): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  952): +onBluetoothStateChange prev=10 new=11
D/BluetoothManagerService(  952): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  952): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  952): Bluetooth State Change Intent: 10 -> 11
I/IntentController( 1269): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/BluetoothBondStateMachine( 6009): make
,V/BluetoothPbapReceiver( 6009): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 6009): ***********state = 11
D/BluetoothAdapterService( 6009): checkA2dpState: isA2dpSinkEnabled = false
E/BluetoothAdapterService( 6009): checkA2dpState: returning
D/BluetoothAdapterService( 6009): checkHfpState: isHfpClientEnabled = false
E/BluetoothAdapterService( 6009): checkHfpState: returning
I/BluetoothBondStateMachine( 6009): StableState(): Entering Off State
,D/PMS     (  952): releaseWL(391605c8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null,
,D/NGFService( 3551): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
,D/Tethering(  952): interfaceAdded wlan0,
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
,V/Tethering(  952): TetherInterfaceSM: wlan0: enter InitialState
,D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  952): interfaceAdded p2p0
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
,E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  952): p2p0 is not a tetherable iface, ignoring
D/Tethering(  952): interfaceLinkStateChanged p2p0, false
D/Tethering(  952): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
I/BluetoothAdapterState( 6009): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/Tethering(  952): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering(  952): TetherInterfaceSM: wlan0: InitialState processMessage what=CMD_INTERFACE_DOWN
V/Tethering(  952): TetherInterfaceSM: wlan0: exit InitialState
D/PMS     (  952): acquireWL(ac9ffd3): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
V/Tethering(  952): TetherInterfaceSM: wlan0: enter UnavailableState
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  952): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  952): setWifiState: enabling
D/UsbnetService(  952): BroadcastReceiver::onReceive+
E/WifiStateMachine(  952): Supplicant start successful
D/WifiMonitor(  952): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  952): connecting to supplicant
D/BluetoothHeadset( 1510): Proxy object connected
D/BluetoothHeadset( 1269): Proxy object connected
D/HeadsetService( 6009): Received start request. Starting profile...
D/PMS     (  952): releaseWL(ac9ffd3): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/HeadsetStateMachine( 6009): Version 1.5
V/NetworkPolicy(  952): updateNetworkEnabledLocked()
D/HeadsetStateMachine( 6009): make
V/NetworkPolicy(  952): updateNotificationsLocked()
I/IntentController( 1269): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/PMS     (  952): acquireWL(14266710): PARTIAL_WAKE_LOCK  NetworkStats 0x1 952 1000 null
,D/TetherSettings( 5426): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5426): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5426): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5426): Cust_ConnectToPC   : spcsc>false
D/        ( 5426): Cust_ConnectToPC   : IPT>true
D/        ( 5426): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 5426): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5426): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5426): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 5426): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
,E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
,W/ContextImpl( 5426): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
,D/UsbDeviceManager(  952): [USBNET] bCheckSuppFunc: cdc_network
,D/UsbnetService(  952): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/UsbnetService(  952): BroadcastReceiver::onReceive+
D/UsbDeviceManager(  952): [USBNET] bCheckSuppFunc: cdc_network
D/UsbnetService(  952): ACTION_TETHER_STATE_CHANGED: active=[],USB_FUNCTION_NCM=false
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/BluetoothHeadset(  952): Proxy object connected
,I/ActivityManager(  952): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=6045 uid=10034 gids={50034, 9997, 3002, 3001} abi=arm64-v8a
D/BluetoothPhoneService( 1510): BluetoothHeadset onServiceConnected
D/BluetoothHeadset( 1510): Proxy object connected
D/BluetoothHeadset( 1510): Proxy object connected
D/PMS     (  952): releaseWL(14266710): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,V/NetworkPolicy(  952): updateNetworkEnabledLocked()
I/SmartNS_Utility( 5426): setISNotification
V/NetworkPolicy(  952): updateNotificationsLocked()
,D/HeadsetStateMachine( 6009): max_hf_connections = 2
,D/BluetoothAdapter(  952): 489133643: getState(). Returning 11,
,D/SmartNS_Utility( 5426): usb_cable_connect = 1
D/SmartNS_Utility( 5426): usb_denied = 0
,I/SmartNS_PSService( 5426): usb notificaiton:true
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
I/QuickSettingMiniLite( 1269): btListener.connect:HEADSET/android.bluetooth.BluetoothHeadset@3335000c
D/WIFI_ICON( 1269): updateWifiState: WIFI_STATE_CHANGED disabled
D/HeadsetPhoneState( 6009): listenForPhoneState..for service and signal 
D/StatusBar.NetworkController( 1269): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/BluetoothAdapter( 1510): 181485979: getState(). Returning 11
,D/HeadsetDualPhoneStateListener_SLOT1( 6009): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6009): listen phone state by slot:SLOT2  id:-100
,D/HeadsetStateMachine( 6009): Enter Disconnected: -2, size: 0
,D/HeadsetDualPhoneStateListener_SLOT1( 6009): listen phone state by slot:SLOT1  id:-1
,D/HeadsetDualPhoneStateListener_SLOT2( 6009): listen phone state by slot:SLOT2  id:-100,
I/HeadsetStateMachine( 6009): setCurrentDevice, the latest mCurrentDevice is:null
D/bt-btif ( 6009): BTHF: set_current_device
,D/BluetoothAdapterService( 6009): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f77748d
I/QuickSettingBluetooth( 1269): receive.ACTION_STATE_CHANGE:STATE_TURNING_ON
,D/BluetoothA2dp(  952): Proxy object connected
D/A2dpService( 6009): Received start request. Starting profile...
V/Avrcp   ( 6009): make
I/QuickSettingWifi( 1269): receive.wifiState:WIFI_STATE_ENABLING setEnable:false
D/BluetoothAdapter(  952): 489133643: getState(). Returning 11
I/ActionCombine( 5426): replace[setMax, setProgress, setTextSize, setTextColor, setVisibility, setImageLevel, setX, setY, setAlpha, setScaleX, setScaleY, setRotation, setRotationX, setRotationY, setElevation, setTranslationX, setTranslationY, setBase, setTime, setEnabled, setStarted, setAllCaps, setClickable, setFocusable, setIndeterminate, setText, setContentDescription, setFormat, setViewPaddingInternal, setTextViewTextSizeInternal, setTextViewCompoundDrawablesInternal, setTextViewCompoundDrawablesRelativeInternal]
,D/SmartNS_Utility( 5426): usb_cable_connect = 1
D/HtcBtWidget_BTWidgetProvider( 6045): onBTStateChanged() for widget: 
,D/SmartNS_Utility( 5426): usb_denied = 0
I/ActivityManager(  952): Killing 5696:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/HtcBtWidget_BTWidgetProvider( 6045): updateWidget(context) for widget: 
I/SmartNS_PSService( 5426): usb notificaiton:true
D/Process (  952): killProcessQuiet, pid=5696
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:237 
,D/wpa_supplicant( 6043): wpa_supplicant v2.3-devel-5.0.2
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/wpa_supplicant( 6043): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6043): random: Trying to read entropy from /dev/random
E/RemoteController( 6009): Cannot set synchronization mode on an unregistered RemoteController
D/wpa_supplicant( 6043): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6043): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 6043): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 6043): Successfully initialized wpa_supplicant
D/wpa_supplicant( 6043): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6043): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6043): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/A2dpStateMachine( 6009): make
D/wpa_supplicant( 6043): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6043): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6043): update_config=1
D/wpa_supplicant( 6043): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6043): device_name='Android_608e'
D/wpa_supplicant( 6043): manufacturer='HTC'
D/wpa_supplicant( 6043): model_name='HTC_PHONE'
D/wpa_supplicant( 6043): model_number='1234'
D/wpa_supplicant( 6043): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6043): p2p_oper_reg_class=126
D/wpa_supplicant( 6043): p2p_oper_channel=149
D/wpa_supplicant( 6043): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6043): persistent_reconnect=1
D/wpa_supplicant( 6043): key_mgmt_offload=1
D/bt-btif ( 6009): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/wpa_supplicant( 6043): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6043): nl80211: RFKILL status not available
D/DotMatrix( 1354): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/wpa_supplicant( 6043): nl80211: Using driver-based roaming
D/wpa_supplicant( 6043): nl80211: TDLS supported
D/wpa_supplicant( 6043): nl80211: TDLS external setup
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6043): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supp,licant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported ke,y derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/A2dpService( 6009): setA2dpService(): set to: null
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/BluetoothAdapterService( 6009): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f77748d
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
I/RemoteViews( 1269): reapply : com.android.settings 1 36
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6043): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6043): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6043): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 6043): nl80211: Set mode ifindex 30 iftype 2 (STATION)
D/wpa_supplicant( 6043): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a500dfd0
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=0104
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=040a
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=040b
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=040c
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=040d
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=090a
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=090b
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=090c
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=090d
D/A2dpStateMachine( 6009): Enter Disconnected: -2
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=0409506f9a09
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=7f506f9a09
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=0801
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=040e
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=06
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=0a07
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=0a11
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a500dfd0 match=0a1a
D/wpa_supplicant( 6043): netlink: Operstate: ifindex=30 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6043): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 6043): Add interface p2p0 to a new radio phy0
I/wpa_supplicant( 6043): htc_wext_command_init +
E/wpa_supplicant( 6043): htc_wext_command_init: ifname=p2p0, ignore
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6043): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
D/Tethering(  952): interfaceLinkStateChanged p2p0, false
D/Tethering(  952): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/Tethering(  952): interfaceLinkStateChanged p2p0, false
D/Tethering(  952): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/HidService( 6009): Received start request. Starting profile...
D/BluetoothAdapterService( 6009): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f77748d
D/HealthService( 6009): Received start request. Starting profile...
D/BluetoothAdapterService( 6009): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f77748d
D/PanService( 6009): Received start request. Starting profile...
D/PanService( 6009): HTC_CUSTOMIZATION_MHS_ENABLE = false
D/BluetoothAdapterService( 6009): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f77748d
D/BtGatt.DebugUtils( 6009): handleDebugAction() action=null
D/BtGatt.GattService( 6009): Received start request. Starting profile...
D/BtGatt.GattService( 6009): start()
D/BtGatt.AdvertiseManager( 6009): advertise manager created
,D/BluetoothAdapter( 1269): 14047888: getState(). Returning 11
I/QuickSettingMiniLite( 1269): updateLiteState:no connect device!
,I/ActivityManager(  952): Recipient 5696,
,D/BluetoothAdapterService( 6009): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f77748d
,D/SmartNS_NSReceiver( 5426): Tethered state change:false isNSOpening:false
,I/HeadsetPhoneState( 6009): updateServiceState service = 0,roam = 0
D/HeadsetPhoneState( 6009): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 6009): Disconnected process message: 11, size: 0
D/DotMatrix( 1354): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
D/TetherSettings( 5426): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 5426): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 5426): Cust_ConnectToPC   : Modem_Link>false
D/        ( 5426): Cust_ConnectToPC   : spcsc>false
D/        ( 5426): Cust_ConnectToPC   : IPT>true
D/        ( 5426): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 5426): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 5426): hasRemovableStorageSlot: true
D/SmartNS_Utility( 5426): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 5426): onReceive : android.net.conn.TETHER_STATE_CHANGED hasTethered:false isNSOpening:false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
D/HeadsetStateMachine( 6009): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 6009): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6009): Disconnected process message: 11, size: 0
D/BluetoothAdapter( 1510): 181485979: getState(). Returning 11
W/BluetoothHeadset( 1510): Proxy not attached to service
I/RemoteViews( 1269): reapply : com.android.settings 3 36
D/BluetoothAdapterState( 6009): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
W/ContextImpl( 5426): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:432 android.app.ActivityThread.handleReceiver:2712 
I/wpa_supplicant( 6043): wapi_supplicant_init: Init WAI packet p2p0
D/wpa_supplicant( 6043):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6043):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6043):  Initialization: WAPI:set Staues=1 
I/bt-btu  ( 6009): btu_task pending for preload complete event
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=30 (p2p0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6043): nl80211: Flush PMKIDs
I/SmartNS_Utility( 5426): setISNotification
D/wpa_supplicant( 6043): p2p0: State: DISCONNECTED -> INACTIVE
D/SmartNS_Utility( 5426): usb_cable_connect = 1
D/BluetoothHeadset( 1510): java.lang.Throwable
,D/BluetoothHeadset( 1510): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:827)
D/BluetoothHeadset( 1510): 	at com.android.phone.BluetoothPhoneService.handleQueryPhoneState(BluetoothPhoneService.java:663)
D/BluetoothHeadset( 1510): 	at com.android.phone.BluetoothPhoneService.access$500(BluetoothPhoneService.java:79)
D/BluetoothHeadset( 1510): 	at com.android.phone.BluetoothPhoneService$1.handleMessage(BluetoothPhoneService.java:277)
D/BluetoothHeadset( 1510): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1510): 	at android.os.Looper.loop(Looper.java:155)
D/BluetoothHeadset( 1510): 	at android.app.ActivityThread.main(ActivityThread.java:5721)
D/BluetoothHeadset( 1510): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1510): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
D/BluetoothHeadset( 1510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
D/SmartNS_Utility( 5426): usb_denied = 0
,I/SmartNS_PSService( 5426): usb notificaiton:true
E/bt_vendor( 6009): get_bt_soc_type: Failed to get soc type
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
,D/SmartNS_Utility( 5426): usb_cable_connect = 1
D/SmartNS_Utility( 5426): usb_denied = 0
I/SmartNS_PSService( 5426): usb notificaiton:true
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false,
D/BluetoothMasReceiver( 6009): Bluetooth STATE CHANGED to 11
,D/DotMatrix( 1354): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false,
I/RemoteViews( 1269): reapply : com.android.settings 2 36
,D/SmartNS_NSReceiver( 5426): Tethered state change:false isNSOpening:false
V/BluetoothSapReceiver( 6009): SapReceiver onReceive 
V/BluetoothSapReceiver( 6009): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6009):  Bluetooth Adapter state = 11
V/BluetoothSapReceiver( 6009): startService = false
,D/DotMatrix( 1354): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837808, tag: null, isClearable: false
,I/qcom-bluetooth( 6079): /system/etc/init.qcom.bt.bluedroid.sh: init.qcom.bt.bluedroid.sh config =  
,I/RemoteViews( 1269): reapply : com.android.settings 1 36
,I/ActivityManager(  952): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.htchotspotwidget/.HotspotReceiver: pid=6081 uid=10040 gids={50040, 9997, 3002, 3001, 3003} abi=arm64-v8a,
,D/AuthorizationBluetoothService( 1932): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,D/wpa_supplicant( 6043): TDLS: TDLS operation supported by driver
,D/wpa_supplicant( 6043): TDLS: Driver uses external link setup
D/wpa_supplicant( 6043): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/wpa_supplicant( 6043): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 6043): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 6043): nl80211: Skip set_supp_port(unauthorized) while not associated
D/wpa_supplicant( 6043): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6043): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6043): EAP: EAP entering state DISABLED
D/wpa_supplicant( 6043): Using existing control interface directory.,
D/wpa_supplicant( 6043): P2P: Add operating class 81
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6043): P2P: Own listen channel: 81:6
D/wpa_supplicant( 6043): P2P: Configured operating channel: 126:149
D/wpa_supplicant( 6043): P2P: initialized
,D/wpa_supplicant( 6043): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6043): P2P: cli_channels:
D/wpa_supplicant( 6043): p2p0: Added interface p2p0
D/wpa_supplicant( 6043): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 6043): nl80211: Set p2p0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6043): netlink: Operstate: ifindex=30 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6043): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface 'N/A' bridge 'N/A'
D/wpa_supplicant( 6043): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6043): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6043): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 6043): disable_scan_offload=1
D/wpa_supplicant( 6043): driver_param='use_p2p_group_interface=1'
D/wpa_supplicant( 6043): update_config=1
D/wpa_supplicant( 6043): uuid=12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6043): device_name='m8qlul_htc_europe'
D/wpa_supplicant( 6043): manufacturer='HTC'
D/wpa_supplicant( 6043): model_name='HTC One M8s'
D/wpa_supplicant( 6043): model_number='HTC One M8s'
D/wpa_supplicant( 6043): config_methods='physical_display virtual_push_button'
D/wpa_supplicant( 6043): hs20=1
D/wpa_supplicant( 6043): interworking=1
D/wpa_supplicant( 6043): external_sim=1
D/wpa_supplicant( 6043): key_mgmt_offload=1
,I/qcom-bluetooth( 6105): /system/etc/init.qcom.bt.bluedroid.sh: Transport : smd ,
,D/wpa_supplicant( 6043): Priority group 280
D/wpa_supplicant( 6043):    id=0 ssid='NG700'
I/wpa_supplicant( 6043): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 6043): nl80211: RFKILL status not available
D/wpa_supplicant( 6043): nl80211: Using driver-based roaming
D/wpa_supplicant( 6043): nl80211: TDLS supported,
D/wpa_supplicant( 6043): nl80211: TDLS external setup
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:1
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:5
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:2
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:4
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-14-72:1
D/wpa_supplicant( 6043): nl80211: Supported cipher 00-0f-ac:6
D/wpa_supplicant( 6043): nl80211: Supports Probe Response offload in AP mode
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
,D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Su,pported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=9
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=22
,D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=34
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=35
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=36
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=38
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=40
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=39
D/wpa_supplicant( 6043): nl80211: Supported vendor command: vendor_id=0x1374 subcmd=42
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=10
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=14
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=15
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=16
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=17
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=18
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=19
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=20
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=21
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=23
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=24
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=25
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=26
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=27
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=28
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=29
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=30
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=31
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=32
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=33
D/wpa_supplicant( 6043): nl80211: Supported vendor event: vendor_id=0x1374 subcmd=37
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key managment offloads 0x0
D/wpa_supplicant( 6043): nl80211: Supported key derivation offloads 0x0
D/wpa_supplicant( 6043): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 6043): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 6043): nl80211: Disable use_monitor with device_ap_sme since no monitor mode support detected
D/wpa_supplicant( 6043): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 6043): nl80211: Set mode ifindex 29 iftype 2 (STATION)
D/wpa_supplicant( 6043): nl80211: Subscribe to mgmt frames with non-AP handle 0x55a502d100
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=0104
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=040a
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_hand,le=0x55a502d100 match=040b
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=040c
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=040d
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=090a
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=090b
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=090c
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=090d
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=0409506f9a09
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=7f506f9a09
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=0801
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=040e
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=06
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=0a07
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=0a11
D/wpa_supplicant( 6043): nl80211: Register frame type=0xd0 (WLAN_FC_STYPE_ACTION) nl_handle=0x55a502d100 match=0a1a
D/wpa_supplicant( 6043): netlink: Operstate: ifindex=29 linkmode=1 (userspace-control), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6043): nl80211: driver param='use_p2p_group_interface=1'
D/wpa_supplicant( 6043): nl80211: Use separate P2P group interface
D/wpa_supplicant( 6043): Add interface wlan0 to existing radio phy0
I/wpa_supplicant( 6043): htc_wext_command_init +
I/wpa_supplicant( 6043): htc_wext_command_init -
I/wpa_supplicant( 6043): [InternalDB] it needs to set 00 when we turn on Wifi : COUNTRY 00
I/wpa_supplicant( 6043): Don't set 00 to countryID.conf
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd COUNTRY 00 len = 0, 4096
D/wpa_supplicant( 6043): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6043): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=00
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6043): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 6043): nl80211: 57240-63720 @ 2160 MHz 0 mBm
I/qcom-bluetooth( 6106): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6043): P2P: Add operating class 81
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=11): 01 02 03 04 05 06 07 08 09 0a 0b
D/wpa_supplicant( 6043): P2P: Update channel list
D/wpa_supplicant( 6043): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11
D/wpa_supplicant( 6043): P2P: cli_channels:
D/wpa_supplicant( 6043): p2p0: Updating hw mode
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6043): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
,D/wpa_supplicant( 6043): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=00
D/wpa_supplicant( 6043): nl80211: 2402-2472 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 2457-2482 @ 40 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 2474-2494 @ 20 MHz 20 mBm (no OFDM) (no IR)
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 5735-5835 @ 80 MHz 20 mBm (no IR)
D/wpa_supplicant( 6043): nl80211: 57240-63720 @ 2160 MHz 0 mBm
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  952): interfaceLinkStateChanged wlan0, false
D/Tethering(  952): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
I/qcom-bluetooth( 6110): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 6111): /system/etc/init.qcom.bt.bluedroid.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 6112): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 3,
I/qcom-bluetooth( 6113): /system/etc/init.qcom.bt.bluedroid.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,D/HtcWiFiWidget_WiFiWidgetProvider( 6081): onWiFiStateChanged() for widget: ,
,D/HtcWiFiWidget_WiFiWidgetProvider( 6081): updateWidget(context) for widget: ,
,D/Process (  952): killProcessQuiet, pid=5718
I/ActivityManager(  952): Killing 5718:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,I/ActivityManager(  952): Recipient 5718
,I/wpa_supplicant( 6043): wapi_supplicant_init: Init WAI packet wlan0
,D/wpa_supplicant( 6043):  TE_WAPI_ASUE_Init: WAPI: ASUE INIT 
D/wpa_supplicant( 6043):  Initialization: WAPI: Initializing WAPI Supplicant
E/wpa_supplicant( 6043):  Initialization: WAPI:set Staues=1 
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=4 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wpa_driver_nl80211_set_key: ifindex=29 (wlan0) alg=0 addr=0x0 key_idx=5 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 6043): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 6043): nl80211: Flush PMKIDs
,I/qcom-bluetooth( 6116): /system/etc/init.qcom.bt.bluedroid.sh: = Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 90:e7:c4:f6:69:77 ,
,I/qcom-bluetooth( 6117): /system/etc/init.qcom.bt.bluedroid.sh: ** Bluedroid stack ** 
,I/bt-btu  ( 6009): btu_task received preload complete event,
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x0001
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x001f
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x0003
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x1487
,D/bt-btm  ( 6009): btm_acl_device_down
D/PMS     (  952): acquireWL(d55d46c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 6009 1002 null
D/bt-btm  ( 6009): btm_acl_reset_paging
D/bt-btm  ( 6009): btm_acl_set_discing
,D/wpa_supplicant( 6043): TDLS: TDLS operation supported by driver,
,D/wpa_supplicant( 6043): TDLS: Driver uses external link setup
,D/wpa_supplicant( 6043): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6043): EAPOL: SUPP_PAE entering state DISCONNECTED,
D/wpa_supplicant( 6043): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 6043): nl80211: Skip set_supp_port(unauthorized) while not associated
,D/wpa_supplicant( 6043): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 6043): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 6043): EAP: EAP entering state DISABLED
,D/wpa_supplicant( 6043): Using existing control interface directory.
,I/wpa_supplicant( 6043): set country (DE) from /data/misc/wifi/countryID.conf
I/wpa_supplicant( 6043): Initial scan channel cmd: COUNTRY DE
I/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd:156 set country (DE) in /data/misc/wifi/countryID.conf
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd COUNTRY DE len = 0, 4096
D/wpa_supplicant( 6043): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6043): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6043): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6043): P2P: Add operating class 81
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6043): P2P: Add operating class 115
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6043): P2P: Add operating class 116
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6043): P2P: Add operating class 117
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=2): 28 30
D/wpa_supplicant( 6043): P2P: Update channel list
D/wpa_supplicant( 6043): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6043): P2P: cli_channels:
D/wpa_supplicant( 6043): p2p0: Updating hw mode
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6043): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
I/wpa_supplicant( 6043): Auto country group 1: ch36
D/wpa_supplicant( 6043): wlan0: Added interface wlan0
D/wpa_supplicant( 6043): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 6043): nl80211: Set wlan0 operstate 0->0 (DORMANT)
D/wpa_supplicant( 6043): netlink: Operstate: ifindex=29 linkmode=-1 (no change), operstate=5 (IF_OPER_DORMANT)
D/wpa_supplicant( 6043): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 6043): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 6043): CTRL_IFACE monitor attached /data/misc/wifi/sockets/wpa_ctrl_952-2\x00
D/wpa_supplicant( 6043): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=0 linkmode=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 6043): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=5 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6043): RTM_NEWLINK: ifi_index=29 ifname=wlan0 operstate=2 linkmode=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 6043): nl80211: Drv Event 36 (NL80211_CMD_REG_CHANGE) received for wlan0
D/wpa_supplicant( 6043): nl80211: Regulatory domain change
D/wpa_supplicant( 6043):  * initiator=1
D/wpa_supplicant( 6043):  * type=0
D/wpa_supplicant( 6043):  * alpha2=DE
D/wpa_supplicant( 6043): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6043): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6043): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
,D/wpa_supplicant( 6043): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
E/WifiStateMachine(  952): transitionTo: destState=SupplicantStartingState
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 6043): P2P: Add operating class 81
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/wpa_supplicant( 6043): P2P: Add operating class 115
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=4): 24 28 2c 30
E/WifiStateMachine(  952): invokeExitMethods: InitialState
D/wpa_supplicant( 6043): P2P: Add operating class 116
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=2): 24 2c
,E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=1
D/wpa_supplicant( 6043): P2P: Add operating class 117
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=2): 28 30
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
E/WifiStateMachine(  952): invokeEnterMethods: SupplicantStartingState
D/wpa_supplicant( 6043): P2P: Update channel list
E/WifiStateMachine(  952): handleMessage: X
D/wpa_supplicant( 6043): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
,D/wpa_supplicant( 6043): P2P: cli_channels:
E/WifiStateMachine(  952): handleMessage: E msg.what=131144
D/wpa_supplicant( 6043): p2p0: Updating hw mode
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
,D/wpa_supplicant( 6043): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6043): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
,E/WifiStateMachine(  952):  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  952): deferMessage: msg=131144
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131085
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=0 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  952): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiMonitor(  952): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=DE
E/WifiStateMachine(  952):  SupplicantStartingState CMD_START_DRIVER 0 0
,E/WifiStateMachine(  952): deferMessage: msg=131085
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131149
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
E/WifiStateMachine(  952):  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
E/WifiStateMachine(  952): setSuspendOptimizations: 2 true
E/WifiStateMachine(  952): mSuspendOptNeedsDisabled 0
E/WifiStateMachine(  952): handleMessage: X,
E/WifiStateMachine(  952): handleMessage: E msg.what=131145
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
E/WifiStateMachine(  952):  SupplicantStartingState CMD_DISCONNECT 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_DISCONNECT 0 0
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131146
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
,E/WifiStateMachine(  952):  SupplicantStartingState CMD_RECONNECT 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_RECONNECT 0 0
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131101
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
,E/WifiStateMachine(  952):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  952): Default got CMD_TETHER_STATE_CHANGE
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131101
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
E/WifiStateMachine(  952):  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  952): Default got CMD_TETHER_STATE_CHANGE
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147457
E/WifiStateMachine(  952): processMsg: SupplicantStartingState
E/WifiStateMachine(  952):  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
E/WifiStateMachine(  952): Supplicant connection established
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_WIFI_ON 1"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET_WIFI_ON 1'
I/wpa_supplicant( 6043): set wifi ON
E/WifiStateMachine(  952): setWifiState: enabled
E/WifiStateMachine(  952): Enable Wifi On Screen Off, CMD_SET_SUSPEND_OPT_ENABLED 1
E/WifiStateMachine(  952):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 10000 mUserWantsSuspendOpt=false state SupplicantStartingState suppState:UninitializedState
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 6043): SET_SCREEN_ON:Off
I/wpa_supplicant( 6043): htc_wext_set_keepalive +
I/wpa_supplicant( 6043): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 6043): getPrivFuncNum +	
I/wpa_supplicant( 6043): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 6043): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 6043): get_ip_address SIOCGIFADDR failed
I/wpa_supplicant( 6043): get_ip_address source addr = ffffffff
I/wpa_supplicant( 6043): htc_wext_set_keepalive gateway addr = 00000000
I/wpa_supplicant( 6043): htc_wext_set_keepalive - ret = 0
I/WifiNative-HAL(  952): startHal
E/wifi    (  952): getStaticLongField sWifiHalHandle 0x7f5d217300
I/WifiNative-HAL(  952): Could not start hal
E/WifiStateMachine(  952): setScanAlarm false period 10000 initial delay 0mAlarmEnabledfalse
D/WifiStateMachine(  952): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  952): handleScreenStateChanged Exit: false
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER MACADDR"
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER MACADDR'
,I/IntentController( 1269): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET update_config 1"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET update_config 1'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'update_config'='1'
D/wpa_supplicant( 6043): update_config=1
D/wpa_supplicant( 6043): wlan0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
,D/WIFI_ICON( 1269): updateWifiState: WIFI_STATE_CHANGED enabled
D/StatusBar.NetworkController( 1269): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiConfigStore(  952): Loading config and enabling all networks 
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_NETWORKS"
D/wpa_supplicant( 6043): wlan0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6043): wpa_supplicant_ctrl_iface_list_networks: return size = 47
,I/bt-btm  ( 6009): btm_reset_complete,
I/bt-btm  ( 6009): BTM_SetPinType: pin type 0 [variable-0, fixed-1], code , length 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ssid"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
,D/bt-btm  ( 6009): Start reading local supported commands
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 bssid"
D/HtcWiFiWidget_WiFiWidgetProvider( 6081): onWiFiStateChanged() for widget: 
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 priority"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/HtcWiFiWidget_WiFiWidgetProvider( 6081): updateWidget(context) for widget: 
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 scan_ssid"
,D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/bt-btm  ( 6009): btm_read_local_supported_cmds_complete status (0x00)
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_tx_keyidx"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/bt-btm  ( 6009): BTM reads next extended features page (1)
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key0"
,D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wep_key0',
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key1"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/bt-btm  ( 6009): BTM reads next extended features page (2)
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key2"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wep_key3"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/bt-btm  ( 6009): BTM reached last extended features page (2)
D/bt-btm  ( 6009): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3f
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 psk"
,D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 6043): Do not allow key_data field to be exposed
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 proto"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/bt-btm  ( 6009): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x3d
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_mgmt"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 auth_alg"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 auth_alg',
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 pairwise"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/bt-btm  ( 6009): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x31
I/bt-btm  ( 6009): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 group"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='group'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk"
D/bt-btm  ( 6009): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x11
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk'
I/bt-btm  ( 6009): btm_vendor_capability_vsc_cmpl_cback: status=0
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_psk_hex"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wapi_psk_hex'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wapi_psk_hex'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_cert"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wapi_cert'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wapi_cert'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_as_cert"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wapi_as_cert'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wapi_as_cert'
D/bt-btm  ( 6009): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x01
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 wapi_user_cert"
,D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 wapi_user_cert'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='wapi_user_cert'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 eap"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='eap'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 phase2"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 identity"
D/bt-btm  ( 6009): btm_issue_host_support_for_lmp_features lmp_features_host_may_support: 0x00
D/bt-btm  ( 6009): btm_read_ble_wl_size 
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='identity'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 anonymous_identity"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 password"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='password'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 client_cert"
,D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 ca_cert"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/bt-btm  ( 6009): btm_read_white_list_size_complete 
D/bt-btm  ( 6009): btm_get_ble_buffer_size 
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 subject_match"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='engine'
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 engine_id"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 key_id"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 GET_NETWORK 0 private_key"
D/wpa_supplicant( 6043): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 6043): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/bt-btm  ( 6009): btm_read_ble_buf_size_complete 
D/bt-btm  ( 6009): btm_read_ble_local_supported_states 
,D/bt-btm  ( 6009): btm_read_ble_local_supported_states_complete 
D/bt-btm  ( 6009): btm_read_ble_local_supported_features 
,D/bt-btm  ( 6009): btm_read_ble_local_supported_features_complete 
E/WifiConfigStore(  952): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/bt-btm  ( 6009): btm_reset_ctrlr_complete: max_page_number: 2
D/bt-btm  ( 6009): btm_decode_ext_features_page page: 0
D/bt-btm  ( 6009): Local supported ACL packet types: 0xcc18
D/bt-btm  ( 6009): Local supported SCO packet types: 0x038f
I/bt-btm  ( 6009): BTM_SEC_REG[2]: id 42, is_orig 0, psm 0x0003, proto_id 3, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x80, service name [RFC_MUX] (up to 21 chars saved)
D/bt-btm  ( 6009): btm_sec_dev_reset sec mode: 4
I/bt-btm  ( 6009): BTM_SetInquiryMode
I/bt-btm  ( 6009): BTM_SetPageScanType
I/bt-btm  ( 6009): BTM_SetInquiryScanType
D/bt-btm  ( 6009): btm_decode_ext_features_page page: 1
W/bt-btm  ( 6009): btm_decode_ext_features_page Secure conn Host support Enabled
D/bt-btm  ( 6009): btm_decode_ext_features_page page: 2
W/bt-btm  ( 6009): btm_decode_ext_features_page Secure conn Controller support Enabled
D/bt-btm  ( 6009): BTM_BleLoadLocalKeys
D/bt-btm  ( 6009): BTM_BleLoadLocalKeys
I/bt-btm  ( 6009): BTM_Sec: application registered
E/bt-btm  ( 6009): BTM_SecRegister:p_cb_info->p_le_callback == 0xdf84e4d5 
I/bt-btm  ( 6009): BTM_Sec: SMP_Register( btm_proc_smp_cback )
I/bt-smp  ( 6009): SMP_Register state=0
E/bt-btm  ( 6009): BTM_SecRegister: btm_cb.api.p_le_callback = 0xdf84e4d5 
I/bt-btm  ( 6009): BTM_Sec: application registered
D/bt-btm  ( 6009): BTM_SetDefaultLinkSuperTout
I/bt-btm  ( 6009): BTM: BTM_WritePageTimeout: Timeout: 8192.
D/bt-btm  ( 6009): BTM_SetDefaultLinkPolicy setting:0x000f
D/bt-btm  ( 6009): BTM_SetDefaultLinkPolicy park not supported (settings: 0x0007)
D/bt-btm  ( 6009): Set DefaultLinkPolicy:0x0007
D/bt-btm  ( 6009): BTM_RegBusyLevelNotif
D/bt-btm  ( 6009): BTM_BleReadControllerFeatures
I/bt-btm  ( 6009): BTM: BTM_VendorSpecificCommand: Opcode: 0xFD53, ParamLen: 0.
I/bt-att  ( 6009): GATT_Register
D/bt-att  ( 6009): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 6009): allocated gatt_if=3
I/bt-att  ( 6009): GATT_StartIf gatt_if=3
D/bt-att  ( 6009): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6009): gatt_find_the_connected_bda found=0 found_idx=16
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_name m8qlul_htc_europe"
,D/wpa_supplicant( 6043): wlan0: Control interface command 'SET device_name m8qlul_htc_europe'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'device_name'='m8qlul_htc_europe'
D/wpa_supplicant( 6043): device_name='m8qlul_htc_europe'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET manufacturer HTC"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET manufacturer HTC'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'manufacturer'='HTC'
D/wpa_supplicant( 6043): manufacturer='HTC'
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_name HTC One M8s"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET model_name HTC One M8s'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'model_name'='HTC One M8s'
D/wpa_supplicant( 6043): model_name='HTC One M8s'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET model_number HTC One M8s"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET model_number HTC One M8s'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'model_number'='HTC One M8s'
D/wpa_supplicant( 6043): model_number='HTC One M8s'
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET config_methods physical_display virtual_push_button"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button'
D/wpa_supplicant( 6043): config_methods='physical_display virtual_push_button'
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET device_type 10-0050F204-5"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,E/WifiStateMachine(  952): transitionTo: destState=DriverStartedState
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DefaultState,active=true,parent=null
E/WifiStateMachine(  952): invokeExitMethods: SupplicantStartingState
E/WifiStateMachine(  952): moveTempStackToStateStack: i=1,j=1
E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=2
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=1,Top=DriverStartedState
E/WifiStateMachine(  952): invokeEnterMethods: SupplicantStartedState
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN_INTERVAL 15"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 6043): wlan0: Setting scan interval: 15 sec
D/WifiNative-HAL(  952): Setting external_sim to 1
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET external_sim 1"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET external_sim 1'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'external_sim'='1'
D/wpa_supplicant( 6043): external_sim=1
D/WifiP2pService(  952): P2pDisabledState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  952): DefaultState{ when=-1ms what=131332 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings( 5245): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  952): Setting OUI to DA-A1-19
I/WifiNative-HAL(  952): startHal
E/wifi    (  952): getStaticLongField sWifiHalHandle 0x7f5d217360
I/WifiNative-HAL(  952): Could not start hal
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 STA_AUTOCONNECT 0"
D/wpa_supplicant( 6043): wlan0: Control interface command 'STA_AUTOCONNECT 0'
E/WifiStateMachine(  952): invokeEnterMethods: DriverStartedState
E/WifiStateMachine(  952): Driverstarted State enter
,W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXSCAN-STOP"
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd BTCOEXSCAN-STOP len = 0, 8192
E/WifiStateMachine(  952): DriverStartedState call setCountryCode()
E/WifiStateMachine(  952): setDetailed state, old =IDLE and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  952): NetworkAgent == null
,D/bt-btm  ( 6009): btm_ble_vendor_capability_vsc_cmpl_cback
D/bt-btm  ( 6009): btm_ble_vnd_cap_vsc_cmpl_cback: stat=0, irk=0, ADV ins:10, rpa=1, ener=1
I/bt-btm  ( 6009): BTM Register For VSEvents is successfully
D/bt-btm  ( 6009): BTM_BleGetVendorCapabilities
I/bt-btif ( 6009): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 6009): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 0 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = true
,E/WifiStateMachine(  952): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/bt-btif ( 6009): Calling BTA_HhEnable
I/bt-btif ( 6009): BTA_MceEnable
,D/bt-btm  ( 6009): bta_dm_set_dev_name: name: HTC One M8s 
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btm  ( 6009):  BTM_BleConfigPrivacy
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): BTM: BTM_WriteVoiceSettings: Settings: 0x0060.
D/bt-btif ( 6009): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:3
D/bt-btm  ( 6009): BTM_AllocateSCN
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:4
,D/bt-btm  ( 6009): BTM_AllocateSCN
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btm  ( 6009): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6009):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6009):                : sec: 0x1086, service name [] (up to 21 chars saved)
D/bt-btif ( 6009): AG evt (hdl 0x0002): State 0, Event 0x0500
I/bt-btm  ( 6009): BTM_SEC_REG[3]: id 12, is_orig 0, psm 0x0003, proto_id 3, chan_id 2
I/bt-btm  ( 6009):                : sec: 0x1086, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[4]: id 29, is_orig 0, psm 0x0003, proto_id 3, chan_id 3
I/bt-btm  ( 6009):                : sec: 0x1086, service name [] (up to 21 chars saved)
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x0019
I/bt-btm  ( 6009): BTM_SEC_REG[5]: id 37, is_orig 1, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[5]: id 37, is_orig 0, psm 0x0019, proto_id 7, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x3092, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 1
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-ADD 3"
I/bt-btm  ( 6009): BTM_SEC_REG[6]: id 38, is_orig 1, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[6]: id 38, is_orig 0, psm 0x0019, proto_id 7, chan_id 2
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
D/WIFI_ICON( 1269): updateWifiState: NETWORK_STATE_CHANGED disconnected
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x0017
I/bt-btm  ( 6009): BTM_SEC_REG[7]: id 39, is_orig 1, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x2090, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[7]: id 39, is_orig 0, psm 0x0017, proto_id 0, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x3092, service name [] (up to 21 chars saved)
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:5
I/bt-avp  ( 6009): AVRC_AddRecord uuid: 110c
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:6
I/bt-a2d  ( 6009): A2D_AddRecord uuid: 110a
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
D/bt-btif ( 6009):  AVRC_Open AVRC_Open role: 1, control:3 status:0, handle:0
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:7
I/bt-avp  ( 6009): AVRC_AddRecord uuid: 110e
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/IntentController( 1269): receive(android.net.wifi.STATE_CHANGE,1,false)
I/bt-btm  ( 6009): BTM_SEC_REG[8]: id 32, is_orig 0, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6009):                : sec: 0x86, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[8]: id 32, is_orig 1, psm 0x0011, proto_id 6, chan_id 1
I/bt-btm  ( 6009):                : sec: 0xb6, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[9]: id 33, is_orig 0, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[9]: id 33, is_orig 1, psm 0x0011, proto_id 6, chan_id 2
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[10]: id 34, is_orig 1, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars ,saved)
I/bt-btm  ( 6009): BTM_SEC_REG[10]: id 34, is_orig 0, psm 0x0013, proto_id 6, chan_id 0
I/bt-btm  ( 6009):                : sec: 0x80, service name [] (up to 21 chars saved)
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x0011
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x0013
I/bt-att  ( 6009): GATT_Register
D/bt-att  ( 6009): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 6009): allocated gatt_if=4
I/bt-att  ( 6009): GATT_StartIf gatt_if=4
D/bt-att  ( 6009): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 6009): gatt_find_the_connected_bda found=0 found_idx=16
E/bt-btif ( 6009): btif_storage_get_adapter_property service_mask:0x2140040
I/bt-btif ( 6009): HAL bt_hal_cbacks->adapter_properties_cb
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER RXFILTER-ADD 3'
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd RXFILTER-ADD 3 len = 0, 8192
D/BluetoothAdapterProperties( 6009): Address is:90:E7:C4:F6:69:77
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER RXFILTER-START'
E/WifiTrafficPoller(  952): ENABLE_TRAFFIC_STATS_POLL false Token 0
,D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-STOP"
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd RXFILTER-STOP len = 0, 8192
D/BluetoothAdapterProperties( 6009): Scan Mode:21
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-REMOVE 2"
D/BluetoothAdapterProperties( 6009): Discoverable Timeout:120
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd RXFILTER-REMOVE 2 len = 0, 8192
D/StatusBar.NetworkController( 1269): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER RXFILTER-START"
I/bt-btif ( 6009): BTA_JvEnable
I/bt-btif ( 6009): BTA_JvRegisterL2cCback
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd RXFILTER-START len = 0, 8192
,I/bt-btm  ( 6009): BTM_ReadConnectability
I/bt-btm  ( 6009): BTM_ReadDiscoverability
I/bt-btm  ( 6009): BTM_SetDiscoverability
I/bt-btm  ( 6009): btm_ble_set_discoverability mode=0x0 combined_mode=0x2
D/bt-btm  ( 6009): disc_mode 0002
D/WifiDataStallTracker(  952): setDhcpActive: false
D/bt-btm  ( 6009): btm_ble_update_adv_flag new=0x18
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): evt_type=0x0 p-cb->evt_type=0x3 
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 STATUS"
I/bt-btm  ( 6009): BTM_SetDiscoverability: mode 2 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6009): BTM_SetConnectability
I/bt-btm  ( 6009): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6009): disc_mode 0002
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
W/bt-l2cap( 6009): L2CAP - L2CA_Register() called for PSM: 0x000f
I/bt-btm  ( 6009): BTM_SetDiscoverability
I/bt-btm  ( 6009): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6009): disc_mode 0000
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): evt_type=0x0 p-cb->evt_type=0x0 
D/wpa_supplicant( 6043): wlan0: Control interface command 'STATUS'
I/bt-btm  ( 6009): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x1000
I/bt-btm  ( 6009): BTM_SetConnectability
I/bt-btm  ( 6009): btm_ble_set_connectability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6009): disc_mode 0000
D/bt-btm  ( 6009): btm_ble_update_adv_flag new=0x1c
,D/bt-btm  ( 6009): btm_ble_update_adv_flag old=0x18
I/bt-btm  ( 6009): btm_gen_resolvable_private_addr
I/bt-btm  ( 6009): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6009): bta_pan_co_init
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:8
I/bt-btm  ( 6009): BTM_SEC_REG[11]: id 27, is_orig 1, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6009):                : sec: 0x20b0, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[11]: id 27, is_orig 0, psm 0x000f, proto_id 5, chan_id 4374
I/bt-btm  ( 6009):                : sec: 0x30b6, service name [Android Network Access Point] (up to 21 chars saved)
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btm  ( 6009): BTM_SEC_REG[12]: id 25, is_orig 1, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6009):                : sec: 0x20b0, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6009): BTM_SEC_REG[12]: id 25, is_orig 0, psm 0x000f, proto_id 5, chan_id 4373
I/bt-btm  ( 6009):                : sec: 0x30b6, service name [Android Network User] (up to 21 chars saved)
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=1 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
E/WifiStateMachine(  952): transitionTo: destState=DisconnectedState
E/native  (  952): do suspend false
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange():id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  952): WifiMonitor:getSSIDFromString id=-1 state=0 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 0'
D/HTCRequest(  952): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 8192
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET ps 1"
D/WifiP2pService(  952): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 6043): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiMonitor(  952): WifiMonitor: prevSupplicantState =INVALID newSupplicantState =DISCONNECTED
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 7(0x302e302e302e30),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, SUCCESS
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_gen_resolve_paddr_low
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = db c4 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = b8 37 5d b2 5a d3 a4 e2 09 b8 8f 6b 53 c5 23 f5 
I/bt-btm  ( 6009): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6009): Stopping oneshot timer
D/bt-btm  ( 6009): Starting oneshot timer type:103 timeout:900s
D/WifiMonitor(  952): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  952): P2pEnablingState
E/WifiStateMachine(  952): Driverstarted State enter done
E/WifiStateMachine(  952): moveDeferredMessageAtFrontOfQueue; what=131085
E/WifiStateMachine(  952): moveDeferredMessageAtFrontOfQueue; what=131144
E/WifiStateMachine(  952): handleMessage: new destination call exit/enter
E/WifiStateMachine(  952): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=SupplicantStartedState
E/WifiStateMachine(  952): moveTempStackToStateStack: i=1,j=3
E/WifiStateMachine(  952): moveTempStackToStateStack: i=0,j=4
E/WifiStateMachine(  952): moveTempStackToStateStack: X mStateStackTop=4,startingIndex=3,Top=DisconnectedState
,E/WifiStateMachine(  952): invokeEnterMethods: ConnectModeState
E/WifiStateMachine(  952): invokeEnterMethods: DisconnectedState
E/WifiStateMachine(  952): DisconnectedState call setCountryCode()
E/WifiStateMachine(  952):  Enter disconnected State scan interval 300000 mEnableBackgroundScan= true screenOn=false
I/QuickSettingWifi( 1269): receive.wifiState:WIFI_STATE_ENABLED setEnable:true
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiScanningService(  952): SCAN_AVAILABLE : 3
D/RttService(  952): SCAN_AVAILABLE : 3
D/wpa_supplicant( 6043): wlan0: Control interface command 'SET pno 1'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'pno'='1'
D/WifiScanningService(  952): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 6043): wlan0: nl80211: sched_scan request
I/WifiNative-HAL(  952): startHal
D/RttService(  952): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:9
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): HAL bt_hal_cbacks->adapter_state_changed_cb
D/bt-btif ( 6009): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 6009): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6009): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 6009): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 6009): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/BluetoothAdapterState( 6009): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6009): ScanMode =  21
D/BluetoothAdapterProperties( 6009): State =  11
D/BluetoothAdapterProperties( 6009): Setting state to 12
I/BluetoothAdapterState( 6009): Bluetooth adapter state changed: 11-> 12
I/bt-btif ( 6009): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 6009): Discoverable Timeout:120
D/BluetoothManagerService(  952): +onBluetoothStateChange prev=11 new=12
,D/BluetoothManagerService(  952): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  952): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  952): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  952): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 6009): Entering On State
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
,D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = cd de 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 44 ed 57 e1 9d 76 9a d6 7a 8c e7 4c 7c f1 41 ac 
E/bt_mct  ( 6009): hci lib postload completed
,D/WifiP2pService(  952): P2pEnablingState{ when=-8ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  952): P2p socket connection successful
D/WifiP2pService(  952): P2pEnabledState
D/WifiP2pService(  952): sending p2p connection changed broadcast
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = ea 5b 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
,D/WifiDisplayController(  952): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 61 9c bc 9d 22 17 69 76 56 75 a5 64 d2 a4 a1 32 
D/WifiDisplayController(  952): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayController(  952): mWfdEnabled :false, networkInfo.isConnected() :false
D/WifiDisplayAdapter(  952): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  952):     Client/Owner: Client
D/WifiDisplayAdapter(  952):     GroupId: 
D/WifiDisplayAdapter(  952):     Passphrase: 
D/WifiDisplayAdapter(  952):     SessionId: 0
D/WifiDisplayAdapter(  952):     IP Address: }
,V/AudioService(  952): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  952):     Client/Owner: Client
V/AudioService(  952):     GroupId: 
V/AudioService(  952):     Passphrase: 
V/AudioService(  952):     SessionId: 0
V/AudioService(  952):     IP Address: }
D/HtcEffectManagerBase(  952): onEventChanged id=5 status=false
D/HtcEffectManager(  952): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true mAllPlayOn=false,
D/HtcEffectManager(  952): convertEffect before=902
D/HtcEffectManager(  952): convertEffect after=902
D/BluetoothHeadset( 1510): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1269): onBluetoothStateChange: up=true
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
D/BluetoothHeadset( 1510): onBluetoothStateChange: up=true
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = fa 1a 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = f6 ef e2 36 8d ae 1f 1f 95 d2 62 57 ab 7a 52 bf 
,D/BluetoothHeadset( 1510): onBluetoothStateChange: up=true
D/BluetoothA2dp(  952): onBluetoothStateChange: up=true
D/BluetoothManagerService(  952): Bluetooth State Change Intent: 11 -> 12
,D/NGFService( 3551): Receiver: action = android.bluetooth.adapter.action.STATE_CHANGED
I/IntentController( 1269): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/NGFService( 3551): Bluetooth Adapter: ON
,D/BluetoothManagerService(  952): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  952): Message: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
D/bt-btm  ( 6009): btm_ble_rand_enc_complete
D/BluetoothManagerService(  952): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = 97 2e 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 72 8f 80 a2 ce 50 5d 1f 64 5d 5f cb cf d9 c9 fa 
V/BluetoothPbapReceiver( 6009): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 6009): ***********state = 12
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
,I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = 4a fb 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 5e 9a da 2a dc f7 34 96 0b d5 7e 39 9b e7 11 18 
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
,I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = a3 8e 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = c5 34 d8 44 31 e4 53 07 a8 ab 95 e3 c9 e3 e4 de 
,V/BluetoothPbapService( 6009): Pbap Service onCreate
V/BluetoothPbapService( 6009): Starting PBAP service
,D/BluetoothAdapter( 6009): 105178767: getState(). Returning 12
V/BluetoothPbapService( 6009): Handler(): got msg=1
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = b7 fb 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 15 79 1a 1d d0 e4 a6 6f ce f1 d6 0c 09 86 09 32 
V/BluetoothPbapService( 6009): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 6009): Pbap Service initSocket
D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6009): getBluetoothService() called with no BluetoothManagerCallback
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = bb ee 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 68 30 fa bf ae b4 cd 53 c0 06 f2 67 13 b8 be 2d 
I/bt-btm  ( 6009): BTM_SetDiscoverability,
I/bt-btm  ( 6009): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 6009): disc_mode 0000
I/bt-btm  ( 6009): evt_type=0x0 p-cb->evt_type=0x0 
I/bt-btm  ( 6009): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 6009): BTM_SetConnectability
I/bt-btm  ( 6009): btm_ble_set_connectability mode=0x0 combined_mode=0x1
D/bt-btm  ( 6009): BTA_JvCreateRe
I/bt-btif ( 6009): btm_ble_update_adv_flag 
D/bt-btm  ( 6009): btm_ble_update_adv_flag new=0x18
D/bt-btm  ( 6009): btm_ble_update_adv_flag old=0x1c
I/bt-btm  ( 6009): BTM_SetConnectability: mode 1 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btif ( 6009): HAL bt_hal_cbacks->adapter_properties_cb
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:10
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): BTA_JvRfcommStartServer
I/bt-btm  ( 6009): BTM_SEC_REG[13]: id 55, is_orig 0, psm 0x0003, proto_id 3, chan_id 19
I/bt-btm  ( 6009):                : sec: 0x86, service name [JV PORT] (up to 21 chars saved)
V/BluetoothPbapService( 6009): Succeed to create listening socket 
V/BluetoothPbapService( 6009): Accepting socket connection...
D/BluetoothAdapterProperties( 6009): Scan Mode:21
D/WISPrService( 5426): >>>>>WISPrService start isConnected = false<<<<<
D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_ble_multi_adv_gen_rpa_cmpl inst_id = 0
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = d2 08 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = d5 3c a6 6f bc d3 03 e4 ff 2e f9 0d 24 56 1d 12 
D/PMS     (  952): acquireWL(3001cb58): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 5426 1000 null
I/QuickSettingWifi( 1269): receive.wifiConnect:false wifiAPname:null elapse:13
W/ContextImpl( 5426): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  952): releaseWL(3001cb58): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  952): acquireWL(369b6d96): PARTIAL_WAKE_LOCK  StartingDockService 0x1 5426 1000 null
D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_gen_resolve_paddr_low
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = 14 88 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 0b ee ec 4d a3 3f 80 9e fb 12 b5 2d 2a 0f 31 a1 
I/bt-btm  ( 6009): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6009): Stopping oneshot timer
D/bt-btm  ( 6009): Starting oneshot timer type:103 timeout:900s
D/HtcBtWidget_BTWidgetProvider( 6045): onBTStateChanged() for widget: ,
,E/WifiTrafficPoller(  952): ADD_CLIENT: 8
D/WifiService(  952): New client listening to asynchronous messages
D/HtcBtWidget_BTWidgetProvider( 6045): updateWidget(context) for widget: 
D/WISPrService( 5426): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: UNINITIALIZED, RSSI: -127, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,W/System.err(  952): java.lang.Throwable: stack dump
W/System.err(  952): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  952): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
W/System.err(  952): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  952): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  952): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e744504:true
D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_gen_resolve_paddr_low
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = 9e d4 41 00 00 00 00 00 00 00 00 00 00 00 00 00 ,
,W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = b9 5f 24 d2 e4 e3 bb b3 c1 b2 3f 8d 36 ae 5f e3 
I/bt-btm  ( 6009): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6009): Stopping oneshot timer
D/bt-btm  ( 6009): Starting oneshot timer type:103 timeout:900s
D/BluetoothAdapter( 1269): 14047888: getState(). Returning 12
D/BluetoothAdapter( 1269): 14047888: getState(). Returning 12
I/QuickSettingBluetooth( 1269): receive.ACTION_STATE_CHANGE:STATE_ON/(true,false)
D/PhoneStatusBar( 1269): addIcon slot=bluetooth index=12 viewIndex=1 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204ad level=0 visible=true num=0 ) name=stat_sys_data_bluetooth vis=true
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
I/bt-btm  ( 6009): btm_gen_resolve_paddr_low
D/bt-smp  ( 6009): smp_encrypt_data
,W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = 3c 53 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = 40 f6 43 2d 21 f6 a2 6a c7 17 2e 74 61 76 55 fb 
I/bt-btm  ( 6009): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6009): Stopping oneshot timer
D/bt-btm  ( 6009): Starting oneshot timer type:103 timeout:900s
,D/BluetoothAdapter( 5426): 267096950: getState(). Returning 12
,D/bt-btm  ( 6009): btm_ble_rand_enc_complete
,I/bt-btm  ( 6009): btm_gen_resolve_paddr_low
D/bt-smp  ( 6009): smp_encrypt_data
W/bt-smp  ( 6009): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 6009): Plain text(LSB ~ MSB) = f5 d9 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 6009): Encrypted text(LSB ~ MSB) = c6 a7 77 ba b7 4a e1 c5 86 21 08 01 25 02 fe 46 
I/bt-btm  ( 6009): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 6009): Stopping oneshot timer
D/bt-btm  ( 6009): Starting oneshot timer type:103 timeout:900s
,D/BluetoothInputDevice( 5426): BluetoothInputDevice()
D/BluetoothManagerService(  952): registerStateChangeCallback+
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  952): Registered receivers: 7
D/BluetoothPan( 5426): BluetoothPan()
D/BluetoothManagerService(  952): registerStateChangeCallback+
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  952): Registered receivers: 8
,D/wpa_supplicant( 6043): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 6043): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/wpa_supplicant( 6043): wlan0: nl80211: Sched scan started
D/wpa_supplicant( 6043): RTM_NEWLINK: ifi_index=30 ifname=p2p0 operstate=2 linkmode=1 ifi_flags=0x1003 ([UP])
D/Tethering(  952): interfaceLinkStateChanged p2p0, false
D/Tethering(  952): interfaceStatusChanged p2p0, false
E/WifiStateMachine(  952): WiFiDisplay: getWifidisplayApEnabled=false
E/WifiStateMachine(  952): handleMessage: X
E/wifi    (  952): getStaticLongField sWifiHalHandle 0x7f5ae2b520
I/WifiNative-HAL(  952): Could not start hal
E/WifiStateMachine(  952): handleMessage: E msg.what=131144
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiScanningService(  952): could not start HAL
E/WifiStateMachine(  952):  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131085
E/WifiStateMachine(  952): processMsg: DisconnectedState
D/BluetoothMap( 5426): Create BluetoothMap proxy object
E/WifiStateMachine(  952):  DisconnectedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
W/WifiHW  (  952): QCOM Debug wifi_send_command "SET persistent_reconnect 1"
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 6043): GLOBAL_CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6043): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 6043): persistent_reconnect=1
D/wpa_supplicant( 6043): p2p0: WPS: UUID based on configuration: 12345678-9abc-def0-1234-56789abcdef1
D/wpa_supplicant( 6043): P2P: New SSID postfix: -Android_608e
D/wpa_supplicant( 6043): P2P: Set Operating channel: reg_class 126 channel 149
D/BluetoothManagerService(  952): registerStateChangeCallback+
E/WifiStateMachine(  952):  ConnectModeState CMD_START_DRIVER 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
W/ContextImpl( 5426): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1888 android.content.ContextWrapper.bindService:538 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1423 
W/WifiHW  (  952): QCOM Debug wifi_send_command "SET device_name Android_608e"
E/WifiStateMachine(  952):  DriverStartedState CMD_START_DRIVER 0 0
E/WifiStateMachine(  952): handleMessage: X
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=28): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 41 6e 64 72 6f 69 64 5f 36 30 38 65
D/wpa_supplicant( 6043): GLOBAL_CTRL_IFACE SET 'device_name'='Android_608e'
E/WifiStateMachine(  952): handleMessage: E msg.what=131154
D/wpa_supplicant( 6043): p2p0: Control interface command 'SET device_name Android_608e'
E/WifiStateMachine(  952): processMsg: DisconnectedState
D/wpa_supplicant( 6043): CTRL_IFACE SET 'device_name'='Android_608e'
D/wpa_supplicant( 6043): device_name='Android_608e'
D/BluetoothManagerService(  952): Registered receivers: 9
E/WifiStateMachine(  952):  DisconnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/BluetoothMap( 5426): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
E/WifiStateMachine(  952):  ConnectModeState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
E/WifiStateMachine(  952):  SupplicantStartedState CMD_ENABLE_RSSI_POLL 0 0
D/WifiP2pService(  952): DeviceAddress: 92:e7:c4:e6:4c:f8
E/Wi,fiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131323
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState what:131323 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
D/BluetoothManagerService(  952): registerStateChangeCallback+
W/WifiHW  (  952): QCOM Debug wifi_send_command "SET p2p_ssid_postfix -Android_608e"
D/BluetoothSap( 5426): BluetoothSap() call bindService
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=34): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 41 6e 64 72 6f 69 64 5f 36 30 ...
D/wpa_supplicant( 6043): GLOBAL_CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
D/wpa_supplicant( 6043): p2p0: Control interface command 'SET p2p_ssid_postfix -Android_608e'
E/WifiStateMachine(  952):  ConnectModeState what:131323 0 0
D/wpa_supplicant( 6043): CTRL_IFACE SET 'p2p_ssid_postfix'='-Android_608e'
E/WifiStateMachine(  952): processMsg: DriverStartedState
D/wpa_supplicant( 6043): p2p_ssid_postfix='-Android_608e'
D/wpa_supplicant( 6043): P2P: New SSID postfix: -Android_608e
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  952): Registered receivers: 10
E/WifiStateMachine(  952):  DriverStartedState what:131323 0 0
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
W/WifiHW  (  952): QCOM Debug wifi_send_command "SET device_type 10-0050F204-5"
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 6043): GLOBAL_CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/wpa_supplicant( 6043): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'device_type'='10-0050F204-5'
E/WifiStateMachine(  952):  SupplicantStartedState what:131323 0 0
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState what:131323 0 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "SET config_methods virtual_push_button physical_display keypad"
E/WifiStateMachine(  952): setOperatorSSID enter
E/WifiStateMachine(  952): handleMessage: X
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 6043): GLOBAL_CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6043): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 6043): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 6043): config_methods='virtual_push_button physical_display keypad'
E/WifiStateMachine(  952): handleMessage: E msg.what=131104
D/WifiDisplayController(  952): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Android_608e
D/WifiDisplayController(  952):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiDisplayController(  952):  primary type: 10-0050F204-5
D/WifiDisplayController(  952):  secondary type: null
D/WifiDisplayController(  952):  wps: 0
D/WifiDisplayController(  952):  grpcapab: 0
D/WifiDisplayController(  952):  devcapab: 0
D/WifiDisplayController(  952):  status: 3
D/WifiDisplayController(  952):  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
D/WifiDisplayController(  952):  WFD CtrlPort: 0
D/WifiDisplayController(  952):  WFD MaxThroughput: 0
E/WifiStateMachine(  952): processMsg: DisconnectedState
W/WifiHW  (  952): QCOM Debug wifi_send_command "P2P_SET conc_pref sta"
E/WifiStateMachine(  952):  DisconnectedState what:131104 0 0
D/wpa_supplicant( 6043): p2p0: Control interface command 'P2P_SET conc_pref sta'
E/WifiStateMachine(  952): processMsg: ConnectModeState
I/wpa_supplicant( 6043): [p2p command] (P2P_SET conc_,pref sta)
D/wpa_supplicant( 6043): Single channel concurrency preference: sta
E/WifiStateMachine(  952):  ConnectModeState what:131104 0 0
W/Settings(  952): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  952): p2pGetDeviceAddress
W/WifiHW  (  952): QCOM Debug wifi_send_command "STATUS"
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-HAL(  952): p2pGetDeviceAddress returning 92:e7:c4:e6:4c:f8
D/BluetoothPbap( 5426): BluetoothPbap()
D/BluetoothManagerService(  952): registerStateChangeCallback+
W/WifiHW  (  952): QCOM Debug wifi_send_command "P2P_FLUSH"
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  952): Registered receivers: 11
D/wpa_supplicant( 6043): p2p0: Control interface command 'P2P_FLUSH'
I/wpa_supplicant( 6043): [p2p command] (P2P_FLUSH)
D/wpa_supplicant( 6043): P2P: Stopping find
D/wpa_supplicant( 6043): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6043): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6043): wpa_driver_set_ap_wps_p2p_ie: Entry
D/wpa_supplicant( 6043): P2P: Stopping find
D/wpa_supplicant( 6043): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 6043): P2P: State IDLE -> IDLE
D/wpa_supplicant( 6043): wpa_driver_set_ap_wps_p2p_ie: Entry
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 CTRL-DAT-AIR_MODE-0:1"
D/wpa_supplicant( 6043): wlan0: Control interface command 'CTRL-DAT-AIR_MODE-0:1'
D/wpa_supplicant( 6043): CTRL_IFACE: field=AIR_MODE id=0
D/wpa_supplicant( 6043): CTRL_IFACE: value - hexdump(len=1): [REMOVED]
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=131162
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  952): processMsg: DriverStartedState
E/WifiStateMachine(  952):  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
E/WifiStateMachine(  952): set frequency band 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETBAND 0"
D/wpa_supplicant( 6043): wlan0: Control interface command 'DRIVER SETBAND 0'
D/wpa_supplicant( 6043): SETBAND: 0
D/wpa_supplicant( 6043): wpa_driver_nl80211_driver_cmd SETBAND 0 len = 0, 8192
D/wpa_supplicant( 6043): wlan0: Event CHANNEL_LIST_CHANGED (30) received
I/wpa_supplicant( 6043): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiMonitor(  952): Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN]
E/WifiMonitor(  952): WifiMonitor:wlan0 cnt=2 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
E/WifiMonitor(  952): handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=DE
E/WifiMonitor(  952): handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/wpa_supplicant( 6043): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
D/wpa_supplicant( 6043): P2P: Add operating class 81
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 6043): P2P: Add operating class 115
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 6043): P2P: Add operating class 116
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=2): 24 2c
D/wpa_supplicant( 6043): P2P: Add operating class 117
D/wpa_supplicant( 6043): P2P: Channels - hexdump(len=2): 28 30
D/BluetoothManagerService(  952): registerStateChangeCallback+
D/wpa_supplicant( 6043): P2P: Update channel list
D/wpa_supplicant( 6043): P2P: channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48 116:36,44 117:40,48
D/wpa_supplicant( 6043): P2P: cli_channels:
D/wpa_supplicant( 6043): p2p0: Updating hw mode
D/WifiP2pService(  952): sending p2p persistent groups changed broadcast
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  952): Registered receivers: 12
D/wpa_supplicant( 6043): nl80211: Regulatory information - country=DE
D/wpa_supplicant( 6043): nl80211: 2402-2482 @ 40 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5170-5250 @ 80 MHz 20 mBm
D/wpa_supplicant( 6043): nl80211: 5250-5330 @ 80 MHz 20 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 5490-5710 @ 80 MHz 27 mBm (DFS)
D/wpa_supplicant( 6043): nl80211: 57240-65880 @ 2160 MHz 40 mBm (no outdoor)
D/WifiP2pService(  952): InactiveState
D/wpa_supplicant( 6043): nl80211: Added 802.11b mode based on 802.11g information
E/WifiStateMachine(  952): did set frequency band 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS_FLUSH 0"
D/wpa_supplicant( 6043): wlan0: Control interface command 'BSS_FLUSH 0'
W/WifiHW  (  952): QCOM Debug wifi_send_command "P2P_SERVICE_FLUSH"
D/wpa_supplicant( 6043): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
I/wpa_supplicant( 6043): [p2p command] (P2P_SERVICE_FLUSH)
W/WifiHW  (  952): QCOM Debug wifi_send_command "LIST_NETWORKS"
D/wpa_supplicant( 6043): p2p0: Control interface command 'LIST_NETWORKS'
D/wpa_supplicant( 6043): wpa_supplicant_ctrl_iface_list_networks: return size = 34
W/WifiHW  (  952): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN TYPE=ONLY"
D/wpa_supplicant( 6043): wlan0: Control interface command 'SCAN TYPE=ONLY'
D/wpa_supplicant( 6043): Stop ongoing sched_scan to allow requested full scan to proceed
D/wpa_supplicant( 6043): wlan0: Cancelling sched scan
D/wpa_supplicant( 6043): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 6043): wlan0: Setting scan request: 0.000000 sec
I/wpa_supplicant( 6043): wpa_supplicant_scan enter
D/wpa_supplicant( 6043): wlan0: Skip scan - PNO is in progress
D/wpa_supplicant( 6043): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/wpa_supplicant( 6043): wlan0: nl80211: Sched scan stopped
D/wpa_supplicant( 6043): wlan0: Event SCHED_SCAN_STOPPED (38) received
E/WifiStateMachine(  952): done set frequency band 0
W/WifiHW  (  952): QCOM Debug wifi_send_command "SAVE_CONFIG"
D/wpa_supplicant( 6043): RX global ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 6043): Writing configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 6043): Configuration file '/data/misc/wifi/wpa_supplicant.conf' written successfully
D/wpa_supplicant( 6043): wlan0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/wpa_supplicant( 6043): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 6043): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 6043): p2p0: CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/BluetoothHeadset( 5426): BluetoothHeadset()
D/BluetoothManagerService(  952): registerStateChangeCallback+
D/BluetoothManagerService(  952): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  952): Registered receivers: 13
D/LocalBluetoothProfileManager( 5426): LocalBluetoothProfileManager construction complete
D/WifiStateMachine(  952): [MLHD] enter handleMediaLinkEvent DriverStartedState
D/WifiStateMachine(  952): Wifi band: 0, ScanBroadCastCounter: 0
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=147462
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=145071  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  952): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  952): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 1 0 rt=145072  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: DISCONNECTED
E/WifiStateMachine(  952): handleMessage: X
E/WifiStateMachine(  952): handleMessage: E msg.what=143371
E/WifiStateMachine(  952): processMsg: DisconnectedState
E/WifiStateMachine(  952):  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  952): processMsg: ConnectModeState
E/WifiStateMachine(  952):  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  952): processMsg: DriverStartedState
D/DockEventReceiver( 5426): finishStartingService: stopping service
E/WifiStateMachine(  952):  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  952): processMsg: SupplicantStartedState
D/BluetoothA2dp( 5426): Proxy object connected
E/WifiStateMachine(  952):  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  952): processMsg: DefaultState
E/WifiStateMachine(  952):  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
E/WifiStateMachine(  952): handleMessage: X
D/A2dpProfile( 5426): Bluetooth service connected
D/BluetoothAdapter( 5426): 267096950: getState(). Returning 12
D/BluetoothHeadset( 5426): Proxy object connected
D/HeadsetProfile( 5426): Bluetooth service connected
V/BluetoothPbapService( 6009): Pbap Service onBind
D/BluetoothAdapter( 5426): 267096950: getState(). Returning 12
D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6009): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6009): BTA_JvCreateRecordByUser
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:11
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): BTA_JvRfcommStartServer
I/bt-btm  ( 6009): BTM_SEC_REG[14]: id 56, is_orig 0, psm 0x0003, proto_id 3, chan_id 12
I/bt-btm  ( 6009):                : sec: 0x80, service name [JV PORT] (up to 21 chars saved)
I/BtOppRfcommListener( 6009): Accept thread started.
D/PMS     (  952): releaseWL(369b6d96): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothAdapter( 6009): 105178767: getState(). Returning 12
D/BluetoothFtpService( 6009): ACTION_STATE_CHANGED: state: 12mHasStarted: true
D/BluetoothInputDevice( 5426): Proxy object connected
D/BluetoothMasReceiver( 6009): Bluetooth STATE CHANGED to 12
D/BluetoothMasReceiver( 6009):  call MAP start service
D/BluetoothFtpService( 6009): htc sense version is 6.0
D/HidProfile( 5426): Bluetooth service connected
D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter( 5426): 267096950: getState(). Returning 12
W/BluetoothAdapter( 6009): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 6009): BTA_JvCreateRecordByUser
D/BluetoothPan( 5426): BluetoothPAN Proxy object connected
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:12
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): BTA_JvRfcommStartServer
I/bt-btm  ( 6009): BTM_SEC_REG[15]: id 57, is_orig 0, psm 0x0003, proto_id 3, chan_id 20
I/bt-btm  ( 6009):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/PanProfile( 5426): Bluetooth service connected
D/BluetoothPbap( 5426): Proxy object connected
D/PbapServerProfile( 5426): Bluetooth service connected
V/BluetoothFtpService:RfcommSocketAcceptThread( 6009): Run Accept thread
E/BluetoothMasService( 6009): BluetoothMasObexConnectionManager: mIsEmailEnabled: true
D/BluetoothMasService( 6009): Add permission for SmsProvider.
V/BluetoothMasService( 6009): Starting MAS instances
D/BluetoothAdapter( 6009): 105178767: getState(). Returning 12
I/MailMessageReceiver( 6009): reg:com.android.bluetooth.btservice.AdapterApp@1302c3b4 with com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1065bdd
I/MailManager( 6009): MailManager contruct! com.htc.lib1.HtcMailLibFramework.MailMessageReceiver@1065bdd
V/EmailUtils( 6009): Manager Instance is not NULL
I/ActivityManager(  952): Start proc com.htc.android.mail:sync for content provider com.htc.android.mail/.MailProvider: pid=6139 uid=10062 gids={50062, 9997, 3003, 1023, 1028, 1015} abi=armeabi-v7a
,D/HtcAdjCursorFactory( 6139): Set CursorWindow size to: 4194304 KB, Tid: 6159,
,D/EmailUtils( 6009): ============NULL aList========,
V/EmailUtils( 6009): <-getEmailAccountIdList
V/BluetoothMasService( 6009): onCreate: mIsEmailEnabled: true
D/BluetoothAdapter( 6009): 105178767: getState(). Returning 12
V/BluetoothMasService( 6009): parseIntent 1: mIsEmailEnabled: true
V/EmailUtils( 6009): Manager Instance is not NULL
,D/EmailUtils( 6009): ============NULL aList========,
V/EmailUtils( 6009): <-getEmailAccountIdList
,V/BluetoothSapReceiver( 6009): SapReceiver onReceive 
V/BluetoothSapReceiver( 6009): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 6009):  Bluetooth Adapter state = 12
V/BluetoothSapReceiver( 6009): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothMasService( 6009): handleMessage: mIsEmailEnabledtrue
V/BtMns   ( 6009): BluetoothMns: isEmailEnabled: true
,D/AuthorizationBluetoothService( 1932): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/GpsLocationProvider(  952): [handleMessage] DOWNLOAD_XTRA_DATA
W/BluetoothAdapter( 6009): getBluetoothService() called with no BluetoothManagerCallback
D/GpsLocationProvider(  952): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,I/bt-btif ( 6009): BTA_JvCreateRecordByUser
D/bt-btm  ( 6009): BTM_AllocateSCN
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:13
,I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): BTA_JvRfcommStartServer
I/bt-btm  ( 6009): BTM_SEC_REG[16]: id 58, is_orig 0, psm 0x0003, proto_id 3, chan_id 4
I/bt-btm  ( 6009):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6009): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6009): BTA_JvCreateRecordByUser
D/bt-btm  ( 6009): BTM_AllocateSCN
D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:14
I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): BTA_JvRfcommStartServer
I/bt-btm  ( 6009): BTM_SEC_REG[17]: id 59, is_orig 0, psm 0x0003, proto_id 3, chan_id 5
I/bt-btm  ( 6009):                : sec: 0x1086, service name [JV PORT] (up to 21 chars saved)
,I/ActivityManager(  952): Killing 4618:com.google.android.gms.wearable/u0a24 (adj 15): empty #17
D/Process (  952): killProcessQuiet, pid=4618
D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,I/ActivityManager(  952): Recipient 4618
,V/BluetoothSapService( 6009): Sap Service onCreate,
V/BluetoothSapService( 6009): initBinder
,V/BluetoothSapService( 6009): BluetoothSapBinder: mService: com.android.bluetooth.sap.BluetoothSapService@26e26720
V/BluetoothSapService( 6009): Sap Service onBind: com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@3b01a29e
,V/BluetoothSapService( 6009): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 6009): state: 12
D/SapServerProfile( 5426): Bluetooth service connected
V/BluetoothSapService( 6009): Starting SAP server process
,V/BluetoothSapService( 6009): SAP Service startRfcommListenerThread
,V/BluetoothSapService( 6009): Sap Service initRfcommSocket
,D/BluetoothManagerService(  952): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6009): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 6009): BTA_JvCreateRecordByUser
,D/bt-sdp  ( 6009): SDP_CreateRecord ok, num_records:15
,I/bt-btm  ( 6009): Write Extended Inquiry Response to controller
I/bt-btif ( 6009): BTA_JvRfcommStartServer
I/bt-btm  ( 6009): BTM_SEC_REG[18]: id 60, is_orig 0, psm 0x0003, proto_id 3, chan_id 15
I/bt-btm  ( 6009):                : sec: 0x4086, service name [JV PORT] (up to 21 chars saved)
V/BluetoothSapService( 6009): Succeed to create listening socket 
V/BluetoothSapService( 6009): Accepting socket connection...
,D/wpa_supplicant( 6043): EAPOL: disable timer tick
,D/A2dpService( 6009): getA2DPService(): returning com.android.bluetooth.a2dp.A2dpService@2756d54c,
D/A2dpSinkService( 6009): getA2dpSinkService(): service is NULL
,D/wpa_supplicant( 6043): EAPOL: disable timer tick,
,D/PMS     (  952): releaseWL(d55d46c): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,I/jxcore-log( 5953): Test app app.js loaded
I/jxcore-log( 5953): 
,I/chromium( 5953): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ContextImpl(  952): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,D/PMS     (  952): acquireWL(25452cfc): PARTIAL_WAKE_LOCK  *alarm* 0x1 952 1000 WorkSource{1000}
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
V/AlarmManager(  952): sending alarm PendingIntent{652efb7: PendingIntentRecord{14e40324 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=145628, Int=0
D/libc    (  952): [NET] android_getaddrinfofornet-, err=8
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  952): [NET] android_getaddrinfofornet-, pass to proxy,
D/libc    (  952): [NET] android_getaddrinfo_proxy+
D/libc    (  952): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  397): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,V/AlarmManager(  952): sending alarm PendingIntent{2f30e798: PendingIntentRecord{35f31bf1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158263, Int=0
,D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
V/AlarmManager(  952): sending alarm PendingIntent{39111f85: PendingIntentRecord{29c321da com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=140972, Int=0
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
V/AlarmManager(  952): sending alarm PendingIntent{502060b: PendingIntentRecord{29211d75 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=161774, Int=0
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    (  952): [NET] android_getaddrinfo_proxy-, NODATA,
,D/PMS     (  952): acquireWL(37361ce8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1932): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1932): [NET] android_getaddrinfo_proxy+
D/libc    ( 1932): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1932): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  952): releaseWL(37361ce8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(25452cfc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,D/WeatherUtility( 1269): Weather sync is On
,W/WeatherTimeKeeper( 1269): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  952): acquireWL(2492f01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 952 1000 null,
D/DotMatrix( 1354): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/BatteryService(  952): n_update end
D/PMS     (  952): releaseWL(2492f01): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1354): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1354): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/NotificationService(  952): plugged=true pluggin=true
D/UsbnetService(  952): BroadcastReceiver::onReceive+
D/WifiController(  952): battery changed pluggedType: 2
D/UsbnetService(  952): onReceive BATTERY_CHANGED
D/HtcPowerSaver(  952): updateBatteryInfo
D/UsbnetService(  952):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
D/PMS     (  952): runPSCheck
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  952): Checking...
D/WifiController(  952): handleMessage: E msg.what=155652
I/HtcPowerSaver(  952): >> updateStatus
D/WifiController(  952): processMsg: DeviceActiveState
D/PowerUI ( 1269): closing low battery warning: level=100
,D/WifiController(  952): processMsg: StaEnabledState
D/PowerUI ( 1269): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  952): processMsg: DefaultState
D/WifiController(  952): handleMessage: X
D/HeadsetStateMachine( 6009): Disconnected process message: 10, size: 0
I/IntentController( 1269): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  952): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  952): << updateStatus
,I/BatteryController( 1269): status:5 level:100 unsupport:false plugged:true,
,D/TelephonyReceiver( 1510): switchBindHtcMsgCursor: null,
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 5
,D/HtcUPManager( 1269): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcAppUPService( 1476): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@22d375ac
,D/HtcUPManager( 1269): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
I/ActivityManager(  952): Killing 5749:com.google.android.apps.docs/u0a101 (adj 15): empty #17
,D/Process (  952): killProcessQuiet, pid=5749
,D/Process (  952): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  952): Recipient 5749
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/PMS     (  952): acquireWL(214181a6): PARTIAL_WAKE_LOCK  *alarm* 0x1 952 1000 WorkSource{1000},
V/AlarmManager(  952): sending alarm PendingIntent{ac8f7e7: PendingIntentRecord{36c41f94 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=206471, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{2f30e798: PendingIntentRecord{35f31bf1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=218263, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{652efb7: PendingIntentRecord{14e40324 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=221784, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{1398ba3d: PendingIntentRecord{28f41232 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=183962, Int=0
,V/AlarmManager(  952): sending alarm PendingIntent{12232b83: PendingIntentRecord{1a8da100 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1449751152227, Int=1800000
D/libc    (  952): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 4
D/libc    (  952): [NET] android_getaddrinfofornet-, err=8
,D/libc    (  952): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
,D/libc    (  952): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  952): [NET] android_getaddrinfo_proxy+
D/libc    (  952): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 22(0x322e616e64726f),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    (  952): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  952): acquireWL(3b5bbd39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): acquireWL(ccd1f7e): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4267 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  952): releaseWL(214181a6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
D/PMS     (  952): releaseWL(3b5bbd39): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/WeatherUtility( 1269): Weather sync is On
,W/WeatherTimeKeeper( 1269): [refreshWeatherData] no weather data,
D/PMS     (  952): acquireWL(3a487fb): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4267 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  952): releaseWL(ccd1f7e): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms}
,I/EventLogService( 4267): Aggregate from 1449749352186 (log), 1449749352186 (data),
,I/art     (  952): Explicit concurrent mark sweep GC freed 26261(1359KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 16MB/24MB, paused 1.960ms total 178.222ms,
,D/PMS     (  952): releaseWL(3a487fb): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms},
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  952): acquireWL(3da9a8d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 952 1000 null,
I/BatteryService(  952): n_update end
D/PMS     (  952): releaseWL(3da9a8d7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  952): BroadcastReceiver::onReceive+,
D/NotificationService(  952): plugged=true pluggin=true
,D/UsbnetService(  952): onReceive BATTERY_CHANGED
,D/WifiController(  952): battery changed pluggedType: 2
D/UsbnetService(  952):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  952): updateBatteryInfo
D/UsbnetService(  952): BroadcastReceiver::onReceive-
D/PMS     (  952): runPSCheck
D/WifiController(  952): handleMessage: E msg.what=155652
D/HtcPowerSaver(  952): Checking...
,D/WifiController(  952): processMsg: DeviceActiveState
I/HtcPowerSaver(  952): >> updateStatus
D/WifiController(  952): processMsg: StaEnabledState
D/PowerUI ( 1269): closing low battery warning: level=100
D/WifiController(  952): processMsg: DefaultState
I/HtcPowerSaver(  952): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  952): handleMessage: X
I/HtcPowerSaver(  952): << updateStatus
D/HeadsetStateMachine( 6009): Disconnected process message: 10, size: 0
D/PowerUI ( 1269): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1354): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1354): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1354): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1269): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryController( 1269): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  952): acquireWL(1ff895c4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 952 1000 WorkSource{1000}
,V/AlarmManager(  952): sending alarm PendingIntent{2f30e798: PendingIntentRecord{35f31bf1 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=278263, Int=0
V/AlarmManager(  952): sending alarm PendingIntent{3411acad: PendingIntentRecord{29211d75 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=287059, Int=0
D/PMS     (  952): acquireWL(8f16be2): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1932 10024 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
D/libc    ( 1932): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1932): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    ( 1932): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1932): [NET] android_getaddrinfo_proxy+
D/libc    ( 1932): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  397): [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
D/libc    (  397): [NET] _dns_getaddrinfo+, netid:0, mark:917504
,D/libc    (  397): [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
D/libc    (  397): [NET] android_getaddrinfofornet-, err=7
D/libc    ( 1932): [NET] android_getaddrinfo_proxy-, NODATA
,D/PMS     (  952): releaseWL(8f16be2): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  952): releaseWL(1ff895c4): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1269): Weather sync is On
,W/WeatherTimeKeeper( 1269): [refreshWeatherData] no weather data
,W/Atfwd_Sendcmd(  449): AtCmdFwd service not published, waiting... retryCnt : 5,

```
